# Stanford DEL AI Economic Indicators (June 2026 Note and Monthly Updates)

**Summary**: Covers the series' June 2026 research note and its November 2026 monthly update (data through October 2026, below). Research Note #1 from Stanford Digital Economy Lab (Brynjolfsson et al., June 2026) — three components tracking AI's actual labor market and macroeconomic impact with live ADP data on 4.6 million workers across 730+ occupations. Key finding: automation-type AI usage predicts employment decline for early-career workers; augmentation-type usage does not.

**Sources**: `raw/PDF/AIEI_RN01_Jun26.pdf`, `raw/PDF/CanariesintheCoalMine_Nov25.pdf`, `raw/PDF/Canaries_August2026.pdf`, `raw/PDF/Gradiating into Disruption.pdf`, `raw/PDF/AIEI_MU_Nov26.pdf`

**Last updated**: 2026-11-19

---

## Overview

*AI Economic Indicators: June 2026 Update* is Research Note #1 from the Stanford Digital Economy Lab (DEL), directed by Erik Brynjolfsson and produced in partnership with ADP Research. The initiative tracks three components — Canaries Dashboard, Takeoff Tracker, and Adoption Monitor — as an ongoing empirical monitoring project designed to produce periodic updates rather than a single-point analysis.

Brynjolfsson's framing: "We are flying blind into one of the most consequential periods in world history." The initiative's goal is to replace speculation with ongoing measurement. (source: AIEI_RN01_Jun26.pdf)

---

## Component 1: The Canaries Dashboard

### Design

The Canaries Dashboard is the most novel and empirically powerful component. In partnership with ADP Research, Stanford DEL tracks employment outcomes for roughly **25,000 firms, 4.6 million workers, and 730+ occupations** — the largest longitudinal employment sample for this question in the wiki when this note was ingested (June 2026). Two later sources are larger: the Census graduate study's 6.7 million graduates linked to wage records ([[graduating-into-disruption-census]]) and the 41-country study's 154 million employment records ([[ai-labor-demand-41-countries]]). The "canaries" framing references the historical use of canaries in coal mines to detect invisible hazards: the goal is to identify which workers are showing early-stage employment effects before they appear in aggregate statistics.

The sample is a five-year balanced panel ending April 2026, using ADP payroll records — actual employment data, not surveys. (source: AIEI_RN01_Jun26.pdf)

**A fresher data vintage now exists**: [[canaries-coal-mine-brynjolfsson]]'s August 2026 update extends the underlying academic paper's ADP panel through June 2026 (two months past this dashboard's April cutoff) and revises the headline early-career figure from a 16% relative decline to a **19% "kept-pace" shortfall**, explicitly noting the gap has widened every month since first documented. That page should be treated as the current authoritative vintage of this research program's headline numbers.

### Finding 1: Aggregate Divergence Is Modest — But Early-Career Is Pronounced

Year-over-year employment changes as of April 2026:

| Age group | Most AI-exposed | Least AI-exposed |
|-----------|----------------|-----------------|
| All ages | −0.2% YoY | +0.1% YoY |
| Early-career (22–25) | **−4.2% YoY** | −1.7% YoY |
| Developing (31–34) | −1.7% YoY | — |
| Mid-career (35–40) | +2.0% YoY | — |

Annual growth rate since ChatGPT introduction (November 2022):
- Early-career, most exposed: **−3.8%/year**
- Early-career, least exposed: **+2.0%/year**

The aggregate (all-ages) divergence is modest. The early-career divergence is the key signal — and it has been compounding since November 2022. At −3.8%/year, the most AI-exposed early-career occupations have been contracting for over three years, while the least-exposed early-career occupations have continued to grow. (source: AIEI_RN01_Jun26.pdf)

### Finding 2: Automation Predicts Decline; Augmentation Does Not

The most significant new contribution of the Canaries Dashboard is decomposing AI usage at the occupation level using the **Anthropic Economic Index** (the same methodology introduced in [[anthropic-labor-market-index]]):

- **Automation ratio**: the share of AI usage within an occupation that is automation-type — AI delegating tasks away from workers, reducing human involvement
- **Augmentation ratio**: the share of AI usage that is augmentation-type — AI assisting workers who remain in the loop and exercise judgment

**The finding**: occupations with higher automation ratios show a clear negative correlation with early-career employment trends — more automation usage → worse employment outcomes. Occupations with higher augmentation ratios show **no clear relationship** with employment trends.

This is the mechanism-level insight the broader debate on AI and labor markets has been missing. It is not AI exposure per se that determines employment outcomes — it is *how* AI is used in an occupation. Automation displaces; augmentation does not. (source: AIEI_RN01_Jun26.pdf)

The automation/augmentation distinction is relevant to the WFH confound debate ([[broken-ladder]]): Lambert & Schindler use total AI exposure measures, which conflate automation and augmentation usage. The Canaries Dashboard's decomposition offers a mechanism handle that pure exposure rankings cannot provide — and one the WFH confound critique does not directly address.

### The Underlying Academic Paper

[[canaries-coal-mine-brynjolfsson]] (November 2025) is the peer-reviewed-style working paper this research note's "Canaries Dashboard" is built on — same lead author (Brynjolfsson), same ADP dataset, earlier and more methodologically detailed. It reports the automation/augmentation finding above as one of six documented facts, adds a firm-time fixed-effects regression showing a 15 log-point relative employment decline for 22-25 year-olds in the most AI-exposed occupations (robust to firm-level confounders), and — critically — reports that the pattern **survives restricting the sample to non-teleworkable occupations**, directly complicating the WFH-attribution argument in [[broken-ladder]]. See [[canaries-coal-mine-brynjolfsson]] for the full six-fact breakdown and the codified-vs-tacit-knowledge theoretical mechanism.

### Finding 3: Occupation-Level Examples

The Canaries Dashboard produces occupation-level readings directly relevant to CTE program planning:

**Declining (early-career, most AI-exposed)**:
- Software developers
- Customer service representatives

**Growing (least-exposed, especially for youngest workers)**:
- Home health aides

Home health aides — a core CTE pipeline in the Healthcare & Human Services cluster — are among the few occupations showing employment increases for the youngest age cohorts. This is the first time in this wiki that a specific CTE-aligned occupation appears as empirically growing in live 2026 ADP employment data. (source: AIEI_RN01_Jun26.pdf)

### The Research Debate Context

The Canaries Dashboard explicitly situates itself within the existing empirical debate:

- **Brynjolfsson/Chandar/Chen**: the early-career employment decline in AI-exposed occupations (original finding)
- **Lambert & Schindler ([[broken-ladder]], May 2026)**: WFH and GenAI exposure correlate at 0.77; in joint-treatment specifications, WFH is robust while GenAI attenuates to near-zero. *Later replications of that specification in ADP data ([[canaries-coal-mine-brynjolfsson]], Aug 2026) and Census data ([[graduating-into-disruption-census]], Sep 2026) reverse this result; the debate remains open.*
- **Budget Lab at Yale**: no aggregate employment effect from AI
- **Johnston & Makridis**: sector-level employment increases in some AI-adopting sectors

The initiative is designed to resolve this debate through ongoing monthly measurement. The Canaries Dashboard is the empirical substrate; the automation/augmentation decomposition is the methodological advance. (source: AIEI_RN01_Jun26.pdf)

---

## Component 2: The Takeoff Tracker

The Takeoff Tracker monitors 12 macroeconomic indicators for evidence of AI-driven economic transformation at the aggregate level. As of May 2026:

- **7 indicators**: neutral — no evidence of AI-driven break from recent trends
- **3 indicators**: mild evidence of AI-related change
- **2 indicators**: strong evidence of AI-related change

**Strong evidence**:
- **Capital share**: continuing upward trend — the clearest macroeconomic signal of AI impact, consistent with returns shifting from labor to capital
- **IP equipment investment share**: recovering and rising post-COVID dip

**Neutral — the most important finding**:
- **TFP (Total Factor Productivity) growth**: no break from recent levels. TFP is the most closely watched productivity indicator for AI economic impact. If AI were producing transformative aggregate productivity gains, they would show up here. As of May 2026, they have not.

**Overall verdict**: "We do not see decisive evidence of takeoff in these indicators."

The capital share signal is consistent with the pattern that would precede a labor market disruption — returns flowing to capital rather than labor. But the absence of TFP growth suggests the productivity transformation has not yet arrived at the macroeconomic level, even as occupation-level employment patterns show early-career divergence. This is consistent with Brad Smith's argument ([[brad-smith-ai-jobs-next-generation]]) that diffusion is constrained by institutional change rather than technology. (source: AIEI_RN01_Jun26.pdf)

---

## Component 3: The Adoption Monitor

**Individual adoption**: Self-reported AI adoption for work purposes is generally trending upward, but with some recent reversals in *workplace* AI adoption (as distinct from personal use). The gap between personal and professional AI adoption is a recurring pattern — workers may integrate AI into personal workflows before employers have redesigned professional processes around it.

**Firm-level adoption**: US firms lead global adoption. Firms expect to increase AI adoption over the next three years across most application categories. The exception: **text generation** — firms expect current text generation AI use to plateau or decline, suggesting saturation of the earliest and most widely adopted application category.

**Robotics and autonomous vehicles**: the largest gap between current and expected adoption — firms anticipate significant expansion in physical AI applications. This is relevant to [[cte-and-ai]] because physical AI deployment will require skilled technicians, maintenance workers, and operators in roles that CTE pipelines are well-positioned to fill. (source: AIEI_RN01_Jun26.pdf)

---

## Relationship to Existing Wiki Claims

| Wiki claim | This source's contribution |
|---|---|
| Early-career hiring slowdown (14%) ([[anthropic-labor-market-index]]) | Corroborated with live 2026 ADP data on 4.6M workers; quantified at −3.8%/yr for most AI-exposed occupations |
| WFH confound challenges AI attribution ([[broken-ladder]]) | Automation/augmentation decomposition provides mechanism-level handle that total exposure measures cannot |
| Home health aides are in the protected sector ([[cte-and-ai]]) | First live employment data showing actual 2026 growth for this occupation among youngest workers |
| No decisive AI economic takeoff yet ([[brad-smith-ai-jobs-next-generation]], [[labor-market-polarization]]) | TFP neutral in Takeoff Tracker; capital share rising; decisive productivity transformation not yet visible in aggregate data |
| AI diffusion constrained by institutional change ([[labor-market-polarization]]) | Adoption Monitor: workplace reversals; firms' text generation adoption plateauing; physical AI lags behind digital AI |

## November 2026 Monthly Update (data through October 2026)

The November update is a one-page dashboard rather than a research note (source: AIEI_MU_Nov26.pdf). Its headline figures:

| Component | November reading | Earlier readings |
|---|---|---|
| **Canaries Dashboard**: employment change from a year earlier, ages 22–25, most AI-exposed jobs | **−4.2%** (October 2026) | −3.5% one month earlier; −3.3% six months earlier |
| **Adoption Monitor**: employed US adults using generative AI for their job | **45%** (May 2026 survey) | 43% three months earlier; 35% a year earlier |
| **GDP-B Surplus Observer** (new): what 127 million US users would need to be paid to give up generative AI | **$183B a year** (July 2026) | $172B four months earlier; $116B a year earlier |
| **Transformation Tracker** (formerly Takeoff Tracker): macro indicators well above pre-2020 trends | **3 of 12** (September 2026) | Unchanged |

(source: AIEI_MU_Nov26.pdf)

**The age split.** Over the past year, employment fell for every age group under 35 and rose slightly for those 35 and older in ADP's sample of firms: down 2.2% for ages 22–34 and up 0.4% for ages 35+. For 22- to 25-year-olds, employment in the two most AI-exposed groups of jobs fell nearly 4%, and it has been below its year-earlier level every month since October 2023 (source: AIEI_MU_Nov26.pdf).

**No economy-wide transformation yet.** GDP and productivity are growing at their usual pace. The three indicators above trend all measure capital: IT's share of business equipment, software and R&D's share of business capital, and capital's share of national income (41.7% in 2024) (source: AIEI_MU_Nov26.pdf). This matches the June note's finding of strong signals only in capital share and IP equipment investment.

**A new measure of value outside GDP.** The GDP-B Surplus Observer estimates consumer value from free and low-cost AI tools, which "add little to GDP even when people value them highly" (source: AIEI_MU_Nov26.pdf). It offers one answer to why the productivity statistics look ordinary while use keeps growing ([[ai-economy-measurement-2026]]).

**A change from the June note.** The June note described "some recent reversals in *workplace* AI adoption" (source: AIEI_RN01_Jun26.pdf). The November update shows steady growth in work use: 35% a year earlier, 43% three months earlier, 45% in May 2026 (source: AIEI_MU_Nov26.pdf). The two may describe different series; neither note reconciles them.

**The authors' caveats.** The pattern "alone does not show AI caused these declines"; exposure "may differ from actual AI adoption"; and ADP data "is not a measure of economy-wide employment, but it is an early-warning signal" (source: AIEI_MU_Nov26.pdf).

### ⚠ Figures that do not line up

1. **April 2026 early-career figure.** The June note reported **−4.2%** year-over-year for 22–25-year-olds in the most AI-exposed jobs as of April 2026 (source: AIEI_RN01_Jun26.pdf). The November update gives **−3.3%** for six months earlier, which is also April 2026 (source: AIEI_MU_Nov26.pdf). The difference may reflect data revision or a change in grouping (the November text refers to "the two most AI-exposed groups of jobs"); neither document explains it. Not resolved.
2. **Dates inside the update.** The headline figure is labeled October 2026, while the chart is labeled October 2022 to September 2026 (source: AIEI_MU_Nov26.pdf). Minor.

### Adoption figures in the wiki measure different things

The 45% figure is the highest adoption estimate in the wiki. Most of the others measure different units (firms, establishments, a multi-survey estimate), so they are not contradictions. The exception is Microsoft's 31.3%: it counts a broader group (working-age adults using AI for anything), so it would be expected to be *higher* than 45%, not lower. ⚠ That gap is not explained by either source and is flagged, not resolved (see [[brad-smith-ai-jobs-next-generation]]).

| Figure | What it counts | Source |
|---|---|---|
| 45% (May 2026) | Employed US adults who use generative AI for their job (Bick, Blandin & Deming survey) | AIEI_MU_Nov26.pdf |
| 31.3% (Q1 2026) | Share of the US working-age population using generative AI, for any purpose (Microsoft AI Diffusion Report) | [[brad-smith-ai-jobs-next-generation]] |
| 15–20% | Developed-market AI adoption, Goldman's combination of 11 surveys | [[goldman-sachs-ai-labor-squeeze]] |
| 23% | US establishments with AI built into regular workflows | [[goldman-ai-displacement-cyclical]] |

Individual workers adopt faster than organizations build AI into their workflows, so worker-use figures run well above firm figures (wiki inference).

---

## Related pages

- [[anthropic-labor-market-index]]
- [[labor-market-polarization]]
- [[broken-ladder]]
- [[cte-and-ai]]
- [[nber-data-centers-local-economies]]
- [[bcg-ai-reshapes-jobs]]
- [[brad-smith-ai-jobs-next-generation]]
- [[transferable-skills]]
- [[canaries-coal-mine-brynjolfsson]]
- [[graduating-into-disruption-census]]
- [[entry-level-labor-market]]
- [[education-to-workforce-data-systems]]
- [[ai-economy-measurement-2026]]
- [[goldman-sachs-ai-labor-squeeze]]
- [[goldman-ai-displacement-cyclical]]
- [[ai-labor-demand-41-countries]]
