# One Click Away: AI Tutoring with Khanmigo in a Two-Year School Experiment

**Summary**: An NBER working paper (Oreopoulos & Low, August 2026) reporting the largest and longest randomized controlled trial of an AI tutor in public schools to date — two years, 18 Tennessee middle schools, 53 randomized clusters. Khanmigo raised math achievement by 0.06-0.08 SD/year, statistically indistinguishable from Khan Academy's effect *without* AI assistance, because engagement with the AI tutor — not access to it — was the binding constraint: the median student sent Khanmigo no messages on two-thirds of the days they practiced.

**Sources**: `raw/PDF/One Click Away.pdf` (Oreopoulos & Low, NBER Working Paper 35620, August 2026)

**Last updated**: 2026-08-28

---

## About this study

Philip Oreopoulos (University of Toronto/NBER) and Nina Low (Charles River Associates) conducted a cluster-randomized trial across the 2024-25 and 2025-26 school years in Hamilton County, Tennessee. Within 18 middle schools, one or two grades per school were randomly assigned to use Khan Academy with Khanmigo (Khan Academy's GPT-4-based AI tutor, configured to coach via guiding questions rather than give direct answers) during the district's existing daily Response to Intervention (RTI) remedial mathematics sessions; control grades continued business-as-usual remediation (a mix of teacher-led practice and non-conversational adaptive software). Because delivery was embedded in mandatory session time rather than offered as an opt-in resource, the study avoids the selective-takeup problem that limits most educational-technology evaluations — this is the wiki's first randomized, large-scale evidence on what happens when an AI tutor is simply made available to *ordinary* students within *routine* instruction, rather than to a self-selected or lab-recruited sample.

## The three headline findings

**1. The program worked — but not obviously because of the AI.** Assignment raised end-of-term MAP mathematics scores by 1.3 national percentile ranks per term (about 0.06-0.08 SD per school year), concentrated in Year 2 (0.084 SD, statistically significant) as implementation matured; the implied effect for actively participating students in Year 2 reaches 0.14 SD — nearly half the effect of the most intensive human tutoring programs, at a fraction of the cost. Critically, these gains "are similar to those predicted by the same platform without AI assistance" — quasi-experimental estimates of Khan Academy practice *without* Khanmigo imply nearly identical per-hour returns. **Nothing in the achievement data requires the AI tutor to explain it.**

**2. Access was nearly universal; engagement was thin.** 96% of treated students messaged Khanmigo at least once. But the median student sent it a message on only 33% of the days they practiced, in only 14% of exercise sessions, and in only 17% of sessions where they'd made a mistake — the exact moment a tutor is nominally for. The typical exercise session, of any kind, contained no message to the tutor at all.

**3. The messages students did send required little mathematical thinking.** Classifying all student messages: 39.4% were bare numeric answers to Khanmigo's own questions, 24.2% were clicks on suggested prompts, 12.6% were low-effort ("idk," requests for the answer), 9.3% were off-task. Only **14.5%** — roughly one message in seven — contained an actual mathematical question or a step of reasoning.

## Why this is the rigorous version of a story the wiki already has

The wiki already documents Khan Academy's own qualitative admission that Khanmigo was, for most students, "a non-event" ([[sal-khan-khanmigo-limits]], Chalkbeat, April 2026) — Sal Khan's own account, Kristen DiCerbo's "students aren't great at asking questions well," and the geometry teacher at Hobart High School who stopped using it. This paper is the **large-scale, randomized, causally identified version of that same story**. Where the Chalkbeat piece offers a single school's anecdote and a company's internal reflection, this NBER paper offers message-level engagement data matched to exercise logs across 563 students, 100,017 exercise sessions, and two full school years. The mechanism the wiki previously had as a plausible narrative — "students don't seek out help, and when they do, they don't engage substantively" — is now precisely quantified: 33% of days, 14% of sessions, 14.5% of messages containing real mathematical content.

## Mechanism: this is agentivism and the learning-performance paradox, demonstrated at scale

This paper is a field-scale empirical instance of two theoretical frameworks already central to the wiki:

- **[[agentivism]]**: durable learning requires epistemic monitoring and reconstructive internalization — actively evaluating and reworking an AI's output rather than passively receiving it. The paper's finding that bare answers and button-clicks dominate student-tutor interaction, while genuine mathematical reasoning appears in only 1 in 7 messages, is exactly the "metacognitive laziness" failure mode Agentivism predicts — now measured directly rather than inferred.
- **[[building-ai-companions]]**'s learning-performance paradox and "seeking help with one's own confusion remained a choice, and most students declined it most of the time" — a direct restatement of the paper's own interpretation, which explicitly cites behavioral-economics evidence on help-avoidance (Lavecchia et al., 2016) as the operative mechanism, not a defect specific to Khanmigo's design.

The paper's own interpretation converges with the wiki's existing thesis almost exactly: "The limited dialogue we document is thus less a defect of the AI tutor than a lack of interest in attention and learning" — and "making AI effective for learning appears to be as much a behavioral challenge as a technological one."

## What carries the achievement effect, if not the tutor

Within the treated arm, achievement growth is associated with the **mastery-of-skills margin of practice** (each additional skill brought to proficiency per week: +0.015 SD), not with chat activity — the Khanmigo-chat association shrinks to approximately zero once skill mastery is controlled for. The paper's interpretation: the program functioned in large part as an **implementation technology for the remedial block itself** — automatically placing each student into the correct difficulty level from their MAP scores, standardizing pacing and content in ways that vary widely across ordinary teacher-led remediation — rather than as a conversational tutoring technology. Realized dosage (30 minutes/week average, rising to 45+ minutes among actively-enrolled students in Year 2) approximates the platform's recommended dose and stands in sharp contrast to voluntary AI-tutoring deployments elsewhere, where median use is close to zero.

## Cost-effectiveness: real, but modest, and not about the AI

At roughly **$15 per student per year** (the license cost; delivery occurred within remedial blocks districts already staff), the program delivers a meaningful share of the individualized-feedback margin that has historically required several-thousand-dollar-per-student human tutoring — a genuine scaling achievement. But the paper is explicit that this is a statement about **structured adaptive practice**, not about conversational AI tutoring specifically: "the AI tutor — included in the license but contributing no detectable achievement effect as deployed — represents capability districts have already paid for" without it converting to measured learning gains.

## Subsequent developments the paper treats as corroboration, not coincidence

Khan Academy redesigned Khanmigo in 2026 to activate automatically during practice rather than requiring a student click — explicitly because "students had not been seeking out the tutor's help on their own." This is the same 2026 product redesign already documented in [[khanmigo]] and [[sal-khan-khanmigo-limits]]; this paper is the first source in the wiki to show, with matched message-level data, exactly what usage pattern motivated that redesign.

## Limitations, stated by the authors

The design cannot isolate the AI tutor's marginal contribution from the rest of the bundled program (structured, MAP-placed practice delivered simultaneously). The control-arm counterfactual is heterogeneous and not technology-free — most control classrooms also used adaptive practice software, just without conversational AI — so the estimated effect is against realistic business-as-usual remediation, not a never-software baseline. The sample is below-grade-level middle schoolers in one Tennessee district; generalization to other populations, subjects, or AI tutor designs is not established. State test (TCAP) results, registered as a co-primary outcome, were not yet finalized at the time of writing.

## Implications for CTE

1. **This is now the single most rigorous piece of evidence in the wiki for why AI tutoring interventions must force engagement rather than merely offer it.** For CTE program design, this reinforces (with RCT-scale evidence) the applied-co-intelligence-model's insistence that AI mastery must be built into structured, assessed tasks — not left to student initiative.
2. **The "implementation technology" reading is directly relevant to CTE's own AI-adoption debates**: much of this program's real value came from automated, MAP-linked placement and pacing — a lesson for CTE programs considering AI tools that the biggest near-term wins may come from structuring and personalizing *existing* practice, not from adding conversational AI on top of it.
3. **The contrast with [[applied-co-intelligence-model]]'s implementation case studies is instructive** (see [[aci-three-cte-programs]]): Khanmigo's null incremental effect comes from a generic, decontextualized subject with low student-initiated engagement, while the ACI model's occupation-embedded case studies (soil science scenario prompts, welding AI feedback loops) build engagement into the task itself rather than relying on student-initiated help-seeking. This is a natural, if informal, test of the ACI model's central design claim.

## Related pages

- [[khanmigo]]
- [[sal-khan-khanmigo-limits]]
- [[ai-tutoring]]
- [[agentivism]]
- [[evidence-base-ai-k12]]
- [[building-ai-companions]]
- [[cognitive-debt]]
- [[applied-co-intelligence-model]]
- [[aci-three-cte-programs]]
- [[ai-agents-k12-meta-analysis]]
