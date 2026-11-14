# Sanity Check

A Claude Skill that stress-tests any piece of work before it is used or shared: reports, decks, analyses, CVs, posts and AI output. It tries to break the content instead of polishing it.

## How it works

It reviews the work in eleven layers, in a fixed order:

1. Logic
2. Evidence
3. Coverage
4. Consistency
5. Structure
6. Overlap (MECE)
7. Claim strength
8. Specificity
9. Implication
10. Third-party readability
11. Wording and precision, last

It returns a verdict (**Works**, **Needs refinement** or **Doesn't hold**), then each issue with the exact line, the layer it fails and a corrected version.

## Design choices

- **Logic before wording.** A well-written sentence with an indefensible conclusion gets flagged, not polished.
- **Evidence problems and wording problems are kept apart.** A missing source and an overstated sentence need different fixes.
- **No invented evidence.** If support is missing, it asks for it or recommends a softer claim.
- **Built from real use.** This is the review I run on my own work and on AI output before anything goes out.

## Use it

Copy the `sanity-check` folder and add it to Claude as a Skill. Then ask it to "sanity check" anything.

## Author

Vidhisha Jain · [LinkedIn](https://www.linkedin.com/in/vidhishajain1805)
