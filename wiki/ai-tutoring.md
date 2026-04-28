# AI Tutoring

**Summary**: The use of AI systems to provide personalized, interactive instruction to students — an approach that has shown limited real-world adoption despite technical promise, and which raises fundamental questions about whether AI-assisted interaction constitutes genuine learning.

**Sources**: `raw/The education of Sal Khan and the limits of his chatbot.md`, `raw/Applied-Co-Intelligence–Preparing-Career-and-Technical-Education-Learners-for-an-AI-Driven-Workforce-FINAL.pdf`, `raw/Agentivism.pdf`, `raw/The Evidence Base on AI in K-12 Report.pdf`, `raw/Your Brain on ChatGPT.pdf`

**Last updated**: 2026-04-28

---

## Overview

AI tutoring refers to the use of large language models and other AI systems to provide individualized, responsive instruction — simulating the benefits of a human tutor. The concept gained widespread attention after Sal Khan's 2023 TED Talk invoked Bloom's 2-sigma research (1984), which found individualized tutoring produced two standard deviations of learning improvement over conventional instruction.

## The Promise

The theoretical case for AI tutoring is strong:
- Available 24/7 at zero marginal cost per additional student
- Can adapt to individual pace, knowledge gaps, and learning style
- Provides immediate, patient, non-judgmental feedback
- Could democratize access to high-quality, individualized instruction at scale

## The Reality: Evidence is Limited

The [[evidence-base-ai-k12]] report (Stanford SCALE, 2026) reviewed 818 papers and found only 20 with strong causal evidence — and zero high-quality causal studies of student learning in U.S. K–12 settings (source: The Evidence Base on AI in K-12 Report.pdf). The most prominent real-world deployment, [[khanmigo]], has largely underperformed:

- Most students don't proactively seek out AI tutoring when given the option
- Students struggle to formulate useful questions
- Even students who engage may do so passively — receiving information without building durable understanding
- Teacher enthusiasm has been consistently lower than administrator enthusiasm

## The Learning Theory Problem

[[Agentivism]] provides the theoretical explanation for AI tutoring's limitations (source: Agentivism.pdf). Students interacting with an AI tutor without engaging in:
- **Epistemic monitoring** (evaluating whether the AI's explanation is correct, relevant, adequate)
- **Reconstructive internalization** (reworking the AI's explanation into their own understanding)

...may feel they understand material, or produce correct answers, without having developed durable capability. The AI does the cognitive work; the student receives the output.

The Khanmigo failure — students not seeking out help — is actually the more optimistic failure mode. The more concerning failure mode is students who engage with AI tutoring but passively accept AI explanations, experiencing what Agentivism calls "metacognitive laziness": stronger surface performance with no corresponding knowledge gain.

## The Crutch Effect: Causal Evidence

The [[evidence-base-ai-k12]] report provides the first systematic causal evidence on what AI tutoring actually does to student learning. The findings are sobering for general-purpose AI, and more nuanced for tutoring-specific tools.

**General-purpose AI harms independent learning** (source: The Evidence Base on AI in K-12 Report.pdf):
- Bastani et al. (2025, Turkey): Students with general-purpose AI access scored *worse* on a closed-book exam than peers who used only a textbook. Their practice performance was higher — the crutch was invisible until support was removed.
- Fischer et al. (2025): Unfettered AI access improved practice grades but caused a **17% performance drop** on unassisted exams. Pedagogical guardrails that required student engagement ("GPT Tutor") mitigated this effect.
- Kosmyna et al. (2025): AI essay writing reduced brain activity and recall. 83% of AI essay writers couldn't quote from their own essay afterward; only 11% of search-engine or no-tool users showed this failure. The full [[your-brain-on-chatgpt]] study adds a neurological mechanism (EEG): LLM users showed up to 55% reduced directed neural connectivity in semantic and memory networks. The content passed through their hands but not their minds — bypassing the theta and alpha wave activity required for episodic memory consolidation. Repeated over sessions, this produces [[cognitive-debt]]: participants who wrote AI-assisted essays for three sessions and then wrote without tools showed brain connectivity *below the baseline of peers who had never practiced at all*.
- Lehmann et al. (2025): Unrestricted AI access widened achievement gaps for students with low prior knowledge.

**Tutoring-specific design narrows the gap**: The Bastani et al. study also tested a tutoring-specific AI that gave hints without direct answers. These students performed *the same as the textbook control group* — not better, but not worse either. Pedagogical design (guided hints vs. complete answers) was the decisive variable.

**The Socratic chatbot paradox**: Two studies examined Socratic AI chatbots (which ask probing questions rather than providing answers). Students rated them as *less helpful* than direct-answer chatbots while showing better outcomes for critical and reflective thinking. Students' stated preferences reliably diverge from their learning interests — they prefer the experience that teaches them less.

**Dr. Bastani's key question**: "Students keep bypassing heuristic guardrails — can we build a 'science of guardrails' to understand what works in education?" (source: The Evidence Base on AI in K-12 Report.pdf)

## AI for Educator Development

A distinct and more consistently positive evidence base covers educator-facing AI — tools that augment teachers rather than (or in addition to) students.

**Time efficiency**: ChatGPT saved teachers ~25 minutes per week (27–31% reduction) on lesson preparation with no detectable loss in lesson quality based on blind expert ratings (Roy et al., 2024). Notably, teachers' use of AI became *more selective* over time even as time savings persisted — suggesting they learned where AI adds value.

**Real-time instructional coaching**: Tutor CoPilot (Wang et al., 2025) provided tutors with real-time expert-like suggestions during math sessions in a 900-tutor RCT. Student topic mastery improved by 4 percentage points overall — rising to 7 pp for students of less experienced tutors and 9 pp for students of lower-rated tutors (source: The Evidence Base on AI in K-12 Report.pdf).

**The expertise reversal equity finding**: The Tutor CoPilot finding is significant for equity: AI pedagogical supports benefit *less experienced and lower-rated* educators most. Since under-resourced schools disproportionately employ novice teachers, equitably deployed AI coaching could reduce instructional quality gaps between schools — a meaningful inversion of the usual pattern where better-resourced institutions benefit most.

**Dr. Dora Demszky's design distinction** (Stanford): AI tools that *automate* teacher tasks risk skill degradation and don't guarantee instructional quality. AI tools that *build* teacher capacity — through consistent, customized feedback — are the higher-value design goal. The latter are most relevant to genuine professional development; the former are efficiency tools only.

## Implications for Pedagogy

All three sources in this wiki converge on a consistent answer:

1. **[[sal-khan-khanmigo-limits]]**: Khanmigo's 2026 redesign embeds it directly within practice exercises, not as a standalone resource. AI tutoring works better when integrated into structured learning activity.

2. **[[agentivism]]**: Assessment and pedagogy must require process evidence (justification, revision, source-checking) rather than accepting final product quality as proof of learning.

3. **[[applied-co-intelligence-report]]**: The [[ai-mastery-continuum]] provides a structured progression that moves learners from passive AI use (Literacy) through active verification (Fluency/Agency) to independent critique (Mastery) — the conditions under which AI tutoring can produce genuine learning.

## Conditions for Effective AI Tutoring

Drawing on all three sources, effective AI tutoring likely requires:

- Integration into structured tasks with clear learning objectives
- Explicit requirements for the student to justify, verify, or reconstruct AI explanations
- Educator presence to model critical engagement and provide the "caring adult" relationship DiCerbo identifies as essential
- Assessment of process (how the student engaged with AI) not just product (what the student produced)

## A Positive Case: Social Skills Training

The [[llms-workplace-social-skills]] research (Yang, Louie et al., Stanford 2026) provides the strongest RCT evidence to date that AI tutoring can produce genuine skill gains — under the right conditions. A 90-person trial found that practicing social skills (conflict resolution, counseling, therapy) with an AI partner built confidence, while practice combined with AI mentor feedback built measurable competence: increased empathy, client-centeredness, and reflective questioning. The feedback condition maps directly onto Agentivism's mechanism of reconstructive internalization.

The critical design requirement: generic, out-of-the-box LLMs are too [[ai-sycophancy|sycophantic]] to be effective practice partners. The team had to engineer explicit behavioral constitutions — rules forcing AI personas to show realistic resistance and skepticism — to create genuine learning opportunities.

## Risk: Delusional Spirals

The [[ai-delusional-spirals]] research (Moore, Haber et al., Stanford 2026) documents the opposite failure mode: AI tutoring or companionship without deliberate design can amplify distorted beliefs through sycophancy, producing escalating spirals in vulnerable users. One case in their dataset ended in suicide. This is particularly relevant for AI tutoring in emotionally sensitive contexts (mental health, counseling, personal development) — the same domains where the social skills training research shows greatest promise.

The difference between beneficial and harmful AI interaction in these contexts appears to be deliberate anti-sycophancy design and human expert oversight.

## Related pages

- [[khanmigo]]
- [[sal-khan-khanmigo-limits]]
- [[agentivism]]
- [[ai-in-k12-education]]
- [[applied-co-intelligence-model]]
- [[evidence-base-ai-k12]]
- [[your-brain-on-chatgpt]]
- [[cognitive-debt]]
