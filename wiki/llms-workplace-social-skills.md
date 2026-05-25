# Using LLMs to Improve Workplace Social Skills

**Summary**: Stanford research showing that AI practice partners with expert-designed personas and AI mentor feedback can build both confidence and competence in social skills like conflict resolution, peer counseling, and therapy — but require deliberate anti-sycophancy design to work.

**Sources**: `raw/misc/Using LLMs To Improve Workplace Social Skills.md`

**Last updated**: 2026-04-26

---

## Overview

Research by Diyi Yang, Ryan Louie, and colleagues at Stanford's Human-Centered AI Institute describes the AP/AM (AI Partner/AI Mentor) framework for practicing workplace and therapeutic social skills. The team built systems for conflict resolution (Rehearsal), peer counseling, and novice therapy skills (CARE). A 90-person randomized controlled trial evaluated CARE. The work was funded by the Stanford Institute for Human-Centered AI.

## The AP/AM Framework

**AI Partner**: A practice partner with a persona tailored to a specific social context. Designed to simulate realistic client behavior — including initial resistance, skepticism, and controlled disclosure — that creates opportunities to practice specific skills in realistic conditions.

**AI Mentor**: An expert feedback system that evaluates the learner's responses, identifies strengths and areas for improvement, and suggests alternative ways to respond that mirror how experienced supervisors coach novices. The mentor was developed by fine-tuning on annotations from Stanford School of Medicine therapist supervisors.

## Key RCT Findings

A 90-person randomized controlled trial of CARE compared practice-with-feedback vs. practice-only vs. control (source: Using LLMs To Improve Workplace Social Skills.md):

- **Practice alone builds confidence** — even without feedback, LLM practice improved self-reported confidence in counseling abilities
- **Feedback is necessary for skill competence** — only the practice-and-feedback group showed measurable improvements in specific skills
- The practice-and-feedback group showed increased **empathy** and **client-centeredness** — helping clients develop their own solutions
- The practice-only group defaulted to suggesting solutions rather than facilitating client agency — a less effective therapeutic approach

> "Practice alone matters for building confidence. But feedback is needed for improving skills."

## The Sycophancy Problem and the Solution

Out-of-the-box LLMs are too cooperative and agreeable to be useful practice partners. [[ai-sycophancy]] means that:
- A conflict won't escalate if the AI resolves it too readily
- A therapy session won't develop skills if the AI discloses everything immediately
- A user won't learn empathy if the AI accepts all their suggestions without resistance

The team's solution: co-designing **constitutions** with domain experts — rule sets that constrain persona behavior to be realistic rather than pleasing. Examples (source: Using LLMs To Improve Workplace Social Skills.md):
- "Show initial skepticism about seeking help"
- "Don't disclose too much at the start"
- "Be resistant or hesitant about accepting suggested solutions"

Personas also varied across the 25 practice scenarios, ensuring learners practiced different skills in different contexts. The system self-checks each response against all constitution rules before output, regenerating if any rule is violated.

## Connection to Agentivism

The CARE RCT directly validates [[agentivism]]'s Proposition P2: "Interaction designs requiring verification, source comparison, or justification of AI uptake should improve delayed transfer even when reducing convenience."

| CARE condition | Agentivism mechanism | Outcome |
|---------------|---------------------|---------|
| Practice only | Assisted performance without reconstruction | Confidence gains only |
| Practice + feedback | Epistemic monitoring; reconstructive internalization | Confidence + competence gains |

The practice-only condition produces surface confidence (the learner completes interactions) without durable skill development. The feedback condition forces learners to understand *why* their responses were effective or ineffective — precisely the reconstructive internalization Agentivism identifies as necessary for durable capability.

## Limitations and Future Directions

- Creating high-quality simulations requires significant expert involvement; not easily scalable to new use cases without substantial co-design work
- Personalization is a major open challenge: systems need the "right zone of difficulty" for each user
- AI partners and mentors should **complement, not replace**, peer practice and human supervisor feedback
- Currently adapting CARE for community mental health centers and for cross-cultural deployment in India (requiring persona and language adaptation)

## Relevance for CTE

Social skills — empathy, communication, conflict resolution, counseling — are core [[transferable-skills]] in the [[applied-co-intelligence-model]]. This research provides a concrete, RCT-validated method for developing these skills in CTE learners in Healthcare & Human Services, Education, and Public Service & Safety roles. The key caveat: generic AI chatbots will not produce these outcomes. Expert-informed design is required — which connects directly to the human capital gap identified in the [[applied-co-intelligence-report]].

## Related pages

- [[ai-delusional-spirals]]
- [[ai-sycophancy]]
- [[agentivism]]
- [[transferable-skills]]
- [[ai-tutoring]]
- [[ai-and-mental-health]]
- [[cte-and-ai]]
