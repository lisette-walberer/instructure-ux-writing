# Tone Check

## Description
Check UX copy against the Instructure style guide for voice, tone, grammar, and mechanics.

## When to use
- A designer wants to verify copy before handoff
- Copy feels off-brand but it's hard to articulate why
- Reviewing error messages, button labels, tooltips, or empty states
- Onboarding new designers to Instructure's voice

## Instructions
1. Read `references/style-guide.md` in full before doing anything else
2. Ask the user to paste the copy they want checked — or accept what they've already provided
3. Check the copy against each of these areas in order:
   - Voice: Is it clear, confident, and conversational?
   - Tone: Is it appropriate for the context and user's emotional state?
   - Plain language: Is it under 25 words per sentence? 8th grade reading level?
   - Inclusive language: Does it use any terms from the avoid list?
   - Grammar and mechanics: Capitalization, contractions, punctuation, active voice
4. Return a report structured like this:
   - ✅ What's working
   - ⚠️ Suggestions (could be better)
   - ❌ Violations (conflicts with the style guide)
5. For every ⚠️ and ❌ item, provide a specific rewrite

## Examples

**Input:** "Are you sure you want to delete this item? This action cannot be undone."

**Output:**
- ⚠️ "Are you sure" is a weak opener — avoid confirmation question patterns
- ⚠️ "This action cannot be undone" is passive and wordy
- Suggested rewrite: "Delete this item? You won't be able to undo this."

**Input:** "Please click the button below to facilitate your request."

**Output:**
- ❌ "Please" — we don't use filler politeness words
- ❌ "click" — avoid self-evident verbs in CTAs
- ❌ "facilitate" — hidden verb, use simpler language
- ❌ "below" — avoid directional language
- Suggested rewrite: "Submit your request."
