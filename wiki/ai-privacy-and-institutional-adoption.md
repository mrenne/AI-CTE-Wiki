# AI Privacy and Institutional Adoption

**Summary**: The cluster of cost, data privacy, infrastructure, and policy barriers that prevent schools and colleges from adopting AI — and the emerging strategies (local SLM deployment, elastic policies, fellowship programs) for overcoming them equitably.

**Sources**: `raw/SmallLLMs.pdf`, `raw/Can Small Language Models Help K–12 Schools.md`, `raw/Applied-Co-Intelligence–Preparing-Career-and-Technical-Education-Learners-for-an-AI-Driven-Workforce-FINAL.pdf`

**Last updated**: 2026-04-27

---

## Overview

The promise of AI in education runs headlong into a cluster of practical institutional barriers: cost, data privacy, infrastructure constraints, policy uncertainty, and internal institutional divides. These barriers are not evenly distributed — they fall hardest on the districts and institutions that serve the most vulnerable students, threatening to make AI a privilege rather than an equalizer.

## The Core Barriers

### 1. Cost
Cloud-based LLM APIs charge per token. For an institution with thousands of students and teachers querying AI tools throughout the day, costs scale rapidly and unpredictably. On top of per-query costs, running large models locally requires expensive GPU infrastructure most schools do not have.

[[Small language models]] offer a direct response: 3–7B parameter models run on standard institutional hardware at no marginal per-query cost (source: SmallLLMs.pdf).

### 2. Data Privacy
Routing student submissions, grades, and curriculum materials through third-party cloud APIs creates significant privacy exposure. Student data is subject to FERPA, state privacy laws, and district policies — and most cloud AI providers cannot offer the institutional control these regulations require. Faculty who are already skeptical of AI may refuse to use tools that route student work through external servers.

Local SLM deployment eliminates this problem: all data stays within the institution's secure network. The [[small-models-big-support]] framework was designed around this as a non-negotiable constraint (source: SmallLLMs.pdf).

### 3. Infrastructure and the Digital Divide
The [[applied-co-intelligence-report]] identifies a persistent digital divide as a structural barrier: "A private school might offer a full semester of prompt engineering, while many rural or low-income districts still lack reliable Wi-Fi or basic computing infrastructure" (source: Applied-Co-Intelligence PDF). Federal data confirms geographic and resource gaps significantly impact access to advanced technologies.

SLMs reduce infrastructure requirements (standard PCs instead of GPU servers) but do not eliminate them — connectivity and basic computing remain prerequisites.

### 4. Policy Patchwork
In the absence of federal AI law, institutions face a fragmented landscape: some ban AI entirely, others have no policy, most operate without clear guidance. In a 2025 Tennessee survey, 85% of CTE coordinators believed AI would significantly change their fields; only 15% had clear guidance on how to prepare (source: Applied-Co-Intelligence PDF).

The result is what the ACI report calls a "Wild West scenario" — individual instructor judgment substituting for institutional strategy, creating inequitable and incoherent student experiences.

### 5. Internal Institutional Divides
Many faculty distrust AI as a cost-cutting tool disguised as pedagogical innovation — a fear validated by reports of administrators asking whether AI means they can "fire all the adjuncts and increase class sizes" (C. Edward Watson, AAC&U, cited in Applied-Co-Intelligence PDF). This internal divide must be addressed through faculty-led, administratively-supported implementation rather than top-down mandates.

## The Equity Dimension

These barriers compound each other and fall unevenly. Well-resourced institutions can absorb API costs, hire AI staff, negotiate favorable vendor agreements, and develop coherent policy frameworks. Rural, low-income, and under-resourced institutions cannot. As the ACI report warns:

> "Until all three of these structural barriers — policy, leadership, and access — are addressed, the promise of AI will exacerbate, not close, existing opportunity gaps." (source: Applied-Co-Intelligence PDF)

## Emerging Responses

| Barrier | Emerging Response |
|---------|------------------|
| Cost | Local SLM deployment on standard hardware; open-weight models (Llama, Qwen, Neural-Chat) |
| Data privacy | On-premises deployment; no cloud API routing; local vector stores |
| Infrastructure gap | SLMs on standard PCs; federal/state investment in connectivity and devices |
| Policy patchwork | Elastic frameworks (FACCC, ASCCC in California); WICHE policy toolkit |
| Internal divides | Faculty-led AI fellowships (Tennessee Perkins READI, CA Community Colleges Chancellor's AI Fellows) |
| Sovereignty | Open-weight models under institutional control; RLHF from local teacher feedback |

## Implications for CTE

CTE institutions — often community colleges and technical schools serving diverse, lower-income populations — face these barriers acutely. The [[applied-co-intelligence-report]] recommends policymakers invest in equitable AI infrastructure as a prerequisite for meaningful [[applied-co-intelligence-model]] implementation. Without it, the ACI model remains a vision for well-resourced institutions only.

The [[small-models-big-support]] research demonstrates that the technical barriers are more surmountable than they appear: a locally-deployed 7B model on consumer hardware can support educator workflows effectively. The remaining barriers are policy, funding, and institutional will — all human choices, not technical inevitabilities.

## Related pages

- [[small-language-models]]
- [[small-models-big-support]]
- [[small-language-models-k12]]
- [[applied-co-intelligence-report]]
- [[cte-and-ai]]
- [[ai-in-k12-education]]
