# Compare Links

A Claude Skill for comparing two or more links: degree programmes, fellowships, scholarships, courses or jobs. It reads what the official sources say about each one, lines them up side by side, judges each against my profile and goals, and returns one page I can read in five minutes.

The full instructions include my personal details, so this folder documents the design only.

## How it works

1. **Load context:** my profile, goals and the applications I already track
2. **Pick the goal test by link type:** degrees and fellowships are judged on where they take me, and jobs on whether they are a step up
3. **Classify each link** and pick the fields to collect: a programme schema, a fellowship schema, a job schema, or a custom one
4. **Gather from official sources only,** following each link to the organisation's own admissions, fees, curriculum, outcomes and FAQ pages
5. **Judge eligibility and fit:** prerequisites against my transcript, tests, references, deadlines and cost
6. **Build one page:** a ranked verdict, a deadline calendar with live day counters, a side-by-side matrix, one dossier per link, open flags and a full source list

## Design choices

- **Official sources first.** Aggregator sites are a last resort and are labelled as unofficial when used. Every fact carries its source.
- **No estimates.** If an acceptance rate, salary or employer list isn't published, the page says "Not published" instead of guessing.
- **A verdict, not a summary.** Each link gets Anchor, Apply, Backup, Check first or Drop, with a one-line reason, and the ranking pushes back when the evidence says so.
- **Read-only browsing.** When a page needs a browser, it never signs in, submits a form or accepts terms.
- **Stays current.** Adding or dropping a link re-checks every deadline and fee and updates the same page.

## Author

Vidhisha Jain · [LinkedIn](https://www.linkedin.com/in/vidhishajain1805)
