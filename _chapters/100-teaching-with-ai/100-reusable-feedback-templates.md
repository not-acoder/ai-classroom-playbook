---
title: Anticipate Misconceptions and Draft Reusable Feedback Templates
slug: reusable-feedback-templates
play_number: 11
evidence: paired
drafted_steps: 0
total_steps: 5
last_checked: 2026-10
---


## Intent

The instructor builds a personalisable bank of feedback comments for the errors students recurrently make, instead of writing each comment from scratch.


## Problem

Timely feedback is among the most valuable things an instructor provides and among the first things sacrificed under load. Much of its content repeats across students and across terms, but rewriting the same explanation dozens of times is slow, and quality drifts as fatigue accumulates. Anticipating which errors will recur is itself a skill that takes years to develop, and the instructor's own expertise works against it: having long since automated the concept, the instructor no longer has direct access to the ways a novice goes wrong.


## Solution

The instructor uses AI in two connected ways: to surface the common mistakes and misconceptions students hold about a specific concept, and to draft feedback templates addressing them. Templates are then personalised for individual students rather than pasted unchanged. All generated content is reviewed and modified before it reaches students; the AI produces a starting point, not a final product.


## Applicability

Works well in:

+ Courses with recurring assignment types where similar errors appear each term
+ Large sections where feedback volume is the binding constraint
+ Courses where feedback is currently late or thin because of workload

Tradeoffs and limitations:

+ Templated feedback reads as generic if it is not genuinely personalised
+ The generated misconception list reflects the model's expectations, not your students, and must be checked against actual submissions
+ Time saved on drafting can be lost to editing if the templates do not match your voice

Not a good fit when:

+ Assignments are highly individual and errors do not recur in patterns


## How to Implement

1. Ask the AI, acting as a subject matter expert in your course, to identify common mistakes and misconceptions students have about a specific concept or skill, and to suggest strategies for addressing them proactively.
2. Check that list against the errors you actually see in your students' work.
3. Draft a feedback template for each recurring issue, specifying the role, level, and skill in the prompt to improve the output.
4. Review and modify every template so it aligns with your course objectives and teaching style.
5. Personalise each template for the individual student rather than sending it unchanged.


## Examples

Mollick and Mollick identify uncovering and addressing student misconceptions as one of five evidence based strategies AI makes practical.

Whitman supplies a directly reusable prompt with bracketed fields: act as a subject matter expert in a named course, identify common mistakes and misconceptions students have about a named concept or skill, and suggest strategies to address them proactively. Whitman recommends applying the same role, level, and skill framing when generating the feedback templates themselves.

Two randomised trials bear on whether AI assisted feedback works, and both point the same way with the same caveat. Lu and colleagues ran a controlled trial in a large introductory economics course with 354 students and 11 teaching assistants across 1,366 essays. Students receiving feedback that teaching assistants had authored with AI suggestions produced significantly higher quality revisions, an effect the authors describe as roughly equivalent to moving a student from the 50th to the 70th percentile. Teaching assistants approved 88.7 percent of the AI's rubric level judgments and corrected the remaining 11.3 percent. Zhang ran a four week randomised controlled trial with 259 undergraduates comparing AI generated writing feedback with instructor feedback and reported significant improvement in the AI condition, strongest on organisation and content development.

In both trials the AI operated against explicit rubrics and under human review. Neither tested AI feedback delivered to students without an instructor in the loop.


## See Also

+ {% include chapter-link.html slug="draft-assessment-rubrics" %}
+ {% include chapter-link.html slug="summarize-student-confusion" %}


## Source

+ **Practice:** Mollick, E., and Mollick, L. (2023). Using AI to Implement Effective Teaching Strategies in Classrooms: Five Strategies, Including Prompts. The Wharton School Research Paper. https://ssrn.com/abstract=4391243
+ **Operational prompt:** Whitman, M. (2025). Getting Started with AI in Higher Education: A Practical Guide for Faculty Newcomers. Aspen University. https://www.aspen.edu/altitude/getting-started-with-ai-in-higher-education-a-practical-guide-for-faculty-newcomers/ (A marketing article published by a for-profit university. Used for operational detail only.)
+ **Evidence:** Lu, X., Ju, K. P., Dudley, M., Sano, L., and Wang, X. (2026). AI-Mediated Feedback Improves Student Revisions: A Randomized Trial with FeedbackWriter in a Large Undergraduate Course. CHI '26, Barcelona. https://doi.org/10.1145/3772318.3791121
+ **Evidence:** Zhang, K. (2025). Enhancing Critical Writing Through AI Feedback: A Randomized Control Study. Behavioral Sciences 15(5):600. https://doi.org/10.3390/bs15050600

Described by: _TODO: add name and email_

Revision note. In the previous draft this play was sourced only to Whitman and carried the claim that the source offered anecdotal evidence that feedback scales while quality holds. The source contains no such claim and it has been removed. The practice has been re-grounded on Mollick and Mollick, whose misconceptions strategy this play implements, and real outcome evidence has been attached.

Scope note. Discovery originally described a workflow passing individual student submissions to AI for per-student draft feedback. No source describes that. The narrower version here creates reusable templates the instructor personalises, which is what the sources support and which avoids sending student work to an external tool. See Play 28.


## Evidence Status

**Level:** paired, indirect. Both trials tested AI assisted feedback in general, not instructor drafted templates.

In both trials the AI worked against explicit rubrics and under human review. Neither tested AI feedback delivered to students without an instructor in the loop.

**Outcome search, October 2026:** Zhang re-checked: double blind randomised trial, 259 students, four weeks, Qwen-7B based feedback against trained instructors, 0.149 standard deviation greater gain in overall writing score. The paper's group counts are inconsistent (130 and 129 in Methods, 125 and 134 in Results).

**Drafted steps:** none. All five implementation steps come from the sources.


## Freshness

**Source dates:** Mollick and Mollick, March 2023. Whitman, 2025. Zhang, 2025. Lu and colleagues, 2026.

**Time sensitive assumptions:** Both trials evaluated specific systems, FeedbackWriter and a Qwen based tool. Results may not carry over to other tools.

**Last checked:** October 2026.


## Community Discussion

Community members are free to comment on, ask questions about, share
experiences, or otherwise contribute to knowledge about this play by
posting comments below.

* Insert a comment here.
