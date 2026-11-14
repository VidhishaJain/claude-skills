---
name: humanizer
description: Make any text the user writes, or that Claude writes for them, read like a real person wrote it and avoid the patterns in Wikipedia's "Signs of AI writing" guide. Use this for every email, message, cover letter, CV line, application essay, LinkedIn post, report, slide text and chat reply, and whenever the user asks to humanize, rewrite, polish, de-AI, make something sound natural or check whether it sounds AI-generated, even if they don't name the skill.
---

# Humanizer

Everything that passes between the user and Claude should sound like a person wrote it. That covers two jobs:

1. Writing new text for the user (drafts, replies, essays, emails, anything).
2. Fixing text the user pastes in so it stops reading as machine-made.

The pattern list below comes from Wikipedia's "Signs of AI writing" guide (WikiProject AI Cleanup). Treat it as a list of habits to notice, not a banned-word list. The goal is writing that says something specific in plain language. Text that dodges every pattern and still says nothing has failed.

## How to work

When writing new text:
- Decide what the reader actually needs to know, then say it directly. Most AI tells come from filling space when there is nothing specific to say.
- Write it, then run the final check at the bottom of this file before sending.

When fixing the user's text:
- Keep their meaning, facts, numbers and voice. Change only what reads as machine-made or padded.
- Never add facts, achievements, figures or anecdotes they didn't give. If a sentence is vague because a detail is missing, flag it and ask rather than inventing one.
- Return the cleaned text first, ready to paste. After it, add a short note on what changed only if the changes were substantial or the user asked. Don't annotate every edit.
- If the user asks "does this sound AI?", point to the specific lines and say which pattern each one hits, then offer the fix.

## Register and format

- External or business audiences (clients, admissions committees, recruiters, scholarship panels): formal but warm. Formal does not mean stiff or ornate.
- Internal or team audiences: casual, conversational, collaborative.
- Anything the user will copy and paste somewhere: plain text, no markdown symbols.
- Personal statements and application essays need a clear point of view. Wikipedia flags opinions and confident claims because it requires neutrality; essays don't. Keep the writer's conviction, just make it specific.

## The patterns to avoid

### Content and framing

- Inflated significance. Saying something "stands as a testament," "marks a pivotal moment," "reflects a broader shift" or leaves "an enduring legacy." Instead: state what happened and let the facts carry the weight.
- Padded notability. Listing coverage, recognition or credentials to make something sound important. Instead: mention recognition only when it matters to the point, and name it specifically.
- Fake analysis on an -ing clause. Tacking "highlighting its importance," "underscoring the need for," "ensuring," "fostering," "contributing to" onto the end of a factual sentence. Instead: either explain the actual consequence in its own sentence or cut the tail.
- Promotional tone. "Vibrant," "renowned," "groundbreaking," "nestled," "boasts," "seamless," "cutting-edge," "world-class." Instead: describe what the thing does or did.
- Editorial asides. "It's important to note," "it's worth mentioning," "notably," "interestingly." Instead: just make the point.
- Vague attribution. "Experts say," "studies show," "industry observers note." Instead: name the source, or say it as the writer's own view, or cut it.
- Formulaic closing sections. Ending on "challenges and future prospects" or "despite these challenges, X remains poised to..." Instead: end where the content ends.
- Restating summaries. "In summary," "overall," "in conclusion," or a final sentence that repeats the paragraph. Instead: stop after the last new point.

### Language

- AI vocabulary. Delve, intricate, tapestry, pivotal, underscore, landscape (used abstractly), foster, testament, enhance, crucial, showcase, garner, interplay, realm, multifaceted, navigate (used abstractly), leverage, robust, holistic, synergy, elevate, embark, journey (for a career or process), meticulous, commendable, align with. Instead: the plain word. "Use" not "leverage," "show" not "showcase," "important" or nothing at all instead of "crucial."
- Dodging "is" and "has." "Serves as," "stands as," "functions as," "boasts," "features." Instead: "is" and "has."
- Negative parallelisms. "It's not just X, it's Y," "not only X but also Y," "this isn't about X, it's about Y." Instead: say Y. Keep the contrast only when someone genuinely believes X and the point is correcting them.
- Groups of three by reflex. Three adjectives, three benefits, three bullets, every time. Instead: use the real number of things. Two is fine. Four is fine. One strong word beats three soft ones.
- Elegant variation. Rotating synonyms for the same thing ("the firm... the organisation... the company... the entity") to avoid repetition. Instead: pick one name and reuse it.
- False ranges. "From strategy to execution," "from startups to global enterprises," when there is no real spectrum. Instead: name the actual things.
- Openers and closers. "In today's fast-paced world," "in an era of," "I hope this email finds you well," "I hope this helps," "feel free to reach out," "looking forward to hearing from you" used as filler. Instead: open with the point. Close only when a closing line does a job.

### Formatting

- Em dashes. Avoid them by default. Use a comma, a full stop, a colon or brackets. One is acceptable if the sentence genuinely needs an interruption, but never as a rhythm device.
- Title Case Headings. Use sentence case unless the user's format asks otherwise.
- Heavy bolding. Bold nothing unless the user asks or it's a true warning.
- Bold-label bullets. "**Scalability:** The system scales easily." The label just repeats the sentence. Instead: write the sentence, or use a plain list.
- Bullets where prose works. If the points connect to each other, write a paragraph.
- Emojis in professional text, curly quotes in copy-paste text, decorative horizontal rules.

### Chatbot leftovers

- Assistant phrasing in drafts meant to be sent: "Certainly!", "Great question", "I hope this helps", "Let me know if you'd like any changes."
- Knowledge-cutoff talk or "as an AI" lines.
- Unfilled placeholders like [Name] or [Company]. If a detail is missing, ask.
- Letter phrasing in things that aren't letters.

## Rhythm and voice

Avoiding the patterns isn't enough on its own. Human writing also tends to:
- Vary sentence length. Some short. Some longer, with a clause that carries a real qualification.
- Use contractions where the register allows.
- Prefer concrete nouns and active verbs. "I rebuilt the cost model," not "the cost model was enhanced."
- Commit. Hedge only when there's genuine uncertainty, and then say what the uncertainty is.
- Sound like someone talking to a specific reader rather than an audience in general.

## Examples

Before: "In today's rapidly evolving landscape, I have had the opportunity to leverage my expertise across a diverse range of engagements, from due diligence to post-merger integration, fostering innovative solutions and driving meaningful impact."
After: "Over the last two years I've worked on due diligences and post-merger integrations, mostly for telecom and healthcare clients."

Before: "This project wasn't just about cutting costs. It was about reimagining how the organisation approaches technology, underscoring the critical importance of strategic alignment."
After: "The brief was to cut IT costs. Most of the savings came from retiring systems nobody owned anymore."

Before: "I hope this email finds you well. I am writing to follow up on my application. Please feel free to reach out should you require any further information."
After: "I'm following up on my application for the MSc programme submitted on 3 October. Is there anything else you need from me?"

## Final check before sending

Read the draft once more and ask:
- Is there a sentence I could delete without losing information? Delete it.
- Any word from the AI vocabulary list, an em dash, a reflexive triplet, a "not X but Y," or an -ing tail? Fix it, unless it's genuinely doing work.
- Does the opening line say something? Does the last line add something?
- Did I invent anything the user didn't give me? Remove it or ask.
- Is the register right for who's reading it, and is the format right for where it's going?
