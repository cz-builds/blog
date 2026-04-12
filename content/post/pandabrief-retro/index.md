---
title: "I Built a Fully Automated AI Newsletter in 3 Days. Here's Why I'm Pivoting."
date: 2026-04-12
categories:
  - Build Log
tags:
  - AI
  - automation
  - lessons
---

Last week I built **PandaBrief** — a fully automated daily newsletter that translates Chinese tech news into English. From RSS ingestion to LLM scoring to email delivery, zero human intervention required.

The entire pipeline runs on GitHub Actions, costs $0/month, and handles everything from content curation to subscriber management to self-healing code fixes.

**Then I realized the product itself might not be worth building.**

## What I Built

The system has 8 automated steps that run every day:

```
RSS Fetch (16 sources) → LLM Scoring → Dedup → Translation → 
Quality Check → Render HTML → Send Email → Operator Report
```

Tech stack:
- **Content pipeline**: Python + Groq/Gemini API (free tier, with auto-fallback)
- **Hosting**: Cloudflare Pages + KV storage (free)
- **Email**: Resend (free tier)
- **CI/CD**: GitHub Actions (free)
- **Auto-fix**: LLM reads GitHub Issues → generates patches → opens PRs → emails me to review

Total monthly cost: **$0**

## The Interesting Engineering Problems

**LLM rate limits**: Groq's free tier gives you 100K tokens/day. My pipeline burned through that in one run. Solution: built a provider fallback chain (Groq → Gemini → Zhipu) that automatically switches when one provider hits its limit.

**Chinese character corruption**: When asking the LLM to output complete file contents for auto-fix PRs, it would corrupt Chinese characters in source configs (量子位 → 量种体). Solution: switched from "output the whole file" to "output search-and-replace patches" — the LLM copies exact text and only modifies the target section.

**Quality gate false positives**: The translation step uses full article text (3000 chars), but the quality checker only saw a 200-char snippet. It flagged 9/10 translations as "hallucinated" because it couldn't find details that were actually in the full article. Solution: give the checker more context and tell it "the translator had access to the full article."

## Why I'm Pivoting

The engineering was fun. But the product has fundamental problems:

1. **Translation is no longer a moat.** In 2026, anyone can paste Chinese text into ChatGPT. A newsletter that translates is competing with a free, instant, universal tool.

2. **The audience doesn't have a strong pain point.** "Staying updated on Chinese tech" is nice-to-have for Western devs, not must-have. Nobody's workflow breaks without it.

3. **AI Overviews are eating informational content.** Google's AI Overviews now reduce click-through rates by 58% for informational queries. The trend is accelerating.

4. **The Chinese AI narrative has a credibility problem.** Model distillation controversies, benchmark optimization concerns — the Western dev community is increasingly skeptical. Translating these stories doesn't add trust, it just amplifies noise.

## What I Actually Learned

The project wasn't a waste. I learned more in 3 days of building than in weeks of tutorials:

- How to orchestrate multi-step LLM pipelines with fallback and retry logic
- Cloudflare Pages + KV as a zero-cost deployment platform
- GitHub Actions as a free cron + CI/CD system
- How to make LLMs generate safe, reviewable code changes (search-and-replace, not full rewrites)

Most importantly: **the ability to quickly build and ship automated systems is valuable, but it needs to be pointed at a real problem.**

## What's Next

I'm an IC (integrated circuit) student with FPGA experience. The AI arms race everyone talks about is fundamentally a **hardware** arms race. I'm going to explore the intersection of AI and hardware — starting with running neural network inference on my Zynq-7020 FPGA.

I'll document everything here. Follow along if you're interested in where silicon meets intelligence.

---

*This is the first post on this blog. I'm building in public — sharing what I learn, build, and think about at the intersection of AI and hardware.*
