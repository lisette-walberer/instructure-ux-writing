# Prompts

Copy-paste prompts for everyone at Instructure who writes user-facing copy. Don't read the docs unless you want to — fill in the brackets and go.

These prompts work with Claude Code, Figma AI, Cursor, GitHub Copilot, ChatGPT, or any other AI tool that can read the Instructure style guide. If you're not using Claude Code, paste the contents of `references/style-guide.md` into your AI tool first, then run any prompt below.

A note on AI-generated copy: it always needs human review before shipping. The prompts below get you a strong starting point, not a final deliverable.

---

## Write new copy

### Button or CTA label

```
Write three CTA options for [action]. The user is [doing what / where in the flow]. Tone should be [direct / encouraging / sincere]. Constraint: 4 words or fewer.
```

### Error message

```
Write an error message for this scenario: [what happened]. The user was trying to [user action]. They can recover by [recovery action]. Give me a header (max 10 words), body (max 2 lines), and CTA (max 4 words). No exclamation points. No technical jargon.
```

### Empty state

```
Write three options for an empty state. The user is [who they are] and they're seeing this because [why it's empty]. Their next best action is [action]. Give me a header, body, and CTA for each option. Note the tone for each.
```

### Confirmation modal

```
Write a confirmation modal for [destructive or significant action]. The user just clicked [trigger]. After confirming, [what happens]. Give me a header, body explaining the consequence, primary CTA, and secondary CTA. Use passive voice in the body to avoid blaming the user if relevant.
```

### Tooltip

```
Write a tooltip for [UI element]. The user needs to know [what / why]. Constraint: 1 to 2 sentences max. No filler words.
```

### Push or SMS notification

```
Write a push notification for [event]. The user needs to [action] within [timeframe]. Header should be one line. Body should be max 3 lines and indicate where the user lands when they tap through. Total under 90 characters.
```

### Email subject and pre-header

```
Write three subject line and pre-header pairs for an email about [topic]. The recipient is a [user type]. The desired action is [action]. Subject under 40 characters and no punctuation. Pre-header under 40 characters with punctuation. Lead with the deadline or required action.
```

### Form field label and helper text

```
Write a label and helper text for a form field that captures [data]. The user is [context]. Note any validation messaging needed if the input is invalid.
```

---

## Review existing copy

### Quick check on a single element

```
Check this copy against the Instructure style guide:
[paste copy]

Tell me what's working, what could be better, and what violates the style guide. Suggest a specific rewrite for every issue.
```

### Audit a Figma frame

```
Read the style guide, then review every piece of copy in this frame: [Figma link]. For each text element, tell me what's working, what to improve, and any direct violations. Suggest specific rewrites.
```

### Mechanics-only review

```
Check this copy for mechanics only — capitalization, punctuation, contractions, Oxford comma, semicolons, sentence case in headers, active voice. Don't critique the voice or tone. Just flag any mechanics issues with rewrites.
[paste copy]
```

### Inclusive language scan

```
Scan this copy for any terms on the Instructure inclusive language avoid list. Suggest replacements for anything you find.
[paste copy]
```

### Plain language check

```
Run this copy through a plain language check against Instructure's standards: 25 words per sentence max, 8th grade reading level, no hidden verbs, no jargon, simple words preferred. Flag any sentence that fails and suggest a simpler rewrite.
[paste copy]
```

---

## Quick reference

### Capitalization

```
According to Instructure's style guide, what's the correct capitalization for [phrase or term]? Show me which rule applies.
```

### Date or time format

```
What's Instructure's format for [date / time / time range]? Give me an example I can copy.
```

### Punctuation

```
According to Instructure's style guide, what punctuation should I use for [scenario]? Note any exceptions.
```

### Inclusive alternatives

```
What does Instructure prefer instead of [phrase or term]? Show me the rule from the style guide.
```

---

## Repeat patterns

### Button text I can reuse

```
Give me five reusable button labels Instructure already uses across products for [action type, e.g. confirm, cancel, save, dismiss]. Note where they appear if known.
```

### Empty state pattern check

```
Compare this empty state to other Instructure empty states. Is the tone consistent? Is the structure consistent (header, body, CTA)? Flag anything that drifts from the pattern.
[paste empty state]
```

---

## Coming soon

These prompts will work once their skills land in the repo:

### Audit a full flow's microcopy
For end-to-end consistency review across a flow.

### Name a new feature or setting
Pattern-based naming that fits with existing Instructure terminology.

### Review IA copy
Menu labels, breadcrumbs, page titles, and navigation copy.

### Design empty state or error families
System-level patterns across a product, not single instances.

---

## Help

If a prompt isn't working or returns weird output, message Lisette in `#ux-writing-help` or open a GitHub Issue with the prompt you used and what you got back.
