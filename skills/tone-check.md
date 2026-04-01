{\rtf1\ansi\ansicpg1252\cocoartf2868
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Tone Check\
\
## Description\
Check UX copy against the Instructure style guide for voice, tone, grammar, and mechanics.\
\
## When to use\
- A designer wants to verify copy before handoff\
- Copy feels off-brand but it's hard to articulate why\
- Reviewing error messages, button labels, tooltips, or empty states\
- Onboarding new designers to Instructure's voice\
\
## Instructions\
1. Read `references/style-guide.md` in full before doing anything else\
2. Ask the user to paste the copy they want checked \'97 or accept what they've already provided\
3. Check the copy against each of these areas in order:\
   - Voice: Is it clear, confident, and conversational?\
   - Tone: Is it appropriate for the context and user's emotional state?\
   - Plain language: Is it under 25 words per sentence? 8th grade reading level?\
   - Inclusive language: Does it use any terms from the avoid list?\
   - Grammar and mechanics: Capitalization, contractions, punctuation, active voice\
4. Return a report structured like this:\
   - \uc0\u9989  What's working\
   - \uc0\u9888 \u65039  Suggestions (could be better)\
   - \uc0\u10060  Violations (conflicts with the style guide)\
5. For every \uc0\u9888 \u65039  and \u10060  item, provide a specific rewrite\
\
## Examples\
\
**Input:** "Are you sure you want to delete this item? This action cannot be undone."\
**Output:**\
- \uc0\u9888 \u65039  "Are you sure" is a weak opener \'97 avoid confirmation question patterns\
- \uc0\u9888 \u65039  "This action cannot be undone" is passive and wordy\
- Suggested rewrite: "Delete this item? You won't be able to undo this."\
\
**Input:** "Please click the button below to facilitate your request."\
**Output:**\
- \uc0\u10060  "Please" \'97 we don't use filler politeness words\
- \uc0\u10060  "click" \'97 avoid self-evident verbs in CTAs\
- \uc0\u10060  "facilitate" \'97 hidden verb, use simpler language\
- \uc0\u10060  "below" \'97 avoid directional language\
- Suggested rewrite: "Submit your request."}