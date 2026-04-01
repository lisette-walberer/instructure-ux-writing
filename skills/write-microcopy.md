{\rtf1\ansi\ansicpg1252\cocoartf2868
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Write Microcopy\
\
## Description\
Generate on-brand UX copy for a specific UI pattern or Figma frame, following Instructure's style guide.\
\
## When to use\
- A designer needs copy for a new UI pattern (empty state, error, tooltip, modal, etc.)\
- Starting from scratch on a new screen or flow\
- Exploring copy options before a content review\
\
## Instructions\
1. Read `references/style-guide.md` before doing anything else\
2. Ask the user for:\
   - The UI pattern type (e.g. empty state, error message, confirmation modal, tooltip, button label)\
   - A Figma frame link OR a plain description of the screen and what the user is trying to do\
   - Any additional context (user's emotional state, where they are in the journey, space constraints)\
3. Generate 3 copy options for each text element in the pattern\
4. For each option, note the tone being used (knowledgeable, encouraging, sincere, playful, direct)\
5. Flag any options that push toward the edge of the style guide so the writer can make a judgment call\
6. Return options in this format:\
\
   **[Element name]**\
   - Option A (tone: direct): [copy]\
   - Option B (tone: encouraging): [copy]\
   - Option C (tone: sincere): [copy]\
\
## Examples\
\
**Input:** Empty state for a gradebook with no assignments yet. Teacher is new to the platform.\
**Output:**\
\
**Header**\
- Option A (tone: direct): No assignments yet\
- Option B (tone: encouraging): Ready when you are\
- Option C (tone: playful): A clean slate \'97 let's fill it\
\
**Body**\
- Option A (tone: direct): Create your first assignme}