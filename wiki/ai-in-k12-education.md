# AI in K-12 Education

**Summary**: An overview of how generative AI is — and isn't — reshaping K-12 schools, with a focus on tutoring, academic integrity, teacher roles, and the early evidence base.

**Sources**: `raw/The education of Sal Khan and the limits of his chatbot.md`, `raw/Applied-Co-Intelligence–Preparing-Career-and-Technical-Education-Learners-for-an-AI-Driven-Workforce-FINAL.pdf`, `raw/The Evidence Base on AI in K-12 Report.pdf`, `raw/'The reality, for better or worse'_ Columbia computer science students and faculty grapple with AI's disruption of the field.md`

**Last updated**: 2026-05-04

---

## The State of Play (Spring 2026)

Three years after ChatGPT's public release, the consensus view in K-12 education is cautious. The [[evidence-base-ai-k12]] report (Stanford SCALE, 2026) reviewed 818 papers on AI in K–12 education and found only 20 with strong causal evidence — and *zero* high-quality causal studies on student learning in U.S. K–12 settings. 64% of causal research was conducted in postsecondary settings, and only 8% of all papers are RCTs. The anticipated revolution in personalized learning has not materialized. Instead, the most documented impact of AI in schools is on academic integrity (source: The Evidence Base on AI in K-12 Report.pdf).

## What AI Is Actually Doing in Schools

**Cheating**: A Pew Research survey found a majority of teenagers report AI-powered cheating is at least somewhat prevalent in their schools. AI that gives away answers — unlike [[khanmigo]], which refuses to — has become students' primary mode of AI interaction in academic contexts. This has created what teachers describe as a "massive headache."

**Teacher burden**: Teachers are grappling with how to design assignments that meaningfully assess student learning when AI can produce plausible responses to most prompts. Many are doing this without institutional support, often turning to AI themselves for help with lesson planning or feedback — ad-hoc and unsupported.

**AI tutoring underperformance**: [[Khanmigo]] and similar tools have failed to achieve the adoption their creators expected. Students who most need help are least likely to seek it out, even when AI tutoring is freely available. See [[ai-tutoring]] for detailed analysis.

## The Evidence Gap

The [[evidence-base-ai-k12]] report and the [[applied-co-intelligence-report]] both emphasize a near-total absence of rigorous research on AI in education. The Stanford SCALE review makes the gap concrete:
- **818 papers reviewed, 20 with strong causal evidence** — only ~2.4% of the literature clears the bar
- **Zero** high-quality causal student studies in U.S. K–12 settings
- Most studies concentrate in math/CS; literacy, social studies, and language learning are largely unstudied
- Studies compare "AI access" vs. "no AI access" — leaving open how *design choices* shape outcomes
- No research exists on developing student or teacher AI literacy
- Equity effects are largely unstudied; one study found AI widened achievement gaps for low-prior-knowledge students (Lehmann et al., 2025)

The National Science Foundation, Spencer Foundation, and US Department of Education have begun investing in this research agenda, but the field remains data-poor (source: Applied-Co-Intelligence PDF). The rapid evolution of AI systems also creates a structural tension: long-term studies risk measuring yesterday's tools (source: The Evidence Base on AI in K-12 Report.pdf).

## Three Theories of AI's Impact

A 2025 Chalkbeat analysis (cited in [[sal-khan-khanmigo-limits]]) identified three distinct theories of how AI will reshape schools:

1. **Cheating theory**: AI primarily makes academic dishonesty easier, degrading the signal quality of traditional assessments
2. **Teacher theory**: AI reshapes how teachers approach their work — potentially freeing time from routine tasks, potentially displacing roles
3. **Tutoring theory**: AI provides personalized, accessible academic support at scale — the promise that has so far most underdelivered

## Lessons from Khanmigo

The [[khanmigo]] experience provides the clearest real-world test of the tutoring theory so far. Key lessons:

- Technical capability is necessary but not sufficient; student motivation and question-asking skill are equally critical
- AI as a passive, optional resource will not be sought by students who most need it
- Embedding AI in structured tasks (as Khan Academy redesigned in 2026) is more effective than standalone availability
- "Caring adult" relationships — teacher presence and investment — remain irreplaceable for meaningful learning

## Small Language Models: A More Viable Path for Schools?

A growing argument — supported by two 2025 sources — is that general-purpose LLMs like ChatGPT may simply be the wrong tool for most school contexts, and that [[small-language-models]] (SLMs) offer a more practical fit. SLMs (roughly up to 20B parameters) are trained on curated, domain-specific data, run on standard school hardware without expensive GPUs, cost far less to operate, and are easier to align for safety and appropriate tone.

The [[small-language-models-k12]] article notes that only 6% of K-12 educators say AI does more good than harm — skepticism driven precisely by the safety and cost concerns that SLMs address. The [[small-models-big-support]] research demonstrates that 7B open-source models deployed entirely on-premises can achieve near-parity with Gemini 2.5 Pro on semantic similarity for educator tasks, while keeping all student data within the institution's secure network.

This is significant for addressing [[ai-privacy-and-institutional-adoption]] barriers: cost, privacy, and infrastructure constraints that currently make AI inaccessible to many under-resourced districts.

## Higher Education as a Leading Indicator

The [[columbia-cs-ai-disruption]] investigation (Columbia Spectator, May 2026) provides on-the-ground evidence of what AI disruption looks like inside a competitive CS program — and signals dynamics likely to cascade into K-12:

**Enrollment**: Total CS majors at Columbia fell 4.5% in 2024-25 even as some schools grew. Faculty report students still taking CS classes but majoring in other fields, treating technical skills as a cross-disciplinary baseline rather than a major. CS had the 5th highest unemployment rate among majors (7%) per the NY Fed in 2024. (source: Columbia CS article)

**Assessment restructuring**: Homework once accounted for 60-70% of CS grades; that balance has flipped, with exams and quizzes now the majority. Faculty are exploring computerized testing facilities to authenticate work. Students push back: exam-heavy grading doesn't reflect how CS is actually practiced. (source: Columbia CS article)

**Actual AI use**: Student surveys show 60-70% of AI users use it to have concepts explained, clarify instructions, generate test cases, or create practice problems — tutoring-like use, not wholesale homework submission. This complicates the dominant narrative. (source: Columbia CS article)

**A new equity dimension**: Students who arrive with K-12 AI literacy (prompt engineering, context engineering) are better positioned than those whose schools had no AI instruction. "To be born where you were is influencing your ability to get access to these spaces." Faculty also worry about paid vs. free AI tier access ($100+/month for premium tools). This turns K-12 AI policy gaps directly into college-entry inequities. (source: Columbia CS article)

**Social isolation**: Students increasingly ask AI the questions they would previously have directed to peers or TAs. Office hours attendance has dropped to near-zero for some students. A historically collaborative discipline is becoming more individually practiced — with unknown long-term consequences for the collaborative competencies employers value. (source: Columbia CS article)

## Implications for CTE

The [[applied-co-intelligence-report]] argues that AI's potential for positive impact is greater in CTE than in general K-12 education, precisely because CTE is oriented toward tangible skill development with clear industry benchmarks. The [[applied-co-intelligence-model]] offers a more structured approach than simple AI integration: a developmental continuum that progresses learners from passive literacy to expert-level mastery within an occupational context.

## Related pages

- [[khanmigo]]
- [[ai-tutoring]]
- [[sal-khan-khanmigo-limits]]
- [[cte-and-ai]]
- [[agentivism]]
- [[evidence-base-ai-k12]]
- [[columbia-cs-ai-disruption]]
- [[relational-economy]]
