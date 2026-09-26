# How Does AI Change Labor Demand? Evidence from 41 Countries

**Summary**: A September 2026 working paper (Chandar & Klein Teeselink, Stanford/King's College London) that measures actual company AI adoption from 1.25 billion job postings and 154 million employment records across 41 countries. Adopting firms shift their workforce from juniors to seniors: the junior share falls 1.9 points, driven mainly by 6.7% senior growth rather than junior cuts. The shift appears in 23 of 31 countries, with no significant fall in total employment anywhere. AI so far *recomposes* workforces more than it *resizes* them.

**Sources**: `raw/PDF/HowDoesAIChangeLaborDemand.pdf`

**Last updated**: 2026-09-26

---

## About this source

Working paper by Bharat Chandar (Stanford University) and Bouke Klein Teeselink (King's College London / AI Objectives Institute), dated September 20, 2026 (source: HowDoesAIChangeLaborDemand.pdf). Chandar is a co-author of [[canaries-coal-mine-brynjolfsson]], so this paper is not fully independent of the Stanford Digital Economy Lab group, though it uses a different dataset and a different design.

**What makes it different.** Most labor-market sources in the wiki rank occupations by how much AI *could* do (exposure). This paper measures which companies actually **adopted** generative AI, using job ads that involve generative AI, verified by an LLM classifier: 1.36 million postings, 99% of them after ChatGPT's launch. It then compares adopters with similar non-adopters (source: HowDoesAIChangeLaborDemand.pdf). It is the wiki's first adoption-based study, as opposed to exposure-based.

**Data and design** (source: HowDoesAIChangeLaborDemand.pdf):
- Revelio Labs data (the same provider used by [[broken-ladder]]): LinkedIn profiles and job postings, 395,638 affiliates in 41 countries, monthly from January 2021 to March 2026.
- The estimation sample is 100,813 **foreign affiliates** of multinationals, meaning a company's operations in a country other than its parent's home country.
- Each adopting affiliate is matched to up to five non-adopters in the same country and sector, on size, AI exposure, and junior share.
- **Instrument**: adoption is predicted by the AI adoption rate among *other* multinational parents headquartered in the same metropolitan area as the affiliate's parent. The idea is that AI spreads through corporate networks, from neighbors of the headquarters to its affiliates abroad. The first stage is strong (F = 104).
- Treatment is dated from ChatGPT's launch in November 2022.

---

## The model: three forces, and why studies disagree

The authors' task-based model splits the effect of AI adoption on a group of workers into three forces (source: HowDoesAIChangeLaborDemand.pdf):
1. **Labor saving.** AI takes over tasks the group used to do, lowering demand for them.
2. **Labor expanding.** AI creates new tasks, such as AI auditing, prompt engineering, and workflow design, raising demand.
3. **Scale effect.** Lower costs let the firm grow, raising demand for *all* workers, including groups whose tasks AI took.

**Key theoretical result:** a comparison of adopters with non-adopters measures something different from economy-wide employment change, and **the two can have opposite signs**. Adopters can grow relative to non-adopters by taking market share, even while aggregate employment falls (source: HowDoesAIChangeLaborDemand.pdf). This gives the wiki a framework for why adoption-based studies (often null or positive for employment) and exposure-based studies (often negative for juniors) seem to conflict. See [[ai-economy-measurement-2026]].

---

## Main findings (pooled across 41 countries, March 2026)

| Outcome at adopting affiliates vs. matched controls | Effect |
|---|---|
| Junior share of employment | **−1.9 percentage points** (3.3% of the baseline 57% junior share) |
| Senior employment | **+6.7%** |
| Junior employment | −2.5% (not statistically significant) |
| Total employment | +3.3% (marginally significant) |
| Seniors in most- vs. least-exposed occupations | +5% shift *toward* exposed work |
| Juniors in most- vs. least-exposed occupations | −2% shift *away* from exposed work (not significant) |

(source: HowDoesAIChangeLaborDemand.pdf)

For the average matched adopting affiliate, with about 255 positions of which 145 are junior, this means roughly 8 more seniors than it would otherwise have had by March 2026 (source: HowDoesAIChangeLaborDemand.pdf).

**The timing differs by seniority.** Junior employment dropped quickly after ChatGPT (−2.9% within a year, imprecise) and then held steady. Senior employment barely moved for 18 months and then climbed steadily. Until mid-2024 the two offset each other, so "the workforce is recomposed rather than resized" (source: HowDoesAIChangeLaborDemand.pdf).

**Occupations barely change; seniority within them does.** In 21 of 22 occupation groups, the change in employment share is under half a point. The exception is computer and mathematical occupations, the most AI-exposed group, which *grew* 0.8 points, so AI is labor expanding for them. But the junior share *within* occupations fell in 16 of 22 groups, significantly in (source: HowDoesAIChangeLaborDemand.pdf):
- legal: −4.9 points
- computer and mathematical: −3.3 points
- business and financial operations: −3.2 points
- sales: −2.6 points
- management: −1.0 points

The authors' summary: generative AI has so far been "labor saving for junior workers and labor expanding for senior workers and for workers in computer and mathematical occupations" (source: HowDoesAIChangeLaborDemand.pdf).

---

## Across countries

Estimated separately for the 31 countries with a strong enough instrument, the junior share fell in **23 of 31**. It fell significantly in seven very different economies: the United States, United Kingdom, Spain, Poland, Brazil, Mexico, and Saudi Arabia. The meta-analytic mean is −1.1 points. Senior employment rose 3.4% on average. **No country showed a significant decline in total employment**, and Sweden and Spain showed significant gains (source: HowDoesAIChangeLaborDemand.pdf).

Junior losses run somewhat deeper in richer and more digitized economies and shallower where labor regulation is more rigid, but most of these correlations are not statistically significant. The authors conclude the recomposition "is not just a rich-country phenomenon" (source: HowDoesAIChangeLaborDemand.pdf). This extends [[goldman-sachs-ai-labor-squeeze]]'s cross-country evidence from six developed economies to 41 countries, including middle-income ones.

---

## Where the effect concentrates

- **Exposure drives it.** Affiliates above median baseline AI exposure account for "virtually all" of the recomposition: junior share −3.4 points, senior employment +10.4%, junior employment −6.5%. Below the median, effects are near zero (source: HowDoesAIChangeLaborDemand.pdf).
- **Technology firms show it most, but not only them.** In the information sector the junior share fell 3.9 points and senior employment rose 14.6%. Outside tech the junior share fell 0.9 points and senior employment rose 2.9% (source: HowDoesAIChangeLaborDemand.pdf).
- **It isn't just from hiring AI engineers.** The junior share also falls at companies whose first AI job ad was for a lawyer, manager, or designer (source: HowDoesAIChangeLaborDemand.pdf).

---

## Robustness

The core result holds across many checks (source: HowDoesAIChangeLaborDemand.pdf):
- controlling for local economic booms near headquarters;
- building the instrument from country-and-sector peers rather than metro peers;
- excluding same-sector peers, which rules out plain imitation of organizational practices;
- dropping any of the top ten metro areas;
- a continuous adoption-intensity measure;
- synthetic difference-in-differences with no instrument, which also works on domestic affiliates;
- a placebo launch date of January 2022.

**On the work-from-home debate.** Matching within country and sector on baseline AI exposure also controls for factors that track exposure, which the authors say include "the scope for remote work" (source: HowDoesAIChangeLaborDemand.pdf). The design therefore sidesteps much of the [[broken-ladder]] critique. This is a third approach, alongside the direct replications in [[canaries-coal-mine-brynjolfsson]] and [[graduating-into-disruption-census]], that finds an AI-linked junior shift. It uses the same Revelio data source that Lambert & Schindler used.

**One timing puzzle.** Some effects appear within a year of ChatGPT, although many companies post their first AI job only in 2024–2025. Among cleaner cohorts, the response follows adoption timing. The 2025 cohort's response precedes its first ad, but that estimate has a weak instrument and pre-trends, and the authors treat it as less reliable (source: HowDoesAIChangeLaborDemand.pdf).

---

## Limitations, stated by the authors

- LinkedIn over-represents managers and professionals and **under-represents agriculture, construction, and manual labor**. Coverage is about two-thirds of official employment in the US and UK, a quarter in Brazil and Germany, and 8% in India (source: HowDoesAIChangeLaborDemand.pdf).
- The instrument is imperfect, and the main estimates come from multinationals' foreign affiliates, which are larger than average.
- Firms that use AI without advertising AI jobs count as non-adopters, which likely biases estimates **toward zero**.
- Just over three years of post-period data: "the initial reorganization," not the long-run equilibrium.
- Firm-level gains need not mean aggregate gains.

---

## Relationship to the wiki's evidence base

| This paper finds | Relationship |
|---|---|
| Junior *share* falls mainly through senior growth, not junior cuts | Refines [[entry-level-labor-market]]'s "narrowing bottom rung": a top-loaded ladder, not only a cut bottom rung |
| No significant total-employment fall in any country | Consistent with [[canaries-coal-mine-brynjolfsson]] Fact 1 and [[cesifo-recent-grads-unemployment]] |
| Adopter comparisons can differ in sign from aggregate effects | A framework for the data conflicts in [[ai-economy-measurement-2026]] |
| Junior shift within computer/math occupations | Consistent with CS majors being hit hardest ([[graduating-into-disruption-census]]) |
| Senior demand shifts *toward* AI-exposed work | Echoes the codified-vs-tacit mechanism ([[canaries-coal-mine-brynjolfsson]]) and BCG's "Divergent" roles ([[bcg-ai-reshapes-jobs]]) |
| 41 countries, including middle-income | Extends [[goldman-sachs-ai-labor-squeeze]] |

---

## Implications for CTE

1. **The pipeline problem is about who firms train, not only who they hire.** The authors warn the shift "may have implications for the pipeline of experienced workers that firms will draw on in the future," and note calls to "build other routes into skilled work" (source: HowDoesAIChangeLaborDemand.pdf). Work-based learning and apprenticeships are exactly such routes (see [[entry-level-labor-market]]).
2. **Experience is becoming more valuable relative to credentials.** If seniors gain from AI adoption while juniors don't, programs that give students real, verifiable work experience before graduation (internships, co-ops, [[quanthub-data-scholars-2026-update]]-style placements) narrow the gap that matters.
3. **This paper cannot speak to the trades.** Its LinkedIn data under-represents construction and manual work, so it neither confirms nor challenges the "CTE trades are insulated" thesis. That evidence still comes from exposure-based sources such as [[fostering-ai-ready-building-moving]].
4. **Senior workers moving *toward* AI-exposed work** supports teaching AI as a tool that experienced practitioners direct ([[applied-co-intelligence-model]]). The workers who gain are those with enough domain judgment to use it.

---

## Related pages

- [[entry-level-labor-market]]
- [[canaries-coal-mine-brynjolfsson]]
- [[broken-ladder]]
- [[graduating-into-disruption-census]]
- [[cesifo-recent-grads-unemployment]]
- [[goldman-sachs-ai-labor-squeeze]]
- [[ai-economy-measurement-2026]]
- [[labor-market-polarization]]
- [[bcg-ai-reshapes-jobs]]
- [[cte-and-ai]]
- [[applied-co-intelligence-model]]
- [[fostering-ai-ready-building-moving]]
