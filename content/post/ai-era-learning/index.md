---
title: "The High-Bandwidth Learning Method for the AI Era"
description: "Access to knowledge is now close to unlimited, so the bottleneck has moved into the human brain itself. A complete learning method built on learning science and 2024–2026 AI tutoring trials, covering everything from first principles to daily practice."
date: 2026-10-20
draft: false
categories:
  - Learning
tags:
  - AI
  - learning
  - methodology
---

> 🌐 **中文版**：[AI 时代的高带宽学习法：从第一性原理到每日实操](../ai-era-learning-zh/)

> **A note before we start:** These are research notes plus my own reasoning. I wanted a complete answer, from philosophy down to daily routine, to one question: how can a complete beginner get good at a new field in a short time? Each claim is tagged by strength of evidence:
> **[Strong]** replicated across many studies; **[Moderate]** supported by solid research, with boundary conditions; **[Inference]** my own reasoning from the evidence, not yet directly tested.

---

## 0. The one-page version

**Core claims**

1. **Input bandwidth is no longer the bottleneck.** Human behavior runs at roughly 10 bits/s of information throughput, while our senses take in about 10⁹ bits/s (Zheng & Meister, 2025). Working memory holds only about 4 chunks at a time (Cowan, 2001). AI has made finding the right information nearly free, so the bottleneck now sits entirely at the brain's **write port**.
2. **Maxing out your bandwidth does not mean feeding in more information.** It means four things:
   - **Raise the compression ratio**: build schemas and chunks, so the same 10 bits carry more meaning.
   - **Raise the write frequency**: move time away from reading, listening and watching, toward retrieving, generating, explaining and predicting.
   - **Cut the noise**: hand all cognitive load that is unrelated to the learning goal to AI, until it is close to zero.
   - **Work with your biology**: spacing, sleep and exercise let consolidation run in the background.
3. **AI is an amplifier, and the way you use it decides what it amplifies.** Two versions of the same GPT-4 setup gave opposite results. The one that handed out answers left high-school students scoring 17% below the control group on the exam. The one that gave only hints largely prevented that harm (Bastani et al., 2025). Harvard built an AI tutor that gives one step at a time, and its students learned more, in less time, than students in an active-learning classroom (Kestin et al., 2025).
4. **One governing principle**: **let AI remove all *non-learning friction*, and keep all *learning friction* for yourself.**
5. **One core loop**: run every concept through **Predict → Study → Recall → Explain → Practice → Capture**, wrapped inside a project-level flow of **Target → Map → Skeleton → Loop → Build → Calibrate**.

---

## 1. Reframing the problem: where is the learning bottleneck?

### 1.1 How many gates does information pass before it becomes ability?

```
External information (practically unlimited)
  │
  │ ① Search & filter      ← the expensive step before AI: finding material,
  │                           finding a teacher, finding an explanation that fits you
  ▼
Attention (one thing at a time)
  │
  │ ② Working-memory work  ← ~4 chunks, ~10 bits/s of conscious throughput
  ▼
Long-term memory encoding
  │
  │ ③ Consolidation        ← takes time, spacing and sleep
  ▼
Retrieval & transfer
  │
  │ ④ Feedback & correction ← also expensive before AI: nobody told you
  │                            quickly where you went wrong
  ▼
Ability (you can do it without looking anything up)
```

Before AI, ① and ④ were the expensive gates: good teachers, good textbooks and fast feedback were all scarce. Now ① and ④ are nearly free, and **② and ③ are the only constraints left**. AI cannot directly widen ② or ③. It can do one of two things: help you use them better, or, used badly, let you skip them entirely.

Herbert Simon put it this way in 1971: **"A wealth of information creates a poverty of attention."** Today that sentence is literally true.

### 1.2 What bandwidth really means: compression matters more than throughput

In Chase and Simon's classic 1973 study, chess masters glanced at a real game position for five seconds and could rebuild most of it; novices remembered only a few pieces. When the pieces were placed at random, the masters' advantage nearly vanished. Masters do not have bigger working memories. They see **chunks** ("the typical structure after kingside castling"), while novices see individual pieces.

So:

- **Experts and novices both have about four slots. What differs is how much each slot holds.**
- One way to think about learning: **you are training your brain's compression codec.** The better your schemas, the more information the same conscious bandwidth can carry.
- [Inference] Early on, the most valuable investment is the **core schema (the skeleton)**, because it raises the compression ratio of everything you learn afterward. It also explains why a long AI explanation often goes in one ear and out the other for a beginner: there are no hooks to hang it on.

### 1.3 Writing to memory only happens during processing

Cognitive scientist Daniel Willingham: **"Memory is the residue of thought."** You remember what you thought hard about, not what you looked at.

- Dunlosky et al. (2013) rated 10 common study techniques. **Practice testing** and **distributed practice** were rated "high utility". **Rereading, highlighting and summarizing** were rated "low utility". [Strong]
- Roediger and Karpicke (2006): on a test one week later, students who had repeatedly tested themselves recalled about 61%, versus about 40% for students who had repeatedly reread the text. The students themselves predicted the opposite. [Strong]

**Passively reading AI explanations is basically a new form of rereading.** It feels smooth, and very little gets written.

That suggests a working definition [Inference]:

> **Effective learning bandwidth ≈ high-quality write events per unit of time × difficulty match × retention**
>
> A *write event* is when you produce something **from your own head** (an answer, an explanation, a prediction, a solution) and then get **feedback** on it.

The whole method is built to maximize write events per hour, keep the difficulty at the edge of your ability, and use spacing and sleep to push retention up.

---

## 2. Philosophy: what does "learning something" mean in the AI era?

### 2.1 Socrates' warning, 2,400 years later

In Plato's *Phaedrus*, King Thamus of Egypt judges the invention of writing (Jowett's translation):

> "This discovery of yours will create forgetfulness in the learners' souls, because they will not use their memories; they will trust to the external written characters and not remember of themselves… you give your disciples not truth, but only the semblance of truth; **they will be hearers of many things and will have learned nothing; they will appear to be omniscient and will generally know nothing**; they will be tiresome company, having the show of wisdom without the reality."

What actually happened: writing did end the tradition of memorizing epics by heart, but it also let knowledge accumulate and made science possible. Thamus was half right. **A tool changes what needs to live in your head. It does not change whether you need to learn.**

Still, "they will appear to be omniscient and will generally know nothing" is close to an exact description of the biggest risk in AI-assisted learning: **how you perform with AI is not the same as what you can do.** The experiments in Section 3 confirm this again and again.

### 2.2 What has to live in your head

| Keep it outside (AI and docs, look it up when needed) | It has to live in your head |
|---|---|
| Specific numbers, API details, every step of a long derivation | Core concepts and how they relate (schemas) |
| Facts you only need to look up once | Key intuitions; solution patterns for typical problems |
| Things that are cheap to verify | Judgment: what is correct, what is good, what looks suspicious |
| The long tail | The ability to ask questions: knowing what you don't know |

Three reasons the right-hand column cannot be outsourced:

1. **Thinking happens in working memory, and working memory can only draw on long-term memory.** You cannot think *with* knowledge that lives in ChatGPT. To pull in outside knowledge you first have to know what to pull, and every lookup takes up scarce working memory.
2. **The verification paradox: you can only check what you understand.** A Microsoft/CMU survey of 319 knowledge workers found that the more people trusted AI, the less critical thinking they did; the more they trusted themselves, the more they did (Lee et al., 2025). Without knowledge of your own, all you can do is *believe* the AI.
3. **Good questions come from knowledge.** Beginners can't ask good questions because they can't yet see the shape of their own gaps.

A useful metaphor [Inference]: **your head should hold the index plus the core.** The long tail can live outside, but the index has to be detailed enough that you know what to ask and can notice when something is off.

### 2.3 Fluency is not understanding

AI explanations are tailored, fluent and endlessly patient, so the feeling of "I get it" arrives faster and stronger than ever. But **that feeling is a poor predictor of learning**:

- In Kornell and Bjork (2008), most people believed blocked study worked better than interleaved study. The results showed the opposite. [Strong]
- **Recognizing ≠ recalling ≠ using.** Following an AI's solution is the first level. Exams and real work demand the third.

That gives a hard rule: **only trust how you perform with the AI unplugged.**

### 2.4 Forklift or personal trainer

If your goal is to move a barbell from A to B, use a forklift. If your goal is to get stronger, the forklift is useless, or worse.

For a **result task**, AI is a forklift. For a **growth task**, it should be a personal trainer: someone who never lifts for you, but tells you what is wrong with your form and how much to add next set.

A 2026 Anthropic randomized trial (Shen & Tamkin) shows this neatly. Fifty-two developers learned an unfamiliar async Python library. The AI group averaged 50% on the follow-up quiz, versus 67% for the group that coded by hand, and the AI group was not significantly faster. The bigger story is the spread within the AI group:

| Interaction pattern | Quiz score |
|---|---|
| Delegated all the code to AI | < 40% |
| Asked a few questions, then gradually handed everything to AI | < 40% |
| Used AI to debug and verify, only to get things working | < 40% |
| Generated code, then asked follow-up "why" questions | ≥ 65% |
| Asked for code and explanation together | ≥ 65% |
| **Asked only conceptual questions and fixed their own errors** | **≥ 65%** (and second fastest) |

**Same tool, different usage, different outcome.** Before each interaction, ask yourself: **"Do I want the result this time, or the ability?"** Both are legitimate. Mixing them up is the trap.

### 2.5 Difficulty is the signal, not the noise

Psychologist Robert Bjork coined the term **desirable difficulties**: conditions that make learning *feel* harder and slower in the moment, yet substantially improve long-term retention and transfer. Examples are self-testing, spacing, interleaving, and attempting a problem before being taught.

**Not all difficulty is desirable, though.** An afternoon lost to setting up an environment, hours of searching forums for decent material, slogging through a badly written textbook: these struggles have **nothing to do with the learning goal**. Cognitive load theory calls this *extraneous load*. **This is exactly what AI should eliminate.**

That gives the governing principle of this post:

| Non-learning friction (hand to AI) | Learning friction (keep for yourself) |
|---|---|
| Finding and filtering material; deciding where to start | Retrieving from memory |
| Translating obscure writing into language you can follow | Explaining in your own words |
| Setting up environments and tools; syntax details outside the target skill | Attempting before asking for a hint |
| Generating exercises, grading, giving feedback | Making mistakes and diagnosing them |
| Scheduling, formatting notes | Connecting concepts to each other |
| Generating visualizations, simulations, examples | Making decisions and judgments |

Note: **which column an activity falls into depends on what you are trying to learn.** If you are learning Linux administration, setting up the environment *is* learning friction.

### 2.6 Four layers of knowledge: know, understand, do, judge

| Layer | What it looks like | How much AI can help |
|---|---|---|
| **Know** | You can state it | Can be accelerated almost without limit |
| **Understand** | You can explain why and predict | Needs your own generative processing; AI supplies material and questions |
| **Do** | You can execute in a new situation | Needs lots of practice plus feedback. Much of it is tacit knowledge: as Polanyi said, "we can know more than we can tell" |
| **Judge** | You can tell good from bad and make trade-offs | Needs many cases and expert feedback; the slowest layer |

**An honest definition of "mastering something quickly":** within a few weeks, becoming a **competent beginner**. You can follow mainstream discussion in the field, complete entry-level real tasks on your own, tell whether an AI's answer is trustworthy, and keep learning by yourself. Becoming an expert still takes years of deliberate practice (Ericsson et al., 1993). What AI can do is shorten the "zero to useful" stretch a lot.

Bloom (1984) found that students with one-on-one tutoring scored about two standard deviations above students in a regular classroom (the "2 sigma problem"). Later, more careful meta-analyses find a smaller but still large effect of about 0.37 standard deviations (Nickow et al., 2020). **AI makes one-on-one tutoring nearly free, but only if you use it as a tutor and not as an answer machine.**

### 2.7 The learner's new role: from audience to director

It used to be that someone else designed the curriculum and you absorbed it. Now you can design your own curriculum, generate your own exercises and get feedback anytime. **Freedom brings responsibility**, and the evidence shows that the most vulnerable learners are the ones most easily led astray by that freedom (see Section 3.3). So what a beginner needs is not more willpower, but **guardrails built into the system**.

A widely shared piece of learning advice attributed to Andrej Karpathy (second-hand summary) lines up closely with this method: **take on concrete projects and go deep, learning on demand rather than bottom-up and breadth-first; teach or summarize everything you learn in your own words; compare yourself only to your younger self.**

---

## 3. The evidence base

### 3.1 Learning science: which methods have been replicated

| Method | What it is | Evidence | How to use it in the AI era |
|---|---|---|---|
| **Retrieval practice** | Close the material and write or answer from memory | [Strong] Roediger & Karpicke 2006; rated high utility by Dunlosky 2013 | Recall from memory *before* reading the AI's explanation; have AI quiz you |
| **Spaced repetition** | Review again after a gap | [Strong] Cepeda 2008: to remember for a week, the best gap is about 20–40% of that (1–3 days); for a year, about 5–10% (3–5 weeks) | Anki with FSRS scheduling; AI helps turn your mistakes into cards |
| **Interleaving** | Mix different problem types together | [Strong] Rohrer 2020: 787 middle-schoolers, one month later 61% vs 38%, d = 0.83 | Ask AI for mixed problem sets with no chapter labels |
| **Pretesting** | Answer questions before studying, even if you get them wrong | [Moderate–Strong] Richland 2009; Kornell 2009; requires feedback afterward | Have AI ask you 3 questions before each new concept |
| **Self-explanation / elaborative interrogation** | Ask "why?" and "how does this connect?" | [Moderate] Chi 1989; rated moderate by Dunlosky | Reverse Feynman: you explain to AI, which plays a stubborn student |
| **Productive failure** | Try to solve the problem first, then get instruction | [Moderate] Sinha & Kapur 2021 meta-analysis (53 studies): especially effective for conceptual understanding; needs some prior knowledge | Work alone for 10–15 minutes before asking for a hint |
| **Worked examples & expertise reversal** | Beginners study full worked examples; remove the scaffolding as skill grows | [Strong] Cognitive load theory (Sweller); Kalyuga 2003 | Raise the starting rung of the AI hint ladder as you improve |
| **Concrete examples & multiple representations** | Concrete before abstract; words plus pictures | [Moderate] | Have AI build interactive visualizations or simulations |
| **Correcting high-confidence errors** | Confident wrong answers, once corrected, stick especially well | [Moderate] Butterfield & Metcalfe 2001 | Rate your confidence 1–5 before each answer |
| **Learning by teaching** | You learn better when you expect to teach | [Moderate] Nestojko 2014 | Write a blog post or teach someone every week |
| **Rereading, highlighting, summarizing** | — | [Strong] rated low utility by Dunlosky 2013 | **Passively reading AI explanations ≈ rereading** |

**Three popular myths** that may come back under the banner of AI "personalization":

- **Learning styles** (visual, auditory, …): there is no evidence that matching instruction to a "style" improves learning (Pashler et al., 2008). **AI should personalize to what you already know, not to what "type" you are.**
- **Speed reading**: there is a hard trade-off between reading speed and comprehension (Rayner et al., 2016).
- **Brain-training games**: you get better at the trained games, but evidence of transfer to everyday cognition is weak (Simons et al., 2016).

### 3.2 AI and learning: the key experiments of 2024–2026

| Study | Participants & design | Results | Takeaway |
|---|---|---|---|
| **Bastani et al., PNAS 2025** | ~1,000 Turkish high-school math students; GPT Base (ChatGPT-like), GPT Tutor (hints only), and no-AI groups | During practice, Base scored 48% higher and Tutor 127% higher; **on the exam without AI, Base scored 17% below control**, Tutor matched control | Performance with AI ≠ learning; guardrails block the harm |
| **Kestin et al., Sci. Rep. 2025** | 194 students in a Harvard physics course, randomized crossover | AI tutor group showed significantly larger learning gains (reported as more than double the classroom group) in less time | Tutor built on the course's pedagogy: one step at a time, never the full solution at once |
| **World Bank, Nigeria 2025** | 759 secondary students, 6 weeks of after-school GPT-4 tutoring | +0.31 SD overall (+0.23 SD in English) | Control group got no extra study time, so the effect includes "six more weeks of study" |
| **Shen & Tamkin (Anthropic) 2026** | 52 developers learning the unfamiliar Trio library | Quiz 50% vs 67% (d ≈ 0.74); no significant speedup; conceptual askers ≥65%, full delegators <40% | Same tool, usage decides the outcome |
| **Kosmyna et al. (MIT) 2025 preprint** | 54 participants writing essays, with EEG | LLM group showed the weakest brain connectivity; most could not accurately quote the essay they had just written | Small sample, not peer-reviewed; the lead author rejects "AI rots your brain" readings |
| **Lee et al. (Microsoft/CMU) CHI 2025** | Survey of 319 knowledge workers | More trust in AI → less critical thinking; more self-confidence → more | Self-reported; correlation only |
| **Liu, Sweet et al. (U. Maryland) 2026 working paper** | 2,379 undergrads and 30 instructors; instructors randomly assigned to offer a GPT-4o study assistant in the course platform | Within the same course, final grades 0.37 SD lower; course-platform engagement 0.90 SD lower; larger losses for first-generation students; only ~15% of students ever used it | No significant grade effect in the full sample; points to a "crowding-out" effect |

### 3.3 Five conclusions from the evidence [Inference]

1. **Interaction design, not model capability, decides which way AI moves learning.** The successes share a pattern: one step at a time, no full answers up front, the student produces first, and the tool is embedded in a structured course. The failures share another: no guardrails, direct answers, and AI replacing existing learning activities.
2. **Performance during practice is not learning.** AI can sharply raise performance *with* AI while lowering ability *without* it. Measure with the plug pulled.
3. **Beginners are the high-risk group.** The newer, the less confident and the less supported the learner, the more easily AI's convenience leads them astray (first-generation students in the Maryland study; low self-confidence in Lee et al.; mostly junior engineers in the Anthropic study).
4. **AI can crowd out learning activities that were already working.** AI should be **embedded** in your learning system, not **replace** it.
5. **Guardrails have to be built into the system, not left to willpower**: learning modes, system prompts, physical separation, fixed rules.

---

## 4. The method: High-Bandwidth Learning (HBL)

### 4.1 Three time scales

| Scale | Unit | Structure |
|---|---|---|
| **Macro** | Weeks to months (a field or project) | Target → Map → Skeleton → Loop → Build → Calibrate |
| **Meso** | A day (one concept) | Predict → Study → Recall → Explain → Practice → Capture |
| **Micro** | Minutes (every AI interaction) | Think before you ask + the hint ladder + the AI traffic light |

### 4.2 The macro flow

#### Step 0: Target (half a day)

Turn "learn X" into a **checklist of abilities you can actually test**. Fill in this template:

```
3 real tasks I will be able to do on my own:
1.
2.
3.
5 core questions I will be able to explain to a layperson:
3 kinds of claims I will be able to judge as right or wrong:
Final exam (write it now): a timed, integrated task done without AI
```

The principle is **directness** (Scott Young's term in *Ultralearning*): learn in a setting as close as possible to where you will actually use the skill.

#### Step 1: Map (2–4 hours)

- Have AI generate a **field map**: 15–30 core concepts, their dependencies, prerequisites, common beginner misconceptions, the key differences between how experts and novices see the field, and the canonical resources (see P1 in Section 5).
- **Cross-check**: use at least two different models, plus a real university syllabus or the table of contents of a classic textbook. **Where the maps disagree is exactly what to dig into.**
- **Diagnostic test**: have AI write 15–20 questions covering the prerequisites and answer them closed-book to find your starting point (P2).
- **Pick one spine resource**: one textbook or one course is the spine, and AI is the tutor wrapped around it. AI is good at answering questions but not at guaranteeing coverage or a sensible order. A mature course's sequence has been refined over years and is valuable. That's the lesson of the Maryland crowding-out result.
- **Output**: a one-page map you **draw yourself** (the AI version is only a reference).

#### Step 2: Skeleton (1–3 days)

- Learn the 5–9 "big ideas" first, each only to the level of "one sentence plus one example".
- Write a **one-page overview of the field** and **rewrite it every week**. Watching it go from naive to precise is your progress bar.

#### Step 3: Loop (most of your time; see 4.3)

#### Step 4: Build (starts in week one and runs throughout)

- At least one small project per week that **you can finish with AI unplugged**, plus one larger project where AI help is allowed.
- **The driver rule**: you drive, AI navigates. You must be able to explain and reproduce every line of code and every conclusion AI gives you. Whatever you can't is the content of your next loop.
- **Make your output public** (a blog, GitHub, explaining it to a friend). That gives you learning-by-teaching, outside feedback and motivation all at once.

#### Step 5: Calibrate (weekly)

- **The unplug test**: once a week, a closed-book quiz or timed task with no AI.
- **Confidence calibration**: write a confidence score (1–5) before answering, and review the high-confidence misses first.
- **Outside feedback**: real experts, communities (forums, code review on open-source PRs), real exam or interview questions.
- Rewrite the one-page overview, update the map, adjust next week's plan.

### 4.3 Meso: the concept loop — Predict → Study → Recall → Explain → Practice → Capture

One concept takes about 60–90 minutes:

| Step | You | AI | Why it works | Time |
|---|---|---|---|---|
| **1 Predict** | Answer 2–3 prediction questions on paper | Asks the questions, gives no answers | Pretesting effect, curiosity | 5 min |
| **2 Study** | Read the spine resource or a lesson, with those questions in mind | Explains at your level: example before abstraction, multiple representations, answers your "why" questions | Worked examples, elaboration | 15–25 min |
| **3 Recall** | **Close everything.** Write down the core idea, an example, why it holds, and what you already know it connects to | Nothing | Retrieval practice, generation effect | 5–10 min |
| **4 Explain** | Teach it to the AI (Feynman technique) | Plays a stubborn student or examiner: probes, finds holes, names misconceptions, **without handing you the correct version** | Self-explanation, learning by teaching | 10–15 min |
| **5 Practice** | Do problems or a small task, attempting each one alone first | Generates interleaved problems you get right about 80–85% of the time; gives hints via the ladder; grades | Retrieval, interleaving, feedback | 20–30 min |
| **6 Capture** | Turn mistakes and key points into flashcards and an error log | Helps polish your cards (you write them first) | Spaced repetition | 5–10 min |

**Time ratio**: Step 2 (Study) takes no more than a third of the time; **at least two-thirds goes to output**.

### 4.4 Micro: the rules for every AI interaction

**Rule 1: Think before you ask.** In your target field, before you ask AI anything, write down your guess or attempt, even if it's one sentence. That single move triggers both the pretesting effect and the generation effect, and it turns the AI's reply from *input* into *feedback*.

**Rule 2: The stuck threshold.** Ask for a level-1 hint only after 10–15 minutes of real attempts with no progress. Don't grind for two hours (it drains motivation), and don't ask after 30 seconds (then nothing gets generated).

**Rule 3: The hint ladder.**

| Level | What you get |
|---|---|
| L1 | One guiding question ("Have you considered the edge case where X?") |
| L2 | The name of the relevant concept or tool |
| L3 | The first step |
| L4 | The key steps; you finish the rest |
| L5 | The full solution. **Then you must immediately solve a variant on your own, or this problem doesn't count** |

**Rule 4: The AI traffic light** (for growth tasks)

- 🟢 **Green**: finding resources, explaining jargon, grading *after* you answer, generating problems, building visualizations, handling chores outside the target skill
- 🟡 **Yellow** (follow the protocol): hints (via the ladder), worked examples (beginner phase only, then fade them out), summaries (only to compare against yours after you write it)
- 🔴 **Red**: answers before you've tried; writing the very thing you're learning to write; debugging bugs in your target skill for you; doing all the work of your notes and flashcards

Result tasks (a work deadline, say) are exempt. Just be clear that you are **borrowing** ability, not **building** it, and run a loop afterward if it matters.

### 4.5 Build the guardrails into the system

- **Use a learning mode.** The major AI products now ship one (Claude's learning mode, ChatGPT's Study Mode, Gemini's Guided Learning, and others). By default they guide you to think instead of handing over answers.
- **Or set up a dedicated "learning project"** with the P0 system prompt from Section 5, kept completely separate from everyday Q&A.
- **Physical separation**: while studying, keep only the learning project's window open. Put "result" use of AI in a different project or account.
- **Write the four rules on paper and stick them next to your monitor.**

---

## 5. Prompt toolkit

Copy these as-is and replace the [brackets] with your own details.

### P0: Tutor system prompt (put it in your learning project's custom instructions)

```
You are my tutor. Your goal is for me to truly master [FIELD], not to get tasks done for me. Rules:
1. Don't give me answers or full solutions directly. Ask me how I'm thinking about it first.
2. When I'm stuck, give hints one level at a time, then wait for my reply:
   L1 a guiding question → L2 the name of the relevant concept → L3 the first step
   → L4 the key steps → L5 the full solution.
   After an L5, immediately give me a variant problem to solve on my own.
3. When explaining, give a concrete example before the abstract definition. Use analogies to
   concepts I already know, and say where the analogy breaks. My current level: [...].
4. After each key point, check my understanding with a specific question. Never ask "does that make sense?"
5. When I answer wrong, don't correct me right away. First ask a question that lets me spot the contradiction myself.
6. If my question reveals a misconception, name the misconception and explain where it usually comes from.
7. For specific facts, numbers or APIs, state your confidence. If you're unsure, say so and tell me where to verify.
8. If I ask for the answer directly, remind me of these rules once. If I insist and say it's a "result task", give it.
```

### P1: Field map

```
I want to go from zero to [SPECIFIC TARGET ABILITY] in [N WEEKS]. My background: [...]. Please give me:
1. The 15–25 most important concepts in this field, layered by dependency (what must come first);
2. A one-sentence explanation of each, and why it matters;
3. The prerequisites, and which ones I'm likely missing given my background;
4. The 5–10 most common beginner misconceptions;
5. The 3 biggest differences between how experts and novices see this field;
6. 3–5 canonical learning resources (textbooks or courses), marking which one works best as the spine;
7. Which content can be looked up on demand and which must be internalized.
Be specific. No generic study advice.
```

When cross-checking, follow up with: `Here is a map from another model (or a university syllabus): [...]. Compare it with yours, point out the differences worth my attention, and explain why.`

### P2: Diagnostic test

```
Based on the map above, write 15 diagnostic questions covering prerequisites and core concepts, from easy to hard.
Give me one question at a time and wait for my answer (I'll include a 1–5 confidence score).
Tell me whether I'm right with a short explanation, then give the next one.
At the end, list the concepts I've mastered, partly mastered, and know nothing about, plus a suggested starting point.
```

### P3: Pretest

```
I'm about to learn [CONCEPT]. Before I start, ask me 3 questions: one testing my intuitive prediction,
one about how it connects to things I already know, and one about what problem it solves.
Don't give answers. I'll come back and compare after I've studied it.
```

### P4: Layered explanation

```
Explain [CONCEPT] at three levels:
(1) A concrete example I can compute by hand or picture in my head;
(2) An analogy based on [X], which I already know, and where that analogy breaks down;
(3) The rigorous definition.
Finally, tell me one thing that someone who truly understands this concept can do that someone who doesn't, can't.
```

### P5: Reverse Feynman

```
I'm going to explain [CONCEPT] to you. Play a smart first-year student who knows nothing about this field:
- Interrupt me whenever I use a term I haven't explained;
- For every "because", ask "why?" once;
- When I'm done, point out the 2 vaguest parts of my explanation and any likely errors.
  Don't give me the correct version; use questions to lead me to fix it myself.
```

### P6: Socratic examiner

```
Give me an oral exam on [CONCEPT]. Start simple and go deeper based on my answers,
designing questions specifically around this concept's common misconceptions. One question at a time.
After 10 questions, give me a diagnosis: what I truly understand, what I've memorized, and what I've misunderstood.
```

### P7: Problem generator

```
Write me a problem set:
- Mix [TODAY'S CONCEPT] with [EARLIER CONCEPTS A, B, C], shuffled, with no labels saying which topic each covers;
- Pitch the difficulty so I get roughly 80–85% right;
- At least 1 transfer problem: same principle, different surface context;
- At least 1 spot-the-error problem: a piece of reasoning or code with a bug for me to find.
One problem at a time. Give hints via the hint ladder, and never volunteer the answer.
```

### P8: Error diagnosis

```
Here's a problem I got wrong, with my working: [...]
Don't give me the correct answer yet. First classify my error:
(a) conceptual misunderstanding (b) missing prerequisite (c) careless or execution error
(d) didn't know which method to use (strategy error)
Then design the smallest possible exercise to fix that kind of error.
```

### P9: Flashcard polish

```
Here are flashcards I wrote (question/answer): [...]
Improve them by these principles, keeping my wording style: one idea per card; each question has exactly one answer;
prefer "why" and "when to use it" over isolated definitions. If a card isn't worth memorizing
(I could just look it up), tell me to delete it.
```

### P10: Fact check

```
List every specific factual claim in your last answer (numbers, dates, APIs, formulas, citations).
For each, give your confidence (high/medium/low) and a primary source where I can verify it.
If you're unsure about any of them, say so explicitly.
```

### P11: Weekly review

```
Here are my learning log and test results for this week: [...]
Please: 1) find the error patterns I keep repeating; 2) decide which concepts on my map should move
from "learning" to "mastered", or back; 3) give me next week's focus (3 items max);
4) design next weekend's unplug test.
```

---

## 6. Troubleshooting guide

Each entry follows **Symptom → Root cause → Fix**.

### 6.1 Getting started

#### Problem 1: You don't know where to start, or what you don't know

- **Symptom**: You can't find a way in. Everything you search for is either impenetrable or shallow.
- **Root cause**: Without a map, you can't tell where a piece of information sits or how much it matters.
- **Fix**: Do Step 1 (Map). Ask AI "how would a top professor design this course?" and use a real university syllabus as your spine. **The goal of day one is not to understand anything. It's to learn what's out there and where it sits.**

#### Problem 2: Prerequisites that keep multiplying

- **Symptom**: A needs B, B needs C… a week later you're still patching up math.
- **Root cause**: A depth-first search with no depth limit.
- **Fix**:
  - **Backtrack at most two levels.** Treat anything deeper as a black box: accept the result, note its interface (what goes in, what comes out, when it holds), and mark it "to fill in".
  - **Learn just enough**: `Teach me only the part of [B] that's needed to understand [A]. Skip the rest.`
  - After each backfill, **go straight back to the original task**. Switching back is itself a test.
  - If the diagnostic shows large gaps in prerequisites, adjust the goal or the timeline honestly instead of forcing it.

#### Problem 3: Information overload, hoarding, tutorial hell

- **Root cause**: Mistaking *collecting* for *learning*. Input feels instantly rewarding, but only output produces learning.
- **Fix**: One spine resource; everything else is reference. Keep input-to-output time at 1:2 or lower. Cap your bookmarks (say, 10) and delete one before adding another. After every tutorial, produce something you **changed**, not a copy. Ask "where does this go on my map?" and if you can't answer, skip it.

### 6.2 Understanding

#### Problem 4: The explanation makes no sense

- **Root cause**: The explanation doesn't connect to anything you already know (no hooks), or it delivers more at once than working memory can hold.
- **Fix**: Use P4 for a three-level explanation. Ask for "one point at a time". Ask for a small concrete example you can compute by hand. Switch representations (diagram, table, code, analogy, physical intuition). Ask first, "what problem is this concept solving?" — **understand the problem before the solution**. Still stuck? Backfill prerequisites (Problem 2).

#### Problem 5: "I understand it, but I can't do it" (the problem AI amplifies most)

- **Root cause**: Recognizing ≠ recalling ≠ producing. Fluency is a false signal.
- **Fix**: Every time you feel "got it", immediately do Step 3 (Recall): write it out closed-book. Do at least one problem per concept starting from a blank page. Use "can I explain it to a layperson?" and "can I come up with a new example?" as your tests. After a worked example, first do a "twin" problem that changes only the surface, then a "variant" that changes the structure.

#### Problem 6: You can't build intuition for an abstract idea

- **Fix**:
  - Have AI write an **interactive visualization or simulation** (drag a parameter, watch the result change). This used to take hours and now takes minutes. It's one of the most underrated learning gains of the AI era.
  - Compute the smallest possible example by hand (a 2×2 matrix, attention over 3 tokens).
  - Predict, observe, explain: guess the result before you change a parameter.
  - Look for extreme cases and boundary conditions.
  - Ask the reverse: "what would break without this concept?"

#### Problem 7: Fragmented knowledge that doesn't connect

- **Fix**: Draw your own **concept map** and label each link ("A is a special case of B", "A causes B"). Build **comparison tables** for similar concepts ("how are X and Y different, and when do I use each?"). Write a synthesis piece every week. Interleave your practice. Ask AI for problems that need two concepts at once.

### 6.3 Practice and memory

#### Problem 8: You forget everything

- **Root cause**: No retrieval and no spacing, or what you stored is isolated fragments not attached to any schema.
- **Fix**:
  - Use Anki with FSRS scheduling enabled, 15–30 minutes a day, with target retention at 85–90%.
  - **Make cards only for what must be internalized** (see the split in 2.2), not for things you can look up.
  - **Write cards yourself first** (generation effect) and let AI only polish them (P9). Cards should ask "why" and "when to use it", not just definitions.
  - Quickly recall new material before bed the same day, and again the next morning.
  - Rewrite the one-page overview weekly to hang the fragments back on the skeleton.

#### Problem 9: Stuck on a practice problem

- **Fix**: Use the 10–15 minute threshold plus the hint ladder. When stuck, first write down "which step I'm stuck on and what I've tried" (often that alone solves it — rubber duck debugging). Restate the problem in a different representation. Solve a simpler special case first (Pólya, *How to Solve It*). Sleep on it (the incubation effect).

#### Problem 10: You can't transfer: change the problem and you're lost

- **Root cause**: You memorized surface features without extracting the deeper structure.
- **Fix**: Practice the same principle across many surface contexts (varied practice). **Compare two examples that look different but share a structure**, and write down the common principle (analogical comparison is very effective for extracting abstract principles, Gentner et al., 2003). Use interleaving to force yourself to decide "which method applies?" first. Keep asking "where else would this principle work?"

#### Problem 11: A plateau where nothing seems to improve

- **Root cause**: Either practice difficulty no longer matches (too easy means repeating inside your comfort zone; too hard means frustration), or you're in a phase that requires restructuring your schemas, where getting temporarily worse is normal.
- **Fix**: Check your practice accuracy: above 95%, make it harder; below 60%, make it easier. Concentrate training on your weakest link (deliberate practice). Judge progress by the trend in your weekly unplug tests, not by how a given day feels. Reread your week-one overview; you'll find you've improved far more than it feels.

### 6.4 AI-specific problems

#### Problem 12: You can't tell whether the AI is right (hallucinations)

- **Root cause**: Verifying takes knowledge, and you're still acquiring it. The more niche, recent or specific (numbers, citations) the content, the more likely AI is to be wrong.
- **Fix**:
  - Keep a **trust gradient**: established textbook knowledge (rarely wrong) > details and numbers > recent developments > niche topics and specific citations (often wrong).
  - **The spine resource is the final judge.** AI explains; the textbook and official docs calibrate.
  - **If it can be executed, execute it**: run the code, plug numbers into the formula, work the derivation yourself.
  - **Cross-check**: where two models disagree is exactly the point most worth digging into.
  - Use P10 to make AI state its confidence and primary sources. For citations, always check the original.
  - **Treat catching an AI mistake as an achievement.** It means your internal model is getting strong.

#### Problem 13: Dependence on AI; outsourcing your thinking by habit

- **Symptom**: Any small difficulty sends you to the AI. Without it you don't want to think. You feel you know everything, then fail the test.
- **Fix**: Enforce think-before-you-ask, the hint ladder and the traffic light. Set **no-AI blocks** (for example, the first deep-work block each day). Take the unplug test weekly and let the score speak. Turn on learning mode in your learning project. Log "how many problems I solved on my own today".

#### Problem 14: You don't know how to ask questions

- **Fix**:
  - Climb the question ladder: what is it → why → how → when does it fail → how is it different from X → what happens if I change Y.
  - Describe **what you tried and where you got stuck**, not just "I don't get it".
  - Turn it around and have AI ask you: "To help me, what do you most need to know about me?"
  - Collect good questions. Good questions are themselves knowledge.

### 6.5 Mindset and habits

#### Problem 15: Distraction and phone-checking

- **Fix**: Put your phone in another room (silent mode isn't enough). One window, one task. All notifications off. Before each deep-work block, write down the block's single goal. Write stray thoughts on a "parking lot" sheet and deal with them after the block. Switching tasks leaves *attention residue* (Leroy, 2009), so switch as little as possible.

#### Problem 16: Procrastination; trouble getting started

- **Fix**: Lower the start barrier to two minutes ("open Anki and do 5 cards"). Use **implementation intentions**: "If it's 8 a.m., I sit at my desk and do the pretest" (Gollwitzer, 1999). At the end of each day, write tomorrow's first task, and **deliberately leave a problem half-done** so tomorrow is easy to start. **Use AI as a starter motor**: have it ask you a few prediction questions; answering a question is much easier than "starting to study".

#### Problem 17: Fading motivation; quitting halfway

- **Fix**: Let a project pull you along: learn in order to build something. Make progress visible (versions of your one-page overview, concepts lighting up on your map, a test-score curve). **Learn in public** (blog posts, GitHub) for outside commitment and feedback. Compare yourself only to your past self. Allow "minimum days": however bad you feel, do 15 minutes of review so the chain never breaks. **Motivation is often the result of action, not its precondition.**

#### Problem 18: Fragmented time

- **Fix**: Use scraps of time for review (flashcards, reciting out loud, listening to recordings of your own explanations). Use solid blocks for new material and practice; new material needs 45–90 uninterrupted minutes at least. In a spare moment, ask AI for a "thinking question" and carry it with you on a walk or commute.

#### Problem 19: You don't know your real level

- **Root cause**: Beginners' self-assessments are generally optimistic, and AI's encouraging tone makes that worse.
- **Fix**: Calibrate your confidence (rate every answer 1–5 and track your high-confidence error rate). Test against outside standards (real exam questions, interview questions, course assignments, issues in open-source projects). Have AI play a strict interviewer who says whether they'd hire you and why. Find a real expert to look at your work every two weeks.

#### Problem 20: Tacit knowledge, the "feel" you can't seem to learn

- **Root cause**: Some expert knowledge can't be put into words (Polanyi). It only comes from doing plus feedback.
- **Fix**: Do lots of real tasks. Watch experts' **process**, not just their results (live streams, screen recordings, code reviews, a paper's revision history). Imitate, then compare: do it yourself first, then see how an expert does it, and write down the differences. Have AI or experts review your work and ask "how would an expert change this?" Keep a case library, one lesson per case.

#### Problem 21: Reading papers, documentation and other hard material

- **Fix**: Use the three-pass method (Keshav, *How to Read a Paper*): first pass, 5–10 minutes on the title, abstract, figures and conclusions; second pass, the main content; third pass, reproduce the derivations or logic. Ways AI can help:
  - Before reading, have AI list "the background concepts needed to understand this" and quiz you on them;
  - While reading, use P4 whenever you get stuck;
  - Afterward, write a closed-book summary first, then compare it with the AI's summary; the differences are your learning points;
  - Prefer source-grounded tools (ones that answer only from the documents you upload) to reduce hallucination;
  - **Don't let an AI summary replace the reading itself.** That's the forklift.

#### Problem 22: Anxiety, impostor syndrome, pressure to go faster

- **Fix**: Set a realistic expectation for "learning fast" (see 2.6). Plateaus and temporary dips are part of learning. Track only your own curve. Sleep and exercise help both mood and learning. Keep a list of things you can do now that you couldn't do a month ago.

---

## 7. Daily habits: your brain is your learning hardware

### 7.1 The physiological layer

| Habit | Evidence | What to do |
|---|---|---|
| **Sleep** | [Strong] One night without sleep markedly weakens hippocampal encoding and worsens retention of new memories (Yoo et al., 2007; the Walker lab reports drops of up to ~40% in some experiments) | 7–9 hours on a regular schedule. **Never trade sleep for study time**: that night's sleep is what consolidates the day's learning |
| **Aerobic exercise** | [Moderate] A year of aerobic exercise increased hippocampal volume by about 2% in older adults (Erickson et al., 2011) | 3–5 times a week, 30–45 minutes. Take a thinking question with you on walks or runs |
| **Quiet rest** | [Moderate] Brief wakeful rest right after learning ("doing nothing") improves long-term retention (Dewar et al., 2012) | Breaks between blocks **without your phone**: walk, daydream, look out the window |
| **Curiosity** | [Moderate] In a state of curiosity, memory improves, even for incidental information (Gruber et al., 2014) | Start every session with a question you genuinely want answered. That's what the Predict step is for |

### 7.2 The environment layer

- A fixed place to study, your phone isolated, one window open.
- A dedicated AI learning project (learning mode on, or P0).
- **Pen and paper** for predictions and closed-book recall. You can't casually ask an AI about something written on paper.

### 7.3 A daily template

**Full sprint day (6–8 hours)**

| Time | What | Notes |
|---|---|---|
| 15 min after waking | Closed-book recall of yesterday (out loud or on paper) | No notes |
| Deep block 1 (90 min) | One full loop on a new concept | No AI, or only the learning project |
| 15 min break | Walk, daydream | No phone |
| Deep block 2 (90 min) | Another concept loop, or focused practice | Mix in older problems |
| Lunch + 20 min nap | | |
| Build block (2 h) | Project work under the driver rule | More AI allowed, but you must be able to explain every part |
| Review block (30 min) | Anki + redo past mistakes | |
| Exercise (30–45 min) | Aerobic | Take a thinking question |
| Evening (30 min) | Learning log; set tomorrow's first task; write "what I learned today" for a layperson | |
| 5 min before bed | Quickly recall today's 3 most important points | |
| Sleep 7–9 h | | No late nights |

**Part-time day (about 2 hours)**

| Time | What |
|---|---|
| Commute or spare moments | 20 min of Anki, plus one thinking question |
| 60 min in the evening | One concept loop |
| 30 min | Practice or project |
| 10 min | Log; recall before bed |

### 7.4 The weekly rhythm

- **Monday–Friday**: concept loops + project
- **Saturday**: push the bigger project forward; write one synthesis blog post
- **Sunday**: unplug test, weekly review (P11), rewrite the one-page overview, **then rest**

### 7.5 Learning log template

```
Date:
Today's single goal:
New concepts (written closed-book, one sentence each):
Problems solved alone / problems that needed hints (highest hint level used):
Most valuable mistake today:
AI mistakes I caught today (if any):
What I still don't get (tomorrow's pretest questions):
First task tomorrow:
```

---

## 8. A 30-day sprint: template and example

### 8.1 The general template

| Phase | Days | Goal | Output |
|---|---|---|---|
| Target + Map | 1–2 | Map, diagnostic, choose the spine resource | Ability checklist, final exam spec, one-page map v1 |
| Skeleton | 3–6 | Master 5–9 big ideas | One-page overview v1, first small project |
| Deep loops I | 7–13 | Loop through core concepts one by one | Second small project, weekly test #1 |
| Deep loops II | 14–20 | Remaining core concepts + interleaved practice | Medium project, blog post #1, weekly test #2 |
| Integrate & build | 21–27 | A real project; shore up weak spots | Real project, blog post #2, weekly test #3 |
| Graduate | 28–30 | Final exam (no AI), review | Exam result, one-page overview v4, plan for the next phase |

### 8.2 Example: 30 days from zero to understanding LLM inference and its hardware bottlenecks

> Assumed starting point: you can write Python and have taken linear algebra, but you don't know machine learning. You have some digital-design or FPGA background, which makes a perfect set of hooks.

**Ability checklist**

1. Implement a single-layer Transformer forward pass from scratch in NumPy (attention, MLP, LayerNorm), and explain the tensor shape at every step.
2. Given a model's parameter count, numeric precision, context length and batch size, estimate memory use (weights + KV cache) and the theoretical lower bound on per-token latency.
3. Use the roofline model to tell whether prefill and decode are compute-bound or bandwidth-bound, and explain why decode at small batch sizes is usually bandwidth-bound.
4. Read the abstracts of optimization papers on quantization, FlashAttention and speculative decoding, and say which bottleneck each one relieves.

**Final exam** (no AI, 3 hours): given a 7B model's configuration and a piece of hardware's specs, (a) estimate memory requirements and the upper bound on decode throughput; (b) identify the main bottleneck and propose two optimizations with their costs; (c) write pseudocode for the attention forward pass by hand.

**Skeleton (big ideas)**: tokens and embeddings → attention → the Transformer block → autoregressive generation → KV cache → arithmetic intensity and the roofline → quantization → batching and parallelism

| Week | Focus | Project or output |
|---|---|---|
| Week 1 | Skeleton + attention | Compute attention over 3 tokens by hand; implement attention in NumPy |
| Week 2 | The Transformer block, generation, KV cache | Implement the full forward pass; blog post: "Why the KV cache eats so much memory" |
| Week 3 | Arithmetic intensity, memory bandwidth vs compute, the roofline | Write an inference performance estimator in Python |
| Week 4 | Quantization, FlashAttention, speculative decoding | Read the abstracts and key figures of 3 papers; take the final exam |

**Use what you already know as hooks**: hardware concepts like memory bandwidth, on-chip buffers and multiply-accumulate units are ready-made anchors for understanding the roofline model and FlashAttention. That's the "compression ratio" from Section 1.2 at work.

### 8.3 Realistic expectations

At 3–4 hours a day, 30 days is roughly 100 hours. If you stick to the method, you can reasonably expect to reach "competent beginner": you can follow mainstream discussion in the field, complete entry-level real tasks, tell whether an AI's answers hold up, and know what to learn next. It **won't** make you an expert in 30 days, but it can cut roughly half of the wasted detours [Inference].

---

## 9. Metrics: how do you know you've maxed out your bandwidth?

| Metric | Target range | Notes |
|---|---|---|
| Share of time on output | ≥ 60% | Retrieval, explaining, practice, projects |
| Think-before-you-ask rate | ≥ 90% | Counting only questions in your target field |
| Practice accuracy | 70–85% | Above 90%, make it harder; below 60%, make it easier. The "85% rule" (Wilson et al., 2019) comes from computational models; treat it as a guide |
| Anki retention | 85–90% | |
| Average hint level | Falling week by week | You need less help over time |
| Unplug test score | Rising week by week | **The most important metric** |
| High-confidence errors | Falling week by week | Your calibration is improving |
| Concepts you can explain clearly | Share of the map lit up | |
| Public output per week | ≥ 1 piece | |

---

## 10. Limitations and open questions

- Much of learning science comes from lab studies (word lists, short texts); effects usually shrink in real classrooms.
- Most AI learning studies are short and small, many are still working papers, and some contradict each other (Harvard vs Maryland), which shows how much design and context matter.
- Individual differences are large. No method fits everyone.
- The "effective learning bandwidth" formula in this post is a heuristic framework, not a measured scientific quantity.
- Nobody knows the long-term answer: after years of AI-assisted learning, what will people's abilities look like?

**My suggestion**: treat this method as a set of **hypotheses**, and run the experiment on yourself using the metrics in Section 9. That in itself is building in public.

---

## References

**AI and learning**

- Bastani, H. et al. (2025). Generative AI without guardrails can harm learning: Evidence from high school mathematics. *PNAS*, 122(26). [SSRN](https://papers.ssrn.com/abstract=4895486) · [Wharton summary](https://knowledge.wharton.upenn.edu/article/without-guardrails-generative-ai-can-harm-education)
- Kestin, G., Miller, K. et al. (2025). AI tutoring outperforms in-class active learning. *Scientific Reports*, 15, 17458. [PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC12179260/)
- World Bank (2025). From chalkboards to chatbots: Evaluating the impact of generative AI on learning outcomes in Nigeria. [World Bank Blog](https://blogs.worldbank.org/en/education/From-chalkboards-to-chatbots-Transforming-learning-in-Nigeria)
- Shen, J. H. & Tamkin, A. (2026). How AI assistance impacts the formation of coding skills. [Anthropic](https://www.anthropic.com/research/AI-assistance-coding-skills) · [arXiv:2601.20245](https://arxiv.org/abs/2601.20245)
- Kosmyna, N. et al. (2025). Your Brain on ChatGPT: Accumulation of cognitive debt when using an AI assistant for essay writing task. [arXiv:2506.08872](https://arxiv.org/abs/2506.08872)
- Lee, H.-P. et al. (2025). The impact of generative AI on critical thinking. *CHI '25*. [PDF](https://advait.org/files/lee_2025_ai_critical_thinking_survey.pdf)
- Liu, J., Sweet, T. et al. (2026). The effects of course-integrated AI tutoring on student performance and engagement: A randomized university trial. *EdWorkingPaper* 26-1598. [UMD](https://edsi.umd.edu/publications/effects-course-integrated-ai-tutoring-student-performance-and-engagement-randomized)
- Anthropic (2025). Anthropic Education Report: How university students use Claude. [Anthropic](https://www.anthropic.com/news/anthropic-education-report-how-university-students-use-claude)

**Cognitive and learning science**

- Zheng, J. & Meister, M. (2025). The unbearable slowness of being: Why do we live at 10 bits/s? *Neuron*. [arXiv:2408.10234](https://arxiv.org/abs/2408.10234)
- Cowan, N. (2001). The magical number 4 in short-term memory. *Behavioral and Brain Sciences*, 24(1).
- Chase, W. G. & Simon, H. A. (1973). Perception in chess. *Cognitive Psychology*, 4(1).
- Dunlosky, J. et al. (2013). Improving students' learning with effective learning techniques. *Psychological Science in the Public Interest*, 14(1). [APS press release](https://www.psychologicalscience.org/news/releases/which-study-strategies-make-the-grade.html)
- Roediger, H. L. & Karpicke, J. D. (2006). Test-enhanced learning. *Psychological Science*, 17(3).
- Cepeda, N. J. et al. (2008). Spacing effects in learning: A temporal ridgeline of optimal retention. *Psychological Science*, 19(11). [PubMed](https://pubmed.ncbi.nlm.nih.gov/19076480/)
- Rohrer, D. et al. (2020). A randomized controlled trial of interleaved mathematics practice. *Journal of Educational Psychology*, 112(1).
- Richland, L. E., Kornell, N. & Kao, L. S. (2009). The pretesting effect. *Journal of Experimental Psychology: Applied*, 15(3). [PDF](https://learninglab.uchicago.edu/Pre-Testing_files/RichlandKornellKao.pdf)
- Kornell, N., Hays, M. J. & Bjork, R. A. (2009). Unsuccessful retrieval attempts enhance subsequent learning. *JEP: Learning, Memory, and Cognition*, 35(4).
- Kornell, N. & Bjork, R. A. (2008). Learning concepts and categories: Is spacing the "enemy of induction"? *Psychological Science*, 19(6).
- Sinha, T. & Kapur, M. (2021). When problem solving followed by instruction works: Evidence for productive failure. *Review of Educational Research*, 91(5).
- Chi, M. T. H. et al. (1989). Self-explanations. *Cognitive Science*, 13(2).
- Sweller, J. (1988). Cognitive load during problem solving. *Cognitive Science*, 12(2).
- Kalyuga, S. et al. (2003). The expertise reversal effect. *Educational Psychologist*, 38(1).
- Butterfield, B. & Metcalfe, J. (2001). Errors committed with high confidence are hypercorrected. *JEP: LMC*, 27(6).
- Nestojko, J. F. et al. (2014). Expecting to teach enhances learning and organization of knowledge in free recall of text passages. *Memory & Cognition*, 42(7).
- Gentner, D., Loewenstein, J. & Thompson, L. (2003). Learning and transfer: A general role for analogical encoding. *Journal of Educational Psychology*, 95(2).
- Wilson, R. C. et al. (2019). The Eighty Five Percent Rule for optimal learning. *Nature Communications*, 10, 4646. [PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC6831579)
- Ericsson, K. A., Krampe, R. T. & Tesch-Römer, C. (1993). The role of deliberate practice in the acquisition of expert performance. *Psychological Review*, 100(3).
- Bloom, B. S. (1984). The 2 sigma problem. *Educational Researcher*, 13(6).
- Nickow, A., Oreopoulos, P. & Quan, V. (2020). The impressive effects of tutoring on PreK-12 learning. *NBER Working Paper* 27476.
- Pashler, H. et al. (2008). Learning styles: Concepts and evidence. *PSPI*, 9(3).
- Rayner, K. et al. (2016). So much to read, so little time. *PSPI*, 17(1).
- Simons, D. J. et al. (2016). Do "brain-training" programs work? *PSPI*, 17(3).

**Physiology and habits**

- Yoo, S.-S. et al. (2007). A deficit in the ability to form new human memories without sleep. *Nature Neuroscience*, 10(3). [PubMed](https://pubmed.ncbi.nlm.nih.gov/17293859/)
- Erickson, K. I. et al. (2011). Exercise training increases size of hippocampus and improves memory. *PNAS*, 108(7).
- Dewar, M. et al. (2012). Brief wakeful resting boosts new memories over the long term. *Psychological Science*, 23(9).
- Gruber, M. J., Gelman, B. D. & Ranganath, C. (2014). States of curiosity modulate hippocampus-dependent learning. *Neuron*, 84(2).
- Leroy, S. (2009). Why is it so hard to do my work? The challenge of attention residue. *Organizational Behavior and Human Decision Processes*, 109(2).
- Gollwitzer, P. M. (1999). Implementation intentions. *American Psychologist*, 54(7).

**Books and ideas**

- Plato, *Phaedrus* 274c–275b (trans. Benjamin Jowett)
- Simon, H. A. (1971). Designing organizations for an information-rich world.
- Willingham, D. T. (2009). *Why Don't Students Like School?*
- Polanyi, M. (1966). *The Tacit Dimension*.
- Young, S. H. (2019). *Ultralearning*.
- Pólya, G. (1945). *How to Solve It*.
- Keshav, S. (2007). How to read a paper. *ACM SIGCOMM CCR*, 37(3).
- Anki's notes on FSRS: [Anki FAQ](https://docs.ankiweb.net/faqs/what-spaced-repetition-algorithm)
