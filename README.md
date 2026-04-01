# Instructure UX Writing Tools — Designer Guide
Maintained by: Lisette Walberer | Slack: @lisette.walberer | Email: lisette.walberer@instructure.com

---

## Which guide is for me?

- **I use Claude Code** → read Section 1
- **I only use Figma** → read Section 2

---

---

# Section 1: Guide for Claude Code Users

## What's available

Two AI-powered skills that check and generate copy using Instructure's official style guide:

| Skill | What it does |
|-------|-------------|
| `tone-check` | Audits any copy against our style guide and flags violations with suggested fixes |
| `write-microcopy` | Generates on-brand copy options for a UI pattern or Figma frame |

---

## One-time setup

You only need to do this once.

**Step 1 — Open Terminal and clone the repo:**
```
git clone https://github.com/lisette-walberer/instructure-ux-writing.git
```

**Step 2 — Navigate into the folder:**
```
cd instructure-ux-writing
```

**Step 3 — Launch Claude Code:**
```
claude
```

That's it. Claude Code will automatically read the style guide and skills every time you launch from this folder.

---

## How to use the skills

Once you're in Claude Code, just describe what you need in plain language. You don't need to use any special commands.

### Tone check
Paste copy and ask Claude to check it:

> "Check this copy against our style guide: 'Please click the button below to facilitate your request.'"

Or paste a whole screen's worth:

> "Read the style guide and audit all of this copy: [paste copy]"

**What you'll get back:**
- ✅ What's working
- ⚠️ Suggestions
- ❌ Violations — with specific rewrites for each

---

### Write microcopy
Describe the UI pattern and context:

> "Write microcopy for an empty state. A teacher just logged in for the first time and has no courses set up yet."

> "Generate copy options for a confirmation modal when a teacher is about to delete an assignment."

> "Write three button label options for submitting a quiz."

**What you'll get back:**
- 3 copy options per element
- The tone used for each option (direct, encouraging, sincere, etc.)
- Notes on anything that pushes toward the edge of the style guide

---

### Using with Figma
If you have the Figma MCP connected, you can paste a Figma frame link directly:

> "Read the style guide then review the copy in this Figma frame: [paste Figma link]"

> "Generate copy for this empty state design: [paste Figma link]"

---

## Tips

- Always launch Claude Code from inside the `instructure-ux-writing` folder so it loads the style guide automatically
- The more context you give (user's emotional state, where they are in the journey, space constraints), the better the output
- Use tone-check before every design handoff — it takes 30 seconds
- If something feels off about the output, push back. Tell Claude why and ask it to try again.

---

## Getting updates

When Lisette updates the style guide or adds new skills, pull the latest version:

```
git pull
```

---

---

# Section 2: Guide for Figma-Only Users

## What's available

Two resources inside the **Instructure UX Writing Resources** Figma file:

| Resource | What it does |
|----------|-------------|
| Style Guide Quick Reference | A scannable cheat sheet of our most important writing rules |
| Copy Library | Approved, ready-to-use copy for common UI patterns |
| Figma AI Prompt Recipes | Copy-pasteable prompts for generating on-brand copy with Figma AI |

**Access the file here:** [Instructure UX Writing Resources](https://www.figma.com/design/YjxDHyI2xXdIMSNnsqP4xi/Instructure-UX-Writing-Resources?node-id=0-1&p=f&t=725lzuOqemTr5END-0)

---

## How to use the Style Guide Quick Reference

Open the **Style Guide Quick Reference** page in the Figma file. Use it to:
- Check capitalization rules before you write anything
- Look up the correct tone for a context
- Find the preferred word when you're not sure (e.g., "Help" not "Facilitate")
- Verify punctuation rules (no periods in buttons, no semicolons, always Oxford comma)

Keep it open in a tab alongside your working file.

---

## How to use the Copy Library

Open the **Copy Library** page. It has approved, ready-to-use copy for:
- Empty states
- Error messages
- Confirmation modals
- Tooltips
- Button labels

**To use it:**
1. Find the pattern that matches your design
2. Copy the approved text
3. Adapt it to your specific context — swap in the right noun, adjust for your user

If you can't find what you need, reach out to Lisette or use a Figma AI prompt recipe to generate options.

---

## How to use Figma AI Prompt Recipes

Open the **Figma AI Prompt Recipes** page. Each card has a prompt you can copy and paste into Figma AI.

**To use Figma AI:**
1. Press `Cmd + /` in Figma
2. Type "AI" and select it
3. Paste the prompt from the recipe card
4. Replace the bracketed placeholders with your specifics
5. Review the output and adapt as needed

**Available prompts:**
- **Tone check** — paste your copy and get it audited
- **Write microcopy** — describe a UI pattern and get copy options
- **Error messages** — describe the error and get compliant copy
- **Button labels** — describe the action and get CTA options

---

## Tips

- Figma AI works best when you give it context — who the user is, what they're trying to do, and how they might be feeling
- Always review AI-generated copy against the Style Guide Quick Reference before using it
- When in doubt, check with Lisette — a quick Slack to @lisette.walberer is faster than guessing
- The Copy Library is the fastest path for common patterns. Use it first before generating anything new.

---

## Questions or feedback?

If copy feels off, a pattern is missing from the library, or you're not sure what to write — Slack @lisette.walberer or reach out directly. That's what she's here for.

---

*Last updated: April 2025*
