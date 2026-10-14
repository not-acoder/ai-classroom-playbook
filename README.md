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

Version 1.1. 29 plays in four chapters. All sources verified by direct fetch;
last checked October 2026.

| Chapter | Plays |
| --- | --- |
| 1. Teaching with AI: the instructor uses AI to produce instructional material | 10 |
| 2. Designing Assessment for the AI Era | 6 |
| 3. Teaching Students to Use AI Well | 5 |
| 4. Policy, Disclosure, Norms, and Access | 8 |

Play numbers are carried over from the previous draft rather than renumbered,
so they are not sequential within chapters. Each play records its original
number in the `play_number` front matter field; file name prefixes control
reading order within a chapter.


## The play form

Every play has the same eleven slots: the title plus ten sections.

| Section | What it holds |
| --- | --- |
| Intent | What the practice achieves, in one sentence |
| Problem | What goes wrong without it |
| Solution | The practice itself |
| Applicability | Where it works, its tradeoffs, and when it is a bad fit |
| How to Implement | Numbered steps. Steps the sources do not supply are marked _(Drafted)_ |
| Examples | Worked instances from the sources |
| See Also | Related plays |
| Source | Every source, labelled by the role it plays |
| Evidence Status | How strong the evidence is, and how much of the play the drafter wrote |
| Freshness | When the sources date from, which assumptions date them, and when the play was last checked |

The first eight sections are the play form used by the
[Playbook of Alternative Grading Practices](https://cs-alternative-grading-practices.github.io/playbook/),
with Examples added. Evidence Status and Freshness were added in version 1.1
because building version 1.0 kept running into the same two gaps: practices
and their evidence come from different literatures, and sources in this
domain date within a year or two.


## Evidence status

Each play states one evidence level:

- **documented**: a source reports outcome data for this practice
- **paired**: the practice comes from one source and outcome evidence from another. Marked "indirect" when that evidence tests a related practice rather than this one
- **undocumented**: the practice is described but no outcome evidence was found, after a search for outcome studies of that practice

Separately, each play reports how many of its implementation steps were
drafted rather than taken from a source. That is a different question from
evidence strength: a play can rest on strong evidence and still have most of
its steps written by the drafter. Play 21 is the clearest case.

Version 1.1 totals: 2 documented, 4 paired, 23 undocumented. Every play was searched for outcome studies in October 2026; the result is recorded in its Evidence Status. 21 of 29 plays
contain at least one drafted step, 50 drafted steps in all.

The same values are in each play's front matter (`evidence`,
`drafted_steps`, `total_steps`, `last_checked`) so they can be tabulated.


## Versions

- **v1.1** (October 2026): this version. See `CHANGELOG.md`.
- **v1.0** (August 2026): tagged `v1.0`. The playbook exactly as produced by
  running the inherited play template unchanged. The framework paper is built
  on it, so it is frozen. Make changes on top of v1.1, never on v1.0.


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
