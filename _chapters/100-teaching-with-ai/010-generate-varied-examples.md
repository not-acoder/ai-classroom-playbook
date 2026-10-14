---
title: Generate Many Varied Examples of a Concept
slug: generate-varied-examples
play_number: 1
evidence: undocumented
drafted_steps: 0
total_steps: 7
last_checked: 2026-10
---


## Intent

Students encounter multiple varied examples of each difficult concept rather than a single illustration.


## Problem

Students given only one example of a complex concept tend to fixate on that example's surface details rather than the underlying principle. Producing many varied examples is time consuming: the instructor must balance engagement, relevance, and the right level of detail, and overly complex examples confuse while oversimplified ones fail to convey the concept's scope. The result is that a well supported teaching strategy goes unused because it is expensive to implement.


## Solution

The instructor uses a generative AI tool as an example generator. The instructor specifies the concept, the preferred writing style, and the audience level, then asks for several different and varied examples of the concept in action. The instructor vets the output for relevance, factual accuracy, sufficient detail, and genuine variety before using it. The AI absorbs the production cost while the instructor retains the judgment about what is worth showing students.


## Applicability

Works well in:

+ Courses with abstract or heavily conceptual material where students need multiple angles on one idea
+ Large courses where generating tailored examples for varied student backgrounds is otherwise impractical
+ Any course where the instructor has enough subject expertise to catch subtly wrong examples

Tradeoffs and limitations:

+ Examples can be subtly wrong in ways that teach the wrong lesson, so vetting is mandatory and takes real time
+ Models without live search access are more prone to fabricating plausible material
+ Output quality varies between models and between runs of the same prompt

Not a good fit when:

+ The instructor lacks the domain expertise to evaluate the output's accuracy
+ The concept is specialised enough that the model has thin coverage of it


## How to Implement

1. Pick a concept you want students to understand deeply.
2. If using a model with live search, tell it to look up the concept using core works in the field.
3. Tell the AI what you need: many varied examples of this one concept.
4. Describe the writing style you prefer, such as clear, straightforward, concrete, and engaging.
5. Describe your audience, such as college students who have not encountered the concept before.
6. Evaluate before using: are the examples relevant, factually correct, detailed enough, likely to interest students, and genuinely varied in the perspectives they take?
7. Deploy by weaving examples into lecture, posting them in the LMS as supplementary notes, or handing them to students as an exercise.


## Examples

The source provides a directly reusable prompt: instruct the model to act as an example generator for students, ask it to first request the concept and the student level, and then have it provide four different and varied accurate examples of the concept in action.

Three deployment variants from the source, in increasing difficulty: - Give students several examples and ask them to name the core conceptual principle the examples share. - Ask students to compare and contrast the examples and identify which aspect of the concept each one highlights. - For students with an existing knowledge base, deliberately include wrong or subtly wrong output and ask which examples demonstrate the concept and which do not, with reasoning.


## See Also

+ {% include chapter-link.html slug="explanations-at-multiple-levels" %}
+ {% include chapter-link.html slug="generate-case-studies" %}


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

**Time sensitive assumptions:** Step 2 distinguishes models with and without live search. That gap has largely closed since 2023, so the step now applies to most tools. The practice itself is unaffected.

**Last checked:** October 2026.


## Community Discussion

Community members are free to comment on, ask questions about, share
experiences, or otherwise contribute to knowledge about this play by
posting comments below.

* Insert a comment here.
