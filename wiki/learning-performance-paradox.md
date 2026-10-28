# Learning-Performance Paradox

**Summary**: Concept page for the idea that AI tools reliably raise short-term, measurable performance while weakening the processes that build durable learning. It traces how the idea, named by Khosravi, Gašević, Yan et al. (2026), connects classroom evidence, workplace productivity data, and labor-market signals, and what it implies for CTE.

**Sources**: `raw/PDF/Building AI Companions.pdf`, `raw/PDF/The Evidence Base on AI in K-12 Report.pdf`, `raw/PDF/Your Brain on ChatGPT.pdf`, `raw/PDF/Agentivism.pdf`, `raw/PDF/One Click Away.pdf`, `raw/blog/AI is making you faster AND slower, better AND worse at your job.md`, `raw/PDF/Gradiating into Disruption.pdf`, `raw/blog/Is your organisation at risk of 'experience debt' from AI_.md`

**Last updated**: 2026-10-28

---

## Definition

The **learning-performance paradox** is the gap between what a learner can produce *with* AI and what they can do *without* it. AI tools reliably improve short-term task performance while undermining the cognitive processes that produce durable learning: elaboration, productive struggle, memory consolidation, and metacognitive monitoring (source: Building AI Companions.pdf).

The name comes from [[building-ai-companions]] (Khosravi, Gašević, Yan et al., 2026), whose core claim is that "AI tools optimized for work contexts... are inherently misaligned with learning contexts" (source: Building AI Companions.pdf). Three features distinguish the idea from older worries about cheating:

- **It operates in good faith.** A student who honestly uses AI to finish an assignment still skips the struggle that would have built the skill.
- **It is structural, not a misuse problem.** Tools built to minimize friction and maximize output quality are doing what they were designed for; the mismatch is between the tool and the setting (source: Building AI Companions.pdf).
- **It is invisible in the output.** Because performance improves, the usual signals that learning is failing (low grades, visible errors) do not appear.

## Work AI vs. learning AI

The paper's design taxonomy sets out why the same tool cannot serve both purposes: work AI treats errors as defects, minimizes friction, and measures success by output quality; learning AI treats errors as information, preserves productive struggle, and measures success by retention and transfer (source: Building AI Companions.pdf). Most deployed tools, including the general-purpose chatbots students use, are built for work. See [[building-ai-companions]] for the full nine-dimension table.

## The evidence

The paradox is a framing, not a single finding. The evidence behind it comes from several kinds of study:

| Evidence | What it shows | Source |
|---|---|---|
| Bastani et al. (2025), ~1,000 Turkish high-school students | General-purpose AI raised practice performance, then students did *worse* than textbook users on an unassisted exam; a hint-only tutoring AI matched the textbook group | The Evidence Base on AI in K-12 Report.pdf |
| Fischer et al. (2025), "crutch effect" | Unfettered AI raised practice grades but cut unassisted exam performance by 17%; a guardrailed tutor interface reduced the drop | The Evidence Base on AI in K-12 Report.pdf |
| Kosmyna et al. (2025), essay writing with EEG | AI-assisted writers showed weaker recall of their own essays and reduced neural connectivity; the effect persisted after the tool was removed ([[your-brain-on-chatgpt]], [[cognitive-debt]]) | Your Brain on ChatGPT.pdf |
| Socratic-chatbot studies | Students rated question-asking tutors *less helpful* than answer-giving ones despite better critical-thinking outcomes: preference and learning diverge | The Evidence Base on AI in K-12 Report.pdf |
| Prompt-level guardrails | Instructions like "be a Socratic tutor" added to general-purpose AI show near-null effects on learning outcomes | Building AI Companions.pdf |

The strongest evidence is the **practice-versus-exam pattern**: when assisted and unassisted performance are measured separately, they move in opposite directions (source: The Evidence Base on AI in K-12 Report.pdf).

### Where the evidence is less clean

The largest US school trial does not fit the paradox neatly. In the two-year Khanmigo trial ([[one-click-away-khanmigo-rct]]), students did not show inflated assisted performance followed by an unassisted crash. Instead they mostly *did not use* the tutor's help: the median student messaged it on a third of practice days, and only 14.5% of messages contained real mathematical reasoning. Achievement gains matched what structured practice without AI predicts (source: One Click Away.pdf). Help-avoidance, not over-reliance, was the binding problem. The wiki treats this as a neighboring failure mode with the same lesson (task activity is not learning), not as a direct test of the paradox.

The paradox also depends on how AI is used. [[hardman-cognitive-offloading-paradox]] argues that large, deliberate delegation paired with structured reflection ("Zone 3") can free capacity for higher-order thinking rather than eroding it. The paradox describes undesigned use, not every use.

## Beyond the classroom

The same short-term-gain, deferred-cost structure appears in the wiki's workplace and labor-market sources:

- **Workplace productivity.** Hardman's productivity funnel (+740% code produced, only ~20% more shipped) shows assisted production rising while the human stages downstream absorb the gain; [[building-ai-companions]] and [[hardman-ai-faster-slower]] call this the workplace analog of the paradox (source: AI is making you faster AND slower, better AND worse at your job.md).
- **Hiring signals.** The Census graduate study proposes that if AI raises grades and work samples without building skill, those signals lose value to employers, and new graduates, who have little else to show, bear the cost. The authors present this as a plausible channel, not an established one (source: Gradiating into Disruption.pdf; see [[graduating-into-disruption-census]]). This is the wiki's first link from the paradox to labor-market outcomes.
- **Organizations.** Dayforce's "experience debt" names the organizational version: 65% of survey respondents say their people are losing the ability to do tasks AI now does for them (source: Is your organisation at risk of 'experience debt' from AI_.md; see [[experience-debt-dayforce]]). It is self-reported vendor survey data, so it is a parallel concept rather than corroboration.

## Related concepts

- **[[cognitive-debt]]**: the measured, cumulative cost (Kosmyna et al.'s EEG and recall evidence). The paradox is the name for the mismatch that produces it; cognitive debt is what builds up over time.
- **[[agentivism]]**: the learning theory behind the paradox. Durable learning requires the learner to monitor and rework AI output; passive receipt skips that step (source: Agentivism.pdf).
- **[[illusion-of-understanding]]**: why learners do not notice. AI fluency feels like accuracy, so the signals that would prompt self-correction never fire.
- **[[ai-sycophancy]]**: agreeable AI output further lowers the scrutiny that could catch the problem.

## Implications for CTE

These are the wiki's inferences from the sources above, not claims made by them.

1. **Assess without the tool.** The paradox is only visible when assisted and unassisted performance are measured separately. CTE's performance assessments, practical exams, and industry credentials already do this, and the Census paper's signal-erosion argument suggests employers will value such hard-to-fake evidence more (source: Gradiating into Disruption.pdf).
2. **Match the tool to the purpose.** Using AI in the workflow it will be used in on the job is training for work; learning a skill for the first time calls for learning-oriented tools or no AI at all. The [[applied-co-intelligence-model]] continuum and the [[ai-mastery-continuum]] both stage AI use by competence level.
3. **Protect the struggle in work-based learning.** Apprenticeships and internships that hand juniors AI-supervision duties before they have done the underlying work risk reproducing the paradox on the job ([[work-based-learning]]).
4. **Do not rely on prompt-level fixes.** Telling a general-purpose chatbot to act as a tutor shows near-null effects on learning (source: Building AI Companions.pdf); program-level design choices matter more.

## Related pages

- [[building-ai-companions]]
- [[cognitive-debt]]
- [[agentivism]]
- [[illusion-of-understanding]]
- [[evidence-base-ai-k12]]
- [[your-brain-on-chatgpt]]
- [[one-click-away-khanmigo-rct]]
- [[khanmigo]]
- [[ai-tutoring]]
- [[hardman-ai-faster-slower]]
- [[hardman-cognitive-offloading-paradox]]
- [[graduating-into-disruption-census]]
- [[experience-debt-dayforce]]
- [[work-based-learning]]
- [[ai-sycophancy]]
- [[applied-co-intelligence-model]]
- [[ai-mastery-continuum]]
- [[cte-and-ai]]
