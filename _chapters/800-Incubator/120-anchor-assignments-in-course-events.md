---
title: Anchor Assignments in Course-Specific Events
slug: anchor-assignments-in-course-events
---
## Intent

Students complete assignments that require information generated inside the course and unavailable to a model.


## Problem

Assignments that were sound five years ago can now be answered competently by a general-purpose model, because everything they draw on is public. Banning tools does not fix this and detection is unreliable. The durable move is to change what the assignment requires rather than to police how it was produced.


## Solution

The instructor crafts assignments that connect student work to things that happened in the class: a specific discussion, a guest session, a lab result, a dataset the class generated, a debate that occurred in week six. A model cannot access this material, so the assignment resists substitution as a side effect of being more specific. The same move also creates retrieval opportunities and pushes students toward metacognition, so it improves the assignment on its own terms rather than only as a defensive measure.


## Applicability

Works well in:

+ Courses with substantial discussion, lab, or studio components that generate their own material
+ Seminar and project courses where shared class experience accumulates over a term
+ Any course where the instructor is already revising assignments and can fold this in

Tradeoffs and limitations:

+ Assignments become harder to reuse across terms, since the anchors change
+ Students who miss sessions are disadvantaged in a way a generic prompt would not disadvantage them
+ The strategy weakens as models gain access to more course material through students' own uploads

Not a good fit when:

+ The course is asynchronous with little shared class experience to anchor to
+ Assignments must be standardized across many sections


## How to Implement

1. Review an existing assignment and identify what information it draws on. If all of it is public, the assignment is substitutable.
2. Identify course-specific material that could anchor it: an in-class discussion, a demonstration, a class-generated dataset, a guest speaker, a decision the class made together.
3. Rewrite the prompt so the anchor is load-bearing rather than decorative. The student should not be able to answer well without having been present.
4. Add a component calling for active reflection, which requires material a model does not produce as competently.
5. _(Drafted)_ Keep a record of which anchors you used, since the assignment will need new ones next term.


## Examples

The source frames this as one of three integrity measures that also function as good teaching: shifting from few high-stakes assessments to more frequent smaller ones, incorporating components that call for active reflection, and crafting assignments that connect student work to in-class events. It notes that the third both enhances metacognition and provides retrieval opportunities while tapping into information generative AI cannot access.

The source does not supply worked assignment prompts.


## See Also

+ {% include chapter-link.html slug="oral-and-in-class-formats" %}
+ {% include chapter-link.html slug="summarize-student-confusion" %}


## Source

Source: University of Pittsburgh, University Center for Teaching and Learning. *Five Key Generative AI Strategies for Better Teaching.* Last updated 9 February 2026. <https://teaching.pitt.edu/resources/five-key-generative-ai-strategies-for-better-teaching/>

Described by: _TODO: add name and email_

Steps 1 through 4 follow the source's guidance. Step 5 is drafted.

Evidence status: **undocumented**.


## References

[(University of Pittsburgh, 2026)](references.html#pitt-2026)


## Community Discussion

Community members are free to comment on, ask questions about, share
experiences, or otherwise contribute to knowledge about this play by
posting comments below.
See {% include chapter-link.html slug="join-discussions" %} for details.

* Insert a comment here.
