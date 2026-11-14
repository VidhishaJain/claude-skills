# LinkedIn Post Writer

A Claude Skill that acts as my LinkedIn coach and writer. It plans what to post and in what order, keeps a running log of planned and published posts, and writes each post about something I actually built or learnt with AI.

The full instructions include my personal details, so this folder documents the design only.

## How it works

- **Coach mode:** reads the content log, checks my upcoming deadlines, recommends a cadence and an order, and says what to skip and why
- **Writer mode:** turns one real build into one post with a fixed shape: an opening line that stands alone, how it was built, the specifics, the result, and one question for the reader
- **Content log:** records only what I confirm (the plan I accept and the date each post goes live) and moves the next post up when one is published

## Design choices

- **No fluff.** Every sentence has to carry a fact, a step, a tool, a rule or a result. No morals, no motivational lines, no claims about what "everyone" does.
- **Real builds only.** It works from a bank of things I actually built and never inflates them beyond their real size.
- **Two readers in mind.** Each post includes one detail a recruiter values (the tools and automation) and one an admissions reviewer values (a human sign-off step, a rule the AI must follow, a source standard).
- **Facts checked.** Outside news and numbers are verified with a web search and linked before they go into a post.
- **Humanized.** Every draft passes through the [Humanizer](../humanizer/) before I see it.
- **Restraint built in.** At most three posts a week, and a skipped week beats a filler post.

## Author

Vidhisha Jain · [LinkedIn](https://www.linkedin.com/in/vidhishajain1805)
