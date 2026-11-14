# AI Capability Assessment

A Claude Skill that assesses how well someone uses AI, from the evidence in their own chats, memory and files, and writes an AI Capability & Progress Portfolio.

I built it to assess my own AI capability. My portfolio is the output of this Skill.

## How it works

1. **Gathers evidence** from chat history, memory and files, then asks up to five questions where evidence is thin
2. **Scores six capability areas** on a 1 to 5 scale: prompt and context engineering, research and analysis, workflow design and automation, evaluation and governance, agentic AI, and tools and connectivity
3. **Shows growth** for each area: the first attempt, the score now, the strongest example and the next level
4. **Ties every score to proof:** a project, a running agent or a public link
5. **Runs a sanity check** before handing the portfolio over

## Design choices

- **Evidence over self-description.** It ranks evidence from "discussed" up to "running" and never turns "used" into "built".
- **A strict scale.** Level 5 is kept for production-grade systems built independently, and every score comes with a next level.
- **Confidential work stays confidential.** Client work is described generically and marked as confidential.
- **No invented numbers.** It uses only counts it can verify.

## Use it

Copy the `ai-capability-assessment` folder and add it to Claude as a Skill. Then ask: "Assess my AI capability."

## Author

Vidhisha Jain · [LinkedIn](https://www.linkedin.com/in/vidhishajain1805)
