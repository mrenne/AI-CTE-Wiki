# Stanford DEL AI Economic Indicators: June 2026 Update

**Summary**: Research Note #1 from Stanford Digital Economy Lab (Brynjolfsson et al., June 2026) — three components tracking AI's actual labor market and macroeconomic impact with live ADP data on 4.6 million workers across 730+ occupations. Key finding: automation-type AI usage predicts employment decline for early-career workers; augmentation-type usage does not.

**Sources**: `raw/PDF/AIEI_RN01_Jun26.pdf`, `raw/PDF/CanariesintheCoalMine_Nov25.pdf`, `raw/PDF/Canaries_August2026.pdf`

**Last updated**: 2026-08-12

---

## Overview

*AI Economic Indicators: June 2026 Update* is Research Note #1 from the Stanford Digital Economy Lab (DEL), directed by Erik Brynjolfsson and produced in partnership with ADP Research. The initiative tracks three components — Canaries Dashboard, Takeoff Tracker, and Adoption Monitor — as an ongoing empirical monitoring project designed to produce periodic updates rather than a single-point analysis.

Brynjolfsson's framing: "We are flying blind into one of the most consequential periods in world history." The initiative's goal is to replace speculation with ongoing measurement. (source: AIEI_RN01_Jun26.pdf)

---

## Component 1: The Canaries Dashboard

### Design

The Canaries Dashboard is the most novel and empirically powerful component. In partnership with ADP Research, Stanford DEL tracks employment outcomes for roughly **25,000 firms, 4.6 million workers, and 730+ occupations** — the largest longitudinal employment sample for this question in the wiki. The "canaries" framing references the historical use of canaries in coal mines to detect invisible hazards: the goal is to identify which workers are showing early-stage employment effects before they appear in aggregate statistics.

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
- **Lambert & Schindler ([[broken-ladder]], May 2026)**: WFH and GenAI exposure correlate at 0.77; in joint-treatment specifications, WFH is robust while GenAI attenuates to near-zero
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
