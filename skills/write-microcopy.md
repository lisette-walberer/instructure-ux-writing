# Write Microcopy

## Description
Generate on-brand UX copy for a specific UI pattern or Figma frame, following Instructure's style guide.

## When to use
- A designer needs copy for a new UI pattern (empty state, error message, tooltip, modal, etc.)
- Starting from scratch on a new screen or flow
- Exploring copy options before a content review

## Instructions
1. Read `references/style-guide.md` before doing anything else
2. Ask the user for:
   - The UI pattern type (e.g. empty state, error message, confirmation modal, tooltip, button label)
   - A Figma frame link OR a plain description of the screen and what the user is trying to do
   - Any additional context (user's emotional state, where they are in the journey, space constraints)
3. Generate 3 copy options for each text element in the pattern
4. For each option, note the tone being used (knowledgeable, encouraging, sincere, playful, direct)
5. Flag any options that push toward the edge of the style guide so the writer can make a judgment call
6. Return options in this format:

   **[Element name]**
   - Option A (tone: direct): [copy]
   - Option B (tone: encouraging): [copy]
   - Option C (tone: sincere): [copy]

## Examples

**Input:** Empty state for a gradebook with no assignments yet. Teacher is new to the platform.

**Output:**

**Header**
- Option A (tone: direct): No assignments yet
- Option B (tone: encouraging): Ready when you are
- Option C (tone: playful): A clean slate — let's fill it

**Body**
- Option A (tone: direct): Create your first assignment to get started.
- Option B (tone: encouraging): When you're ready to build your first assignment, we're here to help.
- Option C (tone: sincere): Every great course starts with a first step. Add an assignment when you're ready.

**CTA**
- Option A (tone: direct): Create assignment
- Option B (tone: direct): New assignment
- Option C (tone: direct): Add assignment
