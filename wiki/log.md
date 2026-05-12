# Wiki Log

Append-only record of all operations.

---

## 2026-04-25 — Initial ingestion (3 sources)

**Sources ingested**:
1. `raw/The education of Sal Khan and the limits of his chatbot.md`
2. `raw/Agentivism.pdf`
3. `raw/Applied-Co-Intelligence–Preparing-Career-and-Technical-Education-Learners-for-an-AI-Driven-Workforce-FINAL.pdf`

**Pages created**:

*Source summaries*:
- `wiki/sal-khan-khanmigo-limits.md` — Summary of Chalkbeat article on Khanmigo's limits
- `wiki/agentivism.md` — Summary of Yan & Gašević's Agentivism learning theory
- `wiki/applied-co-intelligence-report.md` — Summary of CTE Futures Applied Co-Intelligence report

*Concept pages*:
- `wiki/khanmigo.md` — Khan Academy's AI tutoring chatbot
- `wiki/ai-tutoring.md` — AI tutoring: promise, reality, and conditions for effectiveness
- `wiki/ai-in-k12-education.md` — Broad overview of AI in K-12 schools
- `wiki/applied-co-intelligence-model.md` — The ACI pedagogical framework
- `wiki/ai-mastery-continuum.md` — The four-level AI Mastery Continuum
- `wiki/co-intelligence.md` — Ethan Mollick's co-intelligence concept
- `wiki/cte-and-ai.md` — CTE's risks and opportunities in the AI era
- `wiki/labor-market-polarization.md` — Technology-driven hollowing out of middle-skill work
- `wiki/transferable-skills.md` — Human competencies that AI cannot replicate

*Infrastructure*:
- `wiki/index.md` — Table of contents
- `wiki/log.md` — This file

**Total pages created**: 14

---

## 2026-04-26 — Ingestion (2 sources)

**Sources ingested**:
1. `raw/AI's 'Delusional Spirals' (and What to Do About Them).md`
2. `raw/Using LLMs To Improve Workplace Social Skills.md`

**Pages created**:

*Source summaries*:
- `wiki/ai-delusional-spirals.md` — Stanford study on AI sycophancy and dangerous escalation spirals
- `wiki/llms-workplace-social-skills.md` — Stanford RCT on AI practice partners for social skill development

*Concept pages*:
- `wiki/ai-sycophancy.md` — AI's trained tendency to validate; harm in vulnerable and learning contexts
- `wiki/ai-and-mental-health.md` — AI as training tool vs. harm amplifier in mental health contexts

**Pages updated**:
- `wiki/ai-tutoring.md` — Added sections on social skills training (positive case) and delusional spirals (risk)
- `wiki/agentivism.md` — Added empirical support note to P2 from CARE RCT
- `wiki/transferable-skills.md` — Added section on AI-assisted development of social transferable skills
- `wiki/index.md` — Added new source summaries, AI Risks and Safety section, new theme entry

**Total pages created**: 4 | **Total pages updated**: 4

---

## 2026-04-27 — Ingestion (2 sources)

**Sources ingested**:
1. `raw/Can Small Language Models Help K–12 Schools.md`
2. `raw/SmallLLMs.pdf`

**Pages created**:

*Source summaries*:
- `wiki/small-language-models-k12.md` — EdTech Magazine article on SLMs as a K–12 alternative to LLMs
- `wiki/small-models-big-support.md` — Academic paper on locally-deployed educator AI support framework

*Concept pages*:
- `wiki/small-language-models.md` — SLMs: definition, educational case, performance evidence, architectural strategies
- `wiki/ai-privacy-and-institutional-adoption.md` — Cost, privacy, infrastructure, and policy barriers to equitable AI adoption

**Pages updated**:
- `wiki/ai-in-k12-education.md` — Added SLMs section as a more viable path for schools
- `wiki/index.md` — Added new source summaries, Infrastructure and Adoption section, new theme entry

**Total pages created**: 4 | **Total pages updated**: 2

---

## 2026-04-27 — Ingestion (1 source)

**Sources ingested**:
1. `raw/The Evidence Base on AI in K-12 Report.pdf`

**Pages created**:

*Source summaries*:
- `wiki/evidence-base-ai-k12.md` — Stanford SCALE 2026 systematic review: 818 papers, 20 causal, zero high-quality U.S. K–12 student studies; general-purpose AI harms learning; tutoring-specific design matters; educator AI most consistently positive; expertise reversal equity finding

**Pages updated**:
- `wiki/ai-tutoring.md` — Added "The Crutch Effect" section with Bastani/Fischer/Kosmyna/Lehmann causal findings; added "AI for Educator Development" section with Tutor CoPilot, Roy et al., Demszky's design distinction; updated sources and Evidence Base citation
- `wiki/agentivism.md` — Added empirical support notes to P3 (Kosmyna essay recall, Kreijkes notetaking) and P4 (Bastani Turkey study, Fischer 17% drop); added evidence-base-ai-k12 to sources and related pages
- `wiki/khanmigo.md` — Added "Causal Validation of Khanmigo's Design Philosophy" section: Bastani et al. validates hint-based approach; adoption not design was the failure; updated sources and related pages
- `wiki/cte-and-ai.md` — Added Lehmann et al. widening-gap finding to Equity Concerns section; updated sources and related pages
- `wiki/ai-in-k12-education.md` — Updated State of Play with specific report numbers (818/20/0); expanded Evidence Gap section with quantified gaps and longitudinal tension; updated sources and related pages
- `wiki/index.md` — Added evidence-base-ai-k12 to Source Summaries; added two new Key Themes on AI design and educator AI

**Total pages created**: 1 | **Total pages updated**: 6

---

## 2026-04-27 — Lint audit

**Findings** (7 items):
1. **Broken link** (fixed): `ai-sycophancy.md` — `[[ai-social-skills-training]]` doesn't exist; corrected to `[[llms-workplace-social-skills|social skills training]]`
2. **Missing link** (fixed): `sal-khan-khanmigo-limits.md` — Evidence Base section referenced the Stanford overview paper without linking to `[[evidence-base-ai-k12]]`; added link and specific numbers
3. **Missing links** (fixed): `transferable-skills.md` Related pages — missing `[[llms-workplace-social-skills]]` and `[[ai-sycophancy]]` despite body text discussing both
4. **Missing link** (fixed): `ai-in-k12-education.md` — "cited in the Sal Khan article" lacked explicit `[[sal-khan-khanmigo-limits]]` link
5. **Missing link** (fixed): `applied-co-intelligence-report.md` Related pages — missing `[[evidence-base-ai-k12]]`
6. **No orphans**: All 21 pages have at least 2 inbound links
7. **Concept gap** (flagged, not yet created): AI pedagogical guardrails — content distributed across `evidence-base-ai-k12` and `ai-tutoring`; candidate for a dedicated concept page if a focused source arrives

**Pages updated**: `ai-sycophancy.md`, `sal-khan-khanmigo-limits.md`, `transferable-skills.md`, `ai-in-k12-education.md`, `applied-co-intelligence-report.md`

---

## 2026-04-28 — Ingestion (3 sources; 1 source skipped)

**Sources attempted**:
1. `raw/Your Brain on ChatGPT.pdf` — ingested
2. `raw/Labor market impacts of AI A new measure and early evidence.md` — ingested
3. `raw/The economics of AI in spring 2026.md` — ingested
4. `raw/Dept of Labor AI Literacy Framework.md` — **skipped**: file contains only an embedded image URL with no extractable text content; cannot ingest without visual access to the image

**Pages created**:

*Source summaries*:
- `wiki/your-brain-on-chatgpt.md` — MIT Media Lab EEG study (Kosmyna et al., 2025, 54 participants): LLM users show up to 55% reduced directed neural connectivity vs. Brain-only writers; 83% can't quote their own essays in Session 1 (0% correct); AI judge inflates scores vs. human teachers; Session 4 (n=18): LLM-to-Brain participants score below Session 1 Brain-only baseline — cognitive debt confirmed neurologically; Brain-to-LLM participants use AI more strategically and maintain higher connectivity
- `wiki/anthropic-labor-market-index.md` — Massenkoff & McCrory (Anthropic, March 2026): introduces "observed exposure" metric combining theoretical LLM capability (Eloundou β) with actual Claude usage data; most exposed occupations: Computer Programmers (75%), Customer Service Reps, Data Entry Keyers (67%), Financial Analysts; equity inversion — most exposed workers are older, more educated, higher-paid; no unemployment impact detected; 14% drop in job finding rate for workers aged 22–25 in exposed occupations
- `wiki/ai-economics-scan-2026.md` — Bryan Alexander horizon scan (April 2026): AI bubble question (IT investment at dot-com-era peak; OpenAI not profitable until 2030); business model divergence (Anthropic subscription vs. OpenAI ads/defense); three labor scenarios still open; Project Iceberg estimates 11.7% of skills susceptible; LinkedIn: 640K AI-related jobs created 2023–2025; Harvard: pronounced junior employment decline, senior employment stable; tech sector layoffs attributed to AI (Microsoft 7%, Meta 10%, Block 40%)

*Concept pages*:
- `wiki/cognitive-debt.md` — New concept page: definition (Kosmyna et al.), empirical basis (behavioral + EEG), mechanism (6-step failure of internalization), cognitive debt vs. productive AI use (LLM-first vs. Brain-first pathways), relationship to Agentivism (table mapping mechanisms), relationship to crutch effect, implications for education (4 points on AI sequencing), limitations

**Pages updated**:
- `wiki/agentivism.md` — Added empirical support for P6: Session 4 cognitive debt finding (LLM-to-Brain participants below baseline); added `your-brain-on-chatgpt.pdf` to Sources; added `[[cognitive-debt]]` and `[[your-brain-on-chatgpt]]` to Related pages; updated Last updated
- `wiki/evidence-base-ai-k12.md` — Deepened Kosmyna et al. citation with EEG mechanism (55% reduced connectivity) and longitudinal cognitive debt finding from full study; added `[[your-brain-on-chatgpt]]` and `[[cognitive-debt]]` links; added both to Related pages; updated Sources and Last updated
- `wiki/ai-tutoring.md` — Deepened crutch effect section with EEG mechanism: theta/alpha wave suppression bypasses episodic memory consolidation; cognitive debt finding (LLM-to-Brain below baseline); added `[[your-brain-on-chatgpt]]` and `[[cognitive-debt]]` inline and to Related pages; updated Sources and Last updated
- `wiki/labor-market-polarization.md` — Added "Observed Exposure" section: theory-practice gap (33% vs. 94% theoretical for Computer & Math); equity inversion demographics; no unemployment impact but 14% young worker hiring slowdown; added `[[anthropic-labor-market-index]]` and `[[ai-economics-scan-2026]]` to Related pages; updated Sources and Last updated
- `wiki/cte-and-ai.md` — Added equity inversion finding (exposed workers are more educated and higher-paid) to Equity Concerns; added junior employment decline signal; added `[[anthropic-labor-market-index]]` and `[[ai-economics-scan-2026]]` to Related pages; updated Sources and Last updated
- `wiki/index.md` — Added 3 new source summaries; added `[[cognitive-debt]]` to Concept Pages (AI and Learning Theory); updated labor-market-polarization description; added 2 new Key Themes (equity inversion, cognitive debt)

**Total pages created**: 4 | **Total pages updated**: 6

---

## 2026-05-04 — Ingestion (3 sources)

**Sources ingested**:
1. `raw/What will be scarce_.md` — Alex Imas (UChicago Booth), Substack, April 13, 2026
2. `raw/Why the A.I. Job Apocalypse (Probably) Won't Happen.md` — Ezra Klein, NYT Opinion, May 3, 2026
3. `raw/'The reality, for better or worse'_ Columbia computer science students and faculty grapple with AI's disruption of the field.md` — Columbia Spectator, May 3, 2026

**Pages created**:

*Source summaries*:
- `wiki/what-will-be-scarce.md` — Imas essay: structural change economics (income effects 75% of reallocation); relational sector thesis (care, hospitality, artisanal production, education as high-income-elasticity sectors); mimetic desire as behavioral foundation (Girard; WTP doubles with exclusion; AI involvement halves exclusivity premium); Baumol's cost disease as feature; Starbucks case study; caveats on developing world and labor share
- `wiki/ai-job-apocalypse-klein.md` — Klein NYT synthesis: 70% of Americans expect AI job losses vs. 4.3% unemployment in March 2026; relational economy summary (Imas); Jevons Paradox (accountants quadrupled after VisiCalc); Klein's personal observation (better AI → more human collaboration); two underweighted concerns: partial displacement is politically harder to address than mass unemployment; relational skills deteriorating (12 hrs/week with friends 2003 → 5 hrs/week 2024; dating rates falling)
- `wiki/columbia-cs-ai-disruption.md` — Columbia Spectator investigation: total CS majors fell 4.5% in 2024-25; CS has 5th highest unemployment rate (7%) per NY Fed; "code monkey jobs" at risk; actual AI use is 60-70% tutoring-like (concepts, clarification, practice); assessment restructured (homework → exams now majority); Columbia SEAS curriculum redesign around "read, verify, and reason about code"; new AI minor for non-CS majors; social isolation from AI replacing peer-to-peer questions; K-12 AI literacy as new pre-college equity gap

*Concept pages*:
- `wiki/relational-economy.md` — New concept page synthesizing Imas and Klein: structural change framework (farm → factory → services → relational sector); mimetic desire behavioral foundation (Girard; experimental evidence WTP doubles with exclusion, AI halves exclusivity premium); Baumol's cost disease as feature not bug; Jevons Paradox; formal prediction (automated sectors shrink as GDP share; relational sectors grow); counterargument on relational skills atrophy (Klein's social data); implications for CTE (CTE pathways are largely relational sector pathways); caveats (developing world; labor aggregate share may still fall)

**Pages updated**:
- `wiki/labor-market-polarization.md` — Added "Relational Economy Counter-Thesis" section: structural change mechanism, Jevons Paradox, how relational economy reframes polarization endpoint; added Imas and Klein to Sources; added `[[relational-economy]]`, `[[what-will-be-scarce]]`, `[[ai-job-apocalypse-klein]]` to Related pages; updated Last updated
- `wiki/cte-and-ai.md` — Added "Relational Economy Reframe" to Opportunity Landscape: affirmative (not just defensive) case that CTE pathways are the relational sector; Starbucks case study; income elasticity argument; added Imas and Klein to Sources; added `[[relational-economy]]`, `[[what-will-be-scarce]]` to Related pages; updated Last updated
- `wiki/transferable-skills.md` — Added "Economic Valuation: The Relational Economy Argument" section: structural change grounds transferable skills in labor market theory not just employer surveys; Klein's warning on relational skills atrophy; added Imas and Klein to Sources; added three new Related pages; updated Last updated
- `wiki/cognitive-debt.md` — Added "Relational Debt: An Extension" section: Klein's social isolation data (12 hrs/week → 5 hrs/week with friends); Columbia CS office hours collapse; relational analogue to cognitive debt; relational economy connection; added Klein to Sources; added `[[relational-economy]]`, `[[ai-job-apocalypse-klein]]`, `[[columbia-cs-ai-disruption]]` to Related pages; updated Last updated
- `wiki/ai-in-k12-education.md` — Added "Higher Education as a Leading Indicator" section: Columbia CS enrollment data (4.5% decline, 7% unemployment rate); assessment restructuring; actual AI use patterns (60-70% tutoring-like); K-12 AI literacy as new equity gap; social isolation; added Columbia source; added `[[columbia-cs-ai-disruption]]`, `[[relational-economy]]` to Related pages; updated Last updated
- `wiki/index.md` — Added 3 new source summaries; added `[[relational-economy]]` to CTE and Workforce Concept Pages; updated transferable-skills description; added 3 new Key Themes (relational economy is CTE economy; relational skills becoming scarce)

**Total pages created**: 4 | **Total pages updated**: 6

---

## 2026-05-12 — Ingestion (1 source)

**Sources ingested**:
1. `raw/Meta-analysis on the influence of AI agents on K-12 student cognitive performance.md` — Liu, Mbowe, Tahri & Aziku, *Computers in Human Behavior Reports*, 2026

**Pages created**:

*Source summaries*:
- `wiki/ai-agents-k12-meta-analysis.md` — Liu et al. (2026) meta-analysis: 34 studies, 73 effect sizes, 3,042 participants; overall g = 0.404 (moderate, significant); by cognitive category: skills-based g=0.391, knowledge g=0.344, higher-order g=0.540 (non-significant); by grade level (key moderator, p=0.005): upper-primary g=0.877, lower-secondary g=0.195, high school g=0.037 (non-significant); by discipline: language/literacy g=0.830, arts g=0.755, math/tech g=0.230, natural science g=−0.065 (non-significant); AI type not a significant moderator; high heterogeneity (I²=91.2%); 67.65% of studies from Asia; reconciliation with evidence-base-ai-k12: designed interventions vs. general-purpose chatbots

**Pages updated**:
- `wiki/evidence-base-ai-k12.md` — Added "A Broader Meta-Analytic View" section reconciling Liu et al. with Stanford findings: designed vs. general-purpose AI distinction; grade-level and subject breakdowns; added to Sources and Related pages; updated Last updated
- `wiki/ai-tutoring.md` — Added "What Designed AI Interventions Can Achieve" section: high school near-zero finding, language/literacy strength, natural science negative, AI type non-significant; added to Sources and Related pages; updated Last updated
- `wiki/cte-and-ai.md` — Added "Evidence on AI Effectiveness at the CTE Level" section: high school g=0.037 directly challenges assumptions about AI in CTE programs; added to Sources and Related pages; updated Last updated
- `wiki/index.md` — Added source summary entry; added new Key Theme on high school AI tutoring evidence

**Total pages created**: 1 | **Total pages updated**: 4

---

## 2026-05-12 — Ingestion (2 sources)

**Sources ingested**:
1. `raw/Apocalypse No.md` — Scott Galloway (profgmedia.com), May 8, 2026
2. `raw/The Illusion of Understanding.pdf` — Abdelghani, Murayama, Kidd, Sauzéon, Oudeyer; Hector Research Institute / UC Berkeley / Inria Bordeaux; arXiv:2505.01106v2, March 3, 2026

**Pages created**:

*Source summaries and concept pages*:
- `wiki/apocalypse-no-galloway.md` — Galloway arguing AI job apocalypse is marketing strategy; US tech employment 8.7M→9.6M (2020–2023), flat since; layoff anatomy (Oracle trading people for chips, Meta returning to 2021 headcount, Microsoft still 47% larger than pre-pandemic, xAI grew to 5K employees); three scenarios (bubble, Jevons/creative destruction, permanent underclass); Shiller narrative economics (fear stories can become self-fulfilling); Gini >0.8 as the real inequality risk; companion piece to Klein's [[ai-job-apocalypse-klein]]
- `wiki/illusion-of-understanding.md` — Abdelghani et al. (2026): N=63 French middle-schoolers (age 14–15), six science tasks with ChatGPT; prompt discrimination at chance level (d'=0.19, p=0.08); answer evaluation at chance level (d'=0.07, p=0.65); 71.4% of low-quality answers rated "useful"; only 14 students asked any follow-up; task success M=0.51 (chance); positive AI attitudes negatively predict quality (β=−0.39); metacognition protective (r=0.30); domain knowledge not protective; two recommendations: pedagogical friction, LLM pedagogical alignment; related to but distinct from [[cognitive-debt]]

**Pages updated**:
- `wiki/ai-job-apocalypse-klein.md` — Added "Companion Piece: Galloway's Labor Data" section; added `[[apocalypse-no-galloway]]` to Related pages; updated Last updated
- `wiki/agentivism.md` — Added Abdelghani et al. empirical evidence to P2 (epistemic monitoring absent; chance-level discrimination; only 14/63 follow-up questions; "illusion of understanding" coinage); updated Sources and Related pages; updated Last updated
- `wiki/evidence-base-ai-k12.md` — Added Illusion of Understanding to Key Finding 2 section (Socratic chatbot paradox context); updated Sources and Related pages; updated Last updated
- `wiki/cognitive-debt.md` — Added "The Illusion of Understanding: A Metacognitive Cousin" section: within-session vs. longitudinal accumulation distinction; positive AI attitudes as risk factor for debt accumulation; updated Sources and Related pages; updated Last updated
- `wiki/ai-in-k12-education.md` — Added Abdelghani et al. finding to Evidence Gap section; updated Sources and Related pages; updated Last updated
- `wiki/index.md` — Added 2 new source summaries; added `[[illusion-of-understanding]]` to AI Risks and Safety concept pages; added new Key Theme on illusion of understanding; added `[[apocalypse-no-galloway]]` to source summaries; updated Last updated

**Total pages created**: 2 | **Total pages updated**: 6
