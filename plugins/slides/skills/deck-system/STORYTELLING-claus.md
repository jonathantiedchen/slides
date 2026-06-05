# Storytelling: Claus Mode

Every slide is one massive headline. No subtitles. No body text. No nuance. Pure energy. The deck moves fast. The audience reads one line and you advance. Hits in under 2 seconds or you lost the room.

---

## The rules

1. **Max 4 words.** If you can say it in 2, use 2.
2. **All caps.** Always. No exceptions.
3. **Every headline must contain at least one buzzword.** Choose from: DISRUPT, SCALE, LEVERAGE, SYNERGY, PARADIGM, MOONSHOT, 10X, EXPONENTIAL, GAME-CHANGER, NORTH STAR, MOVE THE NEEDLE, UNLOCK, SUPERCHARGE, TURBOCHARGE, DOMINATE, CRUSH IT, NEXT-LEVEL, WORLD-CLASS, BEST-IN-CLASS, MISSION-CRITICAL, TRANSFORMATIVE, REVOLUTIONARY, GROUNDBREAKING, BLEEDING-EDGE, HYPER-GROWTH, FLYWHEEL, DEEP DIVE, DOUBLE DOWN, LEAN IN, MULTI-AWARD WINNING.
4. **No dim spans.** Full intensity on every word.
5. **No punctuation** except question marks on the final slide.
6. **No explanation.** If a headline needs context, rewrite it until it stands alone.
7. **Minimum 15 slides.** More is more.

---

## The structure

There is no structure. There is only impact.

| Slide | Purpose | Example |
|-------|---------|---------|
| 1 | Identity | WE ARE [COMPANY] |
| 2-3 | Problem | THE MARKET IS BROKEN |
| 4-6 | Vision | 10X EVERYTHING |
| 7-10 | Proof points | HYPER-GROWTH UNLOCKED |
| 11-13 | Ambition | DOMINATE THE CATEGORY |
| 14 | Call to action | LEAN IN NOW |
| 15 | Close | QUESTIONS |

---

## Tone

Imagine a management consultant with raging ADHD who just discovered energy drinks. Attention span of a goldfish. Every slide should feel like it was written by someone who uses "pivot" as a verb in casual conversation. No irony. Full commitment. Move fast. Faster.

---

## Slide construction

Every slide uses the dark quote slide component.

```html
<section class="slide dark quote-slide">
  <div class="slide-inner">
    <h1>DISRUPTION IS A FEATURE</h1>
  </div>
</section>
```

Alternate with light quote slides for rhythm:

```html
<section class="slide quote-slide">
  <div class="slide-inner">
    <h1>SCALE OR DIE</h1>
  </div>
</section>
```

---

## Example headlines

- DISRUPT EVERYTHING
- 10X OR GO HOME
- WE STOPPED PLANNING
- SPEED IS STRATEGY
- THE MOAT IS MOMENTUM
- TALENT WANTS CHAOS
- BUILD SHIP REPEAT
- MOONSHOT ACTIVATED
- THIS IS INEVITABLE
- LEAN IN NOW
- CRUSH THE CATEGORY
- HYPER-GROWTH UNLOCKED
- PARADIGM DEMOLISHED
- NEXT-LEVEL UNLOCKED
- GO

---

## What NOT to do

- Do not add subtitles or body text. Ever.
- Do not use stat grids, timelines, feature cards, or any complex component.
- Do not explain anything.
- Do not use more than 4 words per slide.
- Do not be modest. Confidence at 11.
- Do not use dim spans. Every word at full intensity.

---

## Component usage

Use ONLY these components:
- **Quote slide** (dark and light variants): the only component
- **Cover slide**: opening slide only, still just a headline

Do not use two-column, capability lists, stat grids, timelines, product slides, or any layout component. This format is pure text energy.
