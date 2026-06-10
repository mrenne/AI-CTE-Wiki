# AI is Making You Faster AND Slower, Better AND Worse at Your Job

**Summary**: A June 2026 Substack post by Dr. Philippa Hardman synthesizing a new MIT/Wharton study of 100,000+ GitHub developers (Demirer, Musolff & Yang, 2026) into a five-effects taxonomy for AI's actual workplace impact — naming the productivity funnel, the quality drag mechanism, and the "enter high in the chain" strategic principle.

**Sources**: `raw/blog/AI is making you faster AND slower, better AND worse at your job.md`

**Last updated**: 2026-06-10

---

## Overview

Dr. Philippa Hardman is an instructional designer and L&D researcher (cited by Murgatroyd in [[ai-unplugged-murgatroyd]] as essential reading on deploying AI for learning). This post synthesizes Demirer, Musolff & Yang (2026) — the largest workplace AI study in the wiki, tracking 100,000+ GitHub developers across three generations of AI coding tools (autocomplete → "sync" agents → "async" agents) across the entire software production chain, from first line of code to shipped release.

Hardman's contribution is applying this coding data to L&D by analogy, backed by parallel L&D evidence where it exists. This is the first source in the wiki grounded in large-scale *workplace* productivity data rather than educational experiments or economic theory. (source: AI is making you faster AND slower.md)

---

## The Five-Effects Taxonomy

Hardman names five simultaneous effects of AI on work. The first four are measured in the Demirer et al. data; the fifth is a deliberate design choice.

### Effect 1: Faster Creation (+228% to +740%)

The production velocity gain is real and large. Autocomplete raised lines of code by ~228%; newer async agents pushed past 740%. A P&G/NBER field experiment (Dell'Acqua et al., 2026) found that one person working with AI performed as well as a two-person team without it — AI collapsed a whole second role into one.

In L&D: generative AI can automate or accelerate up to ~80% of content creation tasks (LinkedIn workforce data; industry surveys). The speed-up is not in doubt.

### Effect 2: Only ~20% More Shipped

Here the data becomes interesting. All of that production velocity gain drains away at every human-dependent stage upstream:

**The productivity funnel** (Demirer et al., 2026):
> +740% code produced → +65% review requests → only **~20% more shipped releases**

Every stage of human review, integration, and validation absorbs the gain before it converts into finished output. The bottleneck shifts from "can we make it?" to "can humans keep up with reviewing, integrating, and governing what the machine just produced?" Human review capacity hasn't grown with AI production capacity.

Supporting data:
- MIT Project NANDA (2025): ~**95% of organizations** see no meaningful measurable return from GenAI; only ~5% generate real business impact
- RAND (2025): AI project failure rate **above 80%** — twice the rate of comparable non-AI IT projects; the technology usually worked, downstream conversion failed
- Gartner (2025): 60% of AI projects expected to be abandoned without AI-ready data foundations
- L&D analog: most corporate programs still hover around 20–30% completion, and "completion is closer to 'app downloaded' than 'app used a month later.'" Producing learning faster; shipping real capability at roughly the rate before.

### Effect 3: More Complex

Fast production creates a new kind of bottleneck. AI generates more, more verbose output; that volume must be reviewed, integrated, and untangled by humans whose capacity hasn't changed.

> "The upstream got cheaper; the downstream got heavier. That's the trade." (He et al., 2026 — "Speed at the Cost of Quality: How Cursor AI Increases Short-Term Velocity and Long-Term Complexity")

In L&D: without modular, tagged, governed content architecture, fast generation multiplies assets and multiplies the mess — and that cleanup lands on the same human stakeholders, reviewers, and line managers who were already the weak link. (source: AI is making you faster AND slower.md)

### Effect 4: Lower Average Quality

When AI accelerates the cheap, upstream part of work, the average quality of what ships falls.

> "Generic AI confidently reproduces the most common version of whatever you ask for — and is weak on the depth, context, and judgement that separate good work from merely competent work." — Hardman

Evidence:
- Reimers & Waldfogel (2026): LLMs roughly **tripled Amazon book releases** 2022–2025 while average quality declined
- Coding study: new apps surged across four major app stores; total usage stayed flat; share of new apps failing to reach even a modest audience went up
- L&D: SWOT/case-study analyses consistently find unedited AI output is "generic, error-prone and context-insensitive" — dependent on substantial domain expertise and ID skill to reach acceptable standard

The mechanism: AI confidently reproduces common practice, not best practice. The result is a flood of "technically-fine, faintly hollow content" that overwhelms human reviewers, making the quality problem harder to catch precisely because there's so much more content to review.

**Key distinction from the educational evidence**: This is the *workplace* analog to what [[building-ai-companions]] calls the learning-performance paradox and what [[cognitive-debt]] describes neurologically. The mechanism is identical — AI optimized for output quality produces fast, plausible output at the cost of depth — but operating at the organizational level rather than the individual cognitive level. (source: AI is making you faster AND slower.md)

### Effect 5: Better (When Aimed High)

The fifth effect is real but not automatic:

> "In controlled settings, with a scaffolded, domain-specific assistant, AI can genuinely improve instructional-design quality and designer capability, especially when it is embedded in structured workflows, aligned with explicit pedagogical criteria, and used as a co-creative partner rather than a generic idea pump."

Evidence from educational AI design:
- EduPlanner: multi-agent systems with specialised evaluator/optimiser agents and domain-specific rubrics produce higher-quality lesson plans than single-model baselines
- ARCHED (2025) framework: human-centred AI-assisted ID, with educators as primary decision-makers, improves quality without undermining professional judgement
- Knowledge-enhanced GPT-4 with stepwise self-critique against human criteria: gains in lesson-plan coherence and pedagogical soundness

The catch: *better* and *worse* don't come from different tools. They are the same tool, aimed at different parts of the chain. "Point AI at the cheap upstream task — crank out more modules — and you get tidy, generic, common-not-best-practice. Point the same AI at diagnosis, feedback, reinforcement, and judgement — and quality goes up." (source: AI is making you faster AND slower.md)

---

## The "Enter High in the Chain" Principle

The most strategic finding in this source, drawn directly from Demirer et al.:

> "A modest tool that enters high in the production chain beats a powerful tool that enters low, because its gains have fewer human-dependent stages left to drain through."

For L&D and educational AI, this reframes the entire deployment question. The move is not "generate more content, faster" — that's pouring water into the widest part of a funnel that narrows to nothing. The move is to aim AI at the higher layers, nearer to behaviour change: diagnosis, feedback, coaching, reinforcement, application support.

This principle directly validates [[building-ai-companions]]' architectural argument: prompt-level guardrails on a general-purpose content generator enter low in the chain and drain their gains through every human review stage. A purpose-built learning AI (metacognitive calibration, adaptive learner modeling, Socratic scaffolding) enters high — at the stages where behavior change actually lives. (source: AI is making you faster AND slower.md)

---

## The Anthropomorphism Warning

Kropp et al. (2026), cited by Hardman: **"AI buddy/coach/mentor" framing makes reviewers measurably sloppier.**

> "Drop the anthropomorphic language internally, frame AI as a tool that requires human accountability, and name explicitly who owns the quality check on AI-generated learning."

This is a distinct mechanism from [[ai-sycophancy]]. Sycophancy is in the AI's outputs — it validates and agrees. Anthropomorphism reduces the human's critical scrutiny of those outputs — people reviewing work from a "colleague" apply less skepticism than people reviewing output from a tool. They compound each other: a sycophantic AI whose outputs receive reduced human scrutiny because it is framed as a trusted peer produces the maximum reduction in epistemic monitoring.

The framing choice — "AI tool" vs. "AI teammate" — measurably affects review quality in real organizations. (source: AI is making you faster AND slower.md)

---

## Five Practical Strategies

Hardman's recommendations, roughly ordered by leverage:

1. **Stop optimising for speed** — treat fast content generation as solved; redirect budget and attention elsewhere
2. **Point AI up the chain** — diagnosis, feedback, coaching, reinforcement (not content generation); this is the path to Effect 5
3. **Fix the foundation before scaling generation** — modular, tagged, governed content architecture is the precondition for anything agentic to work
4. **Protect the human review layer; stop anthropomorphising** — name who owns the quality check; frame AI as tool, not colleague
5. **Build the instrumentation you don't have** — measure past completion to behaviour change; you can't manage attenuation you can't see

---

## Relationship to Existing Wiki Claims

| Wiki claim | This source's contribution |
|---|---|
| Learning-performance paradox ([[building-ai-companions]]) | Workplace analog at 100K+ scale: production speed up 740%, shipped output up only 20%; same drain mechanism |
| AI optimised for output quality undermines learning ([[evidence-base-ai-k12]]) | Quality drag mechanism: AI reproduces common practice, not best; average quality falls as volume rises |
| Prompt-level guardrails are insufficient ([[building-ai-companions]]) | "Enter high in the chain" principle: powerful tool entering low beats modest tool entering high |
| AI sycophancy reduces critical evaluation ([[ai-sycophancy]]) | Anthropomorphism compounds sycophancy: framing AI as colleague reduces reviewer scrutiny |
| Educator-facing AI shows more consistent positive evidence ([[evidence-base-ai-k12]]) | Validated: Effect 5 (better) only appears with scaffolded, domain-specific, high-chain deployment |
| AI won't automatically transform outcomes ([[ai-unplugged-murgatroyd]], [[stanford-ai-index-education-2026]]) | Hard numbers: 95% no return, 80% failure rate, 60% abandonment without data foundation |

---

## Related pages

- [[hardman-cognitive-offloading-paradox]]
- [[building-ai-companions]]
- [[evidence-base-ai-k12]]
- [[ai-sycophancy]]
- [[agentivism]]
- [[cognitive-debt]]
- [[ai-tutoring]]
- [[labor-market-polarization]]
- [[ai-unplugged-murgatroyd]]
- [[illusion-of-understanding]]
- [[cte-and-ai]]
