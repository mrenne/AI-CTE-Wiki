# Jevons Paradox

**Summary**: Concept page for the idea that when technology makes something cheaper, total demand for it can rise rather than fall. It is the main argument in the wiki for why AI may expand rather than shrink employment in exposed occupations; this page sets out the argument, the evidence for and against it, and why demand expansion does not guarantee jobs for new entrants.

**Sources**: `raw/blog/Why the A.I. Job Apocalypse (Probably) Won’t Happen.md`, `raw/blog/Apocalypse No.md`, `raw/PDF/ai-will-reshape-more-jobs-than-it-replaces.pdf`, `raw/blog/AI, jobs, and the next generation.md`, `raw/misc/AI could displace one in 11 workers, Goldman says, but the layoffs ar….md`, `raw/misc/Goldman studied where AI is squeezing labor markets. Here's what it found.md`, `raw/PDF/HowDoesAIChangeLaborDemand.pdf`, `raw/blog/How employment is changing at Anthropic.md`, `raw/PDF/Gradiating into Disruption.pdf`, `raw/PDF/AIEI_MU_Nov26.pdf`, `raw/misc/College-labor-data.xlsx`

**Last updated**: 2026-11-23

---

## The idea

The Jevons paradox is named for the economist who observed in the 1860s that more efficient steam engines did not reduce coal use. Cheaper coal enabled new uses, and coal demand rose (source: Why the A.I. Job Apocalypse (Probably) Won’t Happen.md). Applied to work: if AI makes a service much cheaper to produce, people may buy so much more of it that employment in that occupation grows.

The examples the wiki's sources use:

- **Spreadsheets and accountants.** After VisiCalc (1979) automated tasks that took accountants days, the number of accountants quadrupled over the next 40 years. Eldar Maksymov (Arizona State): the spreadsheet "unleashed latent demand for financial intelligence" (source: Why the A.I. Job Apocalypse (Probably) Won’t Happen.md; Apocalypse No.md).
- **Computers in general.** "In every major occupational group that adopted computers heavily, employment grew faster than in groups that did not" (Maksymov, via Klein) (source: Why the A.I. Job Apocalypse (Probably) Won’t Happen.md).
- **Microsoft's institutional memory.** Brad Smith: word processing did not eliminate typing jobs, spreadsheets did not reduce financial work, and email increased communication. "When technology increases supply, human ambition often generates more demand" (source: AI, jobs, and the next generation.md; see [[brad-smith-ai-jobs-next-generation]]).
- **Dario Amodei (May 2026).** "If you automate 90% of the job, then everyone does the 10% of the job... And the 10% kind of expands to be 100% of what people do." He added that AI "is moving faster than all these previous technologies," so big disruption remains possible (source: AI could displace one in 11 workers, Goldman says, but the layoffs ar….md; see [[goldman-ai-displacement-cyclical]]).

## BCG's version: demand expandability

[[bcg-ai-reshapes-jobs]] turns the paradox into a test for each occupation: *is there unmet demand that lower costs can unlock?* (source: ai-will-reshape-more-jobs-than-it-replaces.pdf). The answer decides whether two equally automatable jobs move in opposite directions:

- **Expandable demand → Amplified.** Software engineering: AI doubled output per engineer, software got cheaper, businesses bought more, and total headcount rose after ChatGPT.
- **Bounded demand → Substituted.** Call centers: AI cuts the cost per call, but customers do not want many more calls, so headcount contracts.

This is why BCG puts only about 12% of US jobs in the Substituted segment, a far smaller share than the "47% at risk" estimate from Frey and Osborne (2013) (source: ai-will-reshape-more-jobs-than-it-replaces.pdf; see [[ai-labor-disruption-segments]]).

## What the evidence shows

| Evidence | Direction | Source |
|---|---|---|
| Computer and math occupations *grew* 0.8 points at AI-adopting firms in 41 countries; the authors call AI "labor expanding" for them and for senior workers | Supports | HowDoesAIChangeLaborDemand.pdf ([[ai-labor-demand-41-countries]]) |
| Anthropic's technical hiring still grew in absolute terms as output per person rose sharply | Supports, at one firm | How employment is changing at Anthropic.md ([[employment-at-anthropic]]) |
| Call-center employment is 39% below trend in the US, 33% in Canada, 27% in Germany | Supports the bounded-demand prediction | Goldman studied where AI is squeezing labor markets. Here's what it found.md ([[goldman-sachs-ai-labor-squeeze]]) |
| Software publishing employment is below trend across developed markets | ⚠ Complicates the software example | Goldman studied where AI is squeezing labor markets. Here's what it found.md |
| Junior share of technical hires at Anthropic fell from 27% to 9%; computer science graduates saw the largest drops in starting employment and pay | Expansion is not reaching new entrants | How employment is changing at Anthropic.md; Gradiating into Disruption.pdf ([[graduating-into-disruption-census]]) |

### ⚠ The software example is contested

Software engineering is the paradox's showcase case in the wiki, but the sources disagree on what is happening:

- BCG: software engineer headcount rose after ChatGPT (source: ai-will-reshape-more-jobs-than-it-replaces.pdf).
- Goldman: employment in the software publishing *industry* has fallen sharply below trend across developed markets (source: Goldman studied where AI is squeezing labor markets. Here's what it found.md).

These measure different things. BCG counts an occupation, whose workers are spread across every industry; Goldman counts one industry. Both can be true if software engineering jobs are growing outside software publishers. Neither source reconciles them, so the wiki flags the disagreement rather than resolving it.

## What the paradox does not say

1. **It says nothing about who gets the new jobs.** Demand expansion can go entirely to experienced workers. The 41-country study finds AI "labor saving for junior workers and labor expanding for senior workers" (source: HowDoesAIChangeLaborDemand.pdf). Total headcount can rise while the entry point narrows; see [[entry-level-labor-market]]. NY Fed data show the same split for computing majors: computer engineering and computer science have some of the highest recent-graduate unemployment of 73 majors (7.8% and 7.0%) alongside the highest starting pay (source: College-labor-data.xlsx; see [[ny-fed-recent-grads-labor-market]]).
2. **It says nothing about timing.** Accountants quadrupled over 40 years. Goldman finds that technology-driven job losses concentrate in recessions and that routine jobs lost in past shifts did not come back (source: AI could displace one in 11 workers, Goldman says, but the layoffs ar….md). Amodei himself warns AI is moving faster than earlier technologies.
3. **It depends on demand being expandable.** Where demand is bounded, as in call centers, cheaper production means fewer jobs.
4. **It says nothing about how gains are shared.** Galloway's "permanent underclass" scenario needs no mass unemployment, only gains flowing mainly to capital owners and high-skill workers (source: Apocalypse No.md; see [[apocalypse-no-galloway]]). Stanford's dashboard finds capital's share of income among the few macro indicators clearly above trend (source: AIEI_MU_Nov26.pdf; see [[stanford-del-ai-economic-indicators]]).

**Source caveat.** Most statements of the paradox in the wiki come from opinion pieces (Klein, Galloway), a consulting projection (BCG), or executives of AI companies (Smith at Microsoft, Amodei at Anthropic), whose firms benefit from the optimistic reading.

## Related concepts

- **[[relational-economy]]**: the other main optimist mechanism. Jevons expands demand for cheaper services; the relational economy shifts employment toward work where the human is the product.
- **[[labor-market-polarization]]**: the paradox explains why the same automation exposure can produce opposite outcomes.
- **[[hardman-ai-faster-slower]]**: a reason gains may be slower to arrive. Human review stages absorb much of AI's production gain before it becomes finished output.

## Implications for CTE

These are the wiki's inferences, not claims made by the sources.

1. **Ask BCG's question about every program.** For each occupation a CTE program serves: if AI makes this service cheaper, will customers buy more of it? Healthcare, skilled trades, and personal services with unmet demand are better bets than roles where demand is fixed.
2. **Expansion helps those who can get in.** Even in growing occupations, entry-level hiring is where the squeeze shows. Programs should focus on what gets graduates through the door: credentials, work-based learning, and demonstrated skill ([[work-based-learning]]).
3. **Treat Jevons as a possibility, not a promise.** The historical examples played out over decades. Students entering the labor market now face the transition, not the long-run outcome.

## Related pages

- [[bcg-ai-reshapes-jobs]]
- [[ai-labor-disruption-segments]]
- [[ai-job-apocalypse-klein]]
- [[apocalypse-no-galloway]]
- [[brad-smith-ai-jobs-next-generation]]
- [[goldman-ai-displacement-cyclical]]
- [[goldman-sachs-ai-labor-squeeze]]
- [[ai-labor-demand-41-countries]]
- [[employment-at-anthropic]]
- [[graduating-into-disruption-census]]
- [[entry-level-labor-market]]
- [[relational-economy]]
- [[labor-market-polarization]]
- [[hardman-ai-faster-slower]]
- [[stanford-del-ai-economic-indicators]]
- [[work-based-learning]]
- [[cte-and-ai]]
- [[ny-fed-recent-grads-labor-market]]
