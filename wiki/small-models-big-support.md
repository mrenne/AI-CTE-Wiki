# Small Models, Big Support

**Summary**: An academic paper demonstrating an end-to-end, locally-deployed educator AI support system using 3B–7B open-source models that achieves near-parity with Gemini 2.5 Pro on semantic similarity while keeping all institutional data on-premises.

**Sources**: `raw/SmallLLMs.pdf`

**Last updated**: 2026-04-27

---

## Overview

This academic paper (anonymous college, ~2025) presents an open-source framework for educator-centric AI assistance using [[small language models]] (3B–7B parameters) deployed entirely on institutional hardware. The system supports the full instructional design workflow: exercise generation, rubric generation, and student assessment. All data — curriculum materials, student submissions, grades — remains within the institution's secure network.

The paper directly targets the three core [[ai-privacy-and-institutional-adoption]] barriers: cost, data privacy, and infrastructure constraints of cloud-based systems.

## System Architecture

Four components work together (source: SmallLLMs.pdf):

### Context-Augmented Generation (CAG)
Educator-provided materials (textbook chapters, style guides, learning objectives, example exercises) are injected directly into the prompt context to prime the model toward the correct format, tone, and complexity. Used for exercise generation, where the teacher's own materials define the target output style.

### Retrieval-Augmented Generation (RAG)
A local knowledge base (ChromaDB vector store, all-MiniLM-L6-v2 embeddings, top-3 chunks by cosine similarity) retrieves relevant document chunks to ground outputs in trusted course-specific sources. Used for factual accuracy in assessment and follow-up questions. All indexing and retrieval runs locally — no external API calls.

### Teacher-in-the-Loop Interactive Refinement
Educators guide and refine outputs through conversational prompts. Treated as a feature (ensuring educator agency and control) rather than a workaround for model limitations. Key finding: satisfactory results achieved within an average of **3 refinement prompts**.

### Verifier LLM
A secondary small model (3B parameters) screens all generated content before display, checking for safety guideline adherence, instruction relevance, and pedagogically unsound content ("jailbreaks"). Performance: 88% topical relevance accuracy, 90% safety accuracy, 82% overall (source: SmallLLMs.pdf).

## Models Evaluated

Three open-weight models benchmarked against Gemini 2.5 Pro on physics exercise generation across five lab topics:
- **Llama 3.2 3B Instruct** — most resource-efficient
- **Neural-Chat 7B** (Intel) — best quantitative scores (ROUGE-1: 0.46, METEOR: 0.28)
- **Qwen2.5 7B Instruct** (Alibaba) — best qualitative performance among open-source models

## Key Results

### Quantitative (n-gram and semantic similarity metrics)

| Model | ROUGE-1 | BERTScore F1 |
|-------|---------|--------------|
| Neural-Chat 7B | **0.46** | 0.82 |
| Qwen2.5 7B | — | 0.82 |
| Gemini 2.5 Pro | — | **0.83** |

BERTScore F1 (contextual semantic similarity) is nearly identical between the best open-source 7B models and Gemini. The gap in n-gram metrics reflects lexical diversity, not quality deficit.

### Qualitative (LLM-judge evaluation, 1–5 scale)

| Model | Overall Average |
|-------|----------------|
| Gemini 2.5 Pro | **4.72** |
| Qwen2.5 7B | 3.84 |
| Llama 3.2 3B | ~2.9 |

The qualitative gap — primarily on Completeness and Adherence to Instructions — is addressable through the interactive refinement loop. The paper argues that with teacher guidance, locally-deployed 7B models achieve practical utility comparable to proprietary systems for targeted educator tasks.

## Privacy and Institutional Sovereignty

Complete local deployment ensures:
- No student data or curriculum materials pass through third-party cloud services
- No pay-per-token API costs
- Institutional control over tool behavior and data retention
- Compliance with FERPA and district privacy requirements without vendor dependency

Deployed on a consumer-grade macOS server within the college's IT infrastructure, accessed via Microsoft Azure App Proxy for authenticated access.

## Teacher-Centric Design Philosophy

The system frames educator agency as a design requirement, not an afterthought. This resonates with [[co-intelligence]]'s vision of AI as collaborator and with the [[applied-co-intelligence-report]]'s human capital gap argument: educators who understand how to guide and refine AI outputs are more effective than those who either avoid AI or passively accept its outputs.

The interactive refinement loop operationalizes [[agentivism]]'s principle of selective delegation: teachers delegate drafting to the AI but retain responsibility for evaluating and refining outputs. The ~3-prompt average to satisfaction implies active epistemic monitoring — not passive acceptance.

## Limitations

- 3B–7B models don't match larger proprietary models on complex qualitative tasks without refinement
- Evaluation limited to physics exercise generation at one institution
- LLM-as-judge methodology not a substitute for human domain expert evaluation
- Prototype requires further engineering for production: PostgreSQL database, scalable frontend (FastAPI/React), Docker containerization

## Future Work

- Extended pilot with control groups to assess pedagogical impact on student outcomes
- Fine-tuning on domain-specific educational content; RLHF from teacher feedback
- Docker packaging for adoption at other institutions

## Related pages

- [[small-language-models-k12]]
- [[small-language-models]]
- [[ai-privacy-and-institutional-adoption]]
- [[agentivism]]
- [[co-intelligence]]
- [[applied-co-intelligence-report]]
