# Education-to-Workforce Data Systems

**Summary**: Concept page for data systems that link students' education records to their later employment and earnings records. The wiki's sources show what such linkage makes possible (the Census study of 6.7 million graduates), what its absence costs (Nebraska's CTE evaluation could not measure earnings), and why the wider data used to measure AI's labor-market effects is fragmented and often contradictory.

**Sources**: `raw/misc/Career pathways are growing but evidence isn’t.md`, `raw/PDF/Gradiating into Disruption.pdf`, `raw/misc/A.I. Is Reshaping the Economy. Good Luck Measuring How.md`, `raw/misc/AI was supposed to hit new grads hard. So far, unemployment data says otherwise..md`, `raw/PDF/HowDoesAIChangeLaborDemand.pdf`, `raw/PDF/AIEI_RN01_Jun26.pdf`, `raw/PDF/Applied-Co-Intelligence–Preparing-Career-and-Technical-Education-Learners-for-an-AI-Driven-Workforce-FINAL.pdf`, `raw/PDF/Fostering-AI-Ready-Cultivating-Resources-CTE-Pipelines.pdf`

**Last updated**: 2026-10-28

---

## What these systems are

An education-to-workforce data system links an individual's education records (school, program, credential) to records of what happened afterward (employment, industry, earnings). Advocates call the statewide version a **preschool-through-workforce longitudinal data system**: one that can follow a student from early education through K-12 and postsecondary education into the labor market (source: Career pathways are growing but evidence isn’t.md).

Without that link, a program can report who enrolled and who finished, but not whether completers got jobs or earned more. For CTE, whose central promise is labor-market payoff, that is the question that matters most.

## What linkage makes possible

The clearest example in the wiki is [[graduating-into-disruption-census]]. The Census Bureau's Post-Secondary Employment Outcomes (PSEO) program links college graduation records to Longitudinal Employer-Household Dynamics (LEHD) wage records (source: Gradiating into Disruption.pdf):

- 6.7 million bachelor's-degree records from 27 data partners in 24 states and 350+ institutions, about 29% of US bachelor's degrees conferred 2016–2024;
- wage records covering over 95% of jobs in participating states.

That linkage let the authors show that graduates of the most AI-exposed majors lost about 5 points of initial employment and 13% of initial earnings after ChatGPT, and that half the earnings loss came from starting in retail and food service (source: Gradiating into Disruption.pdf). An unemployment survey could not have shown the second finding: these graduates stayed employed, but in worse jobs.

The coverage has limits. The sample skews toward large, public, urban, research-intensive institutions, and the paper studies bachelor's graduates, not high-school CTE students (source: Gradiating into Disruption.pdf).

## What its absence costs

**Nebraska's unanswered earnings question.** A federally funded REL Central evaluation found that students in Nebraska and South Dakota who completed structured CTE pathways were 7 points more likely to graduate on time and 10 points more likely to enroll in postsecondary education. The evidence helped persuade Nebraska to pass its first dedicated CTE appropriation. But the researchers could not measure whether CTE students earned more "because there is no infrastructure linking education records to workforce data" (source: Career pathways are growing but evidence isn’t.md; see [[career-pathways-evidence-gap]]).

**Work-based learning that cannot be compared.** A Bellwether/Britebound review of work-based learning in 10 states found different definitions of what counts, different data collected, and different tracking infrastructure in each. "Even in states collecting data, few can say which approaches move outcomes, for which students, and under what conditions" (source: Career pathways are growing but evidence isn’t.md; see [[work-based-learning]]).

**Most states cannot follow students.** "Most states still can't follow their students from K-12 into postsecondary education and the workforce." Kentucky and Colorado are the models cited: both run preschool-through-workforce systems and use the results "to inform everything from policy to classroom instruction" (source: Career pathways are growing but evidence isn’t.md).

## The wider measurement problem

Linking student records is one part of a broader problem: the data used to measure AI's labor-market effects is fragmented.

- **Government statistics lag.** The BLS does not break out technology as a sector in its monthly jobs report, and its latest detailed occupational breakdown was over a year old in mid-2026. Falling survey response rates and budget shortfalls are reducing federal statistical capacity. A bipartisan Senate bill (Kelly, Banks, Young, June 2026) would expand federal AI labor-market data collection (source: A.I. Is Reshaping the Economy. Good Luck Measuring How.md; see [[ai-economy-measurement-2026]]).
- **Private data is unrepresentative in different directions.** ADP payroll data skews toward large, established firms; Ramp expense data skews toward tech-savvy firms; the two point in different directions on AI and hiring (source: A.I. Is Reshaping the Economy. Good Luck Measuring How.md).
- **Occupation codes miss new jobs.** Standard Occupational Classification codes were not designed for emerging roles; the Cultivating Resources report gives green-energy jobs as an example that conventional workforce data struggles to track (source: Fostering-AI-Ready-Cultivating-Resources-CTE-Pipelines.pdf; see [[fostering-ai-ready-cultivating-resources]]).

### Different datasets, different answers

Much of the wiki's disagreement about AI and entry-level work traces to which data a study uses:

| Data | Used by | What it sees | What it misses |
|---|---|---|---|
| Linked education–wage records (PSEO/LEHD) | [[graduating-into-disruption-census]] | Employment, earnings, and industry by major for graduates | Non-participating states and institutions; high-school pathways |
| Payroll records (ADP) | [[canaries-coal-mine-brynjolfsson]], [[stanford-del-ai-economic-indicators]] | Employment by age and occupation, monthly, for 4.6 million workers (source: AIEI_RN01_Jun26.pdf) | Firms outside ADP; education history |
| Household survey (CPS) | [[cesifo-recent-grads-unemployment]] | Unemployment of recent graduates | Job quality and earnings by major |
| Job postings and profiles (Revelio) | [[ai-labor-demand-41-countries]] | Firm-level AI adoption and workforce seniority across 41 countries (source: HowDoesAIChangeLaborDemand.pdf) | Workers and firms with little online presence (wiki inference) |

The CESifo finding that recent-graduate unemployment is normal and the Census finding of recession-scale earnings losses are partly a measurement difference: graduates can stay employed while starting in worse jobs (source: AI was supposed to hit new grads hard. So far, unemployment data says otherwise..md; Gradiating into Disruption.pdf). Only linked records show both at once.

## Proposals

- **ALI's federal recommendations**: build state preschool-through-workforce data systems; modernize federal education R&D (an ARPA-style center or an IES Career-Connected Learning Panel); and coordinate funding across NSF, Labor, Commerce, and Defense, building on the DOL/Commerce/BLS AI Workforce Research Hub (source: Career pathways are growing but evidence isn’t.md; see [[ai-education-policy-and-legislation]]).
- **The Senate data bill** noted above, for national AI labor-market statistics.
- **Perkins V** already requires local needs assessments to use labor-market data and performance indicators broken down by learner group (source: Applied-Co-Intelligence–Preparing-Career-and-Technical-Education-Learners-for-an-AI-Driven-Workforce-FINAL.pdf; see [[perkins-v-and-clna]]). Linked outcome data would let those assessments measure results, not just needs (wiki inference).

## Caveats

1. **Advocacy source.** The case for state data systems in the wiki comes mainly from ALI, a coalition that lobbies for federal education R&D funding ([[career-pathways-evidence-gap]]).
2. **No evaluation of the systems themselves.** No source in the wiki shows that states with linked data systems get better CTE outcomes; the argument is that they can find out.
3. **Privacy and governance are not covered.** Linking student records to wage records raises privacy and data-governance questions that none of the wiki's sources on this topic address. This needs a source.

## Implications for CTE

These are the wiki's inferences, not claims made by the sources.

1. **CTE cannot prove its labor-market value without linkage.** The Nebraska case shows that even strong evaluations stop at graduation and enrollment. As AI changes which entry-level jobs pay ([[entry-level-labor-market]]), earnings evidence becomes more important, not less.
2. **Unemployment is the wrong outcome measure.** The Census finding (employed, but in lower-paying sectors) suggests CTE programs should track job quality and earnings, not just placement.
3. **Common definitions come first.** Work-based learning, the wiki's main proposed answer to the disappearing junior rung, cannot be evaluated across states while 10 states define it 10 ways.
4. **Programs can use national data now.** While state systems are built, occupation-level sources such as the [[stanford-del-ai-economic-indicators]] Canaries dashboard and the [[anthropic-labor-market-index]] can inform program planning, with the representativeness caveats above.

## Related pages

- [[career-pathways-evidence-gap]]
- [[graduating-into-disruption-census]]
- [[ai-economy-measurement-2026]]
- [[cesifo-recent-grads-unemployment]]
- [[canaries-coal-mine-brynjolfsson]]
- [[stanford-del-ai-economic-indicators]]
- [[ai-labor-demand-41-countries]]
- [[entry-level-labor-market]]
- [[perkins-v-and-clna]]
- [[work-based-learning]]
- [[ai-education-policy-and-legislation]]
- [[fostering-ai-ready-cultivating-resources]]
- [[anthropic-labor-market-index]]
- [[cte-and-ai]]
