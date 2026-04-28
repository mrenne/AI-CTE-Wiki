# AI-CTE-Wiki

A personal knowledge base on generative AI and its impact on K–12 education, with a specific focus on Career and Technical Education (CTE). Built and maintained using [Andrej Karpathy's LLM Wiki pattern](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f).

---

## What's in this wiki

27 interlinked markdown pages covering:

- **Learning theory**: How AI changes what learning means — and how to design around it ([Agentivism](wiki/agentivism.md), [Cognitive Debt](wiki/cognitive-debt.md))
- **AI tutoring evidence**: What the causal research actually shows about AI in classrooms ([AI Tutoring](wiki/ai-tutoring.md), [Evidence Base](wiki/evidence-base-ai-k12.md), [Khanmigo](wiki/khanmigo.md))
- **Labor market impacts**: How AI is reshaping the workforce — and who it's hitting first ([Labor Market Polarization](wiki/labor-market-polarization.md), [Anthropic Labor Market Index](wiki/anthropic-labor-market-index.md))
- **CTE and equity**: The specific opportunities and risks for career-technical education ([CTE and AI](wiki/cte-and-ai.md), [Transferable Skills](wiki/transferable-skills.md))
- **AI risks**: Sycophancy, delusional spirals, and the risks of over-reliance ([AI Sycophancy](wiki/ai-sycophancy.md), [Cognitive Debt](wiki/cognitive-debt.md))
- **Frameworks**: Applied Co-Intelligence model, AI Mastery Continuum, small language models for schools

Start with [wiki/index.md](wiki/index.md) for the full table of contents.

---

## How this wiki works: the Karpathy LLM Wiki pattern

This wiki is built on a workflow published by [Andrej Karpathy](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f). The core idea: instead of using an LLM to re-derive knowledge from raw sources every time you ask a question (the standard RAG approach), you have the LLM **incrementally compile and maintain a persistent wiki** — a structured set of markdown pages that sit between you and your source materials.

> *"The wiki is a persistent, compounding artifact. Knowledge compiles once, then stays current, rather than being re-derived repeatedly."* — Karpathy

### Why not just RAG?

RAG (Retrieval-Augmented Generation) makes an LLM search a pile of documents and generate an answer at query time. It works, but nothing is built up. Every query starts from scratch. A question that requires synthesizing five documents means re-finding and re-piecing those fragments every time.

The LLM wiki pattern is different: the LLM does the synthesis work **once, permanently**. Cross-references already exist. Contradictions are already flagged. When you ask a question, the answer is drawn from curated pages, not re-assembled from raw PDFs.

### The three-layer architecture

```
raw/        ← Source documents (immutable — LLM reads, never modifies)
wiki/       ← LLM-maintained markdown pages (summaries, concepts, comparisons)
CLAUDE.md   ← The schema: conventions, workflows, and instructions for the LLM
```

**Raw sources** are dropped in by the human and never touched again. **Wiki pages** are owned entirely by the LLM: created, updated, and cross-referenced as new sources arrive. **CLAUDE.md** is the standing instruction set — the equivalent of a style guide and operations manual for the AI editor.

### The three core operations

**1. Ingest**
Drop a new source into `raw/`. The LLM reads it, discusses key takeaways, then writes or updates wiki pages — typically touching 10–15 pages per source. Each ingestion is logged in `wiki/log.md`. A single paper can propagate updates to a source summary page, several concept pages, and the index.

**2. Query**
Ask a question. The LLM searches the wiki, synthesizes an answer with citations to specific pages, and — if the answer is valuable — offers to save it as a new wiki page. Explorations compound into permanent knowledge rather than disappearing into chat history.

**3. Lint**
Periodically audit the wiki: check for broken links, orphan pages (no inbound links), contradictions between pages, stale claims, concept gaps (ideas referenced but without their own page). The LLM produces a numbered findings list with suggested fixes.

### What the human does

- Curates sources (decides what to read and ingest)
- Asks questions and guides analysis
- Approves page creation and significant edits
- Sets the scope and focus of the wiki

The LLM handles the work that causes humans to abandon wikis: updating cross-references, maintaining consistency, flagging contradictions, synthesizing across sources.

> *This pattern echoes Vannevar Bush's Memex (1945) — a personal, curated knowledge store with associative trails — but solves the maintenance problem Bush couldn't: LLMs perform the work humans won't sustain.*

---

## Repository structure

```
wiki/
  index.md          ← Table of contents for the entire wiki
  log.md            ← Append-only record of all ingestions, queries, and audits
  *.md              ← Individual wiki pages (source summaries + concept pages)

CLAUDE.md           ← LLM instructions: page format, ingest workflow, citation rules, lint criteria
README.md           ← This file
```

Source documents (`raw/`) are not included in this repository. They contain copyrighted papers, articles, and reports that the wiki pages summarize and synthesize.

---

## Page format

Every wiki page follows a consistent structure:

```markdown
# Page Title

**Summary**: One to two sentences.

**Sources**: Raw source files this page draws from.

**Last updated**: Date of most recent update.

---

Main content with [[wiki-links]] to related pages.

## Related pages

- [[related-concept-1]]
- [[related-concept-2]]
```

Wiki-links (`[[page-name]]`) connect pages into a navigable graph. The wiki renders natively in [Obsidian](https://obsidian.md/) and any Markdown viewer that supports wikilinks.

---

## Sources and further reading

- [Andrej Karpathy's LLM Wiki gist](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f) — the original pattern this wiki is based on
- [What Is Andrej Karpathy's LLM Wiki? (MindStudio)](https://www.mindstudio.ai/blog/andrej-karpathy-llm-wiki-knowledge-base-claude-code) — walkthrough of the pattern with Claude Code
- [LLM Knowledge Bases (DAIR.AI Academy)](https://academy.dair.ai/blog/llm-knowledge-bases-karpathy) — broader context on LLM-maintained knowledge bases
