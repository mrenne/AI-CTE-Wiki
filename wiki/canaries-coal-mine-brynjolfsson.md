# Canaries in the Coal Mine? Six Facts about the Recent Employment Effects of Artificial Intelligence

**Summary**: A November 2025 Stanford/NBER working paper by Erik Brynjolfsson, Bharat Chandar, and Ruyu Chen using high-frequency ADP payroll data on 3.5–5 million workers per month to document six facts about AI's labor-market effects: early-career workers (22–25) in AI-exposed occupations show a 16% relative employment decline, concentrated in occupations where AI automates rather than augments work, robust across a wide range of alternative explanations including work-from-home amenability.

**Sources**: `raw/PDF/CanariesintheCoalMine_Nov25.pdf` (Brynjolfsson, Chandar & Chen, Stanford Digital Economy Lab / NBER, November 13, 2025)

**Last updated**: 2026-07-09

---

## Overview

This is the academic working paper underlying the "Canaries Dashboard" already summarized in the wiki via [[stanford-del-ai-economic-indicators]] (sourced from a later, June 2026 Stanford DEL research note by the same lead author, Brynjolfsson). This paper is earlier, more methodologically detailed, and uses a larger, more rigorously validated sample — it is the primary research this wiki's existing Canaries Dashboard coverage is built on top of. (source: CanariesintheCoalMine_Nov25.pdf)

The paper uses monthly individual-level payroll records from ADP, the largest US payroll processor, covering millions of workers across tens of thousands of firms through September 2025 — a dataset the authors argue has far greater granularity and immediacy than the Current Population Survey (CPS), which includes only 250–350 workers aged 22–25 per month in comparable occupations, versus 250,000–350,000 in the ADP sample.

## The Six Facts

### Fact 1: Employment for young workers has declined in AI-exposed occupations

Software developers and customer service representatives — both highly AI-exposed — show a consistent pattern: employment for workers aged 22–25 declines considerably after 2022, while other age groups continue growing. By September 2025, employment for software developers aged 22–25 had declined nearly 20% from its late-2022 peak. In sharp contrast, **health aides** (nursing, psychiatric, and home health aides) — a low-AI-exposure occupation — show employment for young workers growing *faster* than for older workers. (source: CanariesintheCoalMine_Nov25.pdf)

### Fact 2: Overall employment grows robustly, but growth for young workers has stagnated

For the three lowest AI-exposure quintiles, employment growth from late 2022 to September 2025 was 5–13% across all age groups, with no clear age ordering. For the two highest exposure quintiles, workers aged 22–25 saw a 6% employment *decline* over the same period, while workers aged 35–49 in the identical occupations grew over 8%. Declining employment in AI-exposed jobs is what's driving the overall stagnation in youth employment growth.

### Fact 3: The decline is concentrated in automating AI use, not augmenting use

Using the Anthropic Economic Index (Handa et al. 2025), which classifies Claude conversations by task as "automative" (Directive, Feedback Loop — AI completing tasks with minimal human involvement) or "augmentative" (Task Iteration, Learning, Validation — AI enhancing human collaboration), the authors find employment declines for young workers concentrated in occupations with high automative AI usage. Occupations with high augmentative usage show *no* such pattern — the highest-augmentation quintile has among the *fastest* employment growth for young workers. This is the paper's central mechanism-level finding: **it is not AI exposure per se that predicts employment decline, but whether AI use in an occupation is substituting for or complementing labor.**

### Fact 4: The decline survives controlling for firm-level shocks

A Poisson event-study regression controlling for firm-time fixed effects (absorbing shocks like interest-rate changes that hit all workers at a firm) finds a **15 log-point decline in relative employment** for the most AI-exposed quintile among 22–25 year-olds — comparable in magnitude to the raw-data estimate and statistically significant. Estimates for every other age group are much smaller and not statistically significant. This rules out the possibility that AI-exposed young workers simply happen to work disproportionately at firms hit by unrelated economic shocks.

### Fact 5: Adjustment shows up in employment, not compensation

Annual base compensation (deflated to 2017 dollars) shows little divergence by age or AI-exposure quintile — in contrast to the sharp divergence in headcount. The authors interpret this as consistent with short-run wage stickiness: firms are adjusting headcount rather than pay in response to AI-driven productivity or substitution effects, at least so far.

### Fact 6: The findings are robust across numerous alternative specifications

- **Excluding technology occupations and technology-sector firms entirely**: results are quite similar — the pattern is not specific to tech roles.
- **Restricting to non-teleworkable occupations** (bank tellers, travel agents, tax preparers): the AI-exposure pattern *still holds*, arguing against outsourcing or remote-work disruption as the primary driver. This is discussed further below as a direct complication for the wiki's existing WFH-attribution thread.
- **Extending the sample back to 2018**: the AI-exposure-ordered pattern is specific to the post-ChatGPT period (late 2022 onward) and does *not* appear before 2022, including during the COVID-19 unemployment spike — a placebo test against the "young workers always get hit hardest in downturns" alternative explanation.
- **Splitting by college share**: the pattern holds in both high-college-share and low-college-share occupations, arguing against a "COVID-era education quality decline" explanation. Critically, for **low-college-share occupations, the AI-exposure divergence persists up to age 40** — not just 22–25 — suggesting experience buffers non-college workers *less* than college-educated workers against AI-driven labor market disruption.
- **Occupational interest-rate exposure**: AI exposure and interest-rate exposure are actually *negatively* correlated (construction has high interest-rate exposure and low AI exposure), and results hold separately for above- and below-median interest-rate-exposure occupations.
- **Gender, unbalanced firm samples, and inclusion of part-time/temporary workers**: results are consistent across all these alternative constructions.

## The Proposed Mechanism: Codified vs. Tacit Knowledge

The authors offer a theoretical explanation grounded in Acemoglu & Autor (2011): AI disproportionately substitutes for **codified knowledge** — the "book-learning" of formal education and knowledge that can be digitized and standardized — while it is less capable of replacing **tacit knowledge**, the idiosyncratic experience-based judgment that accumulates over a career but is never fully documented. Young workers supply relatively more codified knowledge and less tacit knowledge than experienced workers, so they face greater task replacement in AI-exposed occupations. The authors summarize: "AI may be automating the codifiable, checkable tasks that historically justified entry-level headcount, while complementing the judgment-, client-, and process-intensive tasks performed by experienced workers." Contributing mechanisms: AI may raise experienced workers' effective span of control (increased leverage), and reduced junior hiring may simply be firms' lowest-friction adjustment margin compared to displacing incumbents. (source: CanariesintheCoalMine_Nov25.pdf)

## A Direct Complication for the Broken Ladder's WFH-Attribution Thesis

This is the most important cross-reference for the wiki: [[broken-ladder]] (Lambert & Schindler, May 2026) argues that work-from-home exposure, not GenAI exposure, is the more robust predictor of the junior-hiring decline, because WFH and GenAI exposure correlate at 0.77 across occupations and the GenAI coefficient attenuates to near-zero in joint-treatment designs.

This paper's robustness check restricting to **non-teleworkable occupations** — bank tellers, travel agents, tax preparers — finds the AI-exposure employment-decline pattern **still holds** even among jobs that cannot be done remotely at all. If the effect were purely a WFH/remote-work organizational artifact, it should disappear in occupations where remote work isn't even an option. Its persistence in non-teleworkable settings is direct empirical evidence *for* an AI-specific mechanism, independent of the WFH channel Lambert & Schindler emphasize.

The two papers are not strictly contradictory — Lambert & Schindler's joint-treatment DiD uses a different design (total exposure measures, different country sample, different time window) than this paper's non-teleworkable subsample check — but they reach different conclusions about how much of the effect survives once WFH is accounted for. Per the wiki's citation rule to flag disagreement explicitly: **this is an open empirical debate, not a resolved one**, and both papers should be read as competing evidence rather than one superseding the other.

## Relationship to the Wiki's Existing Evidence Base

| Finding | Connects to |
|---|---|
| Same research program, earlier/deeper version | [[stanford-del-ai-economic-indicators]] (Canaries Dashboard, June 2026 research note) |
| Automation vs. augmentation as the decisive mechanism | [[stanford-del-ai-economic-indicators]] (identical finding, same distinction) |
| Health aides growing fastest for young workers | [[relational-economy]] (direct occupation-level confirmation of the relational-sector growth thesis) |
| 16% relative employment decline, 22-25 | [[anthropic-labor-market-index]] (14% hiring-rate decline for 22-25 in exposed occupations — a related but distinct measure from a different dataset) |
| Non-teleworkable robustness check complicates WFH attribution | [[broken-ladder]] (direct empirical tension, flagged above) |
| Codified vs. tacit knowledge mechanism | [[transferable-skills]] (new theoretical grounding for why experience-based judgment resists AI substitution) |
| Experience buffers non-college workers less (divergence to age 40) | [[labor-market-polarization]] (new equity dimension not previously in the wiki) |
| Amodei's 50%-of-entry-level-jobs prediction cited as context | [[ai-economy-measurement-2026]] (measurement-uncertainty theme — this paper is itself an attempt to resolve exactly the kind of measurement dispute that source describes) |

## Limitations (Per the Authors)

The authors are explicit that ADP's firm composition doesn't exactly match the broader US economy (skews toward larger, faster-growing firms; somewhat overrepresents the Northeast and manufacturing/services). They caution their results "may in part be influenced by factors other than generative AI" despite the extensive robustness checks, and note that a comparison to CPS data shows the CPS is too noisy (small sample sizes in fine age-occupation cells) to serve as an independent check at this granularity — future work should compare against the American Community Survey once released. The paper commits to ongoing monthly tracking to assess whether the documented trends continue or reverse.

## Implications for CTE

1. **The automation/augmentation distinction is the single most actionable operational finding for CTE program design in the wiki's entire labor-market evidence base.** If augmentative AI use in an occupation shows no youth-employment penalty (and sometimes growth), CTE programs should explicitly teach students to use AI in task-iteration, learning, and validation modes — not directive, single-shot automation modes — both because it appears to be what protects entry-level employment and because it is the mode most consistent with the wiki's learning-theory findings ([[agentivism]], [[building-ai-companions]]).
2. **Health aides' faster youth employment growth is a concrete, occupation-level data point supporting CTE's Healthcare & Human Services pathway** at a moment when other CTE evidence (e.g., [[fostering-ai-ready-caring-communities]]) had flagged that cluster grouping as the *most* AI-exposed of the four studied. The tension is real: high aggregate AI exposure in healthcare does not preclude specific high-relational-content roles like home health aides from being youth-employment growth areas.
3. **The codified/tacit knowledge mechanism gives CTE's apprenticeship and hands-on-training model a specific defense.** If AI substitutes for codified book-learning but not experience-accumulated tacit knowledge, then CTE pathways emphasizing supervised practical experience — not just credentialed classroom knowledge — may be structurally better positioned than knowledge-work pathways that rely primarily on codifiable expertise.
4. **The non-college-worker finding (divergence persisting to age 40) is a genuine equity warning** that complicates any assumption that CTE graduates automatically "age out" of AI exposure risk the way college-track workers seem to. This should temper optimism in pages like [[cte-and-ai]] that rely on the general "experience protects workers" pattern without noting it may be weaker for non-college pathways specifically.

## Related pages

- [[stanford-del-ai-economic-indicators]]
- [[anthropic-labor-market-index]]
- [[broken-ladder]]
- [[labor-market-polarization]]
- [[relational-economy]]
- [[transferable-skills]]
- [[cte-and-ai]]
- [[ai-economy-measurement-2026]]
- [[fostering-ai-ready-caring-communities]]
