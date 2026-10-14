---
title: Draft Low-Stakes Diagnostic Quizzes
slug: low-stakes-diagnostic-quizzes
play_number: 3
evidence: paired
drafted_steps: 0
total_steps: 8
last_checked: 2026-10
---


## Intent

Students get frequent low stakes retrieval practice, and the instructor learns what students do not yet understand.


## Problem

Frequent low stakes testing is a learning event, not merely a measurement: repeated retrieval helps students retain information long term and shows them where their own gaps are. But building varied quizzes is

effortful. Instructors must align items to learning outcomes, write plausible distractors based on the misconceptions students actually hold, and find a reliable way to grade short answer components. The cost keeps a well evidenced practice out of regular use.


## Solution

The instructor assigns the AI the role of diagnostic quiz creator, supplies the topic and audience, and constrains the item format. The AI drafts questions with an answer key and explanations of the correct responses. The instructor verifies correctness, distractor plausibility, and alignment with course goals before deploying.


## Applicability

Works well in:

+ Content heavy courses where retrieval practice has clear value
+ Large courses where writing frequent quizzes by hand is unmanageable
+ Courses with publicly available assigned readings that can be included in the prompt

Tradeoffs and limitations:

+ Good distractors are hard to generate: they must attract students with incomplete understanding and reflect real misconceptions
+ Answers the model labels correct are not reliably correct and must be checked
+ Generated short answer rubrics need review for clarity, consistency, and measurability

Not a good fit when:

+ Assessment security matters and items must be novel and unpublished


## How to Implement

1. Assign the AI a role: creator of highly diagnostic quizzes.
2. State the topic you want tested and the teaching purpose, which is a low stakes assessment of student knowledge.
3. If you have assigned a publicly available reading, include it in the prompt. Multiple choice reading quizzes are a well suited case.
4. Constrain the item design: questions should go beyond facts, multiple choice items should include plausible competitive alternate responses, and there should be no all of the above option.
5. Ask for an answer key with an explanation of each correct response.
6. Check the output. Verify the correct answers are actually correct and that any generated rubric is clear, consistent, and measurable.
7. Confirm the items align with the goals for the unit and that success on them indicates command of the topic.
8. Deploy as in lecture hinge questions, an in class group exercise with teams reporting out, individual homework, or a discussion board post.


## Examples

A rubric checking technique from the source: ask the AI to answer its own question and then grade itself using the rubric it generated.

A deployment sequence from the source: distribute the test in class, then give students the answer key so they compare their responses against the correct ones, then follow with a reflection prompt asking which skills they think they need to work on and how they might improve.

The source frames in lecture items as hinge questions, which tell the instructor whether the class is ready to move on or whether the lesson needs adjusting.


## See Also

+ {% include chapter-link.html slug="distributed-practice-across-semester" %}
+ {% include chapter-link.html slug="draft-assessment-rubrics" %}


## Source

+ Mollick, E., and Mollick, L. (2023). Using AI to Implement Effective Teaching Strategies in Classrooms: Five Strategies, Including Prompts. The Wharton School Research Paper. https://ssrn.com/abstract=4391243
+ **Reading quiz application:** University of Pittsburgh, University Center for Teaching and Learning. Five Key Generative AI Strategies for Better Teaching. Last updated 9 February 2026. https://teaching.pitt.edu/resources/five-key-generative-ai-strategies-for-better-teaching/

+ **Evidence:** An, Y., Liu, J., Acharya, N., and Hashmi, R. (2025). Enhancing Student Learning with LLM-Generated Retrieval Practice Questions: An Empirical Study in Data Science Courses. arXiv:2507.05629. (Preprint.)

Described by: _TODO: add name and email_


## Evidence Status

**Level:** paired, weak.

Grounded in prior learning science evidence for the underlying strategy, but reports no outcome data for the AI assisted version.

**Outcome search, October 2026:** About 60 students in two data science courses scored 89 percent on LLM generated retrieval practice against 73 percent in a week without it (An and colleagues, 2025). A preprint comparing weeks, not a controlled trial, so differences between the weeks could explain part of the gap.

**Drafted steps:** none. All eight implementation steps come from the sources.


## Freshness

**Source dates:** Mollick and Mollick, March 2023. Pitt, last updated February 2026.

**Time sensitive assumptions:** The prompts were written for 2023 models. Re-test them on the tool you use before relying on the output.

**Last checked:** October 2026.


## Community Discussion

Community members are free to comment on, ask questions about, share
experiences, or otherwise contribute to knowledge about this play by
posting comments below.

* Insert a comment here.
