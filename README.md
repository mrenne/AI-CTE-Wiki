# AI-CTE-Wiki

A personal knowledge base on generative AI and its impact on K–12 education, with a specific focus on Career and Technical Education (CTE). Built and maintained using [Andrej Karpathy's LLM Wiki pattern](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f).

---

## How this wiki works

Source documents go into `raw/`. Claude reads them, discusses key takeaways, then writes and cross-references markdown pages in `wiki/` — source summaries, concept pages, comparisons. A single paper typically touches 10–15 pages. The wiki compounds: every new source propagates updates across existing pages, contradictions get flagged, and cross-references already exist when you need them. Querying the wiki draws on curated synthesis rather than re-assembling raw PDFs from scratch.

The human curates sources and asks questions. Claude handles the work that causes humans to abandon wikis: updating cross-references, maintaining consistency, and synthesizing across sources. Start with [wiki/index.md](wiki/index.md) for the full table of contents.

---

## What the research actually shows

Twenty-eight sources ingested so far, producing 44 interlinked wiki pages. The picture that emerges is more nuanced — and more actionable — than either the AI-will-take-all-jobs or AI-changes-nothing narratives.

### On learning and cognition

**AI completion is not learning.** Yan & Gašević's *Agentivism* framework (2026) and the MIT EEG study (Kosmyna et al.) converge on a hard finding: when AI completes tasks for students before they've built independent capability, measurable neurological harm accumulates over time — up to 55% reduction in neural connectivity. The mechanism is *cognitive debt*: the brain stops practicing the circuits that need exercise. Task performance goes up; durable understanding goes down.

**Students cannot evaluate AI quality — and enthusiasm makes it worse.** Abdelghani et al. (2026) studied 63 middle-schoolers doing science tasks with ChatGPT. Prompt quality discrimination: at chance. Answer quality evaluation: at chance. 71.4% of expert-rated low-quality answers were rated "useful" by students. The only protective factor was metacognition — not domain knowledge, not AI familiarity. Positive AI attitudes *negatively* predicted interaction quality (β = −0.39). The students who felt most comfortable with AI were the most blind to when it was failing them.

**AI tutoring has barely worked, and it may be the wrong tool for high schoolers.** Khanmigo underperformed its adoption targets because students who most need help are least likely to seek it out. A 2026 meta-analysis of 34 experimental studies (Liu et al.) found near-zero cognitive benefit for grades 10–12 (g = 0.037) while upper-primary students benefited substantially (g = 0.877). The core CTE population is in the grade range where AI educational interventions show the weakest evidence.

**The clearest positive evidence is for teachers, not students.** Educator-facing AI tools — especially real-time coaching during lessons — show the most consistent causal benefits, with the largest gains for novice teachers. This is where AI investment in schools is best supported by evidence.

**AI boosts production speed dramatically but converts only marginally to shipped output.** Demirer, Musolff & Yang (2026), tracking 100,000+ GitHub developers across three AI tool generations, find a consistent productivity funnel: +740% code produced → +65% review requests → only ~20% more shipped releases. Every human-dependent review stage absorbs the gain before it converts to finished output. At the organizational level: ~95% of companies see no meaningful return from GenAI (MIT NANDA, 2025); 80% of AI projects fail — twice the rate of comparable non-AI projects (RAND, 2025). The bottleneck is not AI capability; it is human review and integration capacity. The same funnel operates in education: AI dramatically raises output volume while durable learning gains drain through reading, retrieval, and transfer. The strategic implication — "enter high in the chain" — means AI aimed at feedback, metacognitive calibration, and teacher coaching (where cognitive consolidation lives) outperforms AI aimed at content generation. The same technology, aimed at a different stage, produces the opposite result.

**Oral defense is the answer to both cognitive debt and AI detection.** Murgatroyd (2026) and Nurenberg (2026) independently converge on the same classroom solution: design assessment so that understanding must be demonstrated in real time, rather than trying to detect AI-generated artifacts after the fact. Murgatroyd's "Build, Analyze, Defend" scaffold — produce something with AI, interrogate it critically, then defend it orally — maps directly onto the Agentivism framework and makes AI detection irrelevant. AI detection software does not work reliably; institutions relying on it are now losing court cases filed by students falsely accused of academic misconduct.

### On labor markets

**Only 12% of US jobs face true substitution.** BCG Henderson Institute's 2026 analysis of 165 million US jobs across 1,500 occupational roles finds only 12% (the "Substituted" segment) face genuine headcount contraction — roles where AI replaces the core function *and* demand is bounded. The widely-cited Frey & Osborne figure of 47% at risk ignored demand expandability: when AI lowers the cost of a service, demand may expand to absorb the productivity gain (Jevons Paradox). Software engineering is the canonical case — coding AI doubled output per engineer, software got cheaper, and headcount *rose* after ChatGPT.

**The disruption is hitting educated white-collar workers first, not CTE-track workers.** Anthropic's observed-exposure data shows that the most AI-exposed workers are on average 47% higher-paid and four times more likely to hold graduate degrees than zero-exposure workers. BCG's "Limited-Exposure" segment (34% of US jobs) — defined by physical presence, sustained human interaction, and contextual judgment in variable settings — maps almost exactly onto CTE pipelines: healthcare, skilled trades, early childhood education, construction, personal services.

**The entry-level hiring decline is real — but its attribution to AI is now contested.** Lambert & Schindler (Warwick/LSE, May 2026) find that work-from-home and GenAI exposure are correlated at 0.77 (Spearman rank) across occupations — the same workers (software developers, management consultants) top both rankings. In joint-treatment difference-in-differences specifications using 243 million new hires across four countries, the WFH coefficient holds stable (−1.42 to −1.57pp) while GenAI attenuates to near-zero and is often statistically insignificant. The 8–11 percentage-point decline in junior-hire share below 2019 baselines may be primarily an organizational friction from remote work — surmountable through better management practice — rather than irreversible task automation. The diagnosis changes the remedy.

**The relational economy thesis has structural backing.** Alex Imas (UChicago, 2026) argues — with econometric support — that as AI commodifies cognitive production, rising real incomes shift spending toward goods and services where human involvement is inseparable from the value: care, hospitality, artisanal production, coaching, education. Historical structural change data (Comin et al., *Econometrica* 2021) shows income effects account for over 75% of employment reallocation patterns. The sectors CTE prepares are not merely "safe from automation" — they are the sectors that structurally expand as cognitive commodities get cheap.

### On CTE specifically

**Students in the AI capital are already choosing trades as an AI hedge.** Bay Area high school seniors in the class of 2026 (NYT, June 2026) are explicitly avoiding tech careers because of AI and pivoting to construction and trades — articulating the physical-presence insulation argument independently: "A.I. is not going to build a home. A.I. isn't going to weld anything either." This behavioral shift is occurring in the place where AI's disruption of professional work is most visible and the evidence for it is most accessible to students. The prediction that CTE-aligned sectors are protected is showing up in enrollment decisions.

**CTE programs create the choice set — they are discovery mechanisms, not pipelines.** Over 95% of students in California's construction programs had never used tools before the class. One student: "I had no idea this class existed. I didn't even really consider construction seriously until I took this class." The obstacle to scaling the trade pivot is not student interest — it's exposure. State investment in CTE programs is the structural precondition; family cultural pressure (especially in immigrant families, who associate four-year degrees with social mobility) is the binding constraint once interest exists.

**CTE-track occupations are doubly insulated from both post-pandemic shocks.** Electricians, construction workers, and other CTE-aligned workers sit at the bottom of both WFH *and* GenAI exposure rankings. Whether the junior-hiring decline ultimately proves to be AI-driven or WFH-driven — the attribution is now contested — CTE-track workers face neither pressure. The protected-sector thesis holds regardless of which mechanism wins the empirical debate.

### On schools and policy

**The K-12 AI policy gap is structural, not accidental.** Stanford's AI Index 2026 finds that 80% of university students use AI for schoolwork — doubled from 40% in 2023 — but only 6% of teachers report their school's AI policies are clear. No US state has established teacher training standards for AI education. AP CS excludes AI content. State guidance is largely nonbinding. Students are integrating AI into their work at scale, without any institutional literacy framework around it.

**The key design variable is whether AI provides answers or builds thinking.** The evidence base consistently shows that AI tutors designed to give hints and ask guiding questions produce near-equivalent outcomes to traditional instruction; AI that provides complete answers harms independent learning and widens achievement gaps for low-prior-knowledge students. The same technology, with different pedagogical design, produces opposite effects.

**AI equity runs deeper than an infrastructure gap — it is also a cultural representation problem.** AI systems trained predominantly on Western, English-language text produce outputs that systematically misrepresent or erase indigenous and non-Western knowledge systems. In Canada (among the world's wealthiest countries), 650,000 households lack internet access — primarily indigenous and northern rural communities — while Canada ranks among the five most expensive jurisdictions globally for broadband. The answer to both problems points in the same direction: locally deployed AI on locally controlled data (data sovereignty), not scaled access to centralized Western cloud systems.

---

## Repository structure

```
raw/        ← Source documents (immutable — never modified)
wiki/       ← LLM-maintained markdown pages
  index.md  ← Full table of contents
  log.md    ← Append-only record of all ingestions and changes
CLAUDE.md   ← LLM instructions: page format, ingest workflow, citation rules
```

Source documents (`raw/`) are not included in this repository. They contain copyrighted papers, articles, and reports that the wiki pages summarize and synthesize.

---

## Further reading

- [Andrej Karpathy's LLM Wiki gist](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f) — the original pattern this wiki is based on
- [What Is Andrej Karpathy's LLM Wiki? (MindStudio)](https://www.mindstudio.ai/blog/andrej-karpathy-llm-wiki-knowledge-base-claude-code) — walkthrough of the pattern with Claude Code
