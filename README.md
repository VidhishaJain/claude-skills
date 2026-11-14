# Claude Skills

Five custom Skills I built for Claude to handle recurring work the same way every time. Each one writes down a standard I used to repeat in every conversation: how to ask questions, what to check, and what the AI must never do.

Built with Claude, without writing a single line of code.

## The Skills

| Skill | What it does | In this repo |
|---|---|---|
| [Humanizer](humanizer/) | Checks every draft against Wikipedia's "Signs of AI writing" guide and rewrites what reads as machine-made | Full Skill |
| [CV Writer](cv-writer/) | Tailors a CV to one job or programme, passes applicant tracking systems and never invents a fact | Design only |
| [LinkedIn Post Writer](linkedin-post-writer/) | Plans and writes LinkedIn posts about AI builds, with a running log of what is planned and published | Design only |
| [College Application Writer](college-application-writer/) | Drafts paste-ready answers to application questions, working like a study abroad consultant | Design only |
| [Compare Links](compare-links/) | Compares programmes, scholarships or jobs from official sources only and ranks them against a profile | Design only |

The Humanizer is generic, so the full Skill is here. The other four contain my personal details, so their folders document the design, not the instructions.

## How a Skill works

A Skill is a folder with a `SKILL.md` file. The file starts with a name and a one-line description that tells Claude when to use it, followed by the instructions Claude follows once it does. Claude loads a Skill on its own when a request matches the description.

## Design choices across all five

- **Intake first.** Each Skill asks only for what is missing before it starts, and reads what is already known before asking anything.
- **No invented content.** No Skill may add a fact, number, date or source it was not given or did not open. If a stronger claim needs a missing fact, it asks.
- **Official sources only** where facts matter. Aggregator sites are a last resort and are labelled when used.
- **Shared writing rules.** No em dashes, no filler, no AI-sounding vocabulary, plain words and short sentences.
- **A check before output.** Each Skill verifies its own work before handing it over: word counts run in code, facts checked against sources, files rendered and inspected.
- **Narrow permissions.** The Skills draft and recommend. They never submit, send or sign in on anyone's behalf.

## Status

Built September to October 2026. All five are in active use.

## Author

Vidhisha Jain · [LinkedIn](https://www.linkedin.com/in/vidhishajain1805) · [GitHub](https://github.com/VidhishaJain)
