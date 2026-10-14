---
title: Build Distributed Practice Across the Semester
slug: distributed-practice-across-semester
play_number: 5
evidence: undocumented
drafted_steps: 0
total_steps: 7
last_checked: 2026-10
---


## Intent

Students revisit earlier course topics at spaced intervals rather than encountering each topic once and moving on.


## Problem

Practising material several times across days and months builds robust, flexible knowledge and helps students connect ideas. Most course materials work against this: topics are covered one after another in a linear sequence, without reference to previous topics or explicit connections between them. Students also prefer massed practice and continue to cram even when told spacing works better. Implementing distributed practice requires the instructor to identify the most important topics, decide which connections are critical, produce materials, and schedule them at intervals, which is slow work.


## Solution

The instructor gives the AI the course schedule and asks it to generate review questions that connect

current content to previously covered topics, along with guidance on when each set should be used. These items are folded into later quizzes and class activities. As students begin answering the early items correctly, the instructor asks for harder versions or alternate sequences.


## Applicability

Works well in:

+ Semester long courses with cumulative content
+ Courses where later topics genuinely build on earlier ones
+ Courses that already run regular quizzes, which can absorb additional items without new infrastructure

Tradeoffs and limitations:

+ The model may surface connections that exist but are not important
+ Suggested items may be too easy or too difficult, or may not test what matters most
+ The model's timing suggestions need checking against your actual course calendar

Not a good fit when:

+ Course topics are genuinely modular with few meaningful cross connections
+ Students will resist the apparent inefficiency and the instructor is not prepared to explain the rationale


## How to Implement

1. Decide what you want students to still know and remember about each topic at the end of the course.
2. Give the AI a week by week syllabus schedule of topics with a brief description of each.
3. State the level of students you are teaching.
4. Ask for quizzes containing both short answer and multiple choice items that test students on new and previously learned topics and that connect the two. Require later weeks' quizzes to include topics from earlier weeks.
5. Ask the AI to tell you when each quiz should be used in the course.
6. Evaluate the suggestions: are the exercises related to key topics, will they help students connect new and old information, are they feasible given your time frame, and do they offer varied ways of reviewing rather than repeating?
7. Once most students answer the initial questions correctly, ask the AI to increase difficulty or alternate the questions in a sequence.


## Examples

The source's concrete structure: three quizzes, each containing two short answer and two multiple choice questions, with the later quizzes required to include topics learned in earlier weeks, plus instructions on when to use each.

A second use from the source: ask the AI how a previously covered topic relates to the topic students are studying now, then make that connection explicit in lecture or discussion, reminding students what they already learned and linking it forward.

A scheduling principle from the source: introduce a topic, then review it after a week, after a month, and again at the end of the semester, allowing enough forgetting that retrieval takes real effort.


## See Also

+ {% include chapter-link.html slug="low-stakes-diagnostic-quizzes" %}


## Source

+ Mollick, E., and Mollick, L. (2023). Using AI to Implement Effective Teaching Strategies in Classrooms: Five Strategies, Including Prompts. The Wharton School Research Paper. https://ssrn.com/abstract=4391243

Described by: _TODO: add name and email_


## Evidence Status

**Level:** undocumented.

Grounded in prior learning science evidence for the underlying strategy, but reports no outcome data for the AI assisted version.

**Outcome search, October 2026:** Searched for further outcome studies of this practice; none found.

**Drafted steps:** none. All seven implementation steps come from the sources.


## Freshness

**Source dates:** Mollick and Mollick, March 2023.

**Time sensitive assumptions:** The prompts were written for 2023 models. Re-test them on the tool you use before relying on the output.

**Last checked:** October 2026.


## Community Discussion

Community members are free to comment on, ask questions about, share
experiences, or otherwise contribute to knowledge about this play by
posting comments below.

* Insert a comment here.
