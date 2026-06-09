# AI-CTE-Wiki

A personal knowledge base on generative AI and its impact on K–12 education, with a specific focus on Career and Technical Education (CTE). Built and maintained using [Andrej Karpathy's LLM Wiki pattern](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f).

---

## How this wiki works

Source documents go into `raw/`. Claude reads them, discusses key takeaways, then writes and cross-references markdown pages in `wiki/` — source summaries, concept pages, comparisons. A single paper typically touches 10–15 pages. The wiki compounds: every new source propagates updates across existing pages, contradictions get flagged, and cross-references already exist when you need them. Querying the wiki draws on curated synthesis rather than re-assembling raw PDFs from scratch.

The human curates sources and asks questions. Claude handles the work that causes humans to abandon wikis: updating cross-references, maintaining consistency, and synthesizing across sources. Start with [wiki/index.md](wiki/index.md) for the full table of contents.

---

## What the research actually shows

Twenty-six sources ingested so far, producing 42 interlinked wiki pages. The picture that emerges is more nuanced — and more actionable — than either the AI-will-take-all-jobs or AI-changes-nothing narratives.

### On learning and cognition

**AI completion is not learning.** Yan & Gašević's *Agentivism* framework (2026) and the MIT EEG study (Kosmyna et al.) converge on a hard finding: when AI completes tasks for students before they've built independent capability, measurable neurological harm accumulates over time — up to 55% reduction in neural connectivity. The mechanism is *cognitive debt*: the brain stops practicing the circuits that need exercise. Task performance goes up; durable understanding goes down.

**Students cannot evaluate AI quality — and enthusiasm makes it worse.** Abdelghani et al. (2026) studied 63 middle-schoolers doing science tasks with ChatGPT. Prompt quality discrimination: at chance. Answer quality evaluation: at chance. 71.4% of expert-rated low-quality answers were rated "useful" by students. The only protective factor was metacognition — not domain knowledge, not AI familiarity. Positive AI attitudes *negatively* predicted interaction quality (β = −0.39). The students who felt most comfortable with AI were the most blind to when it was failing them.

**AI tutoring has barely worked, and it may be the wrong tool for high schoolers.** Khanmigo underperformed its adoption targets because students who most need help are least likely to seek it out. A 2026 meta-analysis of 34 experimental studies (Liu et al.) found near-zero cognitive benefit for grades 10–12 (g = 0.037) while upper-primary students benefited substantially (g = 0.877). The core CTE population is in the grade range where AI educational interventions show the weakest evidence.

**The clearest positive evidence is for teachers, not students.** Educator-facing AI tools — especially real-time coaching during lessons — show the most consistent causal benefits, with the largest gains for novice teachers. This is where AI investment in schools is best supported by evidence.

### On labor markets

**Only 12% of US jobs face true substitution.** BCG Henderson Institute's 2026 analysis of 165 million US jobs across 1,500 occupational roles finds only 12% (the "Substituted" segment) face genuine headcount contraction — roles where AI replaces the core function *and* demand is bounded. The widely-cited Frey & Osborne figure of 47% at risk ignored demand expandability: when AI lowers the cost of a service, demand may expand to absorb the productivity gain (Jevons Paradox). Software engineering is the canonical case — coding AI doubled output per engineer, software got cheaper, and headcount *rose* after ChatGPT.

**The disruption is hitting educated white-collar workers first, not CTE-track workers.** Anthropic's observed-exposure data shows that the most AI-exposed workers are on average 47% higher-paid and four times more likely to hold graduate degrees than zero-exposure workers. BCG's "Limited-Exposure" segment (34% of US jobs) — defined by physical presence, sustained human interaction, and contextual judgment in variable settings — maps almost exactly onto CTE pipelines: healthcare, skilled trades, early childhood education, construction, personal services.

**The entry-level hiring slowdown is the mechanism to watch.** BCG's "Divergent" segment shows that AI automates junior tasks first while senior roles persist. The result is a pipeline problem: Anthropic data finds a 14% hiring slowdown for workers aged 22–25 entering AI-exposed occupations. Mass unemployment hasn't materialized, but the on-ramp for young workers is narrowing.

**The relational economy thesis has structural backing.** Alex Imas (UChicago, 2026) argues — with econometric support — that as AI commodifies cognitive production, rising real incomes shift spending toward goods and services where human involvement is inseparable from the value: care, hospitality, artisanal production, coaching, education. Historical structural change data (Comin et al., *Econometrica* 2021) shows income effects account for over 75% of employment reallocation patterns. The sectors CTE prepares are not merely "safe from automation" — they are the sectors that structurally expand as cognitive commodities get cheap.

### On schools and policy

**The K-12 AI policy gap is structural, not accidental.** Stanford's AI Index 2026 finds that 80% of university students use AI for schoolwork — doubled from 40% in 2023 — but only 6% of teachers report their school's AI policies are clear. No US state has established teacher training standards for AI education. AP CS excludes AI content. State guidance is largely nonbinding. Students are integrating AI into their work at scale, without any institutional literacy framework around it.

**The key design variable is whether AI provides answers or builds thinking.** The evidence base consistently shows that AI tutors designed to give hints and ask guiding questions produce near-equivalent outcomes to traditional instruction; AI that provides complete answers harms independent learning and widens achievement gaps for low-prior-knowledge students. The same technology, with different pedagogical design, produces opposite effects.

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
