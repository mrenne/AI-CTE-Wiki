# Building AI Companions That Prioritise Learning over Performance

**Summary**: A 2026 position paper by Khosravi, Gašević, Yan et al. that names the "learning-performance paradox," establishes a three-foundation framework for educational AI design (Pedagogical, Adaptive, Responsible), and documents what five deployed tutoring systems reveal about the gap between the tutoring systems that feel best and those that teach best.

**Sources**: `raw/PDF/Building AI Companions.pdf`, `raw/blog/AI is making you faster AND slower, better AND worse at your job.md`, `raw/blog/The _Cognitive Offloading_ Paradox.md`

**Last updated**: 2026-06-10

---

## Citation

Khosravi, H., Gašević, D., Sadiq, S., Yan, L., Lodge, J.M., Tangen, J.M., Denny, P., DiCerbo, K., Buckingham Shum, S., Baker, R.S. "Building AI Companions that Prioritise Learning over Performance." arXiv:2605.04816v2, May 15, 2026.

Authors span University of Queensland, University of Hong Kong, Monash University, Tsinghua University, University of Auckland, Khan Academy, University of Technology Sydney, and Columbia University Teachers College.

---

## The Learning-Performance Paradox

The paper's central contribution is naming and formalizing the **learning-performance paradox**: AI tools reliably improve short-term task performance while simultaneously undermining the cognitive processes — elaboration, struggle, memory consolidation, metacognitive monitoring — that produce durable learning, knowledge transfer, and independent capability.

> "AI tools optimized for work contexts—where efficiency and output quality are paramount—are inherently misaligned with learning contexts, where the struggle to process and understand content is itself essential." (source: Building AI Companions.pdf)

The paradox is distinct from simple cheating or over-reliance. It operates even when students engage in good faith: an AI that removes productive struggle improves measurable output quality while atrophying the cognitive machinery that generates genuine understanding. The paradox is structurally analogous to a physical therapist who carries every patient rather than guiding their own movement — the patient reaches the destination without developing strength.

This concept formalizes what the [[cognitive-debt]] research documents neurologically and what [[agentivism]] predicts theoretically. The paper's contribution is the name, the framing, and the explicit design implication: learning AI and work AI are not the same tool deployed differently — they are fundamentally different engineering problems.

---

## AI for Work vs. AI for Learning: A Nine-Dimension Taxonomy

The paper's Figure 1 provides the most systematic contrast in the literature between AI designed for work contexts and AI designed for learning contexts. These are not design preferences — they are design requirements that are frequently in direct conflict.

| Dimension | AI for Work | AI for Learning |
|-----------|-------------|-----------------|
| **Goal** | Task completion / quality output | Durable understanding / transferable capability |
| **Relationship to error** | Errors are defects to be avoided | Errors are information for diagnosis and correction |
| **Friction** | Minimize friction | Preserve productive struggle |
| **Feedback timing** | Immediate, corrective | Timed for learning; may be delayed or withholding |
| **Transparency** | High (trust through explainability) | Calibrated (may withhold to support discovery) |
| **Memory** | Stateless or session-based | Cumulative longitudinal student model |
| **Success metric** | Output quality / efficiency | Retention, transfer, metacognitive growth |
| **User agency** | Maximize autonomy | Scaffold autonomy developmentally |
| **Personalization basis** | Preference / style | Knowledge state / misconception profile |

The critical observation: most deployed AI tools are built for the left column. When students use ChatGPT or Copilot for schoolwork, they are using work AI in a learning context — a mismatch that the learning-performance paradox makes predictably harmful. The question is not whether these tools "work" but whether they are solving the right problem. (source: Building AI Companions.pdf)

---

## The Three-Foundation Framework

The paper proposes that educationally sound AI companions require three interlocking foundations:

### Foundation 1: Pedagogical

Learning AI must be grounded in learning science, not convenience science. Key principles:

- **Preserve productive struggle**: Difficulty that requires effortful processing is not a bug. Removing it removes the mechanism by which concepts move from working memory to long-term storage.
- **Support metacognitive development**: Learners must develop accurate models of their own knowledge — what they know, what they don't, and how to detect the difference. AI that provides answers short-circuits this development.
- **Sequence appropriately**: The question is not just what to teach but when — which AI-supported activities occur before versus after foundational capability is established. (See [[cognitive-debt]]'s Brain-first vs. LLM-first finding.)
- **Design for transfer**: The standard of educational success is not task completion but whether learned capability persists and transfers with reduced support. (See [[agentivism]], P4.)

### Foundation 2: Adaptive

Effective AI companions must build and maintain a representation of the individual learner over time. The paper describes a four-stage cycle:

1. **Capture**: Collect fine-grained behavioral traces — prompts submitted, errors made, time between attempts, revision patterns, metacognitive signals
2. **Model**: Build a learner model — not a preference profile, but a knowledge-state and misconception map, including calibration between expressed confidence and actual performance
3. **Adapt**: Tailor AI support to the learner's current zone of proximal development — not what they prefer, but what they need
4. **Evolve**: Update the model continuously; track learning velocity, not just current state

**Metacognitive calibration** is identified as a key adaptive mechanism: eliciting students' expressed confidence and comparing it against their demonstrated performance, then using the gap to surface what they don't know they don't know. This is the adaptive complement to [[illusion-of-understanding]]'s finding that students cannot self-detect AI-answer quality failure.

**RLHL (Reinforcement Learning from Human Learning)** is proposed as the next-generation approach: rather than rule-based or static adaptive policies, the AI's tutoring strategy is refined through continual learning from student interaction data — optimizing for learning outcomes rather than satisfaction or engagement metrics. (source: Building AI Companions.pdf)

### Foundation 3: Responsible Design

Educational AI operates in a context of power asymmetry, developmental vulnerability, and institutional accountability. The paper identifies four responsible design requirements:

- **Security and privacy**: Longitudinal student learning data is among the most sensitive data that exists; protections must exceed general data privacy standards
- **Transparency**: Students and educators must be able to understand how the AI is making pedagogical decisions — not just see outputs
- **Accountability**: Clear ownership of educational consequences; AI recommendations are not neutral
- **Inclusion**: Most current AI is optimized on majority-language, majority-cultural data; ELL students, students with disabilities, and students from non-dominant cultural backgrounds face compounding disadvantage

---

## Five Case Studies: What Deployed Systems Actually Show

The paper examines five systems with real deployment data, each illustrating a different design principle.

### Khanmigo (Khan Academy)

The most prominent case study, and the most instructive failure-to-success story.

**Original design**: The system prompt began "You are a Socratic tutor." GPT's response was rigid enforcement of the Socratic method — refusing to provide any direct answer, asking probing questions regardless of context. Student reaction: frustration, abandonment. Students who didn't know what they didn't know had no entry point to a system that only responded to their questions.

**Failure analysis**: Pure Socratic withholding fails students with low prior knowledge. If a student genuinely doesn't understand a concept, guiding questions about it are unanswerable — the student has no internal basis for responding. The design that feels educationally virtuous produces educational helplessness for the students who most need help.

**Redesign**: Khan Academy moved to a three-stage scaffold:
1. Allow the student to attempt the problem first
2. If no idea, provide a hint
3. If wrong after engagement, provide a worked example — with structured follow-up requiring deep engagement (explanation, variation, transfer)

This matches what learning science calls the ICAP hierarchy of cognitive engagement (Interactive > Constructive > Active > Passive). The worked-example-with-engagement condition produces the same level of cognitive engagement as Socratic dialogue but without the precondition of prior knowledge.

**Personalization finding**: Khan Academy tested two personalization approaches. Interest-based personalization (tailoring content to student interests) produced **no learning gains**. Skill-level mastery information (identifying exactly where in a knowledge sequence the student is stuck) was the only useful personalization signal. Students do not learn faster when they are entertained; they learn better when they are accurately placed.

**Key lesson**: The design that felt most educationally correct (pure Socratic) was the most educationally harmful for students without prior knowledge. Effective design requires empirical testing, not intuition about virtue. (source: Building AI Companions.pdf)

### RiPPLE (University of Queensland)

RiPPLE is the paper's most technically mature example. Deployed across 80,000+ students, it is the largest-scale AI learning companion with longitudinal data in the paper.

Key features:
- Peer-generated content with AI quality validation
- Item response theory (IRT) adaptive assessment — places students precisely within a knowledge continuum
- Personalized learning pathways based on knowledge-state, not preference
- Social learning features: peer comparison, collaborative question creation
- Tracks learner trajectories over time, not just single-session performance

RiPPLE demonstrates that large-scale adaptive learning is technically feasible in a university context. The constraints are institutional, not technical: faculty adoption, curriculum integration, data governance. (source: Building AI Companions.pdf)

### CodeHelp (University of Auckland / Dartmouth)

CodeHelp is an AI coding assistant for introductory programming courses with a deliberate anti-answer design: it provides explanations, debugging strategies, and conceptual guidance — but **withholds working solution code**.

This operationalizes the learning-performance paradox at the tool level: students using it may produce code more slowly or with more visible struggle than if they had used GitHub Copilot, but their demonstrated ability on unassisted assessments is stronger.

CodeHelp also collects interaction logs that reveal the most common misconceptions in intro CS courses — generating a feedback signal that helps instructors understand where conceptual breakdowns cluster. (source: Building AI Companions.pdf)

### JeepyTA (University of Pennsylvania)

JeepyTA is a TA-replacement AI deployed in Penn undergraduate courses. Two functions: Socratic-style discussion facilitation and structured essay feedback.

Key design: JeepyTA does not grade — it comments, questions, and pushes back. The feedback is tuned to require student response (explaining reasoning, not just correcting errors). This operationalizes reconstructive internalization ([[agentivism]], mechanism 3): students must rework the AI's feedback into their own revised understanding. (source: Building AI Companions.pdf)

### Recast (University of Technology Sydney)

Recast is an institutionally integrated AI learning platform (not a consumer product) designed to work within UTS's LMS and curriculum infrastructure.

The key contribution of the Recast case study is institutional design: AI learning tools deployed outside institutional infrastructure face adoption barriers and data governance failures. Recast demonstrates that institutional embedding — connecting AI to curriculum data, gradebooks, LMS workflows, and educator oversight structures — is both achievable and necessary for responsible deployment at scale. (source: Building AI Companions.pdf)

---

## Prompt-Level Guardrails Are Insufficient

The paper directly addresses a common institutional response to the learning-performance paradox: adding guardrail instructions to general-purpose AI prompts ("be a Socratic tutor," "don't give direct answers").

Finding: **prompt-level guardrails show near-null effects on learning outcomes.** The reason is structural: guardrails are reactive, stateless, and task-level only. They cannot:
- Track whether the student has prior knowledge that would make hints useful
- Distinguish productive struggle from unproductive confusion
- Maintain a model of what the student learned in prior sessions
- Adapt across a sequence of interactions to support learning velocity

A Socratic guardrail added to ChatGPT produces the same failure Khanmigo's initial design produced: rigid question-asking regardless of context. The fix required architectural redesign, not prompt refinement. The paper's conclusion: designing AI for learning requires building different systems from the ground up, not modifying work AI with instructions. (source: Building AI Companions.pdf)

---

## The Offloading Paradox: Empirical Support for Zone 3 Design

[[hardman-cognitive-offloading-paradox]] (Hardman, 2026) adds a critical empirical layer to this paper's architecture argument. Wang & Zhang (2026) found that **partnership orientation** with AI simultaneously activates both vigilance (β=0.335) and strategic offloading (β=0.351) — and both independently predict transformative learning. The same tool, framed as an intellectual collaborator rather than a passive answer-machine, produces opposite outcomes.

This validates the paper's three-foundation framework from the learner's side. The Pedagogical foundation (preserve productive struggle, design for transfer) corresponds to Zone 3's requirement that freed cognitive capacity be directed to higher-order work. The Adaptive foundation (metacognitive calibration, learner modeling) corresponds to the vigilance pathway Wang & Zhang identify. The Responsible Design foundation corresponds to the structural design question: will the deployment design produce Zone 2 or Zone 3 conditions?

**The cognitive partnership vs. social anthropomorphism distinction**: Kropp et al. (2026), cited in [[hardman-ai-faster-slower]], found that "AI buddy/mentor" framing makes reviewers sloppier. Wang & Zhang found that "intellectual collaborator" framing activates critical vigilance. These findings are compatible:
- **Cognitive partnership** = treating AI as an intellectual collaborator you think *with* and actively evaluate → more vigilance, more strategic delegation, better learning
- **Social anthropomorphism** = treating AI as a trusted peer/friend whose outputs you accept → less critical scrutiny, reduced epistemic monitoring

The distinction matters for Responsible Design (Foundation 3): institutions should explicitly frame AI as a cognitive tool requiring active evaluation — not as a tutor, mentor, or companion who can be trusted passively. The persona design choices that maximize engagement (warm, named, relational AI tutors) may be precisely the design choices that reduce the vigilance needed for Zone 3 learning. (source: The "Cognitive Offloading" Paradox.md)

## Workplace-Scale Validation: The Five-Effects Taxonomy

[[hardman-ai-faster-slower]] (Hardman, 2026) provides the largest-scale empirical validation in the wiki for this paper's core architecture argument, drawn from Demirer, Musolff & Yang (2026) — 100,000+ GitHub developers tracked across three AI tool generations.

**The productivity funnel maps exactly to the learning-performance paradox.** At work: +740% code produced → +65% review requests → only ~20% more shipped. In education: AI boosts task completion dramatically while durable learning gains drain away through every stage of human cognitive consolidation. The mechanism is structurally identical — rapid AI-assisted production enters a human-dependent attenuation process, and the bottleneck is the human stages downstream, not the AI-assisted production upstream.

**The "enter high in the chain" principle directly validates this paper's architectural argument.** Hardman's finding: "A modest tool that enters high in the production chain beats a powerful tool that enters low, because its gains have fewer human-dependent stages left to drain through." Applied to learning: a general-purpose chatbot with prompt-level Socratic guardrails enters low in the learning chain — at content generation — and drains all gains through reading, retrieval, reflection, and transfer. A purpose-built learning AI (adaptive learner modeling, metacognitive calibration, Socratic scaffolding timed to the learner's knowledge state) enters high — at the stages where cognitive consolidation lives. This is exactly what the three-foundation framework specifies architecturally and what the Khanmigo case study demonstrates empirically.

**Effect 4's quality drag mechanism is the workplace analog to the learning-performance paradox.** Hardman: "Generic AI confidently reproduces the most common version of whatever you ask for — weak on depth, context, and judgement." This is not a different phenomenon from the paradox; it is the same AI-optimization artifact operating in the production domain rather than the learning domain. AI optimized for output produces output at the expense of depth.

**Effect 5 (better) corroborates the high-chain design goal.** Hardman's evidence for genuine quality improvement — EduPlanner multi-agent systems with domain-specific rubrics, ARCHED human-centred ID framework, knowledge-enhanced GPT-4 with stepwise self-critique — all share the property this paper identifies: scaffolded, domain-specific, architecturally designed AI targeting the high-value stages of the work chain. Prompt guardrails on a general-purpose model do not appear in Effect 5. (source: AI is making you faster AND slower.md)

---

## Relationship to This Wiki

This paper is the most comprehensive design synthesis in the wiki on what AI tutoring needs to be — as distinct from what it currently is. Its relationships:

- **[[cognitive-debt]]**: The learning-performance paradox is the name for what cognitive debt describes mechanistically — the paper contributes the framing and design implication
- **[[agentivism]]**: By the same author group (Gašević, Yan) — this paper is the applied design successor to Agentivism's theoretical framework; Agentivism defines what learning requires; this paper specifies what AI design must therefore do
- **[[ai-tutoring]]**: The AI for Work vs. AI for Learning taxonomy and the three-foundation framework are the most comprehensive design synthesis in the wiki for what makes AI tutoring work or fail
- **[[khanmigo]]**: Provides the fullest account of Khanmigo's Socratic design, its failure, and its redesign — including the interest vs. mastery personalization finding
- **[[illusion-of-understanding]]**: Metacognitive calibration (Foundation 2) is the adaptive design response to the illusion; the paper makes explicit what intervention addresses the finding
- **[[evidence-base-ai-k12]]**: Prompt-level guardrails finding directly addresses the Bastani "science of guardrails" question; this paper's answer is that guardrails must be architectural, not instructional

---

## Related pages

- [[agentivism]]
- [[khanmigo]]
- [[ai-tutoring]]
- [[cognitive-debt]]
- [[illusion-of-understanding]]
- [[evidence-base-ai-k12]]
- [[your-brain-on-chatgpt]]
- [[ai-sycophancy]]
- [[applied-co-intelligence-report]]
- [[ai-mastery-continuum]]
- [[middle-path-ai-literacy-nurenberg]]
- [[hardman-ai-faster-slower]]
- [[hardman-cognitive-offloading-paradox]]
