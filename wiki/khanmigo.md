# Khanmigo

**Summary**: Khan Academy's AI-powered tutoring chatbot, built on GPT-4, designed to guide students toward answers through Socratic dialogue — but which has struggled to achieve meaningful adoption among the students who need it most.

**Sources**: `raw/The education of Sal Khan and the limits of his chatbot.md`, `raw/Applied-Co-Intelligence–Preparing-Career-and-Technical-Education-Learners-for-an-AI-Driven-Workforce-FINAL.pdf`, `raw/The Evidence Base on AI in K-12 Report.pdf`

**Last updated**: 2026-04-27

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

## Related pages

- [[sal-khan-khanmigo-limits]]
- [[ai-tutoring]]
- [[agentivism]]
- [[ai-in-k12-education]]
- [[applied-co-intelligence-report]]
- [[evidence-base-ai-k12]]
