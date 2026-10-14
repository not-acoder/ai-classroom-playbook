---
title: Generate Case Studies and Scenarios with AI
slug: generate-case-studies
play_number: 19
evidence: undocumented
drafted_steps: 3
total_steps: 5
last_checked: 2026-10
---


## Intent

Students work through case based scenarios in courses where no suitable published cases exist.


## Problem

Case based learning depends on having cases, and for many courses the available cases are wrong: too advanced, from another discipline, dated, or written for a different national context. Writing a case from scratch requires inventing a plausible situation with enough detail to reason about and enough ambiguity to argue over. Most instructors do it once, reuse it for years, and watch it circulate among students.


## Solution

The instructor specifies the concept under study, the student level, and the context, and asks the AI for a case or scenario. Because cases are fictional by construction, the model's tendency to invent is less costly here than in factual material, though plausibility still has to be checked against how the domain actually behaves. Fresh cases each term also reduce the value of circulated solutions.


## Applicability

Works well in:

+ Professional and pre-professional programmes where case discussion is already the method
+ Courses where published cases are priced or licensed out of reach
+ Courses needing cases refreshed each term

Tradeoffs and limitations:

+ Generated cases can be plausible in surface detail and wrong in how the situation would actually unfold, which teaches the wrong intuitions
+ Cases can be too clean, resolving neatly toward one answer, when the pedagogical value is in the ambiguity
+ Cases involving people default to narrow demographic and cultural assumptions unless specified otherwise

Not a good fit when:

+ The learning objective depends on the case being real, as in courses studying documented events


## How to Implement

Steps 3, 4, and 5 are drafted.

1. Specify the concept, the student level, and the context, and ask for a case or scenario built around them.
2. Treat the output as a first draft and revise it into your own material.
3. _(Drafted)_ Check plausibility against how the domain actually behaves, not just internal consistency. A case can be coherent and still be wrong about the field.
4. _(Drafted)_ Check whether the case resolves too cleanly. If there is one defensible answer, add a constraint that creates a genuine trade off.
5. _(Drafted)_ Check the assumptions the case makes about the people in it, and vary them deliberately across the cases you use.


## Examples

Pitt lists case studies among the categories generative AI handles adeptly, in a single clause.

Whitman gives one adjacent concrete use, creating discussion scenarios for case based learning, and separately recommends scenario based learning exercises among supplementary materials.

Neither source supplies a worked case, a prompt, or any deployment guidance. This is the thinnest sourcing in Chapter 1 and the Examples section reflects it. See Appendix A.


## See Also

+ {% include chapter-link.html slug="generate-varied-examples" %}
+ {% include chapter-link.html slug="generate-activity-prompts" %}


## Source

+ University of Pittsburgh, University Center for Teaching and Learning. Five Key Generative AI Strategies for Better Teaching. Last updated 9 February 2026. https://teaching.pitt.edu/resources/five-key-generative-ai-strategies-for-better-teaching/
+ Whitman, M. (2025). Getting Started with AI in Higher Education: A Practical Guide for Faculty Newcomers. Aspen University. https://www.aspen.edu/altitude/getting-started-with-ai-in-higher-education-a-practical-guide-for-faculty-newcomers/ (A marketing article published by a for-profit university. Used for operational detail only.)

Described by: _TODO: add name and email_


## Evidence Status

**Level:** undocumented.

**Outcome search, October 2026:** Searched for further outcome studies of this practice; none found.

**Drafted steps:** 3 of 5, marked (Drafted) in How to Implement.


## Freshness

**Source dates:** Pitt, last updated February 2026. Whitman, 2025.

**Time sensitive assumptions:** None identified.

**Last checked:** October 2026.


## Community Discussion

Community members are free to comment on, ask questions about, share
experiences, or otherwise contribute to knowledge about this play by
posting comments below.

* Insert a comment here.
