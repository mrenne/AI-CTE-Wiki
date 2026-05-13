# Stanford HAI AI Index 2026: Chapter 7 — Education

**Summary**: Stanford HAI's AI Index 2026 Chapter 7 provides the most comprehensive quantitative snapshot of AI in education as of 2026 — covering CS enrollment shifts, student AI use rates, K-12 policy gaps, global comparisons, and AI skill diffusion in the workforce.

**Sources**: `raw/ai_index_report_2026_chapter_7_education.pdf`

**Last updated**: 2026-05-13

---

## Three Distinct Domains

The chapter opens with a definitional framework that cuts through a significant conceptual confusion in the field:

- **AI in Education**: Using AI tools to teach any subject (most schools are doing this, mostly ad-hoc)
- **AI Literacy**: Understanding how AI works, its capabilities and limitations (explicitly curriculum-targeted)
- **AI Education**: Technical skills to build, evaluate, and deploy AI systems (CS/engineering pathway)

These three are often conflated in policy discourse. A school that lets students use ChatGPT for essays is doing "AI in Education" — it may be doing nothing about AI Literacy and has no AI Education program. Separately tracking each domain reveals that progress is uneven: AI in Education is widespread and ungoverned; AI Literacy is nascent; AI Education is growing in higher education while shrinking by enrollment in undergrad CS. (source: ai_index_report_2026_chapter_7_education.pdf)

## Enrollment Signals

**Undergraduate CS enrollment** at 4-year universities declined 11% from 2024 to 2025 — a significant reversal after a decade of growth. This is likely a labor market signal: students are reading declining CS unemployment prospects and reducing major commitments. However, CS as a skill (not a major) is growing: students are taking CS courses while majoring elsewhere, treating technical literacy as a baseline rather than a career anchor.

**Graduate AI education** is growing rapidly:
- AI software master's graduates: +17% (2023–2024); +82% since 2022
- AI PhD graduates to academia: nearly doubled since 2022
- AI PhD graduates to industry: share fell from 77% to 65% — more AI researchers entering universities

The divergence (undergrad CS down, grad AI up) suggests that AI is bifurcating CS education into a commodity layer (coding skills taught across majors) and a specialized layer (ML/AI systems training increasingly at graduate level). (source: ai_index_report_2026_chapter_7_education.pdf)

## Student AI Use at Scale

**80% of university students** report using generative AI for schoolwork — double the 40% figure from 2023. The normalization of AI use in higher education has occurred faster than policy, curriculum, or pedagogy have adapted.

Anthropic's own usage data (from Claude) shows a more nuanced picture of *how* students use AI:
- 39.8% creating content
- 30.2% analyzing information
- Remaining: coding, research, synthesis

These are largely higher-order cognitive tasks — not the simple answer-copying that dominates the academic integrity narrative. This does not resolve the [[agentivism]] concern (that AI-assisted completion prevents durable learning) but does complicate the "cheating tool" framing. (source: ai_index_report_2026_chapter_7_education.pdf)

The [[illusion-of-understanding]] finding from Abdelghani et al. is directly relevant here: students may believe they are learning while using AI for analysis and creation, when in fact the AI is doing the cognitive work. High-order task labels do not guarantee high-order learning.

## K-12 Policy Gap

The Stanford chapter quantifies a structural governance failure:

- **Only 4 states** explicitly emphasize AI in their K-12 CS standards
- **Only 50% of middle and high schools** have any AI policy
- **Only 6% of teachers** report their school's AI policies are clear
- **60% of high schools** offer CS; this number has not grown despite AI urgency

The ECEP (Expanding Computing Education Pathways) analysis is especially damning: state CS education guidance is largely **nonbinding and decentralized**. No state has established teacher training standards for AI. AP CS — the primary gateway to college CS — excludes AI content. The infrastructure for delivering AI literacy education does not yet exist at scale. (source: ai_index_report_2026_chapter_7_education.pdf)

Notably, the new **CSTA K-12 Computer Science Standards** (expected summer 2026) will integrate significant AI content across K-12 grade bands for the first time. This represents a potential turning point, but implementation will depend on states adopting the standards — which, given ECEP's findings on nonbinding guidance, is not guaranteed.

## Global Comparisons

The international picture reveals significant variation in AI education policy commitment:

- **China and UAE** mandated AI education for all students at the K-12 level in 2025–2026
- **India** leads all countries in LinkedIn AI skill penetration — approximately 3x the global average
- **United States** is at approximately 2x the global average — behind India but above most countries

China's mandate is particularly notable: a national curriculum requirement for AI education represents a categorically different policy instrument than the voluntary, decentralized, standard-setting approach the US uses. The competitive implications for workforce preparation are significant but long-term. (source: ai_index_report_2026_chapter_7_education.pdf)

## AI Skill Diffusion in the Workforce

LinkedIn data on fastest-growing skills in the US workforce (2024–2025):

**AI Literacy skills**:
- AI prompting
- Microsoft Copilot Studio

**AI Engineering skills**:
- AI agents
- AI productivity tools
- AI strategy

The pattern is consistent with the BCG [[ai-labor-disruption-segments]] framework: literacy-layer skills (prompting, using Copilot) are growing broadly across roles, while engineering-layer skills (building agents, AI strategy) are growing in more specialized contexts. Both are growing faster than most non-AI skills. (source: ai_index_report_2026_chapter_7_education.pdf)

## Implications for K-12 AI Policy

Three actionable conclusions from the Stanford data:

1. **The policy gap is the primary bottleneck**: It is not lack of AI tools or student demand. 80% of students are already using AI. The problem is that schools have no coherent framework for what AI use should look like — which means no friction, no metacognitive scaffolding, and likely widespread [[illusion-of-understanding]].

2. **Teacher training is the critical missing link**: The ECEP finding that no state has teacher training standards for AI education means that even where standards exist, the human infrastructure to implement them does not. Curriculum without teachers who understand it changes nothing.

3. **CS enrollment decline is a signal, not a crisis**: The -11% undergrad CS enrollment is not evidence that students are ignoring AI — it is evidence that they are reading the labor market correctly. Students are diversifying rather than concentrating. The right policy response is to ensure AI literacy is available across all majors, not to prop up CS enrollment.

## Related pages

- [[ai-in-k12-education]]
- [[cte-and-ai]]
- [[evidence-base-ai-k12]]
- [[ai-privacy-and-institutional-adoption]]
- [[columbia-cs-ai-disruption]]
- [[illusion-of-understanding]]
- [[agentivism]]
- [[ai-labor-disruption-segments]]
- [[small-language-models]]
