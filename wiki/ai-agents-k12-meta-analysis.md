# AI Agents in K-12: Meta-Analysis of Cognitive Outcomes

**Summary**: A 2026 meta-analysis (Liu et al.) synthesizing 34 experimental studies and 73 effect sizes on AI agent effectiveness in K-12 cognitive learning — finding a significant moderate overall effect (g = 0.404), but with effectiveness that varies sharply by grade level (upper-primary strongest; high school near-zero) and subject (language/literacy strong; natural science negative).

**Sources**: `raw/Meta-analysis on the influence of AI agents on K-12 student cognitive performance.md`

**Last updated**: 2026-05-12

---

## Overview

*Meta-analysis on the influence of AI agents on K-12 student cognitive performance* was published in 2026 in *Computers in Human Behavior Reports* (DOI: 10.1016/j.chbr.2026.100973), authored by Ji Liu, Airini Erasmi Mbowe, Dahman Tahri, and Millicent Aziku. It is an open-access study using a random-effects meta-analytic approach.

**Sample**: 34 experimental and quasi-experimental studies published January 2020–December 2025; 73 effect sizes; 3,042 total participants (1,495 experimental, 1,472 control). Studies span Asia (67.65%), Europe (14.71%), Africa (8.82%), and North America (8.82%).

**Scope**: AI agents as instructional interventions compared to conventional methods on student cognitive learning outcomes, categorized as knowledge-based outcomes, skills-based outcomes, and higher-order thinking skills.

**AI types coded**: Intelligent Tutoring Systems (ITS), AI Educational Robots, Generative AI Agents, Conversational AI Agents.

This study complements the [[evidence-base-ai-k12]] report (Stanford SCALE, 2026), which found zero high-quality U.S. K–12 causal studies. The Liu et al. meta-analysis provides the broadest available quantitative synthesis — but with a very different profile: predominantly Asian contexts, quasi-experimental designs, and structured AI interventions rather than general-purpose chatbots.

---

## Overall Effect

**g = 0.404** (95% CI [0.242, 0.567], p < 0.001) — a statistically significant, moderate positive effect of AI agents on K-12 student cognitive outcomes compared to conventional instruction.

This is a non-trivial result: AI educational interventions, when designed intentionally, show reliable moderate benefits. However, the finding requires careful interpretation (see Limitations).

High heterogeneity across studies: Q = 813.560 (p < 0.001), I² = 91.2% — well above the 75% threshold indicating high variability. The average effect is positive, but individual study results vary enormously. This heterogeneity is why moderator analysis is essential.

**Effect size distribution** across 73 effects:
- Large (g ≥ 0.8): 17.81% of effects
- Moderate (0.5 ≤ g < 0.8): 10.95%
- Small positive (0.2 ≤ g < 0.5): 21.92%
- Negligible or negative (g < 0.2): **49.32%**

Nearly half of individual effect sizes are negligible or negative — the positive overall average is driven by a subset of strong studies, not a consistent pattern.

---

## Finding 1: Cognitive Category Effects

| Cognitive Category | k | Hedges' g | Significant? |
|-------------------|---|-----------|-------------|
| Skills-based outcomes | 42 | 0.391 | Yes (p < 0.001) |
| Knowledge-based outcomes | 18 | 0.344 | Yes (p = 0.026) |
| Higher-order thinking | 13 | 0.540 | **No** (p = 0.066) |

**Key finding**: AI agents show the most consistent benefit for **procedural skills development** (problem-solving, computational skills, oral fluency, writing) — cognitive work involving practice, feedback, and application. Knowledge acquisition (factual recall, conceptual understanding) shows smaller but significant benefits. Higher-order thinking shows the largest effect size but is not statistically significant, with extremely high heterogeneity (I² = 95.4%).

The interpretation: AI agents are better at supporting "practice until mastery" modes of learning than at developing the deep analytical reasoning, creative synthesis, and inquiry skills associated with higher-order cognition. This is consistent with [[agentivism]]'s concern that AI-assisted task completion does not automatically produce durable understanding or transfer.

---

## Finding 2: Grade Level Effects (Most Significant Moderator)

| Learner Level | k | Hedges' g | Significant? |
|--------------|---|-----------|-------------|
| Upper-primary (Grades 4–6) | 28 | **0.877** | Yes (p < 0.001) |
| Lower-primary (Grades 1–3) | 8 | 0.237 | Yes (p < 0.05) |
| Lower-secondary (Grades 7–9) | 17 | 0.195 | Yes (p < 0.05) |
| Upper-secondary/High school (Grades 10–12) | 19 | **0.037** | **No** (p > 0.05) |

Between-group test: Q_B = 12.97, **p = 0.005** — learner level is a statistically significant moderator.

**The grade-level finding is the study's most actionable result**:

- AI agents are **most effective in upper-primary school** (grades 4–6), the developmental window when students are transitioning from basic to complex cognitive skills. This is where adaptive feedback and guided interactivity have the greatest leverage — students are ready for abstract reasoning but still benefit from structured support.
- **High school students (grades 10–12) show near-zero, non-significant effects** from AI interventions. At this stage, students are preparing for examinations and future careers; the procedural scaffolding that makes AI useful for younger students may not match what older students need. The authors suggest self-regulated learning approaches may be more appropriate at the upper-secondary level.
- The pattern suggests AI interventions should be prioritized earlier in the K-12 pipeline, with different designs for older students.

---

## Finding 3: Subject/Discipline Effects (Also Significant)

| Discipline | k | Hedges' g | Significant? |
|-----------|---|-----------|-------------|
| Language and Literacy | 28 | **0.830** | Yes (p < 0.001) |
| Arts and Creativity | 4 | 0.755 | Yes (p < 0.05) |
| Mathematics and Technology | 28 | 0.230 | Yes (p < 0.01) |
| Natural Science | 11 | **−0.065** | **No** (p > 0.05) |

Between-group test: Q_B = 7.61, **p = 0.006** — discipline is a statistically significant moderator.

**Language and literacy** shows the largest significant effect (g = 0.830). AI agents — especially conversational AI and educational robots that provide interactive dialogue, corrective feedback, and repetitive practice — are well-suited to vocabulary acquisition, oral reading fluency, EFL writing, and literacy skill development.

**Natural science shows a non-significant negative effect** (g = −0.065). Science learning requires open-ended inquiry, hypothesis testing, and experimentation — modes of cognition that most current AI agents are not designed to support. The procedural scaffolding that helps in literacy may actively constrain authentic scientific inquiry.

**Mathematics and technology** shows a small but significant positive effect (g = 0.230), lower than language/literacy. Possible explanation: math problem-solving at K-12 level requires more than step-by-step guidance; pattern recognition and conceptual understanding may require different approaches than AI's feedback loop.

---

## Finding 4: AI Type Effects (Non-Significant Moderator)

| AI Agent Type | k | Hedges' g | Significant? |
|--------------|---|-----------|-------------|
| Intelligent Tutoring Systems | 10 | 0.540 | Yes |
| AI Educational Robots | 16 | 0.474 | Yes |
| Conversational AI Agents | 30 | 0.468 | Yes |
| Generative AI Agents | 17 | 0.421 | Yes |

Between-group test: Q_B = 0.069, **p = 0.793 — AI type is NOT a significant moderator**.

All four AI types show significant positive effects on cognitive outcomes. The differences between types are not statistically significant. ITS has the highest point estimate, GenAI the lowest — but the overlap in confidence intervals means the ordering is not reliable.

**Important caveat**: The GenAI agents in these studies are not general-purpose chatbots used for homework help. They are intentionally designed instructional interventions with structured tasks and feedback. This result does not contradict the [[evidence-base-ai-k12]] finding that general-purpose AI harms learning — it addresses a different condition (designed GenAI interventions vs. conventional instruction, not ChatGPT-style tools vs. unaided work).

---

## Finding 5: Intervention Duration (Non-Significant Moderator)

| Duration | k | Hedges' g | Significant? |
|---------|---|-----------|-------------|
| < 1 month | 14 | 0.244 | Yes |
| 1–3 months | 22 | 0.385 | Yes |
| > 3 months | 6 | 0.650 | No |
| Not mentioned | 31 | 0.463 | Yes |

Between-group test: Q_B = 0.23, **p = 0.632 — duration is NOT a significant moderator**.

Longer interventions trend toward larger effects, but the trend does not reach statistical significance (and the >3 months group has only 6 studies). There is no evidence that brief AI interventions are inherently less effective than longer ones — though the authors note that very short interventions may produce superficial engagement without deep internalization.

---

## Publication Bias

The trim-and-fill method found **no missing studies** needed to restore funnel plot symmetry — the strongest test for publication bias in meta-analysis. The Classic fail-safe N indicates 378 additional null studies would be needed to reduce the overall effect to non-significance — well above the 180 required for confidence (5k + 10, where k = 34 studies).

Publication bias does not appear to be driving the overall positive result.

---

## Limitations

1. **Geographic skew**: 67.65% of studies from Asian contexts (primarily China). The applicability to Western and U.S. K-12 settings is uncertain — different curricular structures, technological infrastructure, teaching practices, and cultural norms around AI use.

2. **High heterogeneity** (I² = 91.2%): The average effect is reliable, but the range is enormous. The positive average conceals many near-zero and negative individual effects. Context matters far more than the pooled number suggests.

3. **Quasi-experimental designs**: The meta-analysis includes quasi-experimental studies, which typically show inflated effects compared to RCTs. The Stanford SCALE review, which applies stricter What Works Clearinghouse standards, found only 20 studies meeting strong causal criteria — this meta-analysis's 34 studies use a more permissive threshold.

4. **Designed AI interventions, not general-purpose tools**: The AI agents studied are structured educational interventions. Findings do not directly address what happens when students use ChatGPT or Claude for homework assistance. See [[evidence-base-ai-k12]] for that evidence — which shows harms for general-purpose AI.

5. **Cognitive outcomes only**: No data on emotional, motivational, or social outcomes. No data on [[cognitive-debt]] accumulation — the measure of what happens to independent capability over time.

6. **No quality appraisal of individual studies**: The authors note this explicitly — without formal risk-of-bias assessment, internal validity of primary studies cannot be systematically evaluated.

---

## Reconciling with the Wiki's Existing Evidence

This meta-analysis is in **partial tension** with the [[evidence-base-ai-k12]] report, which emphasizes harms of AI for student learning. The reconciliation requires understanding what each is measuring:

| Dimension | Liu et al. (this study) | Stanford SCALE (evidence-base-ai-k12) |
|-----------|------------------------|---------------------------------------|
| AI type | Designed educational interventions | Predominantly general-purpose chatbots |
| Design | Structured, task-specific | Often unguided access |
| Standard | Quasi-experimental | WWC high-quality causal |
| Geography | 67.65% Asia | Primarily U.S./international |
| Overall finding | Moderate positive average | Harms from general-purpose AI; design is decisive |

The two bodies of evidence are compatible: **intentionally designed AI educational interventions (especially ITS, adaptive systems, and structured conversational agents) produce moderate cognitive benefits — particularly for younger students in language and literacy. General-purpose AI used without pedagogical scaffolding harms independent learning.** Design remains the decisive variable; this meta-analysis quantifies what well-designed interventions can achieve.

The grade-level finding adds an important new dimension: the benefit of any AI educational intervention is substantially modulated by developmental stage, with high school students showing near-zero effects. This has direct implications for AI in CTE (which primarily serves high school and post-secondary students) — the settings where AI cognitive benefits are least well-supported by evidence.

---

## Implications for CTE and K-12

1. **Upper-primary (grades 4–6) is the highest-leverage window** for AI cognitive interventions. CTE frameworks that advocate AI integration should consider front-loading that exposure at the most responsive developmental stage.

2. **High school AI interventions need different designs** — the procedural scaffolding that works in elementary school does not show significant cognitive benefits at the high school level. Self-regulated learning approaches may be more appropriate. This directly applies to most CTE programs, which serve students in grades 9–14.

3. **Language and literacy AI applications are most evidence-supported** — relevant for ELA integration in CTE, ESL students, and professional communication skill development.

4. **Natural science requires redesigned AI tools** — existing AI agents don't support authentic scientific inquiry. CTE programs with strong science components (healthcare, agriculture, environmental tech) should be cautious about AI-for-learning claims.

5. **The design-vs-access distinction remains essential** — this meta-analysis measures designed AI interventions, not ChatGPT access. The positive result here does not license replacing instruction with general-purpose AI tools.

---

## Related pages

- [[evidence-base-ai-k12]]
- [[ai-tutoring]]
- [[agentivism]]
- [[ai-in-k12-education]]
- [[cte-and-ai]]
- [[cognitive-debt]]
- [[khanmigo]]
