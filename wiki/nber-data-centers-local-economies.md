# Data Centers and Local Economies in the Age of AI

**Summary**: A May 2026 NBER working paper using shift-share instrumental variables to causally identify how data center construction affects local employment, income, house prices, and electricity prices across 3,100+ US counties from 1995–2020.

**Sources**: `raw/PDF/DATA CENTERS AND LOCAL ECONOMIES IN THE AGE OF AI.pdf`, `raw/misc/Mark Zuckerberg Says America Needs 'Hundreds Of Thousands' Of Skilled Tradespeople As Meta Launches Workforce Academy To Provide 'Free Training'.md`

**Last updated**: 2026-06-14

---

## Overview

*Data Centers and Local Economies in the Age of AI: A Shift-Share Approach* (NBER Working Paper 35194, May 2026) was authored by Fernando E. Alvarez (University of Chicago/NBER), David Argente, Joyce Chow, and Diana Van Patten (Yale/NBER). It is a causal inference study — not a correlational analysis — using two independent instruments to isolate the effect of data center construction on local economic outcomes across more than 3,100 US counties over 25 years.

The paper directly addresses a question with high policy relevance for [[cte-and-ai]]: does the AI infrastructure buildout actually create local jobs, and for whom?

## Research Design

### Why IV Estimation Matters

Data centers are not placed randomly. Companies build them in counties with cheap land, reliable power, proximity to fiber infrastructure, and favorable tax treatment. A naïve comparison of counties with and without data centers would conflate data center effects with pre-existing local advantages.

The authors solve this with **two independent shift-share instruments**:

1. **Fiber proximity × Chinese demand growth**: The negative log distance from each US county to the nearest pre-1995 long-haul fiber node, interacted with the national revenue growth of Chinese data center operators. Counties near pre-existing fiber nodes (placed before the modern AI era) absorb disproportionate demand when global data center investment surges — but the fiber placement predates the AI boom and is independent of recent local conditions.

2. **College share × rest-of-world demand growth**: Each county's 1980 urban college population share, interacted with rest-of-world (ex-China) data center revenue growth. Counties with high 1980 college shares tend to attract data centers due to the educated local labor force — again, a characteristic that predates the AI era and is independent of recent local shocks.

**First-stage F-statistics**: 786–907 across estimation horizons — well above the threshold for strong instruments.

**Sample**: 3,143 US counties, long-difference estimation across 1995–2020 and sub-periods.

## Key Finding 1: Data Centers Raise Local Employment — Construction Leads

Full 25-year IV estimates (Table 4):

| Outcome | IV Effect (1995–2020) |
|---------|----------------------|
| Total employment | **+3.9%** (p<0.01) |
| Data-processing employment | **+29.4%** (p<0.01) |
| Construction employment | **+7.1%** (p<0.01) |
| Business establishments | **+6.2%** (p<0.01) |

**The construction timing pattern** is the most important CTE finding: construction employment is front-loaded, showing the largest early-horizon effects in the years immediately following data center investment. This matches the known capital structure: critical facility infrastructure (power substations, cooling systems, structural shell) comprises roughly 53% of total construction costs. The construction spike is real, substantial, and concentrated in trades — electricians, HVAC technicians, plumbers, structural workers.

Data-processing employment growth (+29.4%) is persistent but modest in absolute terms — less than 1% of county total employment. Data centers are capital-intensive, not labor-intensive, in their permanent operations.

The employment gains are the result of **multiplier effects**, not just direct hiring: more income in the county → more local spending → more businesses → more employment across service and retail sectors.

## Key Finding 2: Income Rises — But Unevenly

Income results (Table 5, 1995–2020):

| Outcome | IV Effect |
|---------|-----------|
| Adjusted gross income | **+8.2%** (p<0.01) |
| Wages | **+5.9%** (p<0.01) |
| Tax returns filed | **+5.9%** (p<0.01) |
| Annual payroll | Not significant at longer horizons |

The wage and income gains confirm that data centers produce real household economic improvement at the county level — not merely gross output effects. The gap between wages (+5.9%) and payroll (insignificant) suggests the gains are distributed across a broader population rather than concentrated in a small number of high-salary hires.

## Key Finding 3: Two Equity Costs — Electricity and Housing

The paper's most policy-relevant findings for equity are on the **cost side**:

**Electricity prices rise +0.9%** (p<0.01) for all county residents. Data centers are among the most electricity-intensive facilities in the American economy. US data center electricity consumption jumped from 58 TWh (2014) to 176 TWh (2023) — 4.4% of national electricity consumption. At the county level, this demand increase translates into higher prices for everyone: households, small businesses, schools, and manufacturers. The cost is broadly shared while the income gains accrue primarily to workers with the skills data centers need.

**House prices rise +17.7%** (p<0.01). Data center investment raises land values in host counties. Rising property values benefit homeowners and landowners — they are a loss for renters and prospective buyers. Low-income residents, who are disproportionately renters, absorb the displacement pressure while capturing little of the income gain.

The equity concern is structural: the benefits (construction wages, multiplier income) flow to workers with CTE-aligned skills in the short run and to knowledge workers in the long run; the costs (electricity, housing) fall on all county residents regardless of skill level. This is not an argument against data centers — but it is a reason not to treat the local employment boom as a straightforward community benefit without attending to distributional effects.

## Key Finding 4: Geographic Concentration

Data centers are not evenly distributed across the United States:

- Only **7.6% of US counties** had any data center presence by 2020
- **Virginia** (Northern Virginia in particular — home to the world's largest data center cluster) and **Texas** dominate
- The geographic concentration means that most counties will not directly receive construction employment booms; the AI infrastructure opportunity is geographically targeted

This has implications for how [[cte-and-ai]] programs are designed. CTE programs in high-concentration states and regions can treat data center construction as a durable employment pipeline with strong causal evidence behind it. Programs outside those corridors face a different strategic calculation.

## Robustness and Limitations

**What holds with state fixed effects**: Data-processing employment growth, business establishment growth, and house price increases are robust to adding state fixed effects — confirming these are local rather than regional phenomena.

**What is not robust to state fixed effects**: Total employment, construction employment, and electricity prices — these effects may be more regional in character, or the state-level variation is absorbing identifying variation.

**External validity note**: The 1995–2020 period precedes the most recent AI-driven data center acceleration (the post-2022 buildout following ChatGPT). The observed effects are likely lower bounds on what current expansion will produce, both in scale and in the construction intensity of the specific facilities being built.

## The Meta Texas Case: A Named 2026 Example

The Meta Workforce Academy announcement ([[meta-workforce-academy]], June 2026) provides a named, current illustration of this paper's central temporal finding:

> "Meta's Texas data center project is expected to employ more than 1,800 workers during peak construction but create around 100 operational roles after completion." (source: Mark Zuckerberg Says America Needs...md)

The construction-to-permanent ratio (roughly 18:1) maps almost exactly to the NBER paper's causal finding that construction employment gains are front-loaded and that data-processing employment — while persistent — is small as a share of total county employment. Meta's concurrent commitment of $115 million for free trades training (America's Workforce Academy) and Zuckerberg's explicit statement that "America is going to need hundreds of thousands of skilled tradespeople" confirm the demand-side reality this paper identifies from the supply side. Together they constitute the most complete current picture of the AI infrastructure → CTE labor demand chain: causal IV estimation for the employment mechanism (NBER) + named company commitment to training supply (Meta). (source: Mark Zuckerberg Says America Needs...md)

---

## Implications for the NBER Paper's Wiki Contribution

This paper provides three things the wiki previously lacked:

1. **Causal identification** for the AI infrastructure jobs claim. The claim in [[cte-and-ai]] that "data centers require electricians, HVAC technicians, plumbers, and construction workers — core CTE pipelines" was previously supported only by descriptive labor market analysis. This paper provides IV-estimated causal evidence at the county level.

2. **A temporal structure**: the construction boom is front-loaded; the data-processing employment gain is persistent but small. CTE programs should expect the near-term infrastructure opportunity (5–10 years) to be trade-heavy, with knowledge-work opportunities accruing over a longer horizon.

3. **An equity dimension**: electricity and housing costs are new additions to this wiki's equity analysis. The standard equity framing in [[labor-market-polarization]] focuses on who gets the income gains; this paper quantifies costs that fall broadly, including on the communities CTE serves.

## Related pages

- [[cte-and-ai]]
- [[labor-market-polarization]]
- [[meta-workforce-academy]]
- [[relational-economy]]
- [[bcg-ai-reshapes-jobs]]
- [[ai-labor-disruption-segments]]
- [[anthropic-labor-market-index]]
- [[transferable-skills]]
