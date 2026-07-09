# Anthropic Labor Market Index

**Summary**: An Anthropic research report (Massenkoff & McCrory, 2026) introducing *observed exposure* — a new metric combining theoretical LLM capability with actual Claude usage data — and finding no detectable unemployment impact so far, but suggestive evidence that hiring of young workers into AI-exposed occupations has slowed by 14%.

**Sources**: `raw/misc/Labor market impacts of AI A new measure and early evidence.md`, `raw/PDF/AIEI_RN01_Jun26.pdf`, `raw/PDF/CanariesintheCoalMine_Nov25.pdf`

**Last updated**: 2026-07-09

---

## Overview

*Labor market impacts of AI: A new measure and early evidence* is an Anthropic research report by Maxim Massenkoff and Peter McCrory (published March 2026, with a correction on March 8, 2026). It builds on the **Anthropic Economic Index** — Anthropic's ongoing series measuring how Claude is actually used in professional settings — to create a new occupational exposure metric and test it against early labor market data.

The report is positioned explicitly as a longitudinal monitoring project: the authors intend to update both the methodology and findings as new data emerges, rather than making definitive claims from an initial snapshot.

## The Core Innovation: Observed Exposure

Prior approaches to measuring AI's labor market impact relied primarily on *theoretical capability* — most influentially, the β metric from **Eloundou et al. (2023)**, which scores each O\*NET task as:
- **β = 1**: Task can be doubled in speed by an LLM alone
- **β = 0.5**: Task can be doubled in speed by an LLM with additional tools
- **β = 0**: Task cannot be sped up by 50%+

The problem: theoretical feasibility doesn't tell you what's actually happening. The Massenkoff & McCrory paper combines three data sources to build *observed exposure*:

1. **O\*NET database**: ~800 occupations with task-level descriptions
2. **Anthropic Economic Index**: real Claude usage data from professional contexts (August and November 2025)
3. **Eloundou et al. β scores**: the theoretical capability baseline

A task earns observed exposure if it is:
- Theoretically feasible (β > 0 from Eloundou et al.)
- Observed in work-related Claude usage at sufficient frequency
- Weighted more heavily if the usage pattern is **automated** (API/agentic) rather than **augmentative** (user-directed)

The result is a measure that captures where AI is *actually penetrating* professional work, not just where it theoretically could. Crucially: **97% of observed Claude tasks fall into theoretically feasible categories (β ≥ 0.5)**, confirming that usage and capability are highly correlated — but actual coverage is still a fraction of theoretical potential.

## Most Exposed Occupations

The top occupations by observed exposure:

1. **Computer Programmers** — 75% task coverage (consistent with Claude's heavy coding use)
2. **Customer Service Representatives** — high first-party API usage automating their core tasks
3. **Data Entry Keyers** — 67% coverage; primary task of reading and entering source data sees significant automation
4. **Financial Analysts** — extensive information processing and analytical tasks

At the other end, **30% of workers have zero observed exposure** — their tasks appear too infrequently in Claude usage data to meet the minimum threshold. This group includes Cooks, Motorcycle Mechanics, Lifeguards, Bartenders, and Dishwashers. Physical, in-person, and dexterous tasks remain effectively unexposed.

The occupational category data shows that while Computer & Math occupations have theoretical feasibility for 94% of tasks, observed exposure (actual Claude usage) covers only **33% of those tasks** — illustrating the persistent gap between what AI can do and what it is currently doing.

## Validation: BLS Projections

The report compares observed exposure to independent BLS employment projections (2024–2034). The finding: **for every 10 percentage point increase in observed exposure, BLS growth projections fall by 0.6 percentage points**. This is a modest but meaningful correlation — and notably, *the correlation does not appear when using Eloundou et al.'s β alone*. Only the observed, usage-grounded measure tracks with professional labor market forecasters' independent predictions.

## The Equity Inversion

One of the most counterintuitive findings concerns the demographics of highly exposed workers. Looking at pre-ChatGPT baseline data (August–October 2022), workers in the **top quartile of exposure** versus those with **zero exposure** differ sharply:

| Characteristic | Zero exposure | Top quartile exposed |
|---------------|--------------|---------------------|
| Female | baseline | +16 percentage points |
| White | baseline | +11 percentage points |
| Asian | baseline | ~2× more likely |
| Average earnings | baseline | +47% higher |
| Graduate degree | 4.5% | 17.4% (4× more likely) |

The most AI-exposed workers are **older, better-educated, higher-paid, and disproportionately female and Asian** — precisely the opposite of the typical "AI threatens low-skill workers" narrative, and also the opposite of who bore the brunt of COVID-era displacement (lower-paid, in-person workers).

This pattern reflects which tasks currently appear in Claude's professional usage: cognitive, knowledge-intensive, information-processing work. AI is first reaching white-collar professional work, not manual or service work. See [[labor-market-polarization]] and [[cte-and-ai]] for the implications of this inversion.

## Employment Impact: No Signal Yet (With One Exception)

The paper's main labor market analysis compares unemployment trends for workers in the top quartile of exposure versus zero-exposure workers, using the Current Population Survey (CPS) from 2016 to present.

**Main finding: no detectable unemployment impact.** The difference-in-differences estimate for changes since ChatGPT's release is small and statistically insignificant. The authors note their framework could detect a differential increase of approximately 1 percentage point — so the absence of a signal rules out a "Great Recession for white-collar workers" scenario (which would require unemployment doubling from 3% to 6% in exposed occupations).

**The one exception: young worker hiring slowdown.** The paper finds tentative evidence that the hiring rate of workers aged 22–25 *into exposed occupations* has declined:

> "The averaged estimate in the post-ChatGPT era is a **14% drop in the job finding rate** compared to that in 2022 in the exposed occupations, although this is just barely statistically significant."

This echoes a parallel finding from Brynjolfsson et al. (2025), who found a 6–16% fall in employment in exposed occupations among workers aged 22–25, attributed primarily to slowed hiring rather than layoffs. The mechanism: young workers who aren't hired may not appear in unemployment statistics if they remain in school, take different jobs, or exit the labor force — making the impact visible in hiring data but not CPS unemployment counts.

(There is no such decrease for workers older than 25.)

## Methodological Honesty

The paper is unusually candid about its limitations and the difficulty of causal inference in this domain:

- The introduction acknowledges the track record of past exposure measures: a prominent offshorability study identified ~25% of US jobs as vulnerable, but "a decade on, most of those jobs maintained healthy employment growth"
- AI's effects "might be less like COVID and more like the internet or trade with China" — slow, diffuse, and confounded by other economic forces
- The Eloundou et al. β scores reflect LLM capabilities as of early 2023 and may not capture current model capabilities
- The young worker hiring finding is described as "just barely statistically significant" and may reflect alternative explanations (tariffs, immigration policy, general economic uncertainty)
- The report covers only Claude usage; it does not capture ChatGPT, Gemini, or other AI system penetration

## Implications for Education and CTE

The report's findings have several implications for how AI's labor market effects should be communicated in educational and workforce contexts:

1. **The threat profile is inverted from common assumptions.** Students entering high-paying, knowledge-intensive fields — not low-skill service work — face the most immediate AI exposure. This is relevant for [[cte-and-ai]] planning, where AI's threat to trades and hands-on work may be overstated near-term.

2. **Young workers are the canary.** The 14% hiring slowdown for entry-level workers in exposed occupations suggests that AI's first visible labor market impact may be suppressing entry-level professional job formation — precisely where recent graduates would enter. The Harvard parallel finding (from [[ai-economics-scan-2026]]) reinforces this: "a pronounced decline in junior employment, while senior employment remains unchanged."

3. **The theory-practice gap is large and informative.** Only 33% of theoretically feasible Computer & Math tasks are currently observed in actual Claude usage. This gap represents where diffusion, legal constraints, and workflow integration have not yet occurred — and where future exposure growth is most likely.

4. **Monitoring requires ongoing measurement.** The Anthropic Economic Index approach — periodically measuring actual usage and mapping it to occupations — is more informative than static theoretical capability assessments. As AI capabilities and adoption evolve, exposure rankings will shift.

## Methodological Caveat: The WFH Confound

Lambert & Schindler ([[broken-ladder]], May 2026) raise a first-order challenge to the attribution of young-worker hiring declines to GenAI — one that directly applies to this paper's 14% finding.

Their core observation: **WFH exposure and GenAI exposure have a Spearman rank correlation of 0.77 across O\*NET occupations.** The same occupations hit hardest by GenAI (software developers, management consultants, financial analysts) are also the most remote-capable. Single-treatment designs that estimate GenAI exposure alone will pick up WFH effects as a confound.

In their joint-treatment difference-in-differences across 243 million hires and 407 million job postings (US, UK, Canada, Australia, 2017–2025): when WFH and GenAI exposure enter simultaneously, the WFH coefficient is stable and significant; the GenAI coefficient attenuates heavily and is often statistically indistinguishable from zero. Using actual WFH adoption (not just exposure) produces the same result. Multiple robustness exercises — non-parametric co-treatment controls, selection-on-unobservables diagnostics, Monte Carlo measurement-error simulations — preserve the WFH-dominant pattern.

The Massenkoff & McCrory paper uses a different design (unemployment stocks via CPS, not junior hire shares via résumé data) and a different measure (observed Claude exposure, not theoretical Eloundou exposure), so the two papers are not directly testing the same specification. But the WFH confound is a genuine concern for any design that uses occupational exposure variation to attribute effects to AI. The authors themselves note that their young-worker hiring finding is "just barely statistically significant" and may reflect "alternative explanations (tariffs, immigration policy, general economic uncertainty)" — WFH adoption is the most structurally motivated of those alternatives.

**Working synthesis**: The early-career hiring slowdown is empirically real and documented in multiple data sources. Whether WFH or GenAI (or both) is the primary driver remains actively contested. The Lambert & Schindler finding is cause for optimism — WFH's organizational frictions around junior development are surmountable through better management practice, whereas a GenAI-driven effect would require more structural policy remedies. (source: The Broken Ladder.pdf)

## The Canaries Dashboard: Corroboration and a Mechanism-Level Extension

Stanford Digital Economy Lab's Canaries Dashboard (Brynjolfsson et al., June 2026) provides the most current and largest-sample corroboration of this paper's early-career finding — 4.6 million workers in a live ADP payroll panel — while adding a critical mechanism-level insight this paper's design cannot produce. See [[stanford-del-ai-economic-indicators]] for the full treatment.

**Corroboration**: Early-career (22–25) workers in the most AI-exposed occupations are contracting at −3.8%/year since ChatGPT, while the least-exposed are growing at +2.0%/year. The pattern is directionally consistent with this paper's 14% job-finding-rate slowdown and with the Brynjolfsson/Chandar/Chen parallel finding. The live 2026 ADP data confirm the signal has not reversed.

**The mechanism extension**: The Canaries Dashboard decomposes AI usage at the occupation level using the Anthropic Economic Index (the same source underlying this paper's observed-exposure measure). The finding: occupations with higher **automation**-type AI usage show a clear negative correlation with early-career employment; occupations with higher **augmentation**-type usage show **no relationship**. This is the mechanism the observed-exposure measure cannot distinguish — it matters not just which occupations AI touches, but whether AI is replacing workers' tasks or assisting workers who remain in the loop.

This finding also provides a partial response to the [[broken-ladder]] WFH confound concern: Lambert & Schindler's critique applies to total exposure measures that conflate automation and augmentation. The automation/augmentation decomposition is a different analytical handle that the WFH confound argument does not directly address. (source: AIEI_RN01_Jun26.pdf)

**The underlying academic paper**: [[canaries-coal-mine-brynjolfsson]] (Brynjolfsson, Chandar & Chen, November 2025) is the working paper the Canaries Dashboard research note above is built on. It reports a directly comparable but distinct figure — a **16% relative employment decline** for 22-25 year-olds in the most AI-exposed occupations (versus this page's 14% hiring-rate slowdown) — using a firm-time fixed-effects design on ADP payroll data rather than this paper's Claude-usage-based observed-exposure measure. The two studies use different datasets, different outcome variables (hiring rate vs. headcount), and different methodologies, yet converge on the same early-career-specific pattern — a meaningful cross-validation from largely independent data sources.

## Related pages

- [[labor-market-polarization]]
- [[cte-and-ai]]
- [[ai-economics-scan-2026]]
- [[ai-in-k12-education]]
- [[transferable-skills]]
- [[bcg-ai-reshapes-jobs]]
- [[ai-labor-disruption-segments]]
- [[broken-ladder]]
- [[stanford-del-ai-economic-indicators]]
- [[canaries-coal-mine-brynjolfsson]]
