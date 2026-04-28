# The Evidence Base on AI in K–12 Education

**Summary**: A 2026 systematic review by Stanford SCALE of 818 papers on AI in K–12 education — only 20 meet the bar for strong causal evidence, and zero are high-quality causal studies of student learning in U.S. K–12 settings.

**Sources**: `raw/The Evidence Base on AI in K-12 Report.pdf`, `raw/Your Brain on ChatGPT.pdf`

**Last updated**: 2026-04-28

---

## What This Is

*The Evidence Base on AI in K–12 Education* was produced by Stanford University's SCALE (Stanford Center for Assessment, Learning and Equity) in spring 2026. It reviews 818 papers from the AI Hub for Education Research Repository and identifies 20 with sufficient methodological rigor to contribute to causal findings. Papers were assessed using the What Works Clearinghouse (WWC) Handbook standards.

This report is the Stanford "overview paper" referenced in the [[sal-khan-khanmigo-limits]] Chalkbeat article, which described the evidence base as "extremely limited." The full report confirms and quantifies that characterization.

## The Headline Numbers

- **818 papers** reviewed in total
- **20 papers** with strong enough causal evidence to contribute to key findings
- **0 high-quality causal studies** on student learning in U.S. K–12 settings
- **8 causal studies** on educator use; **12 causal studies** on student use
- **64%** of causal research conducted in postsecondary settings
- **35%** of causal papers focus on math; heavily skewed away from literacy, social studies, language learning
- **8%** of papers are RCTs (randomized controlled trials)
- **59%** of all papers study students; the rest study educators or mixed populations

The report's core conclusion: the field is data-poor, evidence is narrow in scope, most studies are short-duration, and findings from international or postsecondary contexts may not transfer to U.S. K–12 classrooms.

## Key Finding 1: General-Purpose AI Harms Learning

The sharpest causal finding across student-facing studies is that general-purpose AI chatbots — tools that provide complete answers rather than guided hints — consistently undermine independent learning:

**The Turkey study (Bastani et al., 2025)**: ~1,000 high school students given access to a general-purpose AI chatbot to study for an exam performed *worse* than peers who worked through a textbook. Students given a tutoring-specific AI chatbot that provided *hints without direct answers* performed the same as textbook students. The general-purpose AI group showed higher performance during practice but crashed on the unassisted exam.

**The essay recall study (Kosmyna et al., 2025)**: Writing essays with AI chatbot assistance reduced brain activity and weakened recall. 83% of AI essay writers could not quote from their own essay afterward; only 11% of search-engine or no-tool users showed this failure. Students *preferred* the AI experience while producing worse outcomes. The full study (see [[your-brain-on-chatgpt]]) adds an EEG neurological mechanism — LLM users showed up to 55% reduced directed neural connectivity in semantic and memory networks — and a longitudinal finding: after three sessions of AI-assisted writing, participants who then wrote without tools showed brain connectivity *below the baseline of peers who had never written essays at all*. Kosmyna et al. call this accumulation of long-term cognitive harm [[cognitive-debt]].

**The crutch effect (Fischer et al., 2025)**: Unfettered AI access improved practice grades but caused a **17% performance drop** on unassisted exams. Adding pedagogical guardrails — an interface called "GPT Tutor" that required students to engage rather than simply receive answers — mitigated this crutch effect.

**The reasoning quality study (Stadler et al., 2024)**: Students using general-purpose AI chatbots to research scientific issues produced lower-quality reasoning and argumentation than students using traditional search engines.

**The widening gap study (Lehmann et al., 2025)**: Unrestricted AI chatbot access increased the volume of topics covered but *harmed* understanding and *widened achievement gaps* for students with low prior knowledge.

> "While AI can reduce perceived difficulty and increase fluency, this may come at the cost of reduced independent reasoning and weaker knowledge acquisition." — Dr. Matthias Stadler

> "Students keep bypassing heuristic guardrails — can we build a 'science of guardrails' to understand what works in education?" — Dr. Hamsa Bastani

## Key Finding 2: Tutoring-Specific Design Outperforms General-Purpose AI

The Bastani et al. Turkey study directly compared tutoring-specific AI (hints, guided questions) to general-purpose AI (direct answers) and textbook control. The tutoring-specific AI matched the textbook condition on exam performance, while general-purpose AI underperformed it.

This validates a core design principle: AI that withholds direct answers and guides students toward reasoning — as [[khanmigo]] was designed to do — is more educationally sound than AI that provides complete solutions. The problem with Khanmigo was adoption, not design philosophy.

**Socratic chatbots: students prefer what harms them.** Two studies examined Socratic AI chatbots (which ask guiding questions rather than providing answers). Students rated them as *less helpful* than direct-answer chatbots, despite evidence of better critical thinking outcomes. One study found students preferred Socratic chatbots to general-purpose chatbots for reflective thinking (Degen et al., 2025). The pattern: students' stated preferences diverge from their learning interests.

**Reading comprehension**: High-school students found AI use more enjoyable than traditional methods but showed better retention when AI was *complemented* by traditional strategies like note-taking, not used alone (Kreijkes et al., 2026).

## Key Finding 3: Educator-Facing AI Shows More Promise

Eight causal studies on educator-facing tools show more consistent positive findings:

| Study | Intervention | Outcome |
|-------|-------------|---------|
| Roy et al. (2024) | ChatGPT for lesson prep (with guide) | ~25 min/week saved (27–31% reduction), no quality loss; AI use became more selective over time |
| Demszky et al. (2025) | Automated feedback on classroom discourse | Teachers' use of "focusing questions" +20% |
| Demszky et al. (2023) | Automated feedback on uptake of student ideas | Instructor uptake +10%; student satisfaction improved |
| Wang et al. (2025) | Tutor CoPilot: real-time expert-like suggestions | Student mastery +4 pp overall; +7 pp for less experienced tutors; +9 pp for lower-rated tutors |
| LearnLM Team, Google & Eedi (2025) | LearnLM coaching tutors | Student performance on subsequent topics +5.5 pp |
| Kim et al. (2021) | Weekly AI diagnostic reports to tutors | Significant improvements in student learning outcomes |
| Holstein et al. (2018) | Smart glasses with real-time student analytics | Teachers redirected attention to struggling students; narrowed learning gap |
| Ferman et al. (2021) | AI automated writing evaluation | Essay scores improved; teachers reinvested saved time in individual conversations with students |

**The expertise reversal finding**: AI pedagogical supports are *most beneficial* for less experienced and lower-rated educators. This inverts the usual pattern where well-resourced schools benefit most from new tools. If access is equitable, AI coaching could be an equalizer of teacher quality — particularly valuable given that under-resourced schools disproportionately employ novice teachers.

**Dr. Dora Demszky (Stanford) draws a critical distinction**: Tools that *automate* teacher tasks may create efficiency but risk skill degradation and do not guarantee instructional quality. Tools that *build* teacher capacity — by providing consistent, customized feedback — are the higher-value design goal, and a domain where AI's cost and availability advantages over human coaching are most meaningful.

## Key Finding 4: Equity Questions Are Largely Unanswered

The evidence base provides limited insight into how AI affects educational equity:

**Student access**: Digital literacy, infrastructure at home, and language accessibility all mediate AI's benefits. Many tools are optimized for English and may provide lower-quality or biased support for English language learners. Impacts on students with IEPs or 504 plans are essentially unstudied.

**The widening gap risk**: Lehmann et al. (2025) found that AI chatbot access widened achievement gaps for students with low prior knowledge. AI may exacerbate rather than close existing inequities if deployed without deliberate design.

**The educator equity opportunity**: The Tutor CoPilot evidence (Wang et al., 2025) suggests AI pedagogical supports may help equalize access to high-quality instruction by upgrading novice teacher performance. But equitable access to these tools is not guaranteed — under-resourced districts may rely on free general-purpose tools that are less effective or raise privacy concerns.

For structural analysis of access barriers, see [[ai-privacy-and-institutional-adoption]].

## Student Wellness: An Understudied Frontier

Unlike earlier education technologies, AI blurs the boundary between purpose-built education tools and general-purpose social platforms. Survey data shows rapid growth in AI companion use by children and teens seeking emotional bonds with AI systems — a phenomenon that raises distinct developmental concerns beyond cheating and learning effects.

The SAFE AI Companions Task Force (EDSAFE AI Alliance, 2026) organized a research agenda around five topics: mandated reporting, student data privacy, prosocial design and use, learning sciences and pedagogy, and benchmarking.

This connects directly to the [[ai-delusional-spirals]] findings: unguided, emotionally responsive AI can amplify distorted beliefs in vulnerable users — a risk category that includes adolescents.

## What the Evidence Doesn't Tell Us

The report is candid about its limits:

- Most studies compare "AI access" vs. "no AI access" — leaving open how *design choices* shape outcomes
- Most evidence covers short-term task performance, not engagement, metacognition, or long-term skill development
- No studies on AI literacy development for students or teachers (a "timely topic" the report explicitly notes)
- No research on collaborative or group AI use — almost all studies examine 1:1 chatbot interactions
- Rapid AI tool evolution creates tension: long-term studies measure yesterday's tools

The report closes with its central question: not just *whether* AI tools work on average, but *when, how, and for whom* they matter most.

## Relationship to This Wiki

This report is the most comprehensive causal evidence base for claims made across multiple pages:

- The "extremely limited" evidence characterization in [[ai-in-k12-education]] now has specific numbers (818 papers, 20 causal)
- The tutoring design findings directly support [[ai-tutoring]]'s conditions for effectiveness
- The general-purpose AI harm findings provide empirical grounding for [[agentivism]]'s propositions (P2, P3, P4)
- The educator AI findings add a new dimension to [[ai-tutoring]] and [[khanmigo]]
- The equity and widening-gap findings deepen [[cte-and-ai]]'s equity section

## Related pages

- [[ai-in-k12-education]]
- [[ai-tutoring]]
- [[agentivism]]
- [[khanmigo]]
- [[sal-khan-khanmigo-limits]]
- [[cte-and-ai]]
- [[ai-privacy-and-institutional-adoption]]
- [[ai-delusional-spirals]]
- [[your-brain-on-chatgpt]]
- [[cognitive-debt]]
