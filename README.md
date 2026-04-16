# Instructure UX Writing
Maintained by Lisette Walberer | Slack: @lisette.walberer | Questions: #ux-writing-help

This repo contains the Instructure UX Writing Style Guide in a machine-readable format, plus Claude Code skills for designers who want AI-assisted copy review and generation.

---

## The style guide

The style guide lives here:
```
references/style-guide.md
```

It's a plain markdown file — which means it works with any AI tool, not just Claude. Here's how to use it depending on what tools you have:

**With Claude Code**
Clone this repo and launch Claude Code from inside the folder. It reads the style guide automatically before every session.

**With Figma AI**
Open `references/style-guide.md`, copy the contents, and paste them into Figma AI as context before your prompt. Example:
> "[paste style guide contents] Using these guidelines, write three empty state options for a gradebook with no assignments yet."

**With Cursor, Copilot, or any other AI coding tool**
Add `references/style-guide.md` to your project root. Most AI coding assistants will pick it up automatically as context.

**With ChatGPT or any other chat-based AI**
Copy and paste the style guide contents into your conversation before asking for copy help.

**As a reference doc**
The style guide is readable on its own — no AI needed. Use it to check capitalization rules, look up preferred words, or verify punctuation before handoff.

---

## Claude Code skills

If you use Claude Code, this repo includes two skills that automate common UX writing tasks.

### Setup (one time only)

**1. Clone this repo:**
```
git clone https://github.com/lisette-walberer/instructure-ux-writing.git
```

**2. Navigate into the folder:**
```
cd instructure-ux-writing
```

**3. Launch Claude Code:**
```
claude
```

Claude Code will automatically read the style guide and skills every time you launch from this folder.

---

### Skill: tone-check

Audits any copy against the Instructure style guide and flags violations with suggested fixes.

**How to use:**
> "Check this copy against our style guide: [paste copy]"

**What you get back:**
- ✅ What's working
- ⚠️ Suggestions
- ❌ Violations — with specific rewrites

**With a Figma frame:**
> "Read the style guide then review the copy in this frame: [paste Figma link]"

---

### Skill: write-microcopy

Generates on-brand copy options for a UI pattern or Figma frame.

**How to use:**
> "Write microcopy for an empty state. A teacher just logged in for the first time and has no courses yet."

> "Generate copy options for a confirmation modal when a teacher is about to delete an assignment."

**What you get back:**
- 3 copy options per text element
- The tone used for each option
- Notes on anything that pushes toward the edge of the style guide

---

## Keeping up to date

When the style guide is updated, pull the latest version:
```
git pull
```

---

## Questions or feedback

Slack @lisette.walberer or visit #ux-writing-help.
