# Entry-Level Labor Market Disruption

**Summary**: Synthesis page for the wiki's densest evidence thread: the decline in early-career hiring and job quality in AI-exposed fields since late 2022. It brings together eight labor-market sources, sets out what is settled and what is contested (especially the AI-versus-work-from-home attribution debate), and draws out the implications for CTE.

**Sources**: `raw/misc/Labor market impacts of AI A new measure and early evidence.md`, `raw/PDF/ai-will-reshape-more-jobs-than-it-replaces.pdf`, `raw/PDF/The Broken Ladder.pdf`, `raw/PDF/AIEI_RN01_Jun26.pdf`, `raw/PDF/CanariesintheCoalMine_Nov25.pdf`, `raw/PDF/Canaries_August2026.pdf`, `raw/misc/Goldman studied where AI is squeezing labor markets. Here's what it found.md`, `raw/misc/The College Degrees Considered Safest From AI Disruption.md`, `raw/PDF/Gradiating into Disruption.pdf`, `raw/PDF/No+Country+for+Young+Grads+V_Final7.29.25+(1).pdf`, `raw/misc/A.I. Is Reshaping the Economy. Good Luck Measuring How.md`, `raw/blog/AI, jobs, and the next generation.md`, `raw/blog/Microsoft's AI Education Lead Says Job Fear Is Real. Here's The Fix.md`, `raw/video/New Book Podcast_ AI Unplugged_ The Hype and Hope in Education Futures.md`

**Last updated**: 2026-09-23

---

## The core pattern

Since late 2022, workers at the start of their careers in AI-exposed fields have found it harder to get in, while experienced workers in the same fields, and young workers in less-exposed fields, have held steady or grown. Every labor-market source in the wiki that looks at early-career workers finds some version of this. The disagreements are about **how big** it is, **what causes it**, and **whether it lasts**.

---

## The evidence, source by source

| Source | Data | Headline finding |
|---|---|---|
| [[no-country-young-grads-burning-glass]] (Jul 2025) | BLS, Lightcast postings | 20–24-year-old grad unemployment 5.2% → 6.2%; degree's unemployment advantage at a 30-year low; 52% of the Class of 2023 underemployed (source: No+Country+for+Young+Grads+V_Final7.29.25+(1).pdf) |
| [[anthropic-labor-market-index]] (2026) | CPS + Claude usage | No detectable unemployment effect; 14% drop in job-finding rate for 22–25-year-olds into exposed occupations, "just barely" significant (source: Labor market impacts of AI A new measure and early evidence.md) |
| [[bcg-ai-reshapes-jobs]] (2026) | 165M US jobs, 1,500 roles | "Divergent" roles (12% of jobs): AI automates entry-level tasks first; senior roles persist, junior roles contract (source: ai-will-reshape-more-jobs-than-it-replaces.pdf) |
| [[broken-ladder]] (May 2026) | Revelio, 243M hires, 4 countries | Junior share of new hires 8–11 pp below 2019 baselines by 2025 in US/UK/Canada/Australia; attributes it mainly to work-from-home, not GenAI (source: The Broken Ladder.pdf) |
| [[stanford-del-ai-economic-indicators]] (Jun 2026) | ADP, 4.6M workers | Most-exposed early-career occupations contracting −3.8%/yr since ChatGPT vs. +2.0%/yr for least-exposed; automation usage predicts decline, augmentation does not (source: AIEI_RN01_Jun26.pdf) |
| [[canaries-coal-mine-brynjolfsson]] (Aug 2026 vintage) | ADP payroll, millions of workers | 19% "kept-pace" employment shortfall for 22–25-year-olds in the most-exposed occupations, still widening; works through reduced hiring, not layoffs (source: Canaries_August2026.pdf) |
| [[goldman-sachs-ai-labor-squeeze]] (Aug 2026) | 800+ occupations, multi-country | Entry-level workers bear 2–6x the AI-exposure hiring drag of the wider workforce, across developed economies (source: Goldman studied where AI is squeezing labor markets. Here's what it found.md) |
| [[safest-college-degrees-forbes]] (Aug 2026) | NY Fed | Recent-grad unemployment 5.6% vs. 4.2% overall, Q2 2026 (an all-ages comparison; see caution below) (source: The College Degrees Considered Safest From AI Disruption.md) |
| [[graduating-into-disruption-census]] (Sep 2026) | Census PSEO/LEHD, 6.7M graduates | Most-exposed decile of majors: −5 pp initial employment, about −13% initial earnings (recession-scale); half the earnings loss from sorting into retail and food service (source: Gradiating into Disruption.pdf) |

---

## What is settled

**1. The effect is concentrated at entry, not among incumbents.** Canaries finds the decline works through reduced hiring while separations fall (source: Canaries_August2026.pdf). Anthropic finds no unemployment effect but a hiring slowdown (source: Labor market impacts of AI A new measure and early evidence.md). The Census paper finds adjustment "importantly at labor market entry" (source: Gradiating into Disruption.pdf). The ladder isn't being pulled up under people already on it. Its bottom rung is narrowing.

**2. The aggregate economy looks fine, and that doesn't contradict the entry-level signal.** Overall ADP employment grew about 6% from November 2022 to June 2026 (source: Canaries_August2026.pdf), and white-collar sectors posted record revenues while employment stalled (source: No+Country+for+Young+Grads+V_Final7.29.25+(1).pdf). The Census paper shows why both can be true: exposed graduates stay attached to the labor market, but start later and in worse jobs. "Modest employment or unemployment effects can coexist with substantial deterioration" in job quality (source: Gradiating into Disruption.pdf).

**3. The effect is non-linear: concentrated at the very top of the exposure distribution.** Canaries and Stanford DEL find it in the top quintiles. The Census paper finds deciles 7–9 recover within about two years while decile 10 (mostly computer science and information systems) does not (source: Gradiating into Disruption.pdf). What predicts harm is the share of a field's jobs in the most-exposed occupations, not its average exposure.

**4. The pattern is international.** Broken Ladder finds it in four English-speaking economies (source: The Broken Ladder.pdf), and Goldman in six developed economies (source: Goldman studied where AI is squeezing labor markets. Here's what it found.md).

---

## What is contested

### Cause: AI, work-from-home, or several shocks at once?

This is the wiki's main open debate.

- **The WFH case.** Lambert & Schindler show GenAI exposure and WFH exposure are correlated at 0.77 across occupations. In joint-treatment models on Revelio data, the WFH coefficient is stable while GenAI attenuates to near zero (source: The Broken Ladder.pdf).
- **The AI case.** Three findings push back:
  - Canaries finds the decline holds in *non-teleworkable* occupations (source: CanariesintheCoalMine_Nov25.pdf).
  - Two direct replications of the Lambert & Schindler specification find the reverse: the AI effect survives and grows while WFH shrinks. One uses ADP data ([[canaries-coal-mine-brynjolfsson]]; source: Canaries_August2026.pdf); the other uses Census graduate data ([[graduating-into-disruption-census]]; source: Gradiating into Disruption.pdf).
  - The automation/augmentation split (only automation-type use predicts decline) is a mechanism the WFH account does not explain (source: AIEI_RN01_Jun26.pdf).
- **Multi-causal framings.** Burning Glass calls AI an "accelerant" of shifts already under way: post-pandemic lean staffing and employer risk aversion after the Great Resignation (source: No+Country+for+Young+Grads+V_Final7.29.25+(1).pdf). Brad Smith describes a "perfect storm" of AI task automation, headcount cuts to fund AI capital spending, over-hiring correction, and geopolitical uncertainty (source: AI, jobs, and the next generation.md). Monetary tightening explains at most about a quarter of the relative decline (source: Gradiating into Disruption.pdf).

**Current weight of evidence**: two independent replications now favor an AI-specific channel, but every source acknowledges that the two shocks are highly collinear. The Census authors concede that "our ability to isolate the effects of work-from-home and AI exposure is limited" (source: Gradiating into Disruption.pdf). This page does not treat the debate as closed. The diagnosis matters for the remedy: WFH friction could be fixed by better management practice, while task automation would not reverse on its own.

### Magnitude

Estimates vary by data source and method:
- 14% (Anthropic job-finding rate);
- 8–11 pp of junior hiring share (Broken Ladder);
- a 19% kept-pace shortfall (Canaries);
- 5 pp initial employment and 13% initial earnings (Census, top decile only).

The Canaries paper itself documents its estimate drifting from 13% to 19% across data vintages (source: Canaries_August2026.pdf). Private data sources also conflict: Ramp and Revelio data show heavy AI adopters hiring *faster* (source: A.I. Is Reshaping the Economy. Good Luck Measuring How.md). See [[ai-economy-measurement-2026]].

### Graduate oversupply

⚠ **Contradiction**: Burning Glass treats a growing "Graduate Glut" (7–11 million more college-educated adults by 2034) as a structural driver (source: No+Country+for+Young+Grads+V_Final7.29.25+(1).pdf). The Census paper finds that supply growth in the most-exposed majors was fully absorbed until ChatGPT, and that employment broke trend after supply growth had slowed (source: Gradiating into Disruption.pdf). The two differ in scope (all young graduates versus the most-exposed decile), so this is flagged, not resolved.

### Has the degree's advantage "inverted"?

No, not on age-matched data. The widely cited 5.6%-vs-4.2% comparison (source: The College Degrees Considered Safest From AI Disruption.md) sets young graduates against workers of all ages. Age-matched Burning Glass data show the degree's unemployment advantage **narrowed to a 30-year low, not reversed** (source: No+Country+for+Young+Grads+V_Final7.29.25+(1).pdf).

### Persistence

The Census paper finds most exposed graduates recover within two years, but the top decile still trails by 2 pp in employment and 3.3 log points in earnings (source: Gradiating into Disruption.pdf). Canaries finds the gap still *widening* through mid-2026 (source: Canaries_August2026.pdf). Post-ChatGPT data run for less than three years, so no source can yet say whether this is temporary scarring or a permanent change.

---

## Mechanisms proposed

1. **Direct task substitution.** AI performs the routine cognitive work juniors used to do: research, first drafts, basic analysis, routine communication (source: No+Country+for+Young+Grads+V_Final7.29.25+(1).pdf). Automation-type usage specifically predicts decline (source: AIEI_RN01_Jun26.pdf).
2. **Codified vs. tacit knowledge.** AI substitutes for "book-learning" knowledge, which juniors have, more readily than for experience-built judgment, which seniors have (source: Canaries_August2026.pdf). Related to [[satisficing-and-tolerance-principle]].
3. **Loss of the training function.** Entry-level work is how people build expertise. If AI automates it, firms train fewer juniors: Burning Glass's "Flipped Pyramid" and BCG's "Divergent" roles (sources: No+Country+for+Young+Grads+V_Final7.29.25+(1).pdf; ai-will-reshape-more-jobs-than-it-replaces.pdf). This threatens the future senior pipeline, not just current juniors (source: The Broken Ladder.pdf).
4. **Eroding educational signals.** AI-inflated grades and work samples make new graduates' skill harder to read, which could explain why effects appeared before widespread firm adoption (source: Gradiating into Disruption.pdf). This is the thread's direct link to the learning-side evidence ([[cognitive-debt]], [[agentivism]], [[building-ai-companions]]).
5. **WFH organizational friction.** Harder supervision and slower on-the-job learning under remote work (source: The Broken Ladder.pdf). Contested; see above.

---

## Behavioral responses already visible

- **Students are changing course.** 47% of surveyed US students have seriously considered changing majors because of AI, and 16% already have (source: Microsoft's AI Education Lead Says Job Fear Is Real. Here's The Fix.md). CS enrollment is falling ([[columbia-cs-ai-disruption]], [[stanford-ai-index-education-2026]]). Some high-school students are choosing trades as an AI hedge ([[nyt-teens-trade-classes]]). Young adults are the only age group whose AI concern is still rising ([[pew-young-adults-ai-anxiety]]).
- **Exposed graduates move into other activities.** Self-employment and graduate-school enrollment rose among top-decile graduates, likely reflecting weak demand more than new opportunity (source: Gradiating into Disruption.pdf).
- **Some employers are skipping the degree.** Deloitte and Shopify were reported to be hiring directly from high school (practitioner observation, not published research) (source: New Book Podcast_ AI Unplugged_ The Hype and Hope in Education Futures.md).

---

## Implications for CTE

1. **The protected zone is real but defined by the job's tasks, not by the credential.** Low-exposure fields (skilled trades, hands-on healthcare, personal services) sit at the bottom of both the AI and WFH exposure rankings (source: The Broken Ladder.pdf), and young health aides' employment is growing faster than older workers' (source: Canaries_August2026.pdf). But CTE IT and Digital Technology pathways feed directly into the most-exposed decile ([[graduating-into-disruption-census]]). Pathway-level exposure analysis ([[ai-occupational-exposure-index]]) matters more than a blanket "CTE is safe" claim.
2. **Replace the disappearing junior rung.** If firms train fewer juniors, work-based learning, apprenticeships, and employer-embedded programs ([[meta-workforce-academy]], [[berwick-employers-ai-education-gap]], [[quanthub-data-scholars-2026-update]]) become the place where early expertise is built.
3. **Hard-to-fake credentials gain value.** As grades lose signal value, industry certifications, performance assessments, and portfolios defended in person (see [[middle-path-ai-literacy-nurenberg]], [[ai-unplugged-murgatroyd]]) are the kinds of evidence employers can still trust.
4. **Teach AI as augmentation, not automation.** Only automation-type use predicts the decline in young workers' employment. Programs built on the [[applied-co-intelligence-model]] teach students to direct and check AI inside their occupation, the complementary use pattern that the evidence associates with stable or rising employment.
5. **Advise students honestly.** The college-for-all default has lost part of its labor-market guarantee in AI-exposed fields, but the degree's advantage has narrowed, not inverted. Career advising should present both facts.

---

## Related pages

- [[labor-market-polarization]]
- [[broken-ladder]]
- [[canaries-coal-mine-brynjolfsson]]
- [[stanford-del-ai-economic-indicators]]
- [[anthropic-labor-market-index]]
- [[bcg-ai-reshapes-jobs]]
- [[ai-labor-disruption-segments]]
- [[goldman-sachs-ai-labor-squeeze]]
- [[graduating-into-disruption-census]]
- [[no-country-young-grads-burning-glass]]
- [[safest-college-degrees-forbes]]
- [[ai-economy-measurement-2026]]
- [[brad-smith-ai-jobs-next-generation]]
- [[cte-and-ai]]
- [[transferable-skills]]
- [[relational-economy]]
- [[cognitive-debt]]
- [[nyt-teens-trade-classes]]
- [[pew-young-adults-ai-anxiety]]
- [[columbia-cs-ai-disruption]]
- [[ai-occupational-exposure-index]]
- [[applied-co-intelligence-model]]
