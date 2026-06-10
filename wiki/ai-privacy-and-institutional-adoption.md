# AI Privacy and Institutional Adoption

**Summary**: The cluster of cost, data privacy, infrastructure, and policy barriers that prevent schools and colleges from adopting AI — and the emerging strategies (local SLM deployment, elastic policies, fellowship programs) for overcoming them equitably.

**Sources**: `raw/PDF/SmallLLMs.pdf`, `raw/blog/Can Small Language Models Help K–12 Schools.md`, `raw/PDF/Applied-Co-Intelligence–Preparing-Career-and-Technical-Education-Learners-for-an-AI-Driven-Workforce-FINAL.pdf`, `raw/video/New Book Podcast_ AI Unplugged_ The Hype and Hope in Education Futures.md`, `raw/blog/AI, jobs, and the next generation.md`

**Last updated**: 2026-06-10

---

## Overview

The promise of AI in education runs headlong into a cluster of practical institutional barriers: cost, data privacy, infrastructure constraints, policy uncertainty, and internal institutional divides. These barriers are not evenly distributed — they fall hardest on the districts and institutions that serve the most vulnerable students, threatening to make AI a privilege rather than an equalizer.

## The Core Barriers

### 1. Cost
Cloud-based LLM APIs charge per token. For an institution with thousands of students and teachers querying AI tools throughout the day, costs scale rapidly and unpredictably. On top of per-query costs, running large models locally requires expensive GPU infrastructure most schools do not have.

[[Small language models]] offer a direct response: 3–7B parameter models run on standard institutional hardware at no marginal per-query cost (source: SmallLLMs.pdf).

### 2. Data Privacy
Routing student submissions, grades, and curriculum materials through third-party cloud APIs creates significant privacy exposure. Student data is subject to FERPA, state privacy laws, and district policies — and most cloud AI providers cannot offer the institutional control these regulations require. Faculty who are already skeptical of AI may refuse to use tools that route student work through external servers.

Local SLM deployment eliminates this problem: all data stays within the institution's secure network. The [[small-models-big-support]] framework was designed around this as a non-negotiable constraint (source: SmallLLMs.pdf).

### 3. Infrastructure and the Digital Divide
The [[applied-co-intelligence-report]] identifies a persistent digital divide as a structural barrier: "A private school might offer a full semester of prompt engineering, while many rural or low-income districts still lack reliable Wi-Fi or basic computing infrastructure" (source: Applied-Co-Intelligence PDF). Federal data confirms geographic and resource gaps significantly impact access to advanced technologies.

SLMs reduce infrastructure requirements (standard PCs instead of GPU servers) but do not eliminate them — connectivity and basic computing remain prerequisites.

### 4. Policy Patchwork
In the absence of federal AI law, institutions face a fragmented landscape: some ban AI entirely, others have no policy, most operate without clear guidance. In a 2025 Tennessee survey, 85% of CTE coordinators believed AI would significantly change their fields; only 15% had clear guidance on how to prepare (source: Applied-Co-Intelligence PDF).

The result is what the ACI report calls a "Wild West scenario" — individual instructor judgment substituting for institutional strategy, creating inequitable and incoherent student experiences.

### 5. Internal Institutional Divides
Many faculty distrust AI as a cost-cutting tool disguised as pedagogical innovation — a fear validated by reports of administrators asking whether AI means they can "fire all the adjuncts and increase class sizes" (C. Edward Watson, AAC&U, cited in Applied-Co-Intelligence PDF). This internal divide must be addressed through faculty-led, administratively-supported implementation rather than top-down mandates.

## The Equity Dimension

These barriers compound each other and fall unevenly. Well-resourced institutions can absorb API costs, hire AI staff, negotiate favorable vendor agreements, and develop coherent policy frameworks. Rural, low-income, and under-resourced institutions cannot. As the ACI report warns:

> "Until all three of these structural barriers — policy, leadership, and access — are addressed, the promise of AI will exacerbate, not close, existing opportunity gaps." (source: Applied-Co-Intelligence PDF)

## Emerging Responses

| Barrier | Emerging Response |
|---------|------------------|
| Cost | Local SLM deployment on standard hardware; open-weight models (Llama, Qwen, Neural-Chat) |
| Data privacy | On-premises deployment; no cloud API routing; local vector stores |
| Infrastructure gap | SLMs on standard PCs; federal/state investment in connectivity and devices |
| Policy patchwork | Elastic frameworks (FACCC, ASCCC in California); WICHE policy toolkit |
| Internal divides | Faculty-led AI fellowships (Tennessee Perkins READI, CA Community Colleges Chancellor's AI Fellows) |
| Sovereignty | Open-weight models under institutional control; RLHF from local teacher feedback |

## Implications for CTE

CTE institutions — often community colleges and technical schools serving diverse, lower-income populations — face these barriers acutely. The [[applied-co-intelligence-report]] recommends policymakers invest in equitable AI infrastructure as a prerequisite for meaningful [[applied-co-intelligence-model]] implementation. Without it, the ACI model remains a vision for well-resourced institutions only.

The [[small-models-big-support]] research demonstrates that the technical barriers are more surmountable than they appear: a locally-deployed 7B model on consumer hardware can support educator workflows effectively. The remaining barriers are policy, funding, and institutional will — all human choices, not technical inevitabilities.

## International Perspective: Canada's Equity and Access Challenge

Dr. Stephen Murgatroyd ([[ai-unplugged-murgatroyd]], 2026) provides the most specific access equity data in the wiki for a G7 country:

- **650,000 Canadian households** (~4% of the population) have no internet access — concentrated in northern indigenous and rural communities (northern Ontario, Quebec, Manitoba, BC, Alberta)
- **Canada ranks among the 5 most expensive jurisdictions globally** for mobile phone and broadband costs — making even basic AI access a significant household expense
- Many powerful AI tools require payment: "Even $20/month is a huge amount of money if you don't have it." Murgatroyd estimates his own annual AI/technology/software costs at ~$5,000 — and notes most teachers neither have that money nor should be expected to pay it
- As AI companies move toward profitability, tool costs will increase: "Some of them haven't made any money so far" — meaning the access gap will likely widen, not close, as commercial AI matures

The Canadian figures likely understate the severity of the access problem in lower-income countries. The concentration in indigenous and rural northern communities is not incidental — it reflects historical patterns of infrastructure underinvestment that AI adoption inherits rather than remedies. (source: New Book Podcast: AI Unplugged.md)

## Western Cultural Bias and Indigenous Data Sovereignty

Murgatroyd identifies a structural dimension of AI inequity that goes beyond access: the cultural bias embedded in AI training data.

> "A lot of the AI slop is based on a kind of western imperialist colonialist cultural view. If you talk to ChatGPT or Gemini about how the treaties got written and made and signed and agreed to in Canada, it's basically nonsense."

This is not primarily a hallucination problem — it is a training data representation problem. AI systems trained predominantly on English-language, Western-origin text produce outputs that reflect those cultural perspectives, misrepresent or erase non-Western knowledge systems, and may actively harm communities whose histories and practices are poorly represented.

His proposed structural response is **data sovereignty**: locally deployed AI systems built on locally controlled data, rather than cloud-based systems trained on predominantly Western corpora. He is advising an indigenous LMS provider in British Columbia whose systems use local, personal sovereign data — addressing both the privacy concern and the cultural accuracy problem simultaneously.

**Case study — Treaty 8 school, northern Alberta**: A northern Alberta indigenous school in Treaty 8 territory cannot find teachers or educational assistants. AI is being used as a necessity, not a luxury enhancement. They are co-designing learning supports with students and teachers in Cree language, based on indigenous storytelling, with indigenous cultural resources attached. This reframes the equity conversation: for communities that colonial resource allocation has left without human educational capacity, locally designed AI is not a risk to be managed but the only available infrastructure. (source: New Book Podcast: AI Unplugged.md)

The data sovereignty argument reinforces the [[small-language-models]] case for local deployment — but extends it beyond privacy and cost to cultural self-determination. Open-weight models under institutional control, trained on locally relevant data, are the technical mechanism; indigenous and community governance of that data is the institutional requirement.

## Corporate Data Sovereignty: A Competitive Dimension

Brad Smith ([[brad-smith-ai-jobs-next-generation]], 2026) extends the data sovereignty argument from indigenous and national contexts to a competitive imperative for every organization:

> "The benefits of AI for a business will be short-lived if it transfers and trains someone else's AI model using a firm's unique knowledge and expertise. This helps explain why each company needs to develop its own internal AI capabilities and control its own data."

> "Sovereignty must be preserved not only for countries but for companies. And privacy must be protected not only for individuals but for organizations."

The mechanism: an organization whose proprietary knowledge and processes are used to train a third-party model loses the competitive advantage that expertise represents. As general AI capabilities commoditize, the differentiator becomes an organization's unique domain knowledge — which is only valuable if retained under institutional control.

For schools and CTE institutions, this argument maps directly onto the barriers documented above: routing student submissions and curriculum through cloud APIs not only creates FERPA exposure, it transfers institutional learning — the accumulated knowledge of educators, students, and curriculum design — to the infrastructure providers. Local SLM deployment ([[small-models-big-support]]) addresses both concerns simultaneously: privacy protection and institutional sovereignty over the knowledge that shapes the AI's outputs. (source: AI, jobs, and the next generation.md)

## Related pages

- [[small-language-models]]
- [[small-models-big-support]]
- [[small-language-models-k12]]
- [[applied-co-intelligence-report]]
- [[cte-and-ai]]
- [[ai-in-k12-education]]
- [[ai-unplugged-murgatroyd]]
- [[brad-smith-ai-jobs-next-generation]]
