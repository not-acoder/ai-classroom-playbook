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
practice is a bad fit, and cites the source it came from. Individual plays
include a discussion area at the bottom where anyone in the community can add
their own experiences, ask questions, or further develop ideas.

Plays are deliberately scoped to what one instructor can adopt in one course.
Institution-level programs, curriculum-wide initiatives, and statements of
value are out of scope.


## Status

**Draft.** All 16 plays currently sit in the
[Incubator](https://not-acoder.github.io/ai-classroom-playbook/incubator.html).
They have been mined from sources, verified against those sources, and
drafted, but they have not been reviewed or scored, and they have not been
sorted into chapters. Chapter structure is expected to emerge from the plays
rather than being imposed on them.

Every play records its **evidence status** in the Source section. Most of these
practices are documented but not measured: the source describes the practice
and reports no outcome data. That is stated plainly on each play rather than
smoothed over.

Where an implementation step was written by the drafter rather than taken from
the source, it is marked `(Drafted)` inline.


## Relationship to the AGP Playbook

This playbook uses the structure, template, and tooling of
[The Playbook of Alternative Grading Practices](https://cs-alternative-grading-practices.github.io/playbook/)
without modification. That is a deliberate methodological choice, not
convenience. The point of building a second playbook in a different domain is
to find out where a template developed for one domain resists another. Patching
the template in advance would destroy that measurement.

Observations about where the template resisted are recorded in
[`research/appendix-a-template-resistance.md`](research/appendix-a-template-resistance.md),
which is versioned in this repository but not published to the site.


## Contributing

This Playbook is a community-driven resource that welcomes contributions.
All contributions are covered by the CC BY-NC-SA license (see [LICENSE](LICENSE)).
We welcome contributions of all of the following types:

- Suggestions for new plays to include
- Comments or shared experiences added to the discussion of existing plays
- Writing entirely new plays
- Editing/fixing content

Please read [How to Contribute](https://not-acoder.github.io/ai-classroom-playbook/contributing.html)
for instructions on how to file an issue or create a pull request. Or, when
viewing any page on the live site, click the **GitHub icon** in the header of
the left sidebar to go directly to the corresponding source file and use
GitHub's inline editing to open a pull request from your browser.


## Repository layout

```
_chapters/
  000-front/            Title page and table of contents
  800-Incubator/        The 16 drafted plays, awaiting review and chapter assignment
  900-how-to-contribute/  Contributor instructions, play template, discussion norms
  999-back/             References
research/               Research record; excluded from the built site
```

Chapter parts are directories named `NNN-part-name`. The site derives the part
heading from the directory name, so renaming a directory renames the chapter.
Parts numbered `000` and `999` are unnumbered front and back matter.

Plays are files named `NNN-slug.md`. The `NNN` prefix controls ordering within
a part; the `slug` in the front matter controls the URL and must be unique
across the whole book.


## Running the site locally

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.


## Before you publish

Three things in this repository are placeholders:

1. `not-acoder` appears in `_config.yml` and in this README. Replace it with the
   organization or user that will host the repository.
2. `author` and `email` in `_config.yml`.
3. `copyright.start_year` in `_config.yml`.
