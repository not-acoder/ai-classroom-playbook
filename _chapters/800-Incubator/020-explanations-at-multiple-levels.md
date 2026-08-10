---
title: Produce Explanations at Multiple Levels
slug: explanations-at-multiple-levels
---
## Intent

Students who do not understand one explanation of a concept receive alternative versions pitched at different levels and framed through different analogies.


## Problem

Effective explanation requires knowing what students already know, sequencing from simple to complex, providing organizational cues, and adding concrete anchors. Instructors are experts, and to explain clearly to novices they must access their own knowledge and deconstruct what they have long since automated. Producing several versions of one explanation adapted to different levels of student understanding is difficult and slow, so most students receive only the instructor's first version.


## Solution

The instructor asks the AI to generate multiple explanations of one concept from different perspectives, including step-by-step versions, simplified summaries, and analogies matched to the audience. The instructor can also supply their own existing explanation and ask the model to simplify it, add examples, or restructure it stepwise. Every generated explanation is a starting point that the instructor vets before it reaches students.


## Applicability

Works well in:

+ Courses with wide variation in student prior knowledge
+ Courses with few assigned readings, where supplementary explanation carries more weight
+ Review sessions before an assessment, where a simplified pass over a difficult topic is useful

Tradeoffs and limitations:

+ Explanations must be checked for factual accuracy and for being pitched at the right level
+ The model does not know what your specific students already know, so connections to prior course material must be requested explicitly
+ Simplification can quietly drop the qualifications that make a claim correct

Not a good fit when:

+ Precision of disciplinary terminology is itself the learning objective, and paraphrase would undermine it


## How to Implement

1. Pick the concept you want to explain.
2. If using a model with live search, tell it to look up the concept using core works in the field.
3. Tell the AI what you need: a clear multi-paragraph explanation of the topic.
4. Describe the writing style you prefer.
5. Describe your audience level.
6. Follow up the initial prompt by asking for analogies.
7. Check the result: is it clear and unambiguous, focused on the most critical parts, factually correct, adapted to student level, and connected to what students already know?
8. Deploy by integrating into lecture, adding to assignments or in-class exercises, or posting after class in the LMS to summarize key points.


## Examples

The source prompt asks the model to first pose two questions, which concept and which audience, then provide a multi-paragraph explanation using a specific example plus five analogies for understanding the concept different ways.

For an advanced class, the source suggests the inverse move: give students an explanation that is incomplete or wrong and ask them to fill the gaps and add the missing elements.

For students struggling before a test, the source recommends generating a simplified step-by-step explanation and posting it alongside a study guide, which the model can also produce.


## See Also

+ {% include chapter-link.html slug="generate-varied-examples" %}
+ {% include chapter-link.html slug="summarize-student-confusion" %}


## Source

Source: Mollick, E., & Mollick, L. (2023). *Using AI to Implement Effective Teaching Strategies in Classrooms: Five Strategies, Including Prompts.* The Wharton School of the University of Pennsylvania. <https://ssrn.com/abstract=4391243>

Described by: _TODO: add name and email_

All implementation steps taken from the source.

Evidence status: **undocumented**.


## References

[(Mollick & Mollick, 2023)](references.html#mollick-2023)


## Community Discussion

Community members are free to comment on, ask questions about, share
experiences, or otherwise contribute to knowledge about this play by
posting comments below.
See {% include chapter-link.html slug="join-discussions" %} for details.

* Insert a comment here.
