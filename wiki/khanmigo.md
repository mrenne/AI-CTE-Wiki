# Khanmigo

**Summary**: Khan Academy's AI-powered tutoring chatbot, built on GPT-4, designed to guide students toward answers through Socratic dialogue — but which has struggled to achieve meaningful adoption among the students who need it most.

**Sources**: `raw/blog/The education of Sal Khan and the limits of his chatbot.md`, `raw/PDF/Applied-Co-Intelligence–Preparing-Career-and-Technical-Education-Learners-for-an-AI-Driven-Workforce-FINAL.pdf`, `raw/PDF/The Evidence Base on AI in K-12 Report.pdf`, `raw/PDF/Building AI Companions.pdf`

**Last updated**: 2026-05-24

---

## What It Is

Khanmigo is an AI tutoring chatbot developed by Khan Academy using OpenAI's GPT-4. It was designed to guide students toward understanding through Socratic questioning rather than providing direct answers. Khan Academy received early GPT-4 access from OpenAI in 2022, before ChatGPT's public launch, and built Khanmigo as a showcase for AI's potential benefits in education.

## Adoption and Reception

Despite Sal Khan's high-profile 2023 TED Talk predicting an AI-driven "biggest positive transformation that education has ever seen," Khanmigo has largely been "a non-event" for most students (source: The education of Sal Khan.md):

- Most students don't proactively seek out AI tutoring when given the option
- Students find it frustrating — it withholds direct answers and sometimes makes mistakes
- Teacher enthusiasm has been low; administrator enthusiasm markedly higher
- Early-adopter Hobart High School (Indiana) saw the geometry teacher who piloted it stop using it entirely

## Root Cause

Khan Academy's chief learning officer Kristen DiCerbo identified the underlying problem: "Students aren't great at asking questions well." The chatbot can only respond to what students ask. Students who lack motivation, background knowledge, or question-asking skills cannot benefit from a resource that requires all three.

This maps directly onto [[agentivism]]'s analysis: AI tutoring without epistemic monitoring and reconstructive internalization produces no durable learning. The failure mode Khanmigo illustrated is not just that students don't use it — it's that even when they do, passive interaction without genuine engagement yields little.

## The 2-Sigma Hypothesis

Khanmigo was partly motivated by Bloom's 1984 2-sigma research, which found individualized human tutoring produced two standard deviations of improvement over conventional instruction. Sal Khan suggested AI could replicate this effect at scale. The Khanmigo experience suggests the technical capability to provide tutoring is necessary but not sufficient — student motivation, question-asking ability, and pedagogical integration are equally critical.

## Causal Validation of Khanmigo's Design Philosophy

The [[evidence-base-ai-k12]] report (Stanford SCALE, 2026) provides the first direct causal evidence bearing on Khanmigo's core design choice. Bastani et al. (2025), in a study of ~1,000 high school students in Turkey, compared three conditions: general-purpose AI chatbot, tutoring-specific AI chatbot (hints only, no direct answers), and textbook control.

Results on a closed-book exam: general-purpose AI students scored *worse* than textbook students. Tutoring-specific AI students scored *the same* as textbook students (source: The Evidence Base on AI in K-12 Report.pdf).

This validates Khanmigo's pedagogical design — refusing to give direct answers and guiding students toward reasoning — as the educationally correct approach. The problem with Khanmigo was not its philosophy but its adoption: students found the guided approach frustrating precisely *because* it required cognitive work. The fact that students prefer the AI experience that teaches them less is not a quirk of Khanmigo; it appears to be a general human tendency confirmed across multiple studies.

## Product Redesign (2026)

Khan Academy overhauled its product to embed Khanmigo directly within practice exercises rather than offering it as a standalone tool. The rationale: "students were not seeking out Khanmigo's help as much as we had hoped." This shift — from passive resource to embedded scaffold — aligns with the [[applied-co-intelligence-model]]'s argument that AI must be integrated into structured tasks, not offered as an optional add-on.

## The Socratic Design Failure and Redesign

The [[building-ai-companions]] paper (Khosravi, Gašević, Yan et al., 2026) provides the fullest documented account of what went wrong inside the original Khanmigo design and how it was fixed.

**Original design**: The system prompt began "You are a Socratic tutor." GPT's literal interpretation was rigid enforcement of the Socratic method — refusing to provide any direct answer regardless of context, responding only with probing questions. Student reaction: widespread frustration and abandonment. Students without prior knowledge of a concept had no basis for answering Socratic questions about it. The design intended to be pedagogically principled was experienced as pedagogically useless.

**The failure mode**: Pure Socratic withholding fails students with low prior knowledge. Guiding questions about concepts the student doesn't yet understand are unanswerable — the student has no internal basis for responding. This is the condition where students most need help, and it was precisely where the original design offered none. (source: Building AI Companions.pdf)

**The redesign**: Khan Academy moved to a three-stage contextual scaffold that matches the student's knowledge state:
1. Allow the student to attempt the problem first (preserving effort and productive struggle)
2. If no idea, provide a hint (scaffolded entry point)
3. If wrong after genuine engagement, provide a worked example — followed by structured follow-up requiring explanation, variation, and transfer

This matches the ICAP cognitive engagement hierarchy (Interactive > Constructive > Active > Passive). The worked-example-with-structured-engagement condition produces equivalent cognitive depth to Socratic dialogue — without requiring the precondition of prior knowledge.

**The personalization finding**: Khan Academy tested two personalization approaches and got an unexpected result. Interest-based personalization — tailoring content to student declared interests — produced **no learning gains**. Skill-level mastery information — identifying exactly where in a knowledge sequence the student is currently stuck — was the only useful personalization signal. Engagement does not produce learning; accurate placement in a knowledge structure does. (source: Building AI Companions.pdf)

**Broader implication**: The design that felt most educationally virtuous (pure Socratic) was the most educationally harmful for students who lacked prior knowledge. The lesson for AI tutoring design: pedagogical intuition requires empirical testing. The [[learning-performance paradox]] operates in both directions — a tool can feel good to use and still fail to teach; a tool can feel frustratingly difficult and still produce the deepest learning.

## Related pages

- [[sal-khan-khanmigo-limits]]
- [[ai-tutoring]]
- [[agentivism]]
- [[ai-in-k12-education]]
- [[applied-co-intelligence-report]]
- [[evidence-base-ai-k12]]
- [[building-ai-companions]]
- [[cognitive-debt]]
