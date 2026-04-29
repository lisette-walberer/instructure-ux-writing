# Instructure UX Writing

This repository is the canonical source for Instructure UX writing. Maintained by Lisette Walberer.

## Always do this first

Read `references/style-guide.md` before writing or reviewing any copy. The style guide is the source of truth. If anything in this file or in any skill file conflicts with the style guide, the style guide wins.

## What's in this repo

- `references/style-guide.md` — Instructure's official UX writing style guide
- `skills/` — workflows for writing and reviewing copy
- `PROMPTS.md` — copy-paste prompts for common tasks
- `CONTRIBUTING.md` — how to suggest changes

## Skill dispatch

When a user asks for help, route their request to the right skill:

| The user wants to... | Run |
|---|---|
| Write or generate new copy (CTAs, errors, empty states, modals, tooltips, notifications, emails) | `skills/write-microcopy.md` |
| Check, audit, or review existing copy | `skills/tone-check.md` |

If no skill matches the user's request, default to this workflow:
1. Read the style guide.
2. Ask the user for context — UI pattern, audience, where in the journey they are, any space constraints.
3. Apply the style guide's voice, tone, plain language, and mechanics rules.
4. Return options or feedback in a clear structure.

## Ground rules

- Use the Instructure style guide as the source of truth for voice, tone, grammar, and mechanics.
- Prefer simpler, clearer language. If a 10th grader wouldn't understand it, rewrite it.
- Never use semicolons.
- Always use the Oxford comma.
- Default to active voice. Use passive voice only to avoid blaming the user.
- Sentence case in headers, labels, and buttons. No periods at the end of headers, labels, or buttons.

## AI-generated copy review

All AI-generated copy must be reviewed by a human writer before shipping to production. Treat your output as a strong first draft, not a final deliverable. When in doubt, recommend that the user check with Lisette in `#ux-writing-help`.

## When the style guide doesn't cover something

If you encounter a scenario the style guide doesn't address, do this:
1. Apply the closest applicable rule and note your reasoning.
2. Flag the gap so it can be added to the style guide.

Don't make up rules that aren't in the guide. Defer to the user when the guide is silent.
