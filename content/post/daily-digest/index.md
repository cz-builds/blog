---
title: "I Built a Personal AI News Agent That Emails Me Every Morning"
date: 2026-04-12
categories:
  - Build Log
tags:
  - AI
  - automation
  - productivity
---

I spend too much time scrolling Hacker News, arxiv, and tech Twitter. Most of it is noise. So I built a system that does the filtering for me — every morning at 6 AM, I get an email with the 10 most relevant stories across AI, semiconductors, and space.

Fully automated. Zero cost. Built in an afternoon.

## The Problem

My information diet was broken:

- **Douyin/YouTube recommendations** — optimized for engagement, not relevance
- **Manually checking 10+ sites** — time-consuming, easy to miss things
- **Asking ChatGPT** — no context about what I specifically care about

I wanted something that knows my interests (AI hardware, FPGA, space engineering) and filters 200+ daily articles down to the 10 that actually matter.

## How It Works

```
9 RSS Sources → Fetch → LLM Scoring → Summarize (bilingual) → Email
```

Every day at 6 AM Beijing time, a GitHub Actions workflow:

1. **Fetches** ~150 articles from 9 sources (Hacker News, arxiv, Ars Technica Space, SemiAnalysis, EE Times, etc.)
2. **Scores** each article 1-10 based on my specific interests using Gemini
3. **Summarizes** the top 10 in both English and Chinese
4. **Emails** the digest to me with links to every original article

### The Scoring Prompt

This is where the personalization lives. The LLM knows I'm an IC student interested in:

- AI inference on edge hardware (FPGA/ASIC)
- Semiconductor industry moves
- Space technology engineering details
- Open source AI tools
- Contrarian technical takes

A paper about efficient transformer inference on resource-constrained chips scores 9/10. A generic "AI will change everything" opinion piece scores 2/10.

### Model Fallback Chain

Free API tiers have rate limits. Instead of failing when one model is exhausted, the system automatically falls back:

```
gemini-2.5-flash (best quality, 20 req/day)
    ↓ exhausted? auto-switch
gemini-2.0-flash (good quality, 1500 req/day)
    ↓ exhausted? auto-switch
gemini-2.0-flash-lite (basic, unlimited)
```

The most important items get processed by the best model. Later items gracefully degrade.

## Sources

| Source | Category | Why |
|--------|----------|-----|
| Hacker News | AI & Tech | High signal-to-noise, community-validated |
| arxiv cs.AI | AI Research | Primary source for papers |
| arxiv cs.AR | Hardware | Computer architecture papers |
| SemiAnalysis | Hardware | Best semiconductor industry analysis |
| EE Times | Hardware | Electronics engineering news |
| MIT News AI | AI Research | Research breakthroughs |
| Ars Technica Space | Space | Eric Berger's space reporting |
| Everyday Astronaut | Space | Deep engineering explanations |
| SpaceNews | Space | Industry coverage |

## Tech Stack

- **Pipeline**: Python (feedparser + google-genai + resend)
- **Database**: SQLite (ephemeral, rebuilt each run)
- **Scheduling**: GitHub Actions cron (free)
- **LLM**: Gemini API (free tier)
- **Email**: Resend (free tier)
- **Total cost**: $0/month

## What I Learned from PandaBrief

This project reuses the architecture from [PandaBrief](/blog/post/pandabrief-retro/), my previous newsletter project. Key improvements:

1. **Model fallback chain** — never fail because of rate limits
2. **Bilingual output** — Chinese + English in one prompt call
3. **Personalized scoring** — not generic "is this important" but "is this important *to me*"
4. **Private by default** — this is a personal tool, not a product

The biggest lesson: the same automation pipeline that couldn't sustain a public product works perfectly as a personal productivity tool. The difference is that I'm the only user, so I can tune the scoring to exactly what I care about.

## Try It Yourself

The code is at [github.com/cz-builds/daily-digest](https://github.com/cz-builds/daily-digest). Fork it, change `sources.yaml` and the scoring prompt to match your interests, add your API keys as GitHub Secrets, and you'll have your own AI-curated morning briefing.

---

*This is part of my [build in public](/blog/categories/build-log/) series. I'm an IC student exploring the intersection of AI and hardware.*
