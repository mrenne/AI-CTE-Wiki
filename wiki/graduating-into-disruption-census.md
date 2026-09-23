# Graduating into Disruption: Labor Market Outcomes for AI-Exposed College Majors

**Summary**: A September 2026 U.S. Census Bureau working paper (Orr, Tucker & Warren, CES 26-56) linking 6.7 million bachelor's graduates to administrative earnings records. Graduates in the most AI-exposed decile of majors saw a 5-percentage-point drop in initial employment and a 13% drop in initial earnings after ChatGPT — recession-scale — with about half the earnings loss coming from displacement into lower-paying sectors like retail and food service. The result is robust to the work-from-home confound and to graduate-supply explanations.

**Sources**: `raw/PDF/Gradiating into Disruption.pdf`

**Last updated**: 2026-09-23

---

## About this source

Center for Economic Studies working paper CES 26-56 (September 2026) by Cody Orr, Lee C. Tucker, and Lawrence Warren of the U.S. Census Bureau. CES papers have not undergone full Census Bureau publication review and represent the authors' views, not the Bureau's (source: Gradiating into Disruption.pdf).

**Data and design** (source: Gradiating into Disruption.pdf):
- **Graduates**: 6,665,500 bachelor's-degree records from the Post-Secondary Employment Outcomes (PSEO) program — 27 data partners, 24 states, 350+ institutions, roughly **29% of all U.S. bachelor's degrees conferred 2016–2024**. The sample skews toward large, public, urban, research-intensive institutions.
- **Outcomes**: Longitudinal Employer-Household Dynamics (LEHD) administrative wage records covering over 95% of jobs in participating states, through Q3 2025.
- **AI exposure**: Assigned **by college major, not by job**. Each major's exposure is the average Eloundou et al. (2024) GPT-4 Beta occupational exposure score across the occupations that 21–29-year-old graduates of that major held in the 2018–2022 ACS — fixed *before* ChatGPT.
- **Method**: Event-study difference-in-differences comparing exposure deciles 7–10 against a pooled baseline of deciles 1–6, with institution-by-major, institution-by-quarter, and major-by-season fixed effects; 2022 as reference year.

**Why assigning exposure by major matters.** Most prior studies (including [[canaries-coal-mine-brynjolfsson]] and [[broken-ladder]]) assign exposure using the occupation or industry a worker ends up in — which is itself an outcome AI may have changed. Because a major is chosen before graduation, this design can follow graduates into non-employment and into *different* occupations and sectors without losing them from the treated group (source: Gradiating into Disruption.pdf).

---

## Main findings

### 1. Initial employment fell, concentrated in the top decile

After ChatGPT's November 2022 release, the likelihood of employment in the quarter after graduation fell by about **2 percentage points for deciles 7 and 8** and **5 percentage points for decile 10**, relative to deciles 1–6. Pre-trends before 2020 are flat, and the timing is sharp (source: Gradiating into Disruption.pdf).

The top decile is **dominated by computer science, computer and information systems, computer engineering, and other software-adjacent majors**. Computer Science, Computer and Information Systems–General, and Computer Engineering are the three majors with both the largest employment declines and the largest earnings declines (source: Gradiating into Disruption.pdf).

### 2. Initial earnings fell by about 13% — recession-scale

Full-quarter earnings two quarters after graduation fell about **13%** for the top decile (the abstract figure; event-study coefficients reach roughly 14 log points by 2025). The authors compare this to the literature on graduating into a large recession (Oreopoulos et al. 2012; Altonji et al. 2016), whose initial annual earnings losses are roughly 9–10% (source: Gradiating into Disruption.pdf).

### 3. Half the earnings loss is sectoral displacement

The paper decomposes the earnings decline. From 2022 to 2024, top-decile graduates' employment share **fell by nearly 6 points in Professional, Scientific & Technical Services** and **over 3 points in Information** — the highest-paying sectors — while rising by over 2 points each in **Accommodation & Food Services** and **Retail Trade**. Less-exposed graduates' sector mix barely moved (source: Gradiating into Disruption.pdf).

About **half** of the top decile's earnings decline comes from this across-industry shift. Without it, real earnings would still have fallen nearly 8% to below 2019 levels; with it, total earnings fell about 15%, to levels last seen before 2016 (source: Gradiating into Disruption.pdf).

### 4. Deciles 7–9 recover; decile 10 does not fully recover

| Horizon after graduation | Deciles 7–9 | Decile 10 |
|---|---|---|
| 1 quarter (employment) | ~−2 pp | ~−5 pp |
| 4 quarters (employment) | −1.4 pp (7–8) | −4.2 pp |
| 8 quarters (employment) | Little evidence of decline | −2.0 pp |
| 4 quarters (earnings) | Attenuates toward zero | −8.1 log points |
| 8 quarters (earnings) | Near zero | −3.3 log points |

(source: Gradiating into Disruption.pdf)

The authors' reading: for most exposed graduates the effects look "reasonably transitory," with "little evidence ... to suggest long-term scarring," but "a concerning picture" for the most-exposed decile, including possible persistent earnings effects (source: Gradiating into Disruption.pdf).

### 5. Job switching points to weak initial matches

Graduates who were already employed when ChatGPT arrived became *less* likely to switch jobs (like cohorts two years out during COVID). Graduates who entered *after* ChatGPT switched more — consistent with taking weaker first jobs and then trying to leave them (source: Gradiating into Disruption.pdf).

### 6. Concentration of exposure matters more than average exposure

A major's **share of jobs in the top-quintile exposure occupations** predicts outcomes within deciles 7–9 better than its mean exposure. The authors' stylized example: Journalism and Accounting have nearly identical mean exposure, but Journalism has 36% of its occupations in the top exposure quintile vs. 16% for Accounting. Across all majors, a 10-point increase in that share is associated with a 1.3-point lower initial employment rate and 3 log points lower initial earnings. Every major has *some* top-quintile exposure — 82% of majors have at least 10% (source: Gradiating into Disruption.pdf).

---

## Alternative explanations tested

**Work-from-home (Lambert & Schindler).** WFH and AI exposure correlate at 0.88 at the major level (vs. 0.77 at the occupation level in [[broken-ladder]]). The authors (a) add a continuous major-by-year WFH control and (b) replicate the Lambert & Schindler joint-treatment specification. Neither removes the result: post-period employment coefficients are "nearly identical" to baseline, and the earnings gap relative to the long-run average is preserved. They caution that collinearity limits how cleanly the two can be separated (source: Gradiating into Disruption.pdf).

**Graduate oversupply.** Top-decile graduates grew 24% from 2017 to 2022, but initial employment grew in lockstep until 2022. From 2022 to 2024 supply growth *slowed* to under 3% per year while employed-graduate counts broke trend and *fell* 3%. No other decile shows this divergence (source: Gradiating into Disruption.pdf). **This contradicts the "Graduate Glut" explanation in [[no-country-young-grads-burning-glass]]** — see that page for the scope difference.

**Self-employment and graduate school.** Among top-decile grads, self-employment rose 0.48 points and grad-school enrollment 1.66 points (2022–2024) while the baseline group was flat or falling; taken at face value this could explain up to half the initial-employment decline. But self-employed top-decile graduates earn less than a third of their wage-employed peers, suggesting these are responses to weak demand rather than new opportunity (source: Gradiating into Disruption.pdf).

**Monetary tightening.** Drawing on Tucker (2026), monetary shocks can account for at most about a quarter of the relative early-career decline and do not reproduce the sharp timing around ChatGPT (source: Gradiating into Disruption.pdf).

---

## Reconciling the literature

The paper explains why the wiki's labor-market sources have seemed to disagree. Studies of **hiring** in AI-exposed occupations ([[canaries-coal-mine-brynjolfsson]], [[anthropic-labor-market-index]]) find large declines for young workers; studies following **already-employed** workers find little rise in unemployment. Both can be true: adjustment happens **at labor-market entry**, through delayed employment and sorting into lower-paying sectors. "Modest employment or unemployment effects can coexist with substantial deterioration" in earnings and job quality (source: Gradiating into Disruption.pdf). This is the same pattern as recession entry — except concentrated in a subset of fields, so the rest of the labor market can absorb displaced graduates.

---

## Mechanisms — including one that runs through education

The authors do not identify a single mechanism, but discuss three (source: Gradiating into Disruption.pdf):

1. **Task substitution** of work previously done by new graduates.
2. **Loss of the training function of entry-level work.** Entry-level tasks are both productive and developmental; if AI automates the tasks through which juniors acquire tacit knowledge, firms may hire and train fewer of them (citing Garicano & Rayo 2025). This matches the "Expertise Upheaval" / "Flipped Pyramid" framing in [[no-country-young-grads-burning-glass]].
3. **Erosion of educational signals.** If employers cannot distinguish real skill from AI-assisted performance, grades and work samples lose value as hiring signals. The authors cite studies (Hausman et al. 2026; Chirikov 2026) finding AI availability raises grades — most in homework-heavy, AI-exposed courses — compressing grade distributions. They also note secondary-school evidence that unrestricted AI raises assignment performance while lowering later learning (Bastani et al. 2025). This channel could explain why effects on new graduates appeared **before** widespread firm-level AI adoption.

The third mechanism is the first time a labor-economics source in the wiki directly connects the **learning-performance paradox** ([[building-ai-companions]], [[agentivism]], [[cognitive-debt]]) to labor-market outcomes: if AI inflates measured performance without building durable competence, credentials become less informative, and new entrants pay the price.

---

## Limitations, stated by the authors

- Short post-period: cannot yet say whether exposed graduates catch up (source: Gradiating into Disruption.pdf).
- Bachelor's degrees only; sample institutions are not nationally representative.
- The comparison group (deciles 1–6) is also affected by AI, so estimates may understate the full effect.
- Cannot rule out every field-specific shock coinciding with ChatGPT (e.g., the tech-sector contraction), though sectoral movement away from traditional industries makes a narrow tech-downturn story less compelling.
- Exposure measures predate agentic AI and are snapshots of a changing technology.

---

## Relationship to the wiki's evidence base

| Finding | Relationship |
|---|---|
| Survives the Lambert & Schindler WFH specification | Second independent dataset (after ADP in [[canaries-coal-mine-brynjolfsson]]) where the AI effect survives the [[broken-ladder]] critique |
| Adjustment at entry, via sector sorting | Reconciles hiring-decline studies with flat-unemployment studies ([[ai-economy-measurement-2026]]) |
| CS/software majors hit hardest | Causal backing for enrollment declines in [[columbia-cs-ai-disruption]] and [[stanford-ai-index-education-2026]] |
| Oversupply does not explain the drop | Contradicts the "Graduate Glut" driver in [[no-country-young-grads-burning-glass]] |
| Grade-signal erosion | Links labor outcomes to [[cognitive-debt]] and [[agentivism]] |
| Entry-level concentration | Consistent with [[goldman-sachs-ai-labor-squeeze]]'s 2–6x entry-level multiplier |

---

## Implications for CTE

1. **A bachelor's degree in an AI-exposed field is no longer a reliable ticket to high-paying entry work.** The strongest effects fall on exactly the majors (computer science, information systems) that K-12 computing and IT pathways have marketed as the safest bets. CTE Information Technology and Digital Technology pathways should prepare students for that reality rather than assume the pre-2022 pipeline still works.
2. **Graduates in the most-exposed majors are being pushed down into retail and food service** — the occupational tier CTE has historically tried to move students *out of*. This is the most concrete administrative-data evidence yet for the wiki's "CTE as a hedge" thread ([[nyt-teens-trade-classes]], [[safest-college-degrees-forbes]]).
3. **What matters is how concentrated a field's exposure is, not its average.** For pathway design, the useful question is "what share of this pathway's destination jobs are in the most-automatable occupations?" — a sharper version of the exposure analysis in [[ai-occupational-exposure-index]].
4. **Credentials that verify skill directly will gain value as grades lose signal.** Industry credentials, performance assessments, and work-based learning — CTE's native assessment modes — are the kind of hard-to-fake signals the paper's third mechanism implies employers will need.

---

## Related pages

- [[no-country-young-grads-burning-glass]]
- [[canaries-coal-mine-brynjolfsson]]
- [[broken-ladder]]
- [[labor-market-polarization]]
- [[cte-and-ai]]
- [[goldman-sachs-ai-labor-squeeze]]
- [[anthropic-labor-market-index]]
- [[ai-economy-measurement-2026]]
- [[columbia-cs-ai-disruption]]
- [[stanford-ai-index-education-2026]]
- [[safest-college-degrees-forbes]]
- [[nyt-teens-trade-classes]]
- [[cognitive-debt]]
- [[agentivism]]
- [[building-ai-companions]]
- [[ai-occupational-exposure-index]]
