# Columbia CS and AI Disruption

**Summary**: A May 2026 Columbia Spectator investigation into how AI is reshaping computer science education at Columbia — enrollment patterns, teaching restructuring, equity concerns, and student experience — offering ground-level evidence of AI's impact on a flagship CS program.

**Sources**: `raw/blog/'The reality, for better or worse'_ Columbia computer science students and faculty grapple with AI's disruption of the field.md`

**Last updated**: 2026-05-04

---

## Overview

*'The reality, for better or worse': Columbia computer science students and faculty grapple with AI's disruption of the field* was published May 3, 2026 by the Columbia Daily Spectator, written by Ria Vasishtha and Arjun Menon. It is a qualitative investigation drawing on interviews with CS students, faculty, and administrators at Columbia University (SEAS, Columbia College, Barnard, General Studies) and quotes from department leadership.

This is not a research study — it is journalism. Its value in this wiki is as **on-the-ground evidence** of what AI disruption looks like inside a competitive CS program in real time, supplementing the causal research in [[evidence-base-ai-k12]] with lived experience data.

## Enrollment Patterns

CS has grown dramatically at Columbia in recent years (source: Columbia CS article):
- CS accounts for ~11% of Columbia College degrees, ~32% of SEAS degrees, ~12% of General Studies degrees (2024)
- At Barnard, CS is now the second most popular major (up from third); degrees awarded have grown fivefold since 2016

But a shift is appearing (source: Columbia CS article):
- **Total CS majors across schools fell 4.5%** in 2024-25 (393 → 375), driven by declines at Columbia College and General Studies, even as SEAS grew slightly
- Faculty report that students are still taking CS classes but "majoring in other things" — treating technical skills as a baseline rather than a major field of study
- The surge in CS popularity was driven by its "apparent promise of a secure, well-paid career path"; generative AI has "compromised the sense of stability that once defined the field"

**The unemployment data**: According to the Federal Reserve Bank of New York (2024), out of 74 majors tracked, computer science had the **5th highest unemployment rate at 7%**, while computer engineering had the **2nd highest at 7.8%**. This is a striking inversion for a field once synonymous with guaranteed employment.

## The "Code Monkey" Problem

Faculty are explicit about which CS jobs are at risk (source: Columbia CS article):

> "A lot of people thought, 'Oh, it's a guaranteed path to a stable income. You get a six-figure job right out of your undergrad.' Now, companies may see AI as a way to reduce demand for entry-level programmers, especially in what he calls 'code monkey jobs,' roles where a large number of employees are 'just writing out code nine-to-five.'" — Daniel Bauer, senior lecturer, Columbia CS

This is consistent with the [[anthropic-labor-market-index]] finding: Computer Programmers are the most AI-exposed occupation (75% task coverage), and the young worker hiring slowdown is most pronounced in AI-exposed occupations.

Chris Murphy (senior lecturer) describes the current moment as the convergence of two forces: a post-2022 tech hiring downturn and generative AI. The earlier 2014-2016 boom made CS feel like both an academic discipline and a reliable employment path. "That feeling is harder to sustain now as the industry reconfigures."

## How Students Are Actually Using AI

Murphy surveyed students in his introductory classes. The results complicate the "students just submit AI homework" narrative (source: Columbia CS article):

> Around 60-70% of students who reported using AI said they used it to:
> - Have concepts explained
> - Clarify assignment instructions
> - Generate test cases
> - Create practice questions

Murphy: "Those are all ways that you might have had a tutor in the past to do that, and now you have this AI essentially as your tutor."

This finding has significant implications for the [[evidence-base-ai-k12]] evidence base: the actual pattern of AI use in CS education may be more tutoring-like and less wholesale-answer-generation than faculty assume. However, it doesn't address whether this tutoring use develops genuine capability or produces the passive comprehension that [[cognitive-debt]] describes.

One student at a Big Tech internship noted her intern class was the first to complete all assigned projects — attributed to AI-enabled efficiency. Meanwhile, "every single tech company was racing to integrate" LLMs.

## Teaching Is Being Restructured

The CS faculty response to AI has been to shift assessment toward in-person, harder-to-game formats (source: Columbia CS article):

- Homework once accounted for 60-70% of CS grades; that breakdown has **flipped**, with exams and quizzes now the majority
- Murphy shifted after his TAs called his belief that students weren't using AI "naïve"
- The department is exploring computerized testing facilities as an alternative to pen-and-paper exams: "We have to accept that this is the reality, for better or worse"

**Students push back**: More exams don't mean better learning, and don't reflect how CS is actually practiced. "Code is so variable and can be approached in so many directions, there's never just going to be one correct answer. There can be multiple optimal solutions." (Alexa Kafka, BC '27)

Students also worry the shift toward exams pulls focus away from applied, project-based work that better reflects both the discipline and industry expectations — the exact type of work that builds genuine capability rather than just test performance.

## The Department's Curricular Response

Columbia SEAS is making coordinated, department-wide changes (source: Columbia CS article):

- A working group has been **redesigning the introductory and intermediate programming sequence** to integrate generative AI as both subject and tool
- Goal: students should be able to **"read, verify, and reason about code, whether they or a model wrote it"**
- Assessment of how AI integration affects outcomes is underway to guide the next round of changes
- New pilot: individualized AI feedback in a discrete math course; a machine learning course is testing a **Socratic AI dialogue system** designed to "guide inquiry rather than supply answers"

This Socratic AI approach maps directly onto the [[evidence-base-ai-k12]] finding that Socratic chatbots (which ask guiding questions) produce better critical thinking outcomes than direct-answer chatbots — even though students rate them as less helpful.

**Structural initiatives**:
- New **AI minor for non-CS majors** (announced November 2025): "AI in Context," taught by faculty from CS, applied math, philosophy, music, literature, and the Writing Center; targets students who want to bring AI into fields like economics or biology
- New **Master of Science in AI** (inaugural cohort fall 2026)
- Seven cross-departmental faculty projects in generative AI funded this year (biomedical, chemical, industrial engineering, CS)

## Emerging Skills: Context Engineering and Vibe Coding

Students are developing new AI-specific skills ahead of formal curriculum (source: Columbia CS article):

**Vibe coding**: Prompting AI to write code for a task or project — widespread enough that Columbia's Application Development Initiative (ADI) ran a dedicated workshop. The gap between what students were doing and what was being taught was visible enough that student clubs stepped in.

**Context engineering**: Not just writing prompts, but optimizing "the rest of the relevant information that you would feed into the model." Without context engineering, AI-generated code can fail at scale or introduce difficult-to-detect bugs. This skill — managing what the model knows — is becoming a distinct technical competency.

Key shift in how students define competence: "The shift has kind of gone towards what can you create and what can you do, instead of, what do you know." (Asia Genawi, SEAS '29)

## Equity Concerns: Access and Prior Exposure

Two distinct equity issues are surfacing (source: Columbia CS article):

**1. Paid vs. free AI access**: Premium AI models (paid tiers of ChatGPT, Claude) can cost over $100/month and produce measurably better code outputs than free tiers. Faculty: "The equity issues I worry about are students who have access to paid versions of things versus free versions of things."

**2. K-12 AI literacy as a new form of prior advantage**: "Students who go to high schools or K-12 education where they're taught AI literacy, prompt engineering, context engineering — they understand how to do this, as opposed to students who go to schools who don't teach that. Then they come in, and then they're somehow expected to know how to use these tools." (Chris Murphy)

One student: "It's very interesting to consider how lucky you were geographically. To be born where you were is influencing your ability to get access to these spaces." (Asia Genawi)

This directly extends [[ai-privacy-and-institutional-adoption]]'s access concerns and [[ai-in-k12-education]]'s equity framing into the higher-education pipeline: K-12 AI policy gaps are producing a new dimension of pre-college preparation inequality.

## Social Isolation

A less-discussed consequence is emerging (source: Columbia CS article):

- Students in CS clubs report that as AI answers questions they would previously have asked each other, it is **isolating people** from peer learning communities
- One student has not attended office hours "in at least a year" — replacing that interaction with AI
- CS has traditionally been a **collaborative discipline** (code reviews, pull requests, pair programming); AI makes individual work easier, potentially undermining that collaborative culture

This pattern connects to Klein's concern in [[ai-job-apocalypse-klein]] about the deterioration of relational skills, and to [[cognitive-debt]]'s documentation of how AI use reduces the social cognitive processing involved in collaborative work.

## Relationship to This Wiki

- **[[evidence-base-ai-k12]]**: The Columbia data is qualitative but consistent with causal findings. The shift toward exams reflects the "process ≠ product" concern. The tutoring-like actual AI use pattern is a useful nuance.
- **[[ai-in-k12-education]]**: K-12 AI policy gaps are now visibly producing college-entry inequities — a downstream consequence.
- **[[cognitive-debt]]**: The social isolation finding and the office-hours drop are behavioral correlates of what the EEG data shows neurologically.
- **[[anthropic-labor-market-index]]**: CS unemployment (7%) and the "code monkey job" framing at Columbia confirm the observed exposure finding that Computer Programmers are most exposed and entry-level hiring is slowing.
- **[[relational-economy]]**: The shift from "what do you know" to "what can you create" mirrors the structural change from knowledge as the scarce resource to creative direction and human judgment as the scarce resource.

## Related pages

- [[ai-in-k12-education]]
- [[evidence-base-ai-k12]]
- [[cognitive-debt]]
- [[anthropic-labor-market-index]]
- [[relational-economy]]
- [[ai-job-apocalypse-klein]]
- [[ai-privacy-and-institutional-adoption]]
- [[transferable-skills]]
- [[stanford-ai-index-education-2026]]
