# The Broken Ladder

**Summary**: A May 2026 working paper (Lambert & Schindler, Warwick/LSE and Ellison Institute Oxford) arguing that the widely cited decline in early-career hiring has been misattributed to generative AI — and that work-from-home adoption is the more robust predictor once both shocks are estimated jointly.

**Sources**: `raw/PDF/The Broken Ladder.pdf`, `raw/PDF/AIEI_RN01_Jun26.pdf`

**Last updated**: 2026-06-14

---

## The Central Claim

A growing post-ChatGPT literature attributes the sharp decline in early-career hiring since 2022 to generative AI — arguing that GenAI substitutes for the cognitive and analytical tasks firms historically delegated to junior workers. Lambert & Schindler argue this verdict is premature.

Their core methodological point: **GenAI and WFH exposure are correlated at 0.77 (Spearman rank) across O\*NET occupations.** Software developers, accountants, and management consultants sit at the top of *both* rankings; electricians, janitors, and construction laborers sit at the bottom of *both*. Single-treatment designs that include only GenAI exposure are therefore picking up WFH effects as well — and when both are estimated jointly, the WFH effect survives while GenAI attenuates to near-zero.

---

## The Empirical Fact Being Explained

Across the US, UK, Canada, and Australia, the junior share of new hires has fallen 8–11 percentage points below 2019 baselines by 2025. The series is stable through 2019, dips during COVID, recovers briefly in 2021–22, and then breaks sharply downward from late 2022. The synchronicity across four economies with different institutions, immigration regimes, and macro trajectories is the primary evidence of a common underlying shock.

Within countries: entry-level hires are down 14–29%; junior hires down 12–26%; senior hires are 5–21% *above* the pre-period average. Early-career jobs are the primary channel through which workers accumulate human capital; a persistent contraction in this pipeline hollows out the future senior workforce and imposes cohort-specific career scarring. (source: The Broken Ladder.pdf)

---

## Data and Design

Two microdata sources covering the US, UK, Canada, and Australia over 2017–2025:

- **Revelio Labs**: 243 million employer-employee records assembled from résumés. Seniority classified into seven levels based on job title and prior employment history. "Junior" = bottom two levels.
- **Lightcast**: 407 million online job vacancy postings from thousands of job boards. Outcome: share of postings requiring ≤3 years of relevant experience.

**Exposure measures**:
- GenAI: Eloundou et al. (2024) — fraction of an occupation's tasks completable ≥50% faster with generative AI
- WFH: Hansen et al. (2023) — share of postings in 2021–22 offering remote/hybrid work in each occupation
- Both z-score standardized

**Two-treatment difference-in-differences** designs at two levels:
- State × 6-digit O\*NET occupation × month (47,003 units)
- Firm × 2-digit occupation × year (603,650 units)

Pre-period: 2017–2019 (before mass WFH and GenAI adoption). Post-period: 2023–2025. (source: The Broken Ladder.pdf)

---

## Main Results

**Single-treatment**: both WFH and GenAI exposure each predict a ~4–5pp fall in the junior share of new hires (per 2sd increase) by 2025, and ~3pp fall in the share of postings requiring ≤3 years experience. The two event-study paths are nearly indistinguishable from each other.

**Joint-treatment**: the WFH coefficient is stable (−1.42 to −1.57pp); the GenAI coefficient attenuates heavily (−0.41 to −0.45pp) and is often statistically indistinguishable from zero. On the job postings outcome, the GenAI coefficient changes sign. (source: The Broken Ladder.pdf)

| Specification | WFH (pp) | GenAI (pp) |
|---|---|---|
| Single-treatment, hires | −1.69 | −1.34 |
| Joint-treatment, hires | −1.42 | −0.41 (n.s.) |
| Single-treatment, postings | −1.06 | −0.56 |
| Joint-treatment, postings | −1.24 | +0.27 |

*(State × occupation × month panel)*

The diagnostics rule out collinearity as an explanation: variance inflation factors stay below 2.4 and condition numbers below 2.7.

**Actual WFH adoption** (not just occupational exposure): firms that explicitly offered remote/hybrid work in 2021–22 show subsequent declines in junior hiring share and junior-experience postings, matched on WFH and GenAI exposure quintiles. The effects are similar in magnitude to the exposure-based results.

---

## The Formal Mechanism (WFH)

The paper builds a partial-equilibrium model with two-tiered employment, supervision constraints, and on-the-job learning. Key results:

**WFH reduces junior hiring through two channels:**

1. **Higher supervision costs (φ)**: Each junior worker consumes a fraction of senior time for monitoring, feedback, and development. Remote work raises this fraction — communication is slower, mentoring is harder, output is harder to interpret. This reduces the net marginal product of hiring a junior.

2. **Lower promotion rate (λ)**: On-the-job learning slows when workers are remote. Proximity to coworkers increases feedback, especially for younger workers (Emanuel et al., 2026). A lower learning rate means the capital gain from eventually promoting a junior to senior is more heavily discounted — making the investment less attractive. (source: The Broken Ladder.pdf)

Both channels predict the same direction: firms hire proportionally fewer juniors as WFH exposure increases. The model generates wage predictions consistent with empirical patterns: WFH raises the senior-to-junior wage premium and lowers the junior replacement rate — and both auxiliary margins move with WFH exposure but not GenAI exposure in the data.

---

## Robustness Exercises

The WFH-dominant pattern survives an unusually comprehensive battery of robustness tests:

- **Non-parametric co-treatment controls**: replacing the linear GenAI control with step functions of progressively finer quantile resolution. WFH coefficient stable at every resolution; GenAI coefficient collapses to zero with even a single above-median WFH dummy.
- **Selection on unobservables** (Cinelli-Hazlett): the WFH robustness value is 3–5× larger than the GenAI value (0.05–0.09 vs. 0.01–0.03). A confounder explaining only 1–3% of residual variation would suffice to kill the GenAI effect; killing WFH requires 5–9%.
- **Measurement error simulation** (Monte Carlo): implausibly high noise in the GenAI exposure index (signal reliability R = 0.50) would be required to produce the WFH-dominant pattern if GenAI were the true driver. For the postings outcome, misattribution rate is 0% at every noise level.
- **Alternative exposure measures**: WFH coefficient larger in magnitude than GenAI in 22 of 24 combinations of two WFH measures × three GenAI measures.
- **Residualized single-treatment designs**: WFH residualized on GenAI remains a robust predictor; GenAI residualized on WFH is small, insignificant, or wrong-signed.
- **Leave-one-out occupational robustness**: WFH-dominant pattern holds after dropping each of 18 2-digit O\*NET occupation groups individually.
- **Country-by-country**: WFH negative and significant in all four countries on new hires; GenAI insignificant in 7 of 8 country×design cells.

(source: The Broken Ladder.pdf)

---

## What the Paper Does Not Claim

The authors are careful about scope:

- "We do not interpret this evidence as ruling out strong impacts of GenAI on labor markets — our findings bear only on the **relative hiring of junior and senior workers up to 2025**."
- They acknowledge the analysis covers an early period (ChatGPT released November 2022; post-period is 2023–2025) when GenAI adoption was still accelerating.
- They do not address mass unemployment or absolute job loss — only the relative seniority composition of new hires.
- They explicitly call for firm-level GenAI adoption measures with independent variation from WFH, and a longer post-period, to track how effects evolve.

---

## The Optimism Argument

The authors frame the WFH-dominant finding as "cause for optimism" relative to the AI-doomer view:

> "WFH delivers substantial benefits to workers and firms, and the organizational frictions it creates around supervising and developing early-career workers are surmountable through the diffusion of managerial practices better suited to remote-work environments. More dramatic policy remedies would be required if GenAI was the main driver of the junior-hiring decline."

If WFH is the mechanism, the remedy is adapting management practice — hybrid policies, structured onboarding, remote mentoring protocols. If GenAI is the mechanism, remedies would require wage subsidies, differential tax treatment, or other structural interventions. The diagnosis determines the prescription. (source: The Broken Ladder.pdf)

---

## Implications for the Wiki's Labor Market Narrative

This paper directly complicates several claims in this wiki:

| Wiki finding | Status after Broken Ladder |
|---|---|
| Anthropic's 14% young-worker hiring slowdown attributed to AI ([[anthropic-labor-market-index]]) | The slowdown is real; the AI attribution is contested — WFH is the more robust predictor in joint designs |
| BCG Divergent segment: AI automates junior tasks first ([[ai-labor-disruption-segments]]) | The Divergent pattern is real; its cause may be WFH-driven supervision costs rather than task automation per se |
| "The entry-level hiring slowdown is the mechanism to watch" (index Key Themes) | Now requires the caveat: the mechanism behind the slowdown is debated; WFH and AI exposure are highly collinear |

**What the paper reinforces:**
- The CTE protected-sector thesis gains structural support: electricians and construction workers sit at the *bottom* of both WFH and GenAI exposure rankings — doubly insulated from both shocks
- The Anthropic paper's finding that AI exposure is concentrated in high-skill white-collar workers holds — these are exactly the workers most affected by WFH, which is why separating the two effects is hard
- The broader caution about exposure-based designs in AI labor market research extends to several findings this wiki has cited

---

## The Canaries Dashboard: A Subsequent Corroboration (June 2026)

Stanford Digital Economy Lab's Canaries Dashboard ([[stanford-del-ai-economic-indicators]], Brynjolfsson et al., June 2026) explicitly situates this paper in its broader debate context and extends the early-career employment finding into live 2026 ADP payroll data. Two points of contact with Lambert & Schindler's argument:

**Corroboration of the early-career signal**: The Canaries Dashboard confirms that the most AI-exposed early-career (22–25) occupations are contracting at −3.8%/year since ChatGPT while the least-exposed are growing at +2.0%/year. The signal has not reversed in the three-plus years since Lambert & Schindler's post-period ends.

**The automation/augmentation handle**: The Canaries Dashboard decomposes AI usage at the occupation level into automation-type (AI replaces worker involvement) and augmentation-type (AI assists workers who remain in the loop). The finding: **automation usage** predicts employment decline; **augmentation usage** does not. This is a mechanism-level distinction that exposure-based designs — including the total GenAI exposure measure Lambert & Schindler use — cannot make. The WFH confound argument applies to total exposure; it does not directly address whether the employment-contracting occupations are predominantly automation-heavy rather than augmentation-heavy in their actual AI usage.

Lambert & Schindler's finding remains methodologically sound within its scope — the WFH coefficient is robust and the GenAI coefficient attenuates in joint-treatment designs using total exposure. But the Canaries Dashboard's automation/augmentation decomposition opens a second mechanism channel that the WFH confound critique does not foreclose. The debate is not closed. (source: AIEI_RN01_Jun26.pdf)

## Related pages

- [[anthropic-labor-market-index]]
- [[labor-market-polarization]]
- [[stanford-del-ai-economic-indicators]]
- [[bcg-ai-reshapes-jobs]]
- [[ai-labor-disruption-segments]]
- [[cte-and-ai]]
- [[relational-economy]]
- [[sinead-bovell-job-market]]
- [[ai-job-apocalypse-klein]]
- [[ai-economics-scan-2026]]
- [[nyt-teens-trade-classes]]
