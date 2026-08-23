# Canaries in the Coal Mine? Six Facts about the Recent Employment Effects of Artificial Intelligence

**Summary**: A Stanford/NBER working paper by Erik Brynjolfsson, Bharat Chandar, and Ruyu Chen using high-frequency ADP payroll data (now through June 2026) to document six facts about AI's labor-market effects: early-career workers (22–25) in AI-exposed occupations now stand 19% below where they'd be had they kept pace with less-exposed peers — a gap that has widened every month since first documented in August 2025 — concentrated in occupations where AI automates rather than augments work, and robust across most (not all) alternative explanations including work-from-home amenability.

**Sources**: `raw/PDF/Canaries_August2026.pdf` (Brynjolfsson, Chandar & Chen, Stanford Digital Economy Lab / NBER, August 2026 — updates and extends the August 2025 original with data through June 2026); `raw/PDF/CanariesintheCoalMine_Nov25.pdf` (November 2025 version, superseded by this update but retained as a prior data vintage)

**Last updated**: 2026-08-12

---

## Overview

This is the academic working paper underlying the "Canaries Dashboard" already summarized in the wiki via [[stanford-del-ai-economic-indicators]]. This August 2026 release is an update to a paper the wiki already covered at its November 2025 vintage — the authors themselves frame it explicitly as an update-and-extend exercise (see "What Changed Between Versions" below), not a new study. The data now run through **June 2026** via ADP's high-frequency payroll records, a balanced panel of 3.5–5 million workers per month, with an extended pre-ChatGPT comparison sample back to January 2018 for assessing pre-trends. (source: Canaries_August2026.pdf)

## The Six Facts (Current Vintage)

### Fact 1: No evidence of widespread, economy-wide job displacement

Average ADP employment rose about 6% between November 2022 and June 2026; the most AI-exposed quintile grew about 4% over the same period — a mild slowdown, not a decline. Aggregate stability is itself a finding: claims of economy-wide AI-driven job losses are not visible in the payroll data through mid-2026.

### Fact 2: Young workers in AI-exposed occupations are 19% below where they'd be had they kept pace

This is the paper's headline number, and it has changed since the wiki's prior coverage. Employment for 22–25-year-olds in the two most AI-exposed quintiles fell about 11% between November 2022 and June 2026, while the same age group in the three least-exposed quintiles grew about 10% — a 21-percentage-point divergence, expressed as a **19% "kept-pace" shortfall**. Experienced workers show no comparable gap between more- and less-exposed occupations.

**This number has moved, and the paper is explicit about tracking its own drift**: the kept-pace shortfall was 15% as of the July 2025 data vintage and has widened steadily to 19% as of June 2026. Earlier circulated versions instead headlined firm-fixed-effects regression estimates (13% as of July 2025 data, 16% as of September 2025 data — the figure the wiki previously cited). The authors now explicitly de-emphasize that regression estimate in favor of the simpler descriptive divergence, "which requires no modeling choices." **The wiki's prior "16% relative decline" figure is superseded by this 19% kept-pace figure**, and the underlying number is still moving upward.

### Fact 3: The divergence has widened steadily since first documented in August 2025

New in this vintage: an explicit standalone fact tracking the trend's trajectory over time, not just its current level. Figure 4 of the paper (an occupation event-study rolling the divergence forward month by month) shows the gap growing to roughly 18 percentage points by mid-2026 across four different control specifications (no controls; interest-rate exposure; education; work-from-home). The paper flags — and directly addresses rather than downplays — a **pre-trend**: exposed and non-exposed occupations diverged during the COVID-19 pandemic too, peaking around mid-2020, before converging back to roughly their 2018–2019 baseline by November 2022. The post-2022 decline therefore carries the gap **below** its pre-pandemic baseline rather than merely back toward it, and the decline has continued for over three years — well past the point a pure pandemic-reversion story would predict stabilization.

**Health aides, still the clearest occupation-level counter-example**: consistent with the wiki's prior coverage, the appendix case studies (Fig. B.5) continue to show home health aides — a low-AI-exposure occupation — with employment for the youngest workers growing *faster* than for older workers in the same occupation, the sharpest occupation-level confirmation in the wiki's evidence base of the [[relational-economy]] thesis. This finding is unchanged from the prior vintage and remains one of the paper's clearest positive counter-examples to the general youth-employment-decline pattern.

### Fact 4: The decline operates through reduced hiring, not increased separations

Hiring and separation rates both fell after 2022 across all age groups and exposure levels (a "low-hire, low-fire" labor market), but separation rates for young workers in the *most*-exposed occupations fell at least as much as in the least-exposed occupations — the opposite of what a displacement/layoff story would predict. The divergence is a narrowing **entry point**, not workers being pushed out. This distinction matters directly for CTE: the mechanism is fewer new positions opening up, not existing CTE-track workers losing jobs.

### Fact 5: Declines concentrate in occupations where AI substitutes for labor; complementary usage shows flat or rising employment

Using the Anthropic Economic Index's automation/augmentation classification of Claude usage by task, the paper's joint regression (Table 3) finds, for the youngest workers, **only the automation coefficient is negative and statistically significant** (about −0.10 per standard deviation for 22–25-year-olds) — the complementarity coefficient is not significant for this age group and shrinks the automation effect toward zero as age rises. Critically, the **complementarity coefficient turns positive and significant for workers aged 41–49 and 50+** — meaning augmentative AI use is associated with *employment gains* for experienced workers specifically, not merely a lack of penalty. This age gradient — automation hurts the young, complementarity helps the experienced — is described by the authors as "the paper's most direct evidence on mechanism." (Terminology note: the paper now writes "automation" and "complementary usage" rather than the AEI's original "automative"/"augmentative" labels, reserving the latter only for direct citations of AEI figures/tables — a labor-economics precision distinction, not a substantive change.)

### Fact 6: Adjustment is occurring through employment, not base compensation

Real base pay shows little divergence by age or exposure quintile among either job-stayers or new hires — the roughly 20-percentage-point employment divergence dwarfs any compensation-margin adjustment. One partial exception: young software developers' base pay grew somewhat faster than older workers' after ChatGPT, but the authors attribute this to composition effects (contracted hiring skewing toward higher-paid remaining engineers) rather than a genuine wage premium, since it does not appear when aggregating to exposure quintiles.

## The Mechanism: Codified vs. Tacit Knowledge — Now Measured Directly, Not Proxied

The prior vintage of this paper proxied codified/tacit knowledge reliance using O*NET education/experience requirements. This update replaces that proxy with a **direct LLM-based classification**: GPT-5.4-mini scores all 7,514 raw ADP job titles (using their actual job descriptions) on codified-knowledge and tacit-knowledge reliance (1–10 scales), guided by a system prompt trained on O*NET knowledge-domain and work-activity examples. This is methodologically the most direct measurement of the codified/tacit distinction in the wiki's evidence base — not an occupational proxy, but a description-level classification of actual job content.

The results confirm the wiki's existing thesis with a stronger measurement: occupations with higher codified-knowledge reliance show slower entry-level employment growth; occupations with higher tacit-knowledge reliance show faster growth for mid-career and senior workers. One new and important nuance: **the codified-knowledge gradient for young workers is not statistically significant once controlling for college-share quintile** — it substantially overlaps with education. The **tacit-knowledge gradient for experienced workers, by contrast, survives the education control** — meaning tacit knowledge's protective effect is not simply a proxy for being college-educated; it captures something education alone does not.

## A New Data Point in the Broken Ladder Debate — This Time Cutting the Other Way

The wiki has flagged an open empirical tension between this paper and [[broken-ladder]] (Lambert & Schindler) over whether AI exposure or work-from-home exposure better explains the junior-hiring decline. This update adds a significant new piece of evidence: the authors **directly replicate Lambert & Schindler's own state-by-occupation event-study specification inside the ADP data** (Online Appendix Section I), using the same AI-exposure measure, the same Lambert & Schindler work-from-home measure, and the same joint-treatment design.

The result reverses what happens in Lambert & Schindler's own dataset. In the ADP replication, when AI exposure and WFH exposure are entered **jointly**, the **AI-exposure coefficient grows** (from −0.64 percentage points per SD in 2022 to −1.52 by 2025) while the WFH coefficient becomes small, inconsistently signed, and mostly insignificant. This is the *opposite* pattern from Lambert & Schindler's Revelio-based finding, where the GenAI coefficient is the one that attenuates to near-zero under joint treatment.

The authors' interpretation: the diverging results reflect **differences in the underlying datasets** (ADP administrative payroll records vs. Revelio's professional social-media/job-posting data), not necessarily a flaw in either study's methodology, since the identical specification produces opposite conclusions depending on which data source it's run on. This does not resolve the debate — if anything it sharpens it, showing the disagreement is not merely about specification choices but about what different real-world data sources say when asked the identical empirical question. Per the wiki's contradiction-noting rule, this is flagged as an unresolved methodological puzzle, not adjudicated in either direction.

## Robustness — What Held, What Attenuated, What the Paper Flags Itself

Consistent across: excluding technology occupations/firms, controlling for interest-rate exposure, controlling for remote-work amenability (both teleworkable and non-teleworkable occupations separately), five alternative AI-exposure measures (10–13% decline for the most-exposed quintile across all of them), the unbalanced firm sample, and inclusion of part-time/temporary workers.

**What attenuates, stated by the authors themselves rather than left implicit**: controlling for occupational education level produces the largest attenuation of any control — from −18 percentage points (no controls) to −9 points (with college share added, still significant at 10%) in the primary sample. The authors present this as a genuine interpretive fork rather than resolving it: the no-controls estimate is preferable if college share mostly proxies exposure to AI-automatable knowledge work; the controlled estimate is preferable if college share instead proxies independent pandemic-era shocks to educated labor markets. Both readings remain live.

## New: A Transparency Section on the Paper's Own Estimate Drift

New in this vintage is an explicit "Changes from the August 2025 Version" appendix section in which the authors compare their own within-firm Poisson event-study estimates across paper vintages, using identical sample filters. Under the original (August 2025) stricter filters, the most-exposed-quintile estimate for workers aged 22–25 was −11.7 log points (p = 0.02) — a statistically significant finding. Applying those same filters to the current, extended dataset gives −5.3 log points (p = 0.26) — **no longer statistically significant**. The fourth-quintile estimate, by contrast, is stable across vintages (−10.5 to −12.8 log points, consistently significant). The authors attribute part of this to data-pipeline improvements (better occupation-code crosswalk, imputation of missing codes) rather than purely to the additional nine months of data, and state plainly that the within-firm estimates are "more sensitive... than the raw descriptive results" to these pipeline changes. This kind of explicit vintage-to-vintage self-audit is unusual and worth noting on its own terms — it is exactly the practice the wiki's evidence-base pages ([[evidence-base-ai-k12]], [[ai-economy-measurement-2026]]) argue this literature needs more of.

## New Heterogeneity: Gender, Region, and State AI-Adoption Intensity

- **Gender**: Women work in more AI-exposed occupations than men at every age band, consistently across ADP, CPS, and ACS. Even within the same exposure quintile, men concentrate in different occupations than women (manual labor vs. cleaning/healthcare in the least-exposed quintile; software development vs. customer-service-representative-adjacent roles in the most-exposed quintile). Young women show steeper average employment declines than young men, consistent with their greater concentration in declining high-exposure roles.
- **Region**: The Q5-vs-Q1 employment gap for 22–25-year-olds is greatest in the **West and Northeast** (roughly −26 percentage points each) and smallest in the **South and Midwest** (−14 to −16 points) — a new geographic dimension not previously in the wiki's labor-market evidence base.
- **State AI-adoption tier**: Using Anthropic Economic Index state-level relative-usage data, the decline for exposed young workers is sharpest (~−19%) in **leading-adoption states** and smallest in emerging-adoption states — direct evidence that the effect scales with how intensively a state's labor market has actually adopted AI, not just with occupational exposure composition.

## External Validity: A New, More Cautious Read Against National Data

New in this vintage is a dedicated section comparing the ADP findings to the CPS and ACS. The **CPS is too noisy to serve as an independent check** — the fine age-by-occupation cells this paper studies contain only 23–63 respondents per month nationally, producing month-to-month swings of 20% or more that make the CPS unusable at this level of granularity (a genuine data-infrastructure limitation the authors state plainly, not merely infer). The **ACS (annual, larger sample) shows the same direction but a much smaller magnitude**: the Q5-minus-Q1 gap for 22–25-year-olds is −2.2 percentage points in the ACS (confidence interval includes zero) against −13.2 in the comparable ADP window, widening to roughly −20.5 by mid-2026 in ADP. The two sources agree closely within professional/information/financial-services occupations specifically (−21 to −23 points in both) but diverge sharply in education/health/public-administration, where ADP shows a small negative gap and the ACS shows a *positive* one — a discrepancy the authors partly (not fully) attribute to a documented Census Bureau population-control revision in the 2024 ACS weights.

**Caution for the wiki**: the magnitude of the divergence "appears specific to the ADP sample, but its direction is consistent" across data sources, per the authors' own summary. This tempers how confidently the 19% headline figure should be read as generalizing to the full US labor market — the direction of the effect has more support than its size.

## Relationship to the Wiki's Existing Evidence Base

| Finding | Connects to |
|---|---|
| Same research program, now updated through June 2026 | [[stanford-del-ai-economic-indicators]] (Canaries Dashboard) |
| Automation vs. complementarity as the decisive mechanism, now with a positive effect for experienced workers | [[stanford-del-ai-economic-indicators]] |
| 19% kept-pace shortfall (was 16% in the wiki's prior coverage) | [[anthropic-labor-market-index]] (14% hiring-rate decline for 22-25 in exposed occupations — a related but distinct measure from a different dataset) |
| Direct replication of the Lambert & Schindler specification, reversing which coefficient survives | [[broken-ladder]] (sharpens, does not resolve, the open WFH-vs-AI debate) |
| Codified/tacit knowledge mechanism, now LLM-measured directly from job descriptions | [[transferable-skills]] (stronger empirical grounding for why experience-based judgment resists AI substitution) |
| Tacit-knowledge protective effect survives controlling for education; codified-knowledge penalty does not | [[satisficing-and-tolerance-principle]] (a second, data-driven confirmation that experience-based judgment is not just a proxy for credentials) |
| Gender heterogeneity: women more exposed at every age | [[labor-market-polarization]] (new equity dimension) |
| The paper's own estimate for the most-exposed quintile weakened between vintages | [[ai-economy-measurement-2026]] (a concrete, self-reported instance of the measurement instability that source describes generally) |
| The paper's own external-validity caution (ADP larger than ACS) | [[goldman-sachs-ai-labor-squeeze]] (independent cross-country evidence for the same *direction* of effect, from a different data source and methodology entirely) |

## An Independent Cross-Country Corroboration (August 2026)

[[goldman-sachs-ai-labor-squeeze]] (Goldman Sachs, via CNBC, August 2026) provides the wiki's first non-US, non-academic corroboration of this paper's central pattern: automation-heavy occupations show entry-level hiring headwinds. Goldman's finding — a 2x-6x entry-level exposure multiplier replicated across France, Canada, the US, and Australia — is directionally consistent with this paper's automation-vs-complementarity mechanism, though it uses entirely different data (Goldman's own occupational employment-growth analysis across 800+ occupations and 11 adoption surveys) rather than ADP payroll records. This strengthens the *direction* of this paper's findings at exactly the moment its own external-validity section (see above) raised a caution about *magnitude* generalizability from the US-only ADP sample.

## Implications for CTE

1. **The automation/complementarity distinction now has a stronger, age-graded form**: complementary AI use doesn't just avoid penalizing young workers — it actively *helps* experienced workers' employment. CTE AI-literacy curricula should target complementary/augmentative use patterns explicitly, not merely avoid automative ones.
2. **The mechanism is a narrowing front door, not existing-worker displacement.** Fact 4 (hiring, not separations) reframes the CTE policy problem as one of *entry-point scarcity* rather than incumbent job loss — relevant to how CTE programs frame the risk to prospective students versus current workers.
3. **The codified/tacit mechanism now has direct, LLM-measured support from job descriptions rather than an occupational proxy** — strengthening (not just repeating) the wiki's existing defense of CTE's apprenticeship and hands-on-training model, with the added nuance that the *tacit* side of the mechanism is the more robust one (survives education controls), while the codified-knowledge penalty is entangled with education itself.
4. **A caution on how far to generalize the headline number**: the paper's own external-validity section shows the ADP-observed magnitude is larger than what shows up in the ACS, even though the direction agrees. CTE program planning should treat 19% as an upper-bound, ADP-sample-specific estimate rather than a national-economy figure.

## Related pages

- [[stanford-del-ai-economic-indicators]]
- [[anthropic-labor-market-index]]
- [[broken-ladder]]
- [[labor-market-polarization]]
- [[relational-economy]]
- [[transferable-skills]]
- [[satisficing-and-tolerance-principle]]
- [[cte-and-ai]]
- [[ai-economy-measurement-2026]]
- [[fostering-ai-ready-caring-communities]]
- [[goldman-sachs-ai-labor-squeeze]]
