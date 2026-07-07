# Wiki Log

Append-only record of all operations.

---

## 2026-04-25 — Initial ingestion (3 sources)

**Sources ingested**:
1. `raw/blog/The education of Sal Khan and the limits of his chatbot.md`
2. `raw/PDF/Agentivism.pdf`
3. `raw/PDF/Applied-Co-Intelligence–Preparing-Career-and-Technical-Education-Learners-for-an-AI-Driven-Workforce-FINAL.pdf`

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
1. `raw/blog/AI's 'Delusional Spirals' (and What to Do About Them).md`
2. `raw/misc/Using LLMs To Improve Workplace Social Skills.md`

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
1. `raw/blog/Can Small Language Models Help K–12 Schools.md`
2. `raw/PDF/SmallLLMs.pdf`

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
1. `raw/PDF/The Evidence Base on AI in K-12 Report.pdf`

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
1. `raw/PDF/Your Brain on ChatGPT.pdf` — ingested
2. `raw/misc/Labor market impacts of AI A new measure and early evidence.md` — ingested
3. `raw/blog/The economics of AI in spring 2026.md` — ingested
4. `raw/misc/Dept of Labor AI Literacy Framework.md` — **skipped**: file contains only an embedded image URL with no extractable text content; cannot ingest without visual access to the image

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
1. `raw/blog/What will be scarce_.md` — Alex Imas (UChicago Booth), Substack, April 13, 2026
2. `raw/blog/Why the A.I. Job Apocalypse (Probably) Won't Happen.md` — Ezra Klein, NYT Opinion, May 3, 2026
3. `raw/blog/'The reality, for better or worse'_ Columbia computer science students and faculty grapple with AI's disruption of the field.md` — Columbia Spectator, May 3, 2026

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
1. `raw/misc/Meta-analysis on the influence of AI agents on K-12 student cognitive performance.md` — Liu, Mbowe, Tahri & Aziku, *Computers in Human Behavior Reports*, 2026

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
1. `raw/blog/Apocalypse No.md` — Scott Galloway (profgmedia.com), May 8, 2026
2. `raw/PDF/The Illusion of Understanding.pdf` — Abdelghani, Murayama, Kidd, Sauzéon, Oudeyer; Hector Research Institute / UC Berkeley / Inria Bordeaux; arXiv:2505.01106v2, March 3, 2026

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

---

## 2026-05-13 — Ingestion (2 sources)

**Sources ingested**:
1. `raw/PDF/ai-will-reshape-more-jobs-than-it-replaces.pdf` — BCG Henderson Institute, April 3, 2026; authors: Tomas Chamorro-Premuzic, Rainer Strack, Allison Bailey, Nicolas Dollé, Vinciane Beauchene
2. `raw/PDF/ai_index_report_2026_chapter_7_education.pdf` — Stanford HAI AI Index 2026, Chapter 7: Education; Stanford Institute for Human-Centered Artificial Intelligence

**Pages created**:

*Source summaries*:
- `wiki/bcg-ai-reshapes-jobs.md` — BCG six-segment taxonomy applied to 165M US jobs; 50–55% reshaped in 2–3 years, 10–15% eliminated in 4–5 years; three-factor methodology (task automation potential → augmentation vs. substitution → demand expandability); Jevons Paradox as empirical labor market mechanism (software engineers Amplified; call center reps Substituted); entry-level concentration in Divergent roles (pipeline problem); Limited-Exposure (34%) + Enabled (23%) = 57% insulated; CEO imperatives; excludes physical AI/robotics
- `wiki/stanford-ai-index-education-2026.md` — Three-way definitional framework (AI in Education / AI Literacy / AI Education); CS undergraduate enrollment -11% (2024–2025); AI master's graduates +17%; 80% of university students use GenAI (doubled from 40% in 2023); Anthropic Claude data: creating 39.8% / analyzing 30.2%; K-12: 4 states emphasize AI in CS standards; 50% of schools have AI policies; 6% of teachers say policies are clear; ECEP finding: nonbinding guidance, no teacher training standards, AP CS excludes AI; CSTA K-12 standards with AI content expected summer 2026; China/UAE mandated AI education 2025–26; India 3x global average LinkedIn AI skill penetration; US 2x; fastest growing US AI literacy skills: AI prompting, Microsoft Copilot Studio

*Concept page*:
- `wiki/ai-labor-disruption-segments.md` — Full concept page for BCG six-segment framework: Amplified (5%), Rebalanced (14%), Divergent (12%), Substituted (12%), Enabled (23%), Limited-Exposure (34%); each segment defined by automation potential + augmentation/substitution + demand expandability; CTE implications for each; combined 57% protected calculation; demand expandability mechanism; connection to relational economy thesis and Jevons Paradox

**Pages updated**:
- `wiki/labor-market-polarization.md` — Added "BCG Six-Segment Framework" section: 43% automation threshold; Substituted vs. Amplified split; entry-level concentration mechanism; 57% protected; demand expandability as empirical mechanism; updated Sources, Related pages, Last updated
- `wiki/cte-and-ai.md` — Added "BCG Confirmation: CTE Sectors Occupy the Protected 57%" section: Limited-Exposure and Enabled segments mapped to CTE pathways; entry-level concentration risk for CTE graduates entering knowledge-adjacent roles; added "Stanford AI Index: The K-12 AI Policy Gap" section: policy vacuum data; ECEP implementation gap; CSTA standards update; updated Sources, Related pages, Last updated
- `wiki/transferable-skills.md` — Added "BCG's Operationalization" section: human interaction intensity + process structure as the two BCG variables determining augmentation vs. substitution; transferable skills as the operationalized basis for the 57% insulation figure; updated Sources, Related pages, Last updated
- `wiki/ai-in-k12-education.md` — Added "Stanford AI Index 2026: Quantifying the Policy Gap" section: three-way definition; enrollment trends; 80% student use; K-12 policy vacuum; ECEP finding; CSTA update; updated Sources, Related pages, Last updated
- `wiki/index.md` — Added 2 new source summary rows; added "Labor Market Analysis" concept page section with 3 entries (bcg-ai-reshapes-jobs, ai-labor-disruption-segments, stanford-ai-index-education-2026); added 4 new Key Themes

**Total pages created**: 3 | **Total pages updated**: 5

---

## 2026-05-13 — Lint audit

**Findings**: No orphan pages, no contradictions, no format violations. 9 missing cross-links identified across pages that were written before the BCG/Stanford/Galloway/Abdelghani ingestions and not retroactively updated.

**Cross-links added**:
- `wiki/relational-economy.md` — added `[[bcg-ai-reshapes-jobs]]`, `[[ai-labor-disruption-segments]]`
- `wiki/what-will-be-scarce.md` — added `[[bcg-ai-reshapes-jobs]]`
- `wiki/anthropic-labor-market-index.md` — added `[[bcg-ai-reshapes-jobs]]`, `[[ai-labor-disruption-segments]]`
- `wiki/ai-economics-scan-2026.md` — added `[[bcg-ai-reshapes-jobs]]`, `[[apocalypse-no-galloway]]`, `[[stanford-ai-index-education-2026]]`
- `wiki/columbia-cs-ai-disruption.md` — added `[[stanford-ai-index-education-2026]]`
- `wiki/ai-sycophancy.md` — added `[[illusion-of-understanding]]`
- `wiki/your-brain-on-chatgpt.md` — added `[[illusion-of-understanding]]`
- `wiki/applied-co-intelligence-report.md` — added `[[bcg-ai-reshapes-jobs]]`, `[[stanford-ai-index-education-2026]]`
- `wiki/ai-job-apocalypse-klein.md` — added `[[bcg-ai-reshapes-jobs]]`

**Concept gaps flagged (no fix yet — await new sources)**:
- Metacognition: central to illusion-of-understanding, agentivism, cognitive-debt; no dedicated page
- Agentic AI: referenced in applied-co-intelligence-report and cte-and-ai; no dedicated page

**Total pages created**: 0 | **Total pages updated**: 9

---

## 2026-05-18 — Ingestion (1 source)

**Sources ingested**:
1. `raw/PDF/DATA CENTERS AND LOCAL ECONOMIES IN THE AGE OF AI.pdf` — Fernando E. Alvarez (U Chicago/NBER), David Argente, Joyce Chow, Diana Van Patten (Yale/NBER); NBER Working Paper 35194, May 2026

**Two other raw files found but not ingested**:
- `raw/misc/Dept of Labor AI Literacy Framework.md` — web clipper failure: contains only YAML frontmatter and a JPG image link; no actual text content captured
- `raw/Why the 'Middle Path' of AI Literacy May Be the Future of English Class.md` — file found by Glob but unreadable by Read tool; likely apostrophe encoding issue in filename; awaiting user action

**Pages created**:
- `wiki/nber-data-centers-local-economies.md` — Source summary for NBER WP 35194; shift-share IV design (two instruments: fiber proximity × Chinese DC revenue; 1980 college share × ROW DC revenue; F-stats 786–907); key IV results 1995–2020: employment +3.9%, construction employment +7.1% (front-loaded early), data-processing +29.4%, establishments +6.2%, house prices +17.7%, electricity prices +0.9%, AGI +8.2%, wages +5.9%; geographic concentration (7.6% of counties; Virginia/Texas dominant); US DC electricity 4.4% of national consumption; equity analysis: income gains trade-heavy and construction-front-loaded; costs (electricity, housing) broadly distributed and fall hardest on renters and low-income households; robustness: construction employment and total employment not robust to state FE

**Pages updated**:
- `wiki/cte-and-ai.md` — Added causal IV evidence to "AI Infrastructure Jobs" section: county-level employment, income, construction timing, geographic concentration, equity caveat on electricity and housing costs; added `[[nber-data-centers-local-economies]]` to Related pages; updated Sources and Last updated
- `wiki/labor-market-polarization.md` — Added "The Infrastructure Economy: A Distributional Case Study" section: data center gains vs. costs; electricity and housing burden on low-income residents; added `[[nber-data-centers-local-economies]]` to Related pages; updated Sources and Last updated
- `wiki/relational-economy.md` — Added "The Infrastructure Economy as Relational Economy Complement" section: physical AI infrastructure as a site of automation-resistant human labor; added `[[nber-data-centers-local-economies]]` to Related pages; updated Sources and Last updated
- `wiki/index.md` — Added source summary row (both in Source Summaries table and Labor Market Analysis concept section); added new Key Theme on AI infrastructure jobs with distributional costs

**Total pages created**: 1 | **Total pages updated**: 4

---

## 2026-05-18 — Ingestion (1 source)

**Sources ingested**:
1. `raw/blog/Why the Middle Path of AI Literacy May Be the Future of English Class.md` — David Nurenberg; *The 74* (the74million.org), May 8, 2026; abridged version of forthcoming NCTE *English Journal* Issue 115.6 article

**Pages created**:
- `wiki/middle-path-ai-literacy-nurenberg.md` — Source summary; three-option frame (ban / freely allow / teach AI literacy); five classroom activities using AI as text (literary analysis, discussion, essay writing, research, note-taking); AI audit replacing bans (demonstrate how tool operates, what gained/lost, accuracy verified, thinking not relinquished); cognitive surrender vs. cognitive offloading distinction; student-discovered sycophancy ("purposely said dumb things"); less-confident students never escaping AI deference; developmental timing argument (can't wait for skills before AI literacy); equity tension; genuine voice as transferable skill; connections to agentivism, illusion-of-understanding, ai-sycophancy, transferable-skills, cognitive-debt

**Pages updated**:
- `wiki/agentivism.md` — Added Nurenberg's AI audit as classroom operationalization of P2 (epistemic monitoring) and P3 (reconstructive internalization); student "say dumb things" probe as organic P2 instance; cognitive surrender vs. cognitive offloading as student-facing language for Agentivism's core distinction; added `[[middle-path-ai-literacy-nurenberg]]` to Related pages; updated Sources and Last updated
- `wiki/ai-sycophancy.md` — Added "Student-Discovered Sycophancy" section: student probe ("purposely said dumb things"), chatbot-as-discussion-partner as curricular sycophancy exposure tool, ChatGPT killing debate tension; added `[[middle-path-ai-literacy-nurenberg]]` to Related pages; updated Sources and Last updated
- `wiki/illusion-of-understanding.md` — Added "Classroom Observation: Metacognition's Absence in Low-Confidence Students" section: less-confident students deferring to AI writing quality, Nurenberg's unresolved tension, AI audit as structural metacognitive scaffold, equity implication for under-resourced schools; added `[[middle-path-ai-literacy-nurenberg]]` to Related pages; updated Sources and Last updated
- `wiki/transferable-skills.md` — Added "Genuine Voice as a Transferable Skill" section: essay comparison exercise, student discovery of voice vs. generic AI prose, relational economy connection, AI audit as metacognitive transferable-skills practice; added `[[middle-path-ai-literacy-nurenberg]]` to Related pages; updated Sources and Last updated
- `wiki/index.md` — Added source summary row; added new Key Theme on AI audits replacing bans

**Total pages created**: 1 | **Total pages updated**: 5

---

## 2026-05-18 — Lint audit

**Findings**: No orphans, no contradictions, no format violations. 3 missing cross-links to `[[middle-path-ai-literacy-nurenberg]]` identified in pages written before that source was ingested. README source and page counts stale.

**Cross-links added**:
- `wiki/cognitive-debt.md` — added `[[middle-path-ai-literacy-nurenberg]]` (Nurenberg cites cognitive debt research as the rationale for his middle path)
- `wiki/ai-in-k12-education.md` — added `[[middle-path-ai-literacy-nurenberg]]` (wiki's only practitioner K-12 classroom account)
- `wiki/evidence-base-ai-k12.md` — added `[[middle-path-ai-literacy-nurenberg]]` (pedagogical friction recommendation aligns with AI audit approach)

**Stale fact fixed**:
- `README.md` — updated "Nineteen sources ingested so far, producing 33 interlinked wiki pages" → "Twenty-one sources ingested so far, producing 37 interlinked wiki pages"

**Concept gaps flagged (no fix yet — await new sources)**:
- Metacognition: now prominent in 5+ pages; no dedicated page
- Agentic AI: referenced in applied-co-intelligence-report and cte-and-ai; no dedicated page

**Total pages created**: 0 | **Total pages updated**: 4

---

## 2026-05-24 — Ingestion (1 source)

**Sources ingested**:
1. `raw/PDF/Building AI Companions.pdf` — Khosravi, H., Gašević, D., Sadiq, S., Yan, L., Lodge, J.M., Tangen, J.M., Denny, P., DiCerbo, K., Buckingham Shum, S., Baker, R.S. "Building AI Companions that Prioritise Learning over Performance." arXiv:2605.04816v2, May 15, 2026. Authors: University of Queensland, University of Hong Kong, Monash University, Tsinghua University, University of Auckland, Khan Academy, University of Technology Sydney, Columbia University Teachers College.

**Pages created**:
- `wiki/building-ai-companions.md` — Source summary; learning-performance paradox (formal name for the structural mismatch between work AI and learning AI); AI for Work vs. AI for Learning nine-dimension taxonomy (Figure 1); three-foundation framework: Pedagogical (preserve productive struggle, design for transfer), Adaptive (Capture→Model→Adapt→Evolve; metacognitive calibration; RLHL), Responsible Design (security, transparency, accountability, inclusion); five case studies: Khanmigo (Socratic failure and redesign), RiPPLE (80K+ students, IRT adaptive), CodeHelp (withholds solution code), JeepyTA (Socratic discussion + essay feedback), Recast (institutional platform); prompt-level guardrails show near-null effects — architectural design required; Khanmigo finding: interest personalization produces no gains; skill-level mastery is the only useful personalization signal

**Pages updated**:
- `wiki/khanmigo.md` — Added "The Socratic Design Failure and Redesign" section: original "You are a Socratic tutor" prompt, rigid GPT interpretation, student frustration and abandonment; three-stage redesign (attempt → hint → worked example with structured engagement); ICAP cognitive engagement framework; interest vs. mastery personalization finding (interest: no gains; mastery placement: effective); added `[[building-ai-companions]]` and `[[cognitive-debt]]` to Related pages; updated Sources and Last updated
- `wiki/agentivism.md` — Added "Design Successor: Building AI Companions" section: named this paper as applied design successor by same author group (Gašević, Yan); learning-performance paradox as formal label for the performance/learning gap; Agentivism mechanism-to-design-requirement mapping table; prompt-level guardrails are insufficient (architectural, not instructional, fix required); added `[[building-ai-companions]]` to Related pages; updated Sources and Last updated
- `wiki/ai-tutoring.md` — Added "The Learning-Performance Paradox: A Formal Framing" section with the nine-dimension AI for Work vs. AI for Learning taxonomy table; added "The Three-Foundation Framework for Learning AI" section with Pedagogical, Adaptive (metacognitive calibration, RLHL), and Responsible Design foundations; critical guardrails finding (near-null effects; architectural redesign required); added `[[building-ai-companions]]` and `[[illusion-of-understanding]]` to Related pages; updated Sources and Last updated
- `wiki/cognitive-debt.md` — Added "The Learning-Performance Paradox: The Named Concept" section: conceptual relationship between cognitive debt (empirical neurological) and learning-performance paradox (named framing + design implication); both converge on task completion ≠ learning; added `[[building-ai-companions]]` to Related pages; updated Sources and Last updated
- `wiki/index.md` — Added source summary row to Source Summaries table and "AI and Learning Theory" concept table; added new Key Theme on work AI vs. learning AI as different engineering problems

**Total pages created**: 1 | **Total pages updated**: 5

---

## 2026-05-24 — Lint audit

**Findings**: No orphans, no contradictions, no format violations. 4 missing cross-links to `[[building-ai-companions]]` identified in pages written before that source was ingested. README count accurate.

**Cross-links added**:
- `wiki/illusion-of-understanding.md` — added `[[building-ai-companions]]` (metacognitive calibration is the designed response to the illusion)
- `wiki/evidence-base-ai-k12.md` — added `[[building-ai-companions]]` (answers Bastani's "science of guardrails" question)
- `wiki/sal-khan-khanmigo-limits.md` — added `[[building-ai-companions]]` (fullest account of Khanmigo's design failure and redesign)
- `wiki/your-brain-on-chatgpt.md` — added `[[building-ai-companions]]` (cognitive debt finding is building-ai-companions' empirical foundation)

**Concept gaps flagged (no fix yet — await new sources)**:
- Metacognition: now prominent in 13+ pages (illusion-of-understanding has 13 occurrences alone); no dedicated page
- Agentic AI: referenced in applied-co-intelligence-report and cte-and-ai; no dedicated page

**Total pages created**: 0 | **Total pages updated**: 4

---

## 2026-05-25 — Ingestion (1 source)

**Sources ingested**:
1. `raw/video/The Job Market Is Going Away (Here's What's Replacing It).md` — Sinead Bovell, YouTube (I've Got Questions), April 2, 2026; video transcript; futurist and strategic foresight adviser; https://www.youtube.com/watch?v=4whdDIco06c

**Pages created**:
- `wiki/sinead-bovell-job-market.md` — Source summary; task unbundling as core mechanism (AI automates tasks within jobs, not jobs themselves); skills > job titles as organizing principle; financial analyst → financial strategist evolution example; the independence era (entrepreneurial/project-based work, independent contracts); pre/post-AI skill-dominance shift; transition risk (jobs may disappear faster than new work emerges); power asymmetry as structural threat requiring policy response; AI-as-intern frame (frame, evaluate, give feedback, understand limits); AI agent architect as emerging occupation; relationship table mapping Bovell's claims to existing wiki pages

**Pages updated**:
- `wiki/labor-market-polarization.md` — Added "Task Unbundling: The Mechanism Behind Polarization" section: narrative grounding for BCG Divergent segment; fixed job titles becoming obsolete; skill credentials more durable than task credentials; added "The Independence Era: Structural Shift in Work's Form" section: project-based entrepreneurial work, independent contracts, power asymmetry risk; added `[[sinead-bovell-job-market]]` to Related pages; updated Sources and Last updated
- `wiki/transferable-skills.md` — Added "The Pre/Post-AI Skill-Dominance Shift" section: competitive advantage migrates from procedural mastery to judgment/communication/framing; AI-as-intern frame as concrete manifestation of transferable skills in practice; added `[[sinead-bovell-job-market]]` to Related pages; updated Sources and Last updated
- `wiki/cte-and-ai.md` — Added "Task Unbundling and the Skills-Based Credential Imperative" section: unbundling logic applied to CTE fields (HVAC, medical assistant); implication that procedural credentials have shorter shelf-lives; AI agent architect as emerging CTE-adjacent occupation; institutional agility as CTE's asset for tracking new role categories; added `[[sinead-bovell-job-market]]` to Related pages; updated Sources and Last updated
- `wiki/relational-economy.md` — Added "The Independence Era: A Structural Complement" section: project-based independent contracting as natural form for relational work; lifelong learning as structural requirement; policy risk of benefits/bargaining power erosion; added `[[sinead-bovell-job-market]]` to Related pages; updated Sources and Last updated
- `wiki/index.md` — Added source summary row; added new Key Theme on task unbundling and the independence era

**Total pages created**: 1 | **Total pages updated**: 5

---

## 2026-05-27 — Ingestion (1 source)

**Sources ingested**:
1. `raw/video/Preparing CTE Learners for an AI-Driven Workforce_ Introducing An Applied Co-Intelligence Model.md` — CTE Futures, ACTE, Advance CTE; February 23, 2026 webinar; presenter: Dr. Cameron Sublett (Foundation for California Community Colleges / CTE Futures); panelists: Lauren Mason, Alisha Hyslop (ACTE chief policy officer), Kate Kreamer (Advance CTE executive director), Michael Tinsley (Tennessee Board of Regents), Dr. Tom Pigg (Jackson State Community College). Video companion to the Applied Co-Intelligence report.

**Pages created**:
- `wiki/cte-futures-aci-webinar.md` — Source summary; "skill economy not job economy yet" framing; Acemoglu & Johnson *Power and Progress* citation — ACI as countervailing force; National Career Clusters Framework update: Digital Technology added as crosscutting cluster with data science/AI subcluster, designed to integrate across every sector pathway; CLNA (Comprehensive Local Needs Assessment, Perkins V) as existing policy vehicle for continuous employer alignment; traditional advisory board/curriculum cycles insufficient at AI's pace; four obstacles confirmed by practitioners with symmetric alignment crisis (employers confused too); incumbent worker demand signal; "AI is not going to fix it for you" — failure modes in occupational contexts; standalone AI courses insufficient; relationship table mapping to existing wiki pages

**Pages updated**:
- `wiki/applied-co-intelligence-model.md` — Added "Technology Is Not Destiny" section: Acemoglu/Johnson *Power and Progress* argument; ACI as countervailing force; default trajectory favors employers and high-skill workers without deliberate institutional action; added "CLNA as Implementation Vehicle" section: Perkins V existing mandate repurposed for continuous AI curriculum alignment; expanded Stand-Alone vs. Integrated section with Pigg practitioner voice; added `[[cte-futures-aci-webinar]]` to Related pages; updated Sources and Last updated
- `wiki/applied-co-intelligence-report.md` — Added "Webinar Companion" section: key additive content from the video (skill economy framing, Acemoglu anchor, CLNA, Digital Technology crosscutting cluster, symmetric alignment crisis, incumbent worker demand); added `[[cte-futures-aci-webinar]]` to Related pages; updated Sources and Last updated
- `wiki/cte-and-ai.md` — Added Digital Technology crosscutting cluster update to "What is CTE?" section; added [[cte-futures-aci-webinar]] to "Applied Co-Intelligence Response" section with CLNA and countervailing force framing; added `[[cte-futures-aci-webinar]]` to Related pages; updated Sources and Last updated
- `wiki/index.md` — Added source summary row; added two new Key Themes on technology is not destiny and skill economy before job economy

**Total pages created**: 1 | **Total pages updated**: 4

---

## 2026-05-29 — Ingestion (1 source)

**Sources ingested**:
1. `raw/PDF/The Broken Ladder.pdf` — Peter John Lambert (University of Warwick & LSE) & Yannick Schindler (Ellison Institute of Technology, Oxford); May 2026 working paper. Correspondence: p.j.lambert@lse.ac.uk. Funded by ESRC via CAGE (Warwick) and Centre for Economic Performance (LSE).

**Pages created**:
- `wiki/broken-ladder.md` — Source summary; central claim: WFH is the more robust predictor of the early-career hiring decline, not GenAI; data: 243M new hires + 407M job postings, US/UK/Canada/Australia 2017–2025; WFH/GenAI Spearman rank correlation of 0.77 across O*NET occupations; joint-treatment DiD: WFH coefficient stable (−1.42 to −1.57pp), GenAI attenuates to near-zero and often insignificant; actual WFH adoption design confirms result; formal model: WFH raises supervision costs and lowers learning rates → reduced junior hiring share; robustness: non-parametric co-treatment controls, selection-on-unobservables (WFH RV 3–5× larger than GenAI RV), Monte Carlo measurement-error simulations, alternative exposure measures, leave-one-out by occupation and country; scope caveats: covers only junior vs. senior ratio up to 2025, does not address mass unemployment; optimism argument: WFH frictions are surmountable via managerial practice; relationship table mapping to existing wiki pages

**Pages updated**:
- `wiki/anthropic-labor-market-index.md` — Added "Methodological Caveat: The WFH Confound" section: Lambert & Schindler's challenge to AI attribution of 14% young-worker hiring slowdown; design differences between the two papers; working synthesis (decline is real; attribution contested); added `[[broken-ladder]]` to Related pages; updated Last updated
- `wiki/labor-market-polarization.md` — Added "The WFH Confound: Rethinking the Entry-Level Hiring Decline" section: 0.77 rank correlation between WFH and GenAI exposure; joint-treatment DiD results; WFH mechanism (supervision costs + learning rates); caveat on prior wiki framing; CTE double-insulation finding (bottom of both rankings); optimism argument; added `[[broken-ladder]]` to Related pages; updated Sources and Last updated
- `wiki/cte-and-ai.md` — Added WFH confound caveat to BCG Confirmation section; noted that CTE occupations sit at the bottom of both WFH and GenAI exposure rankings (doubly insulated); added `[[broken-ladder]]` to Related pages; updated Sources and Last updated
- `wiki/index.md` — Added source summary row; added two new Key Themes on contested AI attribution and CTE double insulation

**Total pages created**: 1 | **Total pages updated**: 4

---

## 2026-06-09 — Ingestion (1 source)

**Sources ingested**:
1. `raw/video/These Teens Are Choosing Trade Classes to AI-Proof Their Futures.md` — The New York Times video, June 3, 2026; ~4 minutes; Bay Area, California; graduating high school seniors in a construction trades program discussing their trade pivot as an AI hedge.

**Pages created**:
- `wiki/nyt-teens-trade-classes.md` — Source summary; first primary journalistic evidence in the wiki of student-level behavioral response to AI anxiety; Bay Area class of 2026 articulating physical-presence insulation argument independently; CTE as discovery pathway (95%+ had never used tools before; choice required the program to exist); California 2021 construction grant doubling as structural precondition; six-figure wage narrative arriving via social media; trade stigma persists — family/cultural pressure especially strong for immigrant families; "no path is safe" as the underlying psychological frame of the COVID generation; relationship table mapping to existing wiki claims

**Pages updated**:
- `wiki/cte-and-ai.md` — Added "Student Behavioral Response: The Class of 2026" section: AI hedge argument articulated by students; CTE as discovery mechanism; trade stigma as the binding constraint; generalized economic anxiety framing; added `[[nyt-teens-trade-classes]]` to Related pages; updated Sources and Last updated
- `wiki/index.md` — Added source summary row; added new Key Theme on the trade pivot and CTE exposure as the mechanism

**Total pages created**: 1 | **Total pages updated**: 2

---

## 2026-06-10 — Ingestion (1 source)

**Sources ingested**:
1. `raw/video/New Book Podcast_ AI Unplugged_ The Hype and Hope in Education Futures.md` — MindShare TV podcast, June 4, 2026; host: Robert Merloti; guest: Dr. Stephen Murgatroyd (University of Alberta, education futurist); discussing *AI Unplugged: The Hype and Hope in Education Futures* (Routledge, co-authored with John-Claude Couture), his 50th book. First Canadian/non-US source in the wiki.

**Pages created**:
- `wiki/ai-unplugged-murgatroyd.md` — Source summary; historical edtech skepticism ("we've had this conversation since 1927"); interregnum framing for the current transition; "build, analyze, defend" assessment scaffold that maps to agentivism mechanisms and renders AI detection moot; AI detection software legal liability (court cases of students suing); students as knowledgeable participants (Toronto BLDP); teacher working conditions as real adoption constraint (Alberta 10-week strike); Canadian equity/access data (650K households offline, 5 most expensive globally for broadband); western/colonial bias in AI outputs; data sovereignty response; Treaty 8 indigenous school case (AI as necessity, Cree language learning supports); Deloitte/Shopify hiring direct from high school; ecosystem framing for school's role

**Pages updated**:
- `wiki/ai-privacy-and-institutional-adoption.md` — Added "International Perspective: Canada's Equity and Access Challenge" section (650K households, cost data, teacher tool cost); added "Western Cultural Bias and Indigenous Data Sovereignty" section (colonial bias in AI, data sovereignty, BC indigenous LMS, Treaty 8 case study); added `[[ai-unplugged-murgatroyd]]` to Related pages; updated Sources and Last updated
- `wiki/evidence-base-ai-k12.md` — Added "AI Detection Software: Ineffective and Legally Risky" section (legal liability, false accusations, court cases); added "Assessment Redesign: Build → Analyze → Defend" section (scaffold mapped to agentivism; portfolio assessment; 50-year apprenticeship framing); added `[[ai-unplugged-murgatroyd]]` to Related pages; updated Sources and Last updated
- `wiki/labor-market-polarization.md` — Added "Adaptive Employer Responses: Hiring Directly from High School" section (Deloitte, Shopify; skills-over-credentials shift in large employers); added `[[ai-unplugged-murgatroyd]]` to Related pages; updated Sources and Last updated
- `wiki/agentivism.md` — Added "build, analyze, defend" scaffold as second classroom operationalization of agentivism mechanisms, alongside Nurenberg's AI audit; added `[[ai-unplugged-murgatroyd]]` to Related pages; updated Sources and Last updated
- `wiki/index.md` — Added source summary row; added two new Key Themes on oral defense/AI detection and cultural bias/data sovereignty

**Total pages created**: 1 | **Total pages updated**: 5

---

## 2026-06-10 — Lint audit + README update

**Lint findings**: No orphan pages, no format violations, no broken wiki-links. 5 missing cross-links identified for the two most recently added source pages. README "What the research actually shows" section stale — did not yet reflect The Broken Ladder, NYT Teens, or AI Unplugged findings.

**Cross-links added**:
- `wiki/broken-ladder.md` — added `[[nyt-teens-trade-classes]]` (students independently confirm the double-insulation thesis)
- `wiki/cognitive-debt.md` — added `[[ai-unplugged-murgatroyd]]` (Build→Analyze→Defend scaffold as the assessment antidote to cognitive debt)
- `wiki/ai-in-k12-education.md` — added `[[ai-unplugged-murgatroyd]]` (AI detection legal liability; assessment redesign; historical skepticism counterpoint)
- `wiki/cte-and-ai.md` — added `[[ai-unplugged-murgatroyd]]` (Deloitte/Shopify direct HS hiring; teacher conditions; Canadian equity data)
- `wiki/labor-market-polarization.md` — added `[[nyt-teens-trade-classes]]` (student behavioral evidence for the trade pivot section)

**README updated**:
- Added fifth learning/cognition bullet: oral defense as answer to both cognitive debt and AI detection; "Build, Analyze, Defend" scaffold; AI detection legal liability
- Replaced entry-level hiring bullet with updated framing: decline is real but attribution contested; WFH confound (Broken Ladder); 243M hires, four countries, joint-treatment DiD
- Added new "On CTE specifically" section (3 bullets): student behavioral response in AI capital; CTE as discovery mechanism; CTE double insulation from both post-pandemic shocks
- Added third schools/policy bullet: AI equity as cultural representation problem beyond infrastructure; indigenous data; data sovereignty

**Total pages created**: 0 | **Total pages updated**: 6 (broken-ladder, cognitive-debt, ai-in-k12-education, cte-and-ai, labor-market-polarization, README)

---

## 2026-06-10 — Ingestion (1 source)

**Sources ingested**:
1. `raw/blog/AI is making you faster AND slower, better AND worse at your job.md` — Dr. Philippa Hardman, Substack, June 3, 2026. Synthesizes Demirer, Musolff & Yang (2026) study of 100,000+ GitHub developers across three AI tool generations into a five-effects taxonomy for AI's actual workplace impact. First source in the wiki grounded in large-scale workplace productivity data. Cited by Murgatroyd (source 27) as essential reading.

**Pages created**:
- `wiki/hardman-ai-faster-slower.md` — Source summary; five-effects taxonomy: (1) Faster creation (+228% to +740% production velocity); (2) Only ~20% more shipped — productivity funnel (740% code → 65% more reviews → 20% more shipped); (3) More complex (upstream cheaper, downstream heavier); (4) Lower average quality (AI reproduces common practice, not best practice; quality drag mechanism); (5) Better — only when aimed high in the chain with scaffolded domain-specific design; "enter high in the chain" strategic principle; organizational failure rates (MIT NANDA 95%, RAND 80%, Gartner 60%); P&G/NBER 1+AI≈2-person team; anthropomorphism warning (Kropp et al., 2026 — "AI buddy/mentor" framing makes reviewers sloppier); five practical strategies; relationship table mapping to existing wiki claims

**Pages updated**:
- `wiki/building-ai-companions.md` — Added "Workplace-Scale Validation: The Five-Effects Taxonomy" section: productivity funnel as workplace analog to learning-performance paradox; "enter high in the chain" principle validates architectural argument over prompt guardrails; quality drag mechanism as the organizational manifestation of the learning-performance paradox; Effect 5 corroborates the high-chain design goal; added `[[hardman-ai-faster-slower]]` to Related pages; updated Sources and Last updated
- `wiki/evidence-base-ai-k12.md` — Added "Organizational Evidence: The Productivity Funnel" section: 740%→20% productivity funnel; MIT NANDA 95%, RAND 80%, Gartner 60% organizational failure rates; "enter high in the chain" principle applied to educational AI deployment; added `[[hardman-ai-faster-slower]]` to Related pages; updated Sources
- `wiki/ai-sycophancy.md` — Added "The Anthropomorphism Effect: A Compounding Mechanism" section: Kropp et al. (2026) — "AI buddy/mentor" framing makes reviewers measurably sloppier; distinct from sycophancy but compounds it; maximum reduction in epistemic monitoring when both operate; educational framing implications; added `[[hardman-ai-faster-slower]]` and `[[building-ai-companions]]` to Related pages; updated Sources and Last updated
- `wiki/index.md` — Added source summary row; added three new Key Themes (productivity funnel, "enter high in chain," anthropomorphism compounding sycophancy)

**Total pages created**: 1 | **Total pages updated**: 4

---

## 2026-06-10 — Ingestion (1 source)

**Sources ingested**:
1. `raw/blog/AI, jobs, and the next generation.md` — Brad Smith (President, Microsoft), Microsoft On the Issues blog, June 10, 2026. First tech-industry-insider voice in the wiki. Written in response to 2026 college graduates booing AI at commencement ceremonies and the Princeton beer jacket controversy. Cites Microsoft AI Diffusion Report (Q1 2026) and Roslansky/Ramen *Open to Work* (LinkedIn, 2026).

**Pages created**:
- `wiki/brad-smith-ai-jobs-next-generation.md` — Source summary; 2026 student commencement backlash (booing AI, Princeton "100% human" jacket); Microsoft diffusion data (17.8% global, 31.3% US); Narayanan/Kapoor (Knight Columbia) diffusion-is-institutional-change argument; "perfect storm" headwinds (AI automation + capex-driven headcount cuts + COVID overhang + geopolitics); task-bucket framework (Roslansky/Ramen, *Open to Work*): AI alone / you+AI / humans only; Five Cs (curiosity, creativity, compassion, communications, courage); dignity of work as first-order value; corporate data sovereignty; Jevons Paradox from 50-year Microsoft experience; relationship table mapping to existing wiki claims

**Pages updated**:
- `wiki/transferable-skills.md` — Added "The Five Cs: A Convergent Industry Framework" section; added "The Task-Bucket Framework: Personal Operationalization" section; added "The Dignity of Work: A First-Order Value" section; added `[[brad-smith-ai-jobs-next-generation]]` to Related pages; updated Sources and Last updated
- `wiki/labor-market-polarization.md` — Added "The Pace of AI Diffusion: Constrained by Humans, Not Technology" section (Narayanan/Kapoor; 17.8%/31.3% adoption data); added "The 'Perfect Storm'" section (multi-causal headwinds for 2026 graduates); added `[[brad-smith-ai-jobs-next-generation]]` to Related pages; updated Sources
- `wiki/sinead-bovell-job-market.md` — Added "The Task-Bucket Framework: A Complementary Operationalization" section; added `[[brad-smith-ai-jobs-next-generation]]` to Related pages; updated Sources and Last updated
- `wiki/nyt-teens-trade-classes.md` — Added "The Commencement Backlash: A Parallel 2026 Signal" section; added `[[brad-smith-ai-jobs-next-generation]]` to Related pages; updated Last updated
- `wiki/ai-privacy-and-institutional-adoption.md` — Added "Corporate Data Sovereignty: A Competitive Dimension" section; added `[[brad-smith-ai-jobs-next-generation]]` to Related pages; updated Sources
- `wiki/index.md` — Added source summary row; added four new Key Themes

**Total pages created**: 1 | **Total pages updated**: 6

---

## 2026-06-10 — Ingestion (1 source)

**Sources ingested**:
1. `raw/blog/The _Cognitive Offloading_ Paradox.md` — Dr. Philippa Hardman, Substack, April 15, 2026. Third Hardman source in the wiki. Synthesizes Wang & Zhang (2026) — 912 students across China/Europe/US — revealing a U-shaped relationship between AI cognitive offloading and transformative learning. Directly contextualizes the cognitive debt literature.

**Pages created**:
- `wiki/hardman-cognitive-offloading-paradox.md` — Source summary; Gerlich/Kosmyna/Favero/Lodge & Loble prior evidence; Wang & Zhang (2026) study design; three-zone U-curve (Zone 1 no AI / Zone 2 scattered = worst / Zone 3 committed delegation = best); the offloading paradox (partnership orientation activates both vigilance β=0.335 and offloading β=0.351, both independently predict transformative learning); six design principles (offload substantially or not at all; learner first; AI flags errors not fixes; verification in workflow; assess without scaffolding; frame as intellectual partner); Xu et al. (2026) performance-capability gap (g=0.751 vs 0.369 across 35 studies); cognitive partnership vs. social anthropomorphism distinction; relationship table mapping to existing wiki claims

**Pages updated**:
- `wiki/cognitive-debt.md` — Added "The Offloading Paradox: Locating Cognitive Debt on the U-Curve" section: Zone 2 is where cognitive debt accumulates; Zone 3 is the design condition that prevents it; added `[[hardman-cognitive-offloading-paradox]]` to Related pages; updated Sources and Last updated
- `wiki/agentivism.md` — Added "Empirical Validation: The Offloading Paradox Maps to Agentivism's Zones" section: three-zone/four-mechanism mapping table; Zone 3 = all four mechanisms operating; added `[[hardman-cognitive-offloading-paradox]]` to Related pages; updated Sources
- `wiki/evidence-base-ai-k12.md` — Added "The Zone 2/3 Distinction: Why 'AI Harms Learning' Was Incomplete" section; Xu et al. performance-capability gap; added `[[hardman-cognitive-offloading-paradox]]` to Related pages; updated Sources
- `wiki/building-ai-companions.md` — Added "The Offloading Paradox: Empirical Support for Zone 3 Design" section; cognitive partnership vs. social anthropomorphism distinction; added `[[hardman-cognitive-offloading-paradox]]` to Related pages; updated Sources
- `wiki/hardman-ai-faster-slower.md` — Added `[[hardman-cognitive-offloading-paradox]]` to Related pages
- `wiki/index.md` — Added source summary row; added two new Key Themes

**Total pages created**: 1 | **Total pages updated**: 6

---

## 2026-06-14 — Ingestion (2 sources)

**Sources ingested**:
1. `raw/PDF/AIEI_RN01_Jun26.pdf` — Stanford Digital Economy Lab (Erik Brynjolfsson, Director) + ADP Research; Research Note #1, June 2026. Three-component initiative: Canaries Dashboard (25K firms, 4.6M workers, 730+ occupations via ADP payroll), Takeoff Tracker (12 macroeconomic indicators), Adoption Monitor (individual and firm-level AI adoption). Key finding: automation-type AI usage predicts early-career employment decline; augmentation-type usage does not. This is the most current and largest-sample corroboration of the early-career hiring slowdown, with a mechanism-level insight the existing debate was missing.
2. `raw/misc/Mark Zuckerberg Says America Needs 'Hundreds Of Thousands' Of Skilled Tradespeople As Meta Launches Workforce Academy To Provide 'Free Training'.md` — Benzinga/Yahoo Finance, June 11, 2026. Meta's $115M "America's Workforce Academy" for free data center construction training with NCCER credentials. Launch locations: Louisiana, Ohio, Indiana, Texas. Level-Up predecessor: 35,000 applications in first week. Meta Texas: 1,800 peak construction → ~100 permanent roles. Zuckerberg: "hundreds of thousands of skilled tradespeople." Meta cut 8,000 employees (10%) while committing $600B in US infrastructure.

**Pages created**:

*Source summaries*:
- `wiki/stanford-del-ai-economic-indicators.md` — Canaries Dashboard design and findings (25K firms, 4.6M workers; −3.8%/yr vs. +2.0%/yr early-career divergence since ChatGPT; automation ratio predicts decline, augmentation ratio does not; home health aides growing, software developers declining); Takeoff Tracker (7 neutral, 3 mild, 2 strong — TFP neutral, capital share strong, no decisive takeoff); Adoption Monitor (workplace adoption reversals; text generation plateauing; robotics/AV largest expected-vs-current gap); research debate context (Lambert/Schindler, Budget Lab, Johnston/Makridis); relationship table
- `wiki/meta-workforce-academy.md` — America's Workforce Academy design ($115M, free, NCCER + transferable certificate, Louisiana/Ohio/Indiana/Texas); Zuckerberg quote; Level-Up 35,000 applications in week one; Meta Texas 1,800→100 construction/permanent split; simultaneous layoffs and infrastructure investment as "perfect storm" mechanism at named company; source caveat on Benzinga advertising content; relationship table

**Pages updated**:
- `wiki/anthropic-labor-market-index.md` — Added "The Canaries Dashboard: Corroboration and a Mechanism-Level Extension" section: ADP live data corroborates 14% finding; automation/augmentation decomposition offers handle that WFH confound critique does not address; added `[[stanford-del-ai-economic-indicators]]` to Related pages; updated Sources and Last updated
- `wiki/labor-market-polarization.md` — Added "The Canaries Dashboard: Live Employment Data Through April 2026" section: quantified divergence (−3.8%/yr vs. +2.0%/yr); automation/augmentation finding; named occupation examples; Takeoff Tracker TFP neutral; WFH confound implication; added `[[stanford-del-ai-economic-indicators]]` and `[[meta-workforce-academy]]` to Related pages; updated Sources and Last updated
- `wiki/broken-ladder.md` — Added "The Canaries Dashboard: A Subsequent Corroboration (June 2026)" section: live 2026 corroboration; automation/augmentation decomposition as mechanism handle WFH confound critique does not directly address; debate not closed; added `[[stanford-del-ai-economic-indicators]]` to Related pages; updated Sources and Last updated
- `wiki/cte-and-ai.md` — Added "The Meta Workforce Academy: Industry Validation at Scale" section (Zuckerberg quote; $115M; NCCER credentials; 35,000 Level-Up applications; 1,800→100 split; perfect storm juxtaposition); added "Canaries Dashboard: Home Health Aides Are Empirically Growing" section (live ADP data showing home health aide employment increases for youngest workers; −3.8%/yr vs. +2.0%/yr divergence); added `[[meta-workforce-academy]]` and `[[stanford-del-ai-economic-indicators]]` to Related pages; updated Sources and Last updated
- `wiki/nber-data-centers-local-economies.md` — Added "The Meta Texas Case: A Named 2026 Example" section: 1,800→100 ratio as named-project corroboration of NBER's construction-front-loading finding; Zuckerberg "hundreds of thousands" quote; combined NBER+Meta as full picture of AI infrastructure → CTE demand chain; added `[[meta-workforce-academy]]` to Related pages; updated Sources and Last updated
- `wiki/nyt-teens-trade-classes.md` — Added "Corporate Validation: Zuckerberg Confirms the Demand" section: CEO-level confirmation of the demand Bay Area students were betting on; $115M Academy; 35,000 Level-Up applications; student risk arbitrage and executive demand forecasts converging; added `[[meta-workforce-academy]]` to Related pages; updated Sources and Last updated
- `wiki/index.md` — Added 2 new source summary rows (source summaries table and Labor Market Analysis concept section); added 3 new Key Themes (automation vs. augmentation; no macro takeoff but early-career signal real; Big Tech investing in CTE trades training)

**Total pages created**: 2 | **Total pages updated**: 7

---

## 2026-06-18 — Ingestion (1 source)

**Sources ingested**:
1. `raw/misc/Employers step in to fill the AI education gap.md` — Isabel Berwick, FT "Working It" newsletter, June 3, 2026. Reports on SXSW London conversations with IBM global chief impact officer Justina Nixon-Saintil, Mission 44 CEO Jason Arthur, and career consultant Sally Marnan. Central theme: employers beginning to fill the AI skills gap that school curricula cannot keep pace with. Key signals: IBM's "beyond prompt engineering" quality standard; 30M commitment / 22M reached; AI certificates as hygiene factor not differentiator; London AI Campus (Google + Camden Council); employer-led training still in infancy. UK Milburn Review interim report named as government confirmation of entry-level labour market pressure from AI.

**Pages created**:
- `wiki/berwick-employers-ai-education-gap.md` — Source summary; Milburn Review as UK government confirmation of entry-level AI pressure; IBM SkillsBuild model (30M/22M, 1,000 courses, 20 languages, "beyond prompt engineering" quality standard); Mission 44/F1 as STEM engagement vehicle; AI certificate = hygiene factor, not differentiator (Sally Marnan); London AI Campus (Google + Camden Council) as bricks-and-mortar model; employer-led training explicitly in its infancy; equity risk of corporate-led AI literacy infrastructure; relationship table

**Pages updated**:
- `wiki/transferable-skills.md` — Added "AI Certificates as a Hiring Signal: The Hygiene Factor Finding" section: Sally Marnan's finding that AI certs don't move the needle on trust/rapport/making interviewers feel seen; as AI literacy commoditizes, differentiator shifts to human relational qualities; added `[[berwick-employers-ai-education-gap]]` to Related pages; updated Sources and Last updated
- `wiki/stanford-ai-index-education-2026.md` — Added "The Employer Response: Early-Stage Ecosystem" section: IBM/Google/Anthropic as early movers; London AI Campus model; infancy framing; equity risk of corporate-led provision; added `[[berwick-employers-ai-education-gap]]` to Related pages; updated Sources and Last updated
- `wiki/ai-in-k12-education.md` — Added "Employer-Led AI Training: An Emerging but Immature Response" section: IBM/Google early movers; Mission 44 addressing siloed teaching; IBM "beyond prompt engineering" standard; equity implication of selective access (London AI Campus is curated cohort, not universal); added `[[berwick-employers-ai-education-gap]]` to Related pages; updated Sources and Last updated
- `wiki/cte-and-ai.md` — Added "The 'Beyond Prompt Engineering' Employer Standard" section: IBM quality benchmark; 30M/22M commitment; maps to ai-mastery-continuum upper levels; Sally Marnan hygiene factor finding; added `[[berwick-employers-ai-education-gap]]` to Related pages; updated Sources and Last updated
- `wiki/labor-market-polarization.md` — Added Milburn Review (UK government) to "The 'Perfect Storm'" section as government-sourced confirmation of entry-level AI pressure; added `[[berwick-employers-ai-education-gap]]` to Related pages; updated Sources and Last updated
- `wiki/index.md` — Added source summary row; added 2 new Key Themes (prompt engineering as floor; employer-led training in infancy with equity risk)

**Total pages created**: 1 | **Total pages updated**: 6

---

## 2026-06-22 — Ingestion (1 source)

**Sources ingested**:
1. `raw/blog/Microsoft's AI Education Lead Says Job Fear Is Real. Here's The Fix.md` — Dan Fitzpatrick, aieducator.tools, June 22, 2026. Profile interview with Justin Spelhaug, President of Microsoft Elevate — the company's ~$4B, five-year program to credential ~20 million people for the AI economy. Spelhaug validates student AI anxiety (Gallup/Lumina: 47% considered changing majors, 16% already did); names the durable skill as "navigate yourself" (metacognition, not tool-specific competency); cites Microsoft/Digital Promise misplaced confidence research (500 undergrads; confidence climbed, knowledge didn't); takes teacher-first stance citing One Laptop Per Child failure; 2M teachers credentialed by Elevate for Educators in past year; IP/human agency equity argument.

**Pages created**:

*Source summaries*:
- `wiki/spelhaug-microsoft-elevate.md` — Source summary; Gallup/Lumina 47%/16% major-change data; low-hire/low-fire framing; LinkedIn 70% skills change by 2030; "navigate yourself" as the durable skill; metacognitive capabilities that AI won't automate; misplaced confidence trap (Microsoft/Digital Promise ~500 undergrads + CHI 2025 study: more AI trust → less critical thinking); teacher-first principle ("starts with a teacher"); One Laptop Per Child warning; 2M teachers credentialed via Elevate for Educators; IP/human agency equity argument; tensions with Brad Smith's more multi-causal "perfect storm" diagnosis; source and speaker caveats

**Pages updated**:
- `wiki/cognitive-debt.md` — Added "Corporate Research Corroboration: Microsoft's Misplaced Confidence Finding" section: Digital Promise study (~500 undergrads, confidence up, knowledge didn't); CHI 2025 Microsoft Research study (more AI trust = less critical thinking); significance as large-scale corporate corroboration; connection to Zone 3 design (Spelhaug's fix = structured delegation, not passive answering); added `[[spelhaug-microsoft-elevate]]` to Related pages; updated Sources and Last updated
- `wiki/transferable-skills.md` — Added "'Navigate Yourself': The Industry Formulation of Metacognition as the Durable Skill" section: Spelhaug's compressed formulation; writer-to-editor, player-to-coach analogies; metacognitive capabilities AI won't automate; adaptive capacity as structural argument for why transferable skills command growing economic value; honest caveat that this is a wager; added `[[spelhaug-microsoft-elevate]]` to Related pages; updated Sources and Last updated
- `wiki/ai-in-k12-education.md` — Added "Microsoft Elevate: The Largest Employer-Led AI Education Program in the Wiki" section: $4B program; 2M teachers credentialed; 14% of Spain's teachers; "starts with a teacher" governing principle; One Laptop Per Child warning; strongest outcomes when "an agent and a teacher work together"; convergence with evidence-base-ai-k12 systematic review findings on educator-facing AI; added `[[spelhaug-microsoft-elevate]]` to Related pages; updated Sources and Last updated
- `wiki/broken-ladder.md` — Added "Student Behavioral Response: Gallup/Lumina 2026" section: 47% of 3,801 US students considered changing majors; 16% already had; behavioral response to observable career environment regardless of contested causal attribution; connection to NYT teens trade-pivot data; added `[[spelhaug-microsoft-elevate]]` to Related pages; updated Sources and Last updated
- `wiki/index.md` — Added source summary row; added 3 new Key Themes (navigate yourself; misplaced confidence; students changing majors at scale)

**Total pages created**: 1 | **Total pages updated**: 5

---

## 2026-07-02 — Ingestion (4 sources)

**Sources ingested**:
1. `raw/PDF/Fostering-AI-Ready-Building-and-Moving-CTE-Pipelines.pdf` — Sublett, Mason, Rimbach-Jones, Beltran, & Fresard, ERO/Advance CTE/ACTE, March 2025. Building & Moving cluster grouping (Advanced Manufacturing, Construction, Supply Chain & Transportation); 38.9M workers, 26% of US workforce; interview spotlights Nick Goodnight (Ivy Tech), Paul Thurber (Everguard.ai), Tim Sisson (Trane); "toolbelt generation" (Chen 2024, WSJ); least AI-exposed of the four groupings studied.
2. `raw/PDF/Fostering-AI-Ready-Cultivating-Resources-CTE-Pipelines.pdf` — Sublett, Rimbach-Jones, Mason, Beltran, & Fresard, ERO/Advance CTE/ACTE, April 2025. Agriculture and Energy & Natural Resources cluster grouping; interview spotlights Dr. Kevin Wade (McGill, dairy AI), Daniel Goldsmith (Julius Education, green-jobs SOC-code critique), Dr. Ben Hertz-Shargel (Wood Mackenzie, grid AI upskilling); John Deere See & Spray, Cainthus, PAWS/SMART anti-poaching AI; near-national-average AI exposure.
3. `raw/PDF/Fostering-AI-Ready-Caring-for-Communities-CTE-Pipelines.pdf` — Rimbach-Jones, Sublett, Mason, & Fresard, ERO/Advance CTE/ACTE, June 2025. Education, Healthcare & Human Services, Public Service & Safety cluster grouping; interview spotlights Superintendent Michael Matsuda, Dr. Edward Watson (AAC&U), Dr. Jose Bowen (AAC&U, nursing-notes pedagogy), Commander Charlie Epperson (US Coast Guard); Khan Academy's Kristen DiCerbo "human high five" quote; Duke TRINA robot, Rothman Index, ShotSpotter, Corti; the highest-AI-exposure grouping of the four studied.
4. `raw/PDF/Fostering-AI-Ready-Creating-and-Experiencing-CTE-Pipelines.pdf` — Rimbach-Jones, Sublett, Mason, Beltran, & Fresard, ERO/Advance CTE/ACTE, August 2025. Hospitality/Events/Tourism and Arts/Entertainment/Design cluster grouping; interview spotlights Daniel Doppler (QuickText), Robert Morton (Australian Cinematographers Society AI Committee), and Jesse Anglen (Rapid Innovations CEO) — a dissenting voice predicting ~100% knowledge-worker displacement within 5 years; gendered tourism-workforce exposure (54% women); 5-second AI video = 1 hour of microwave energy.

All four reports share identical methodology (AIOE — Felten et al. 2021 — and Task Routinization Index — Acemoglu & Autor 2011) and four-audience recommendation structure (CTE Providers, Industry Partners, Policymakers, Conclusion), enabling direct cross-cluster-grouping comparison. Treated as four separate numbered source ingests per the wiki's established one-source-per-ingest convention.

**Pages created**:

*Concept page*:
- `wiki/ai-occupational-exposure-index.md` — Shared AIOE/Task Routinization Index methodology across all four reports; five cross-report findings (cognitive > physical exposure; education-level gradient; integration ≠ displacement; substitution vs. complementarity; technical vs. transferable skill exposure); cross-cluster-grouping comparison table; limitations

*Source summaries*:
- `wiki/fostering-ai-ready-building-moving.md` — Building & Moving source summary; full AIOE figures for Advanced Manufacturing/Construction/Supply Chain & Transportation; three interview spotlights; "toolbelt generation" term; least-exposed grouping finding
- `wiki/fostering-ai-ready-cultivating-resources.md` — Cultivating Resources source summary; Agriculture and Energy & Natural Resources AIOE figures; three interview spotlights; SOC-code green-jobs classification limitation
- `wiki/fostering-ai-ready-caring-communities.md` — Caring for Communities source summary; Education/Healthcare & Human Services/Public Service & Safety AIOE figures; four interview spotlights; highest-exposure-grouping finding; explicit critique of proposed federal CTE funding cuts
- `wiki/fostering-ai-ready-creating-experiencing.md` — Creating & Experiencing source summary; Hospitality/Events/Tourism and Arts/Entertainment/Design AIOE figures; three interview spotlights including full Jesse Anglen dissenting-voice quote with explicit contradiction framing against the wiki's dominant labor-market narrative; gendered tourism exposure

**Pages updated**:
- `wiki/cte-and-ai.md` — Replaced placeholder "AI Exposure by CTE Cluster" section with real occupation-level data from all four reports (per-grouping exposure ranking, key AIOE figures, education-gradient finding); added "The Fostering AI-Ready CTE Pipelines Series: Occupation-Level Confirmation" section (toolbelt generation cross-reference, nursing-notes pedagogical shift) with "A dissenting view: Jesse Anglen and the contradiction" subsection; added 5 new Related pages; updated Sources and Last updated
- `wiki/relational-economy.md` — Added "A Contested Case Within the Relational Sector: Hospitality's Gendered Exposure" section: hospitality's below-average AIOE score supports the thesis while task-level automation vulnerability and the 54%-women statistic complicate it; added `[[ai-occupational-exposure-index]]` and `[[fostering-ai-ready-creating-experiencing]]` to Related pages; updated Sources and Last updated
- `wiki/labor-market-polarization.md` — Added "Occupation-Level Confirmation: The Fostering AI-Ready CTE Pipelines Series" section: education-credential gradient reproduces inside every cluster grouping regardless of average exposure; Jesse Anglen dissent flagged against the page's core thesis; added 5 new Related pages; updated Sources and Last updated
- `wiki/transferable-skills.md` — Added "Evaluation as the New Production Skill: The Nursing Notes Example" section: Dr. Jose Bowen's good/bad/ugly AI-note pedagogy as a concrete instance of the evaluation-over-production shift, cross-referenced to build/analyze/defend and enter-high-in-the-chain; added `[[ai-occupational-exposure-index]]` and `[[fostering-ai-ready-caring-communities]]` to Related pages; updated Sources and Last updated
- `wiki/index.md` — Added 4 new source summary rows and 1 new concept page row (CTE and Workforce section); added 4 new Key Themes (occupation-level exposure grounding; Jesse Anglen dissent; relational economy stress test; cross-cluster education gradient)

**Total pages created**: 5 | **Total pages updated**: 5

---

## 2026-07-02 — Ingestion (3 sources)

**Sources ingested**:
1. `raw/misc/A.I. Is Reshaping the Economy. Good Luck Measuring How.md` — Ben Casselman, *The New York Times*, July 2, 2026. Meta-level survey of why economists cannot agree on AI's current labor-market effect: conflicting exposure-measure methodologies, outdated federal occupational data (May 2025), and diverging private data sources (Stanford DEL/ADP showing entry-level declines vs. Ramp/Revelio showing heavy AI adopters hiring faster).
2. `raw/misc/Companies Are Throttling Employees' AI Use Because It's Too Expensive.md` — Joseph Cox, *404 Media*, July 2, 2026. Leaked internal communications from Atlassian, Adobe, Amazon, Citi, GitHub, and Accenture documenting enterprise AI-cost throttling: Atlassian AI spend $5M→$15M/month in nine months; Citi disabling Opus 4.6/4.7 and GPT-5.5 access; triggered by GitHub Copilot's June 2026 shift to usage-based billing.
3. `raw/PDF/CEMS AI Report_ Augmented leadership_2026.pdf` — CEMS – The Global Alliance in Management Education (33 business schools, 70+ corporate partners), 2026. Ten workplace takeaways and thirty role-specific insights from seven interviews (ABB, Beko, tesa, American University in Cairo, University of Sydney, Université Catholique de Louvain, Black Door Technology) on AI-age leadership and business education.

A fourth candidate file, `raw/misc/Dept of Labor AI Literacy Framework.md`, was re-checked and confirmed still unextractable (image-only content) — previously logged as skipped on 2026-05-18; not re-ingested.

**Pages created**:

*Source summaries*:
- `wiki/ai-economy-measurement-2026.md` — Casselman/NYT source summary; explains the measurement crisis underlying the wiki's own conflicting exposure-index and labor-data sources; J-curve explanation; federal statistical capacity shrinking; bipartisan Senate data-collection bill
- `wiki/ai-token-costs-throttling.md` — Cox/404 Media source summary; enterprise AI cost-rationing as a new adoption-curve friction not previously represented in the wiki; Accenture irony; implications for small-language-model/cost-tiering literacy
- `wiki/cems-augmented-leadership.md` — CEMS source summary; ten key takeaways; expertise-gap mechanism (Delacour/ABB) as employer-side complement to hiring-decline evidence; cognitive-offloading and metacognition findings as independent adult/corporate-population corroboration of the Abdelghani et al. illusion-of-understanding study; three-institution convergence on oral/process-based assessment design (Léonard, Riemer, plus existing wiki sources); "copilot not autopilot" framing; four skills buckets (Bahrami)

**Pages updated**:
- `wiki/ai-economics-scan-2026.md` — Added `[[ai-economy-measurement-2026]]` and `[[ai-token-costs-throttling]]` to Related pages
- `wiki/illusion-of-understanding.md` — Added `[[cems-augmented-leadership]]` to Related pages
- `wiki/agentivism.md` — Added `[[cems-augmented-leadership]]` to Related pages
- `wiki/co-intelligence.md` — Added `[[cems-augmented-leadership]]` to Related pages
- `wiki/index.md` — Added 3 new source summary rows; added 4 new Key Themes (measurement uncertainty tempering the wiki's own exposure data; enterprise AI cost-rationing as a new adoption friction; CEMS's business-education corroboration of K-12 cognitive-offloading findings; the expertise-gap employer-side mechanism)

**Total pages created**: 3 | **Total pages updated**: 5

---

## 2026-07-07 — Lint audit

**Findings**:
1. **Broken/malformed wiki-links** (fixed): four links used spaces and/or capitalization that didn't match actual filenames, so they rendered as plain text instead of navigable links:
   - `wiki/ai-privacy-and-institutional-adoption.md:20` — `[[Small language models]]` → `[[small-language-models|Small language models]]`
   - `wiki/small-language-models-k12.md:21` — `[[Small language models]]` → `[[small-language-models|Small language models]]`
   - `wiki/small-models-big-support.md:13` — `[[small language models]]` → `[[small-language-models|small language models]]`
   - `wiki/khanmigo.md:63` — `[[learning-performance paradox]]` → `[[building-ai-companions|learning-performance paradox]]` (term is defined on that page, not a standalone page)
2. **No orphan pages** — every content page has at least one inbound link.
3. **No page-format violations** — all 58 content pages have Title/Summary/Sources/Last updated/Related pages. (Initial automated check flagged all older pages for "missing Title" — false positive caused by a UTF-8 BOM preceding the `#` on those files; this is the same cosmetic BOM inconsistency already flagged and deliberately left unfixed in the 2026-05-13 lint audit.)
4. **No new contradictions detected** between pages.
5. **Stale concept gaps carried forward** (unaddressed, awaiting either a dedicated source or explicit go-ahead): standalone **Metacognition** concept page (referenced in 15+ pages); standalone **Agentic AI** concept page.
6. **README source/page counts verified accurate** (41 sources, 58 pages) against actual file count.

**Pages updated**: `ai-privacy-and-institutional-adoption.md`, `small-language-models-k12.md`, `small-models-big-support.md`, `khanmigo.md`

**Total pages created**: 0 | **Total pages updated**: 4

---

## 2026-07-07 — Ingestion (1 source)

**Sources ingested**:
1. `raw/blog/The secret to human 'brilliance' that AI just can't match.md` — Stanford Graduate School of Business news article (news.stanford.edu), June 25, 2026, summarizing Douglas Guilbeault, Spencer Caplan & Charles Yang's *PNAS* research. Satisficing (Herbert Simon) and the Tolerance Principle (originally from language-acquisition linguistics) shown, via two controlled experimental games (Name Game, Mind Reading Game; 24–96 participants), to govern how adults learn social conventions from minimal data via intuitive leaps — structurally distinct from LLM data-maximalist prediction.

**Pages created**:

*Source summary*:
- `wiki/human-brilliance-satisficing.md` — Guilbeault/Stanford GSB source summary; satisficing and Tolerance Principle defined; Name Game and Mind Reading Game experimental results (20–30 rounds to consensus regardless of group size; 25% dissent threshold to overturn consensus); contrast with LLM data-maximalism; explicit caveat that this is a single source with small controlled-game evidence, not yet cross-validated in K-12/CTE settings

*Concept page*:
- `wiki/satisficing-and-tolerance-principle.md` — New concept page defining satisficing and the Tolerance Principle as a pair; why this reframes the "AI has more data, therefore better judgment" assumption; relationship to transferable-skills, agentivism, and relational-economy; limitations section flagging the connections as the wiki's own inference, not claims made by the source research

**Pages updated**:
- `wiki/transferable-skills.md` — Added "A Cognitive-Science Mechanism: Satisficing" section: judgment-under-uncertainty reframed as a specific, identifiable cognitive process rather than vague soft-skill language; added source to Sources; added `[[satisficing-and-tolerance-principle]]` and `[[human-brilliance-satisficing]]` to Related pages; updated Last updated
- `wiki/agentivism.md` — Added paragraph under Reconstructive Internalization (Mechanism 3): satisficing as a possible cognitive account of why reworking AI output into one's own understanding (vs. passively accepting it) produces durable learning; added source to Sources; added `[[satisficing-and-tolerance-principle]]` and `[[human-brilliance-satisficing]]` to Related pages; updated Last updated
- `wiki/index.md` — Added source summary row; added concept page row (Frameworks and Models section); added new Key Theme on human judgment as a categorically different cognitive strategy from LLM prediction

**Total pages created**: 2 | **Total pages updated**: 3
