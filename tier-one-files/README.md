# Instructure UX Writing

The canonical source for Instructure UX writing. Maintained by Lisette Walberer.

Slack: @lisette.walberer | Questions: `#ux-writing-help`

---

## What's in here

Instructure's UX writing style guide, plus skills and prompts for AI-assisted copy work. Built for designers, and useful for anyone at Instructure who writes user-facing copy — PMs, engineers, marketers, and support writers.

A note on AI-generated copy: it's never final. A human writer reviews production copy before it ships. The skills and prompts get you a strong first draft, not a deliverable.

---

## Quick start

Pick the path that matches what you're doing.

| I want to... | Go here |
|---|---|
| Get copy I can use today | `PROMPTS.md` |
| Check copy I already wrote | `PROMPTS.md` (Review section) |
| Read the actual rules | `references/style-guide.md` |
| Set up my AI tool once so this all just works | The AI tool files section in this README |

---

## The style guide

The style guide lives at:

```
references/style-guide.md
```

It's a plain markdown file, which means it works with any AI tool. Pick the section that matches yours.

### With Claude Code

Clone the repo and launch Claude Code from inside the folder.

```
git clone https://github.com/lisette-walberer/instructure-ux-writing.git
cd instructure-ux-writing
claude
```

Claude Code reads the style guide and skills automatically every session. No manual setup.

### With Cursor

Clone the repo and open it in Cursor. The included `.cursorrules` file makes Cursor load the style guide and skills on every prompt.

```
git clone https://github.com/lisette-walberer/instructure-ux-writing.git
```

### With Figma AI

Open `references/style-guide.md`, copy the contents, and paste them into Figma AI as context before your prompt. Example:

> "[paste style guide contents] Using these guidelines, write three empty state options for a gradebook with no assignments yet."

### With GitHub Copilot or other AI coding tools

Clone the repo so the style guide sits in your project root. Most AI coding assistants pick it up automatically as context. If yours doesn't, paste the style guide into your prompt manually.

### With ChatGPT or any chat-based AI

Copy and paste the style guide contents into your conversation before asking for copy help.

### As a reference doc

Open the file and read it. No AI needed.

---

## Skills

Two skills live in `skills/`. More are on the way.

### tone-check

Reviews copy against the style guide and flags violations with suggested fixes.

How to use:

> "Check this copy against our style guide: [paste copy]"

What you get:

- ✅ What's working
- ⚠️ Suggestions
- ❌ Violations — with specific rewrites

With a Figma frame:

> "Read the style guide then review the copy in this frame: [paste Figma link]"

### write-microcopy

Generates on-brand copy options for a UI pattern or Figma frame.

How to use:

> "Write microcopy for an empty state. A teacher just logged in for the first time and has no courses yet."

> "Generate copy options for a confirmation modal when a teacher is about to delete an assignment."

What you get:

- 3 copy options per text element
- The tone used for each option
- Notes on anything that pushes the edges of the style guide

### Coming soon

- **Microcopy audits** — review existing copy across a whole flow or screen
- **Feature and setting naming** — pattern-based naming for new features
- **IA copy review** — menu labels, breadcrumbs, page titles, navigation copy
- **Empty state and error families** — system-level patterns, not single instances

---

## AI tool files

This repo includes ready-to-use instruction files for several AI tools. If you're using one of these, you don't need to set anything up — just clone the repo.

| File | Tool |
|---|---|
| `CLAUDE.md` | Claude Code |
| `.cursorrules` | Cursor |
| `AGENTS.md` | Generic agents (any tool that reads this convention) |

Each file points the AI tool at the style guide and skills, so it knows how to handle copy requests without manual setup.

---

## Keeping up to date

When the style guide gets updated, pull the latest version:

```
git pull
```

---

## Questions or feedback

Slack @lisette.walberer or visit `#ux-writing-help`.
