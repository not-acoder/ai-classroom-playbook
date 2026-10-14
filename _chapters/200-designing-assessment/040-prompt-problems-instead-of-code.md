---
title: Assign Prompt Problems Instead of Code Writing
slug: prompt-problems-instead-of-code
play_number: 22
evidence: undocumented
drafted_steps: 2
total_steps: 5
last_checked: 2026-10
---


## Intent

Computing students are graded on decomposing a problem into a precise natural language specification and evaluating the code that comes back, rather than on writing the code themselves.


## Problem

Large language models solve the majority of the assignments and examinations historically used in introductory programming courses, so those tasks no longer measure what they were designed to measure. At the same time the skill mix in professional practice has shifted toward reading, comprehending and evaluating generated code, and toward specifying a problem well enough for a model to solve it. Banning the tools preserves the assessment and abandons the skill; permitting them without redesign abandons both.


## Solution

The instructor assigns a Prompt Problem. The student is shown a visual representation of a problem, never the text of a specification, and must formulate the natural language prompt that causes an LLM to generate code passing the test cases. The graded skill becomes problem decomposition, precise specification, and evaluation of returned code. Using the model is the assignment rather than a violation of it.


## Applicability

Works well in:

+ Introductory programming courses where LLM substitution has broken existing assignments
+ Courses that already run automated test cases, which supply the success criterion without new infrastructure
+ Programmes deliberately preparing students for LLM assisted professional practice

Tradeoffs and limitations:

+ Requires a visual problem representation for each exercise, which is real authoring effort and does not transfer from existing prompts
+ Model output is non-deterministic, so two students with comparable prompts can get different results, which needs handling in the marking scheme
+ The exercise assumes reliable student access to a model, which raises the access question in Play 27
+ It trains specification and evaluation, not code writing from scratch. If the latter remains a learning outcome it needs separate assessment

Not a good fit when:

+ Code writing fluency is itself the assessed outcome and cannot be relocated


## How to Implement

Steps 4 and 5 are drafted.

1. Take an existing programming exercise and produce a visual representation of the problem that conveys the requirement without giving the student text to copy into a model.
2. Have students formulate a prompt from the visual representation and submit it to an LLM.
3. Have students evaluate the returned code against the test cases and iterate on the prompt where it fails. The iteration is the learning.
4. _(Drafted)_ Assess the prompt and the student's account of their iteration, not only whether the final code passes, since a passing result can follow from a lucky generation.
5. _(Drafted)_ State how you will handle non-determinism before the assignment runs, since students will encounter it and will otherwise read it as unfairness.


## Examples

The source introduces Prompt Problems as a new exercise type in which students are presented with a visual representation of a problem and must devise a prompt that will guide an LLM to generate code solving it, positioning the exercise against the shift in importance toward reading, comprehending and evaluating LLM generated code.

A full course scale application exists. Vadaparty and colleagues report a CS1 course at a large research intensive university that embraces LLM use from the beginning of the course, reprioritising learning outcomes around specification and evaluation and giving students a recommended workflow for working with the model. Their follow up study examines student outcomes in that redesigned course. Note that the 2024 paper is an experience report rather than an outcomes study, and the outcomes claim belongs to the later paper.


## See Also

+ {% include chapter-link.html slug="teach-prompt-decomposition" %}
+ {% include chapter-link.html slug="equal-access-to-ai-tools" %}
+ {% include chapter-link.html slug="two-lane-assessment-design" %}


## Source

+ **Practice:** Denny, P., Leinonen, J., Prather, J., Luxton-Reilly, A., Amarouche, T., Becker, B. A., and Reeves, B. N. (2024). Prompt Problems: A New Programming Exercise for the Generative AI Era. SIGCSE 2024, pp. 296 to 302. https://doi.org/10.1145/3626252.3630909
+ **Course scale application:** Vadaparty, A., Zingaro, D., Smith IV, D. H., Padala, M., Alvarado, C., Gorson Benario, J., and Porter, L. (2024). CS1-LLM: Integrating LLMs into CS1 Instruction. ITiCSE 2024, pp. 297 to 303. https://doi.org/10.1145/3649217.3653584
+ **Outcomes follow up:** Vadaparty, A., Smith IV, D. H., Srinath, S., Padala, M., Alvarado, C., Gorson Benario, J., Porter, L., and Zingaro, D. (2026). Evaluating CS1-LLM. ACE '26. https://doi.org/10.1145/3786228.3786234

Described by: _TODO: add name and email_

Domain note. This is the only play in the collection restricted to a single discipline. It is retained because computing is the domain where LLM substitution of existing assessment is most complete, and because the underlying move, making specification and evaluation the graded skill, may transfer to other domains with a generative equivalent.


## Evidence Status

**Level:** undocumented.

No outcome data exists for Prompt Problems as a standalone exercise. The CS1-LLM course that builds on the same move has its own outcomes study, which evaluates the whole redesigned course, not this exercise alone. The 2024 CS1-LLM paper is an experience report, not an outcomes study.

**Outcome search, October 2026:** An experience report from the same research group found performance on natural language prompting tasks was less tied to students' reported difficulty than traditional assessments were (Kerslake and colleagues, 2024). No comparison group.

**Drafted steps:** 2 of 5, marked (Drafted) in How to Implement.


## Freshness

**Source dates:** Denny and colleagues, 2024. Vadaparty and colleagues, 2024 and 2026.

**Time sensitive assumptions:** The exercise shows the problem as a picture so students have no text to paste into a model. Current models can read images, which may weaken this. Not yet checked against a source; flagged by the drafter.

**Last checked:** October 2026.


## Community Discussion

Community members are free to comment on, ask questions about, share
experiences, or otherwise contribute to knowledge about this play by
posting comments below.

* Insert a comment here.
