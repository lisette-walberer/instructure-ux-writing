# Agents

Generic instructions for any AI agent working in this repo. Optimized for tools that don't read `CLAUDE.md` natively.

## Read this first

Before writing or reviewing any copy, read `references/style-guide.md`. It's the source of truth for Instructure UX writing voice, tone, grammar, and mechanics. If anything in this file or in any skill file conflicts with the style guide, the style guide wins.

## Skills

Two skills live in this repo:

- `skills/tone-check.md` — review existing copy against the style guide and flag violations.
- `skills/write-microcopy.md` — generate new on-brand copy for a UI pattern.

Trigger keywords:
- "Write copy", "draft microcopy", "generate options", "what should this say" → `write-microcopy`
- "Check this", "review this", "audit this", "is this on-brand", "flag issues" → `tone-check`

If no skill matches, read the style guide, ask the user for context, then write or review using the rules in the guide.

## Hard rules

- Read `references/style-guide.md` first.
- Use sentence case in headers, labels, and buttons.
- Use the Oxford comma.
- Never use semicolons.
- Default to active voice unless avoiding user blame.
- Use contractions to sound conversational.
- Don't use exclamation points except in celebratory moments.
- Don't use "click" in CTAs.
- Don't use generic CTAs like "Learn more" or "Submit." Use action verb plus noun.

## Human review required

All AI-generated copy must be reviewed by a human writer before shipping to production. Tell the user this when you return output. Recommend they check with Lisette in `#ux-writing-help` if they're unsure.

## When the guide is silent

If a scenario isn't covered in the style guide, apply the closest rule and explain your reasoning. Flag the gap so the guide can be updated. Don't invent rules.

## Maintenance

Maintained by Lisette Walberer. Questions or suggested changes go through `#ux-writing-help` on Slack or GitHub Issues.
