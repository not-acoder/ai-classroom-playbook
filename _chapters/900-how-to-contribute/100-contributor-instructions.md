---
title: Contributor Instructions
slug: contributor-instructions
---
## Get Involved

This Playbook is a community resource. Contributions are welcome, whether that
means suggesting a practice worth writing up, writing one up yourself, sharing
what happened when you tried one, or fixing something that is wrong.

The two ways in are filing an issue (to suggest a play or report a problem) and
opening a pull request (to contribute or revise content). Every page on the
live site has a GitHub icon in the sidebar header that takes you to the source
file, where you can edit inline and open a pull request from your browser.


## What Counts as a Play

Not every good idea about AI in teaching is a play. A play is **one standalone
practice someone can adopt**. Before writing one up, check it against five
tests:

1. **A _do_, not a _know_.** "Students should think critically about AI output"
   is a value. "Assign a critique of AI-generated work and grade the critique"
   is a play.
2. **Standalone.** It can be adopted on its own, without first adopting three
   other things.
3. **One decision.** If adopting it means making four separate choices, it is
   probably a chapter, not a play.
4. **Worth its own entry.** A single line inside someone else's policy is
   usually an implementation option for an existing play, not a new one.
5. **Distinct.** It is not an existing play with different wording.

Two further boundaries for this Playbook specifically:

- **Instructor scope.** Plays are things an individual instructor can adopt in
  a course. Institution-level programs, curriculum-wide initiatives, and
  departmental policy are out of scope.
- **AI in the mechanism.** The practice should involve AI in how it works, not
  only in why it is being considered. A grading change motivated by the
  existence of AI, but with no AI anywhere in the practice itself, belongs in a
  grading playbook rather than this one.


## Sourcing and Verification

Every play cites a source, and **every citation must be checked against the
actual document before the play is written**. This is not optional cleanup.
Discovery tools produce citations that look correct and are not: fabricated
domains, real documents attributed to the wrong publisher, DOIs that do not
resolve, the same article credited to several different author sets. Fetch the
source, confirm it exists, confirm it says what the play claims it says.

If verification changes the play, say so. Several plays in this book carry a
short **citation note** at the end of the Source section recording that the
original attribution was wrong and what replaced it. Keep that habit.


## Evidence Status

Most practices in this domain are described but not measured. Say which you
have. At the end of the Source section, record one of:

- **documented** — the source reports outcome data for this practice
- **partial** — the source reports related or indirect evidence
- **undocumented** — the source describes the practice and reports no outcome
  data

A play with no evidence is still worth including. A play that implies evidence
it does not have is not.


## Drafted Steps

If you write an implementation step that the source does not support, mark it
`(Drafted)` at the start of the step, and note in the Source section which
steps were drafted. Sources frequently name a practice in one sentence and
leave the procedure to the reader. Filling that gap is useful; hiding that you
filled it is not.


## Markdown

When editing page contents, we generally prefer to use **Markdown format**.
This is a plain text markup notation that is quick to learn and easy
to edit. For details, read:

+ [GitHub's "Getting Started" page on: Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
+ [GitHub's docs on writing Markdown for GitHub use](https://docs.github.com/en/get-started/writing-on-github)
+ [Markdown cheat sheet](https://github.com/adam-p/markdown-here/wiki/markdown-cheatsheet)

Note that HTML content can be embedded in markdown files as well. And if you
want to write vanilla HTML content for a new play instead of using markdown,
you can convert the play template to HTML, keep the metadata section at the
start, but write all the content using HTML markup and give the file a
`.html` extension instead of `.md`.


## Discuss a Play

Every play ends with a **Community Discussion** section. If you have run the
practice, or tried and abandoned it, or think a tradeoff is stated wrongly,
add it there. Experience reports are as valuable as new plays, and in a domain
this thin on outcome data they may be more valuable.
See {% include chapter-link.html slug="join-discussions" %} for details.


## Contributing New Plays

Here is the process for contributing a new play to this book:

1. Decide on a **name** for the play. Choose a clear, evocative name
   (preferably a noun phrase) that future educators can use as a recognizable
   way to identify or talk about this play.
2. Make a copy of the {% include chapter-link.html slug="play-template" %}
   file in this repository, which is located
   at `_chapters/900-how-to-contribute/200-play-template.md`.
3. Fill in the content! Place your play's **name** in the "title:" field
   at the top of the file in the metadata section. Also, add a "slug", or
   the human-readable URL-style page name for this play. This must be unique,
   since it will be used as a unique way to link to the play. We recommend just
   lower-casing the name, with spaces replaced by dashes and special characters
   removed. Then see the explanations below for what you should
   put in each section in the template.
4. Add your file to this
   project's {% include chapter-link.html slug="incubator" %} by placing it in
   the `_chapters/800-Incubator` directory. The file name should follow the
   basic format of `ddd-slug.md`, where `ddd` is a number, `slug` is the
   slug you've entered in the page's metadata, and `.md` is the file extension.
   Just look at the existing files already in that directory, find the highest
   number, and add 10 so your new play will go at the end numerically.
5. Plays added in the {% include chapter-link.html slug="incubator" %} will
   be reviewed and moved to an appropriate chapter.
6. Check it in and create a pull request to send your contribution to GitHub
   for review!


## Play Sections

Each play is written in a style similar
to [software design patterns](https://www.martinfowler.com/articles/writingPatterns.html).
They have a common set of sections that are intended to prompt play writers
to consider the key aspects that others need in order to consider adopting
a play, and also intended to help other educators know where to look for
key information in the play's description. The following explanations
describe the sections that appear in each play:

+ **Name**: The play's name is intended to be a short, evocative label
  that the community can use to refer to the play. We prefer titles that
  are noun phrases that aren't too long, nor too generic.
+ **Intent**: A slightly longer one-sentence (or at least
  concise) description of what the play achieves--that is, what is the
  purpose or intent of using the play?
+ **Problem**: A concise description of the problem or situation that
  the play solves or addresses, answering the question of: why use it?
+ **Solution**: The main description of the play and all of its elements
  or components, in enough detail so the reader can understand how it works.
+ **Applicability**: Describes the context(s) where this play works, and
  the tradeoffs that should be considered in deciding whether or not to
  use it.
+ **How to Implement**: Provides any implementation details or techniques
  about how to actually deploy the play--how do you "make it work". This
  section should provide enough detail so that another educator would know
  how to implement the play in their own classroom. Mark any step you wrote
  yourself with `(Drafted)`.
+ **Examples**: Concrete instances from the source: reusable prompts, worked
  deployments, variants, field reports. If the source does not supply any, say
  so rather than inventing them.
+ **See Also**: A bullet list of related plays.
+ **Source**: A citation to the publication, web page, or source of the
  play, plus the name of the person who wrote up its description. This is also
  where evidence status, drafted-step notes, and citation corrections go.
+ **References**: Any other references that describe more about the play.
+ **Community Discussion**: A "public comments" section where community
  members can share their own experiences, observations, questions, or
  perspectives on the play.

The template in this book is carried over from the
[Playbook of Alternative Grading Practices](https://cs-alternative-grading-practices.github.io/playbook/)
unchanged. Where it fits this domain badly, that is recorded in the project's
research notes rather than patched, because the fit is itself what is being
studied. If you hit a section that will not take the content you have, note it
in your pull request.


## Advanced Features

This book is written using [jekyll](https://jekyllrb.com/) and
the [jekyll-chapterbook](https://github.com/jasongrimes/jekyll-chapterbook) theme.
See the [jekyll-chapterbook README](https://github.com/jasongrimes/jekyll-chapterbook?tab=readme-ov-file)
for details on some of the theme's more advanced features if you want to do
something beyond basic markdown, such as including figures, linking to other
plays, linking to references in the reference section, etc.
