# Humanizer

A Claude Skill that checks everything I write, or that Claude writes for me, for the habits that make text read as AI-generated, and fixes them.

## How I built it

1. Had Claude pull every pattern from Wikipedia's [Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing) guide, maintained by WikiProject AI Cleanup
2. Grouped the patterns into content, language, formatting and chatbot leftovers, each with a plain-English fix
3. Turned the list into a Skill using Claude's skill-creator, with a description broad enough that it runs on every draft without being asked

## What it catches

- Em dashes used for rhythm
- Words like "delve", "pivotal", "leverage" and "showcase"
- Forced groups of three
- "It's not X, it's Y" lines
- Inflated significance, vague attribution and filler openers and closers
- Assistant leftovers such as "I hope this helps"

## Design choices

- **Fix, don't invent.** When it rewrites, it keeps the writer's facts, numbers and voice. If a sentence is vague because a detail is missing, it asks instead of making one up.
- **Patterns, not a banned-word list.** Text that avoids every pattern and still says nothing counts as a failure.
- **Register-aware.** Formal for recruiters and admissions panels, casual for teammates, plain text for anything pasted elsewhere.
- **A final check.** Before sending, it rereads the draft against a short checklist.

## Use it

Copy the `humanizer` folder and add it to Claude as a Skill. It triggers on any drafting or rewriting request.

## Author

Vidhisha Jain · [LinkedIn](https://www.linkedin.com/in/vidhishajain1805)
