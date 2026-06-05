---
description: Generate a Claus Mode deck. Max 4 words per slide. All caps. Extreme buzzwords. Zero nuance. Every slide is a billboard. Minimum 15 slides. Use when the user wants maximum energy and minimum explanation.
---

# /slides-claus

Generate a high-energy deck of nothing but big bold headlines and extreme buzzwords.

## Usage

- `/slides-claus "AI is eating the world"`
- `/slides-claus "our company in 30 seconds"`
- `/slides-claus "why we are winning"`

## What the command does

1. **Use what the user already provided.** Do not re-ask.
2. Load the Claus storytelling guide (`STORYTELLING-claus.md`) from the `deck-system` skill folder.
3. Generate minimum 15 slides of pure headline energy. No subtitles. No body text. No complex components.
4. Use the Solid theme by default. Read `deck-solid.html` from the skill folder and copy its style and script blocks verbatim.
5. Every slide is a dark or light quote slide. Max 4 words. All caps.
6. Every headline must contain at least one buzzword from the approved list.
7. No dim spans. No punctuation except question marks on the last slide.

## Rules

- Maximum 4 words per headline
- All caps always
- Minimum 15 slides
- All quote slides, no other components (except cover)
- No subtitles, no body text, no eyebrows, no meta
- Every headline contains a buzzword
- No dim spans. Full intensity.
- Alternate dark and light slides for rhythm
