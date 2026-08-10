# The Playbook of AI in the Classroom

Generative AI arrived in higher education faster than guidance for using it
did. Instructors are told that these tools will change teaching, and they are
told to worry about academic integrity, but between the enthusiasm and the
alarm there is very little that answers the practical question: what,
concretely, should I do differently on Monday?

Guidance that does exist is scattered across teaching-center pages, working
papers, and institutional policy reports. It is written at different levels of
abstraction, aimed at different audiences, and rarely says what a practice
costs, when it fails, or whether anyone has measured whether it works.

This **Playbook** collects practical *recipes* (or "plays") describing
specific practices an individual instructor can choose to adopt. Each play
names one practice, states the problem it addresses, describes the solution in
enough detail to act on, is explicit about tradeoffs and about when the
practice is a bad fit, and cites the source it came from.

Plays are scoped to what one instructor can adopt in one course. Institution
level policy, tool development, and K-12 only practices are out of scope.


## Contents

Version 1. 29 plays in four chapters. All sources verified by direct fetch.

| Chapter | Plays |
| --- | --- |
| 1. Teaching with AI — the instructor uses AI to produce instructional material | 10 |
| 2. Designing Assessment for the AI Era | 6 |
| 3. Teaching Students to Use AI Well | 5 |
| 4. Policy, Disclosure, Norms, and Access | 8 |

Play numbers are carried over from the previous draft rather than renumbered,
so they are not sequential within chapters. Each play records its original
number in the `play_number` front matter field; file name prefixes control
reading order within a chapter.


## Evidence status

Every play states its evidence status at the end of the Source section, using
four values:

- **documented** — the source reports outcome data for this practice
- **paired** — the practice comes from one source and outcome evidence from another
- **undocumented** — the practice is described but no outcome evidence was found
- **steps-drafted** — implementation steps were written by the drafter and are labelled inline

Implementation steps not supported by a source are marked `(Drafted)` inline.


## Repository layout

```
_chapters/
  000-front/                            Title page and table of contents
  100-teaching-with-ai/
  200-designing-assessment/
  300-teaching-students-to-use-ai-well/
  400-policy-disclosure-norms-and-access/
```

Chapter parts are directories named `NNN-part-name`; the site derives the
chapter heading from the directory name. Plays are files named `NNN-slug.md`,
where the slug in the front matter sets the URL and must be unique.


## Running the site locally

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.
