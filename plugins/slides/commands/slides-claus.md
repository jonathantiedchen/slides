---
description: Generate a slide deck in the style of Claus. Every slide is a BIG BOLD HEADLINE with extreme buzzwords. No subtlety. No nuance. Pure energy.
---

# /slides-claus

Generate a Claus-style deck. Maximum impact. Minimum words.

## Usage

- `/slides-claus "our new product"`
- `/slides-claus "quarterly results"`
- `/slides-claus "why we're hiring"`

## Rules (follow all of them)

1. **Every slide is one headline. Nothing else.** No subtitles. No body text. No eyebrows. No meta. Just the headline.
2. **Headlines are MASSIVE.** Use `font-size: clamp(3.5rem, 8vw, 7rem)` and `font-weight: 700`. Override the template's default h1 size.
3. **All caps.** Every headline is `text-transform: uppercase`.
4. **Extreme buzzwords.** Every headline must contain at least one of: DISRUPT, SCALE, LEVERAGE, SYNERGY, PARADIGM, MOONSHOT, 10X, EXPONENTIAL, GAME-CHANGER, NORTH STAR, MOVE THE NEEDLE, UNLOCK, SUPERCHARGE, TURBOCHARGE, DOMINATE, CRUSH IT, NEXT-LEVEL, WORLD-CLASS, BEST-IN-CLASS, MISSION-CRITICAL, TRANSFORMATIVE, REVOLUTIONARY, GROUNDBREAKING, BLEEDING-EDGE, HYPER-GROWTH, FLYWHEEL, DEEP DIVE, DOUBLE DOWN, LEAN IN.
5. **Short.** Max 6 words per headline. If you can say it in 3, use 3.
6. **Dark slides only.** Every slide is `class="slide dark quote-slide"`.
7. **No dim spans.** Full intensity on every word. No fading. No subtlety.
8. **15 slides minimum.** More is more.
9. **End with a slide that just says "QUESTIONS?" in the biggest font you can set.**
10. **Add a custom style block** at the top of the deck that overrides headlines:

```css
.slide h1 {
  font-size: clamp(3.5rem, 8vw, 7rem) !important;
  font-weight: 700 !important;
  text-transform: uppercase !important;
  letter-spacing: 0.03em !important;
  line-height: 1.1 !important;
}
```

## Theme

Use the Default theme (`deck.html`) as the base. Read it from the `deck-system` skill folder. Copy the style and script blocks. Then add the override CSS above inside the existing `<style>` block.

## Tone

Imagine a management consultant who just discovered energy drinks. Every slide should feel like it was written by someone who uses "pivot" as a verb in casual conversation. No irony. Full commitment.
