# College Application Writer

A Claude Skill that works like a study abroad consultant. It turns a college, scholarship or fellowship application question into a paste-ready answer that sounds like I wrote it myself.

The full instructions include my personal details, so this folder documents the design only.

## How it works

1. **Intake:** the exact question, the word limit, the programme, and the other questions in the same application so stories don't repeat
2. **Gather:** reads what is already known, including earlier answers, so facts stay consistent across applications
3. **Understand the programme:** searches what it looks for in its own words, and never invents programme facts
4. **Ask like a consultant:** 3 to 5 focused questions at a time, pushing for specific moments instead of summaries, and suggesting two or three angles to choose from
5. **Outline, then draft:** an outline first for anything over about 250 words
6. **Check:** counts the words in code, rereads for banned phrasing and checks every fact

## Design choices

- **Draft only.** It never opens, fills in or submits a portal form.
- **No drafting from thin material.** If the answers are generic, it asks another round of questions first.
- **Strict writing rules.** No dashes, at most two commas a sentence, no AI vocabulary, no rhetorical openers and no quotes from famous people.
- **Within the limit.** It aims for 90 to 100 percent of the word limit, counted in code, not estimated.
- **Revisions stay narrow.** It changes only what was asked and returns the full answer with its new count.

## Author

Vidhisha Jain · [LinkedIn](https://www.linkedin.com/in/vidhishajain1805)
