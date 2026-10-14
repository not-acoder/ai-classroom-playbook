# Changelog

## v1.1 (October 2026)

### Play form

- Added an **Evidence Status** section to every play. It holds one evidence
  level (documented, paired, undocumented) and a count of drafted steps.
  Version 1.0 listed "steps-drafted" as a fourth evidence value, but no play
  used it that way. It is a separate measure, so it is now reported
  separately.
- Added a **Freshness** section to every play: source dates, assumptions
  that date the play, and the date it was last checked.
- Evidence notes and freshness notes that v1.0 kept inside Source were moved
  into the new sections. Source now lists citations only, each labelled by
  its role, plus revision and citation notes.
- Added `evidence`, `drafted_steps`, `total_steps` and `last_checked` to
  every play's front matter.

### Corrections

- **Evidence levels tightened.** Play 16 (paired) and Play 29 (documented)
  are now undocumented: neither source measures outcomes. Plays 11 and 18
  stay paired but are marked indirect. "Undocumented" now means none found
  in the sources reviewed. Totals: 1 documented, 2 paired, 26 undocumented.
- **Outcome search, every play.** Each play was searched for studies that
  measured the practice. Upgrades: Play 3 to paired, weak (An and colleagues,
  2025); Play 14 to paired (Xiao and colleagues, 2026, randomised, 979
  students); Play 6 to documented, weak (AI Assessment Scale pilot, Furze and
  colleagues, 2024). Play 26 gains counter-evidence: disclosing AI use lowers
  trust (Reimann and Schilke, 2025). Zhang (Play 11) re-checked. Related but
  non-qualifying studies are noted in Plays 2, 7, 9, 13, 17, 22 and 23.
  Final totals: 2 documented, 4 paired, 23 undocumented.

- **CHEPP report located and verified.** Rajkumar and Klein-Collins, *AI in
  Higher Education: Teaching and Learning*, CHEPP, July 2026, now cited with
  its URL. v1.0 removed the report's specifics because the report could not
  be found. All of them check out: the Dallas College and University of South
  Carolina red, yellow, green course policies, the 97 percent learner survey
  figure (which the report cites from Flaherty, 2025), and the augment versus
  replace table.
  - Play 6: the institutional example and the figure are restored in
    Examples. The AI Assessment Scale stays as the primary tier structure.
    The discipline illustrations are now labelled as coming from learner
    focus groups, as the report says.
  - Play 15: the "provisional" caution is removed. One list item was
    narrowed: the report names real time translation of course materials,
    not of discussions.
- **Lu and colleagues (FeedbackWriter).** Teaching assistant agreement
  corrected from "88 percent" to 88.7 percent approved and 11.3 percent
  corrected, as the paper reports (Plays 11 and 18). The "50th to 70th
  percentile" line in Play 11 is confirmed as the authors' own wording.
- **Davey and colleagues.** The 2009 to 2023 range is confirmed from the
  abstract, and the sample (722 students) is added (Play 8).
- **Estaphan and Zulfiqar (2026).** Authors added to the Play 29 citation,
  which v1.0 cited by title only.
- **Droulers, Krautloher and Shaeri.** Year added: 2025 online, 2026 issue
  (Play 8).
- **Play 21 drafting note** said it had the highest drafted step density in
  the collection. Play 25 is higher (5 of 5 against 4 of 5). Reworded.
- **Broken URLs.** v1.0's Source sections had URLs split by stray spaces
  (for example `better- teaching/`) and citations run together on one line.
  All Source sections were rebuilt.

### Still open

- Tang et al. (2025), Play 25: full author list not confirmed. The publisher
  page could not be fetched.
- Sotiriadou et al. (2020), Play 8: title and DOI not confirmed.
- Play 22 Freshness flags, unchecked against any source, that multimodal models
  can read the picture a Prompt Problem relies on.
- 14 held expansion candidates remain unfetched. Parked.

### Corrections to the compiled v1.0 document (`AI_Classroom_Playbook_v1.md`)

These are in the compiled document's front matter and appendices, which are
not in this repository. They are recorded here so the paper and thesis can
be corrected:

- "What changed" said Plays 6, 8, 11 and 16 moved to paired. In fact Play 6
  stayed undocumented, Play 8 moved to documented, and Play 18 (paired) was
  missing. Appendix C had it right.
- Appendix A observation 6 said drafted steps appear in 18 of 29 plays. The
  count is 20 of 29, 46 steps in all. The thesis draft and Paper 2 repeat
  "18 of 29" and need the same fix.
- Appendix A observation 1 said four plays were paired or documented. Five
  plays carry one of those levels: 8 and 29 documented; 11, 16 and 18
  paired. Plays 21 and 22 have documented evidence for the problem but not
  for the practice, and are undocumented.
- Appendix D was missing Pitt as a source for Play 16.
- Paper 2, Section 4.4 lists "steps drafted" as a fourth evidence value. In
  v1.1 it is a count, as Section 7 of the same paper already describes.

## v1.0 (August 2026)

29 plays in four chapters, built by running the inherited play template
unchanged. Tagged `v1.0` and frozen.
