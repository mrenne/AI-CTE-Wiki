# Agentivism

**Summary**: A 2026 learning theory by Yan and Gašević that defines learning in the AI era as durable human capability growth through selective delegation, epistemic monitoring, reconstructive internalization, and transfer under reduced AI support.

**Sources**: `raw/PDF/Agentivism.pdf`, `raw/PDF/The Evidence Base on AI in K-12 Report.pdf`, `raw/PDF/Your Brain on ChatGPT.pdf`, `raw/PDF/The Illusion of Understanding.pdf`, `raw/blog/Why the Middle Path of AI Literacy May Be the Future of English Class.md`, `raw/PDF/Building AI Companions.pdf`, `raw/video/New Book Podcast_ AI Unplugged_ The Hype and Hope in Education Futures.md`, `raw/blog/The _Cognitive Offloading_ Paradox.md`, `raw/blog/The secret to human 'brilliance' that AI just can't match.md`

**Last updated**: 2026-07-07

---

## Overview

*Agentivism: A Learning Theory for the Age of Artificial Intelligence* (arXiv:2604.07813, April 9, 2026) was authored by Lixiang Yan (Tsinghua University) and Dragan Gašević (University of Hong Kong / Monash University). It proposes Agentivism as a mid-range learning theory specifically designed for the era of generative and agentic AI.

## The Core Problem

Classical learning theories share an implicit assumption: successful task completion implies learning. Generative AI breaks this assumption. A learner can now produce a strong essay, solve a complex problem, or complete a scientific inquiry entirely with AI support, while developing no lasting understanding.

Empirical evidence cited in the paper (source: Agentivism.pdf):

- Students using AI produce stronger essays with less independent revision and no knowledge gain ("metacognitive laziness")
- Students using ChatGPT for scientific inquiry report lower cognitive load while producing less sophisticated reasoning
- General pattern: improved measurable task performance without proportionate gains in metacognitive processing or independent understanding

The paper distinguishes:
- **Assisted performance**: task completion with AI support, without evidence of durable learning
- **Durable human capability**: capability that persists beyond the interaction, is explainable, and transfers with less AI support

## Definition of Learning

Agentivism defines learning as **durable growth in human capability** through four mechanisms:

1. Selective delegation to AI
2. Epistemic monitoring and verification of AI contributions
3. Reconstructive internalization of AI-assisted outputs
4. Transfer under reduced support

## The Four Core Mechanisms

### 1. Delegated Agency
Learning depends on how responsibility for task execution is distributed between learner and AI. Delegation preserves learning when the learner retains responsibility for problem framing, criteria-setting, and judging acceptable reasoning. Delegation undermines learning when those functions migrate to the AI and the learner becomes mainly a selector of fluent outputs.

### 2. Epistemic Monitoring and Verification
Because AI outputs are probabilistic, rhetorically fluent, and persuasive, learners must evaluate them for truthfulness, relevance, adequacy, and fit to task demands. This is not optional responsible-use behavior — it is part of the learning mechanism itself. Research shows requiring learners to justify their acceptance of AI outputs reduces over-reliance even when it feels less convenient.

### 3. Reconstructive Internalization
Learning occurs only when AI-assisted outputs are reworked into the learner's own explainable and usable capability. Task success with AI support is insufficient. A learner must be able to reconstruct why the accepted response is appropriate, identify when it would fail, and adapt it to new situations.

Stanford GSB research on [[satisficing-and-tolerance-principle|satisficing and the Tolerance Principle]] (Guilbeault et al., 2026) suggests a possible cognitive-science account of why this mechanism matters: human understanding appears to form through intuitive leaps from deliberately partial data, not through absorbing a complete, fully-worked answer. If accurate, reconstructive internalization may be this same intuitive-leap process applied to AI-assisted work — which would help explain why passively accepting an AI's complete output bypasses the mechanism that produces durable learning. (source: The secret to human 'brilliance' that AI just can't match.md — treat as a plausible theoretical bridge, not an established finding.)

### 4. Transfer Under Reduced Support
The decisive test of learning: can the learner demonstrate capability with less or no AI support? Immediate assisted performance is no longer sufficient evidence. The question is whether capabilities persist when support changes.

## Why Classical Theories Fall Short

| Theory | Can explain | Cannot explain |
|--------|-------------|----------------|
| Behaviourism | Why AI use becomes reinforcing through immediate feedback and effort reduction | Whether repeated AI-supported success reflects learning or reinforced dependence |
| Cognitivism | How AI changes cognitive load, memory demands, schema construction | When offloading supports learning vs. substitutes for it |
| Constructivism | Why dialogue, interpretation, and meaning-making matter in AI-assisted learning | Whether AI-generated guidance is epistemically trustworthy; interaction alone doesn't guarantee learning |
| Connectivism | Why learning depends on distributed networks of people, tools, and information | What changes when network nodes become generative, persuasive, and agentic |

## What Generative AI Changes

The paper identifies four structural changes:

1. **Knowledge has become mobilizable** — AI can instantly convert external knowledge into usable plans, drafts, and solutions, potentially bypassing internalization
2. **Agency is more dynamically allocated** — learners can now delegate planning, drafting, and problem-solving to AI, making regulation of delegation a first-order concern
3. **Performance and learning are more sharply separable** — empirically confirmed that AI-assisted performance can be stronger than unassisted performance with no corresponding knowledge gain
4. **Epistemic trust and diversity are at center stage** — AI outputs are trained on unevenly distributed data and are fluent enough to invite overconfidence

## Six Testable Propositions

**P1**: Learning should be stronger when AI support preserves learner responsibility for problem framing and justification than when AI delivers direct answers.

**P2**: Designs requiring verification, source comparison, or justification of AI uptake should improve delayed transfer even when reducing convenience. *Empirical support*: The CARE RCT ([[llms-workplace-social-skills]]) found that practice-with-AI-mentor-feedback produced measurable skill gains (empathy, client-centeredness) while practice-only produced confidence gains only — directly validating P2 in a social skills context. Additional evidence from the contrary direction: Abdelghani et al. (2026) found that middle-school students asked to complete science tasks with ChatGPT showed prompt discrimination and answer evaluation both at chance level (d'=0.19 and d'=0.07 respectively) — demonstrating that P2 (epistemic monitoring) is essentially absent in typical unscaffolded AI use by adolescents. Only 14 of 63 students asked any follow-up question; even after unsatisfactory answers, follow-up occurred only 31.8% of the time. The study coins this systematic failure the "[[illusion-of-understanding]]." (source: The Illusion of Understanding.pdf)

**P3**: Learners who substantially re-explain, revise, or transform AI-generated material should show stronger retained understanding than those who lightly edit outputs. *Empirical support*: Kosmyna et al. (2025) found that 83% of students who wrote essays with AI assistance could not quote from their own essays afterward — minimal reconstruction produced minimal retention. Kreijkes et al. (2026) found that AI-assisted reading improved when combined with note-taking (active reconstruction), not as a substitute for it ([[evidence-base-ai-k12]]).

**P4**: Immediate AI-assisted performance should correlate only weakly with later independent performance when monitoring and reconstruction are minimal. *Empirical support*: Bastani et al. (2025) and Fischer et al. (2025) both demonstrate this directly — students with general-purpose AI access showed higher practice performance and lower unassisted exam scores (a 17% performance drop in Fischer et al.). The correlation between assisted and unassisted performance was negative, not merely weak ([[evidence-base-ai-k12]]).

**P5**: Process measures during interaction (prompt trajectories, revision sequences, evidence-checking) should predict later learning better than final product quality alone.

**P6**: Repeated low-friction delegation without reconstruction should be associated over time with weaker self-competence calibration and greater AI dependence. *Empirical support*: Kosmyna et al. (2025) provide the first neurological confirmation of this prediction. After three sessions of ChatGPT-assisted essay writing, participants asked to write without tools showed brain connectivity *below the Session 1 baseline* of peers who had never practiced essay writing at all — and 78% failed to quote anything from their own essays. The cognitive foundations that should have developed through practice had not formed ([[cognitive-debt]], [[your-brain-on-chatgpt]]).

## Implications

- **Assessment**: Final products are increasingly insufficient when AI contributes directly to drafting and solving. Valid assessment requires process evidence.
- **Pedagogy**: Tasks should preserve learner responsibility for problem framing, criteria articulation, evidence comparison, and explanation of why outputs are appropriate.
- **Design**: Interface design, institutional norms, and acceptable-delegation policies shape whether learners remain genuinely agentic.

## Design Successor: Building AI Companions

Agentivism defines what learning requires in the AI age — theoretically. The [[building-ai-companions]] paper (Khosravi, Gašević, Yan et al., 2026) is its direct applied successor, by the same core author group (Gašević, Yan). Where Agentivism provides a learning theory, Building AI Companions specifies what that theory demands of engineering and design.

The paper formalizes the gap between assisted performance and durable capability growth as the **learning-performance paradox**: AI tools optimized for efficiency and output quality reliably improve short-term measurable performance while undermining the cognitive processes required for durable learning — elaboration, productive struggle, memory consolidation, metacognitive monitoring. This is not a misuse problem; it is a structural mismatch between work AI and learning AI.

The Agentivism-to-design mapping:

| Agentivism mechanism | Design requirement (Building AI Companions) |
|---------------------|---------------------------------------------|
| Selective delegation | AI must withhold answers until learner has attempted (Khanmigo redesign three-stage scaffold) |
| Epistemic monitoring | Metacognitive calibration: surface the gap between expressed confidence and actual performance |
| Reconstructive internalization | Worked-example follow-up requires explanation, variation, transfer — not just exposure |
| Transfer under reduced support | Prompt-level guardrails are insufficient; architectural adaptive modeling is required |

The paper's finding on prompt-level guardrails is particularly significant for Agentivism's propositions: adding Socratic instructions to a general-purpose AI does not produce Agentivism-compliant behavior. It produces rigid question-asking that fails students with low prior knowledge. Mechanisms 1–4 require architectural design, not instructional wrapping. (source: Building AI Companions.pdf)

## Empirical Validation: The Offloading Paradox Maps to Agentivism's Zones

Wang & Zhang (2026), synthesized in [[hardman-cognitive-offloading-paradox]], provide cross-cultural empirical validation of Agentivism's core claim. Their 912-student study (China/Europe/US) identifies a U-shaped relationship between AI offloading and transformative learning that maps directly onto Agentivism's mechanism structure:

| Wang & Zhang zone | Agentivism interpretation |
|---|---|
| **Zone 1** (no AI) | P1 absent: no delegation, full cognitive load, learning is slow but the mechanisms are engaged |
| **Zone 2** (scattered AI use — worst outcomes) | P1 without P2+P3: delegation occurs but without epistemic monitoring or reconstructive internalization; exactly the failure Agentivism predicts; where cognitive debt accumulates |
| **Zone 3** (committed, strategic delegation — best outcomes) | P1+P2+P3 operating together: large delegation frees capacity; freed capacity invested in higher-order work requiring vigilance and reconstruction |

The key empirical finding: **partnership orientation** with AI simultaneously activates both **vigilance** (epistemic monitoring, P2; β=0.335) AND **strategic offloading** (selective delegation, P1; β=0.351). Both independently predict transformative learning (deep assumption-questioning, perspective-shifting). This is direct empirical confirmation of Agentivism's claim that delegation and critical monitoring are not opposed but complementary — they activate together when the learner's orientation is correct.

For P6 (repeated low-friction delegation without reconstruction = cognitive dependence): Wang & Zhang confirm the negative case in Zone 2 and demonstrate the positive case in Zone 3. The difference is not more or less AI; it is whether delegation is large enough to genuinely free capacity, and whether the freed capacity is deliberately reinvested in higher-order cognitive work.

The six design principles Hardman derives from Wang & Zhang (offload substantially or not at all; learner generates first; AI flags errors, human fixes them; verification built into workflow; assess without scaffolding) are the classroom-level operationalizations of Agentivism's four mechanisms as design requirements. (source: The "Cognitive Offloading" Paradox.md)

## Connections to Other Sources

The [[khanmigo]] failure documented in [[sal-khan-khanmigo-limits]] is a real-world illustration: students using AI as a passive lookup tool engage in no epistemic monitoring or reconstructive internalization and achieve no transfer. The [[applied-co-intelligence-model]]'s [[ai-mastery-continuum]] maps closely onto Agentivism's mechanisms — progression from passive use (Literacy) through active verification (Fluency/Agency) to independent critique (Mastery).

Murgatroyd's [[ai-unplugged-murgatroyd]] (2026) offers a second classroom operationalization at the assessment level: the **Build → Analyze → Defend** scaffold. Students build work with AI assistance, analyze it critically (what did AI contribute? what's wrong?), then defend it orally to peers. "Build, analyze, defend is the scaffolding process that actually increases cognition." The three stages map directly: Build = delegated agency; Analyze = epistemic monitoring; Defend = reconstructive internalization and transfer under reduced support. Crucially, oral defense renders AI detection moot — independent understanding must be demonstrated in real time regardless of how the artifact was produced.

Nurenberg's [[middle-path-ai-literacy-nurenberg]] classroom account provides a concrete pedagogical operationalization of Agentivism's mechanisms. His **AI audit** — requiring students to demonstrate for every tool they used: how it operates, what was gained and lost, how accuracy was verified, how they did not relinquish their own thinking — is a classroom-ready implementation of selective delegation, epistemic monitoring, and reconstructive internalization. Crucially, one student ran an unprompted probe: "purposely said dumb things just to see how GPT would still find a way to say 'great idea.'" This is P2 (epistemic monitoring) happening organically — the student designed a test, observed the result, and generalized a conclusion about AI's trained deference. The source also introduces the *cognitive surrender vs. cognitive offloading* distinction (from a cited preprint): surrender is passive trust without evaluation; offloading is strategic delegation during deliberation. This is among the clearest student-facing language available for teaching Agentivism's core distinction between assisted performance and durable capability growth. (source: Why the Middle Path of AI Literacy May Be the Future of English Class.md)

## Related pages

- [[sal-khan-khanmigo-limits]]
- [[applied-co-intelligence-report]]
- [[ai-mastery-continuum]]
- [[ai-tutoring]]
- [[transferable-skills]]
- [[evidence-base-ai-k12]]
- [[cognitive-debt]]
- [[your-brain-on-chatgpt]]
- [[illusion-of-understanding]]
- [[middle-path-ai-literacy-nurenberg]]
- [[building-ai-companions]]
- [[ai-unplugged-murgatroyd]]
- [[hardman-cognitive-offloading-paradox]]
- [[cems-augmented-leadership]]
- [[satisficing-and-tolerance-principle]]
- [[human-brilliance-satisficing]]
