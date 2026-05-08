# Storytelling

How to build a 20-minute talk that actually lands.

This deck template is just paint. The story is what carries it. This guide is the storytelling pattern that the template was built around — distilled from talks that worked.

---

## The shape of a 20-minute talk

```
0:00 ─────────────────────────────────────────── 20:00
│ Open │  Act 1  │  Act 2  │     Act 3      │ Act 4 │ Close │
  2min   3min      3min        8min            3min   1min
```

Six beats. Roughly. Don't overthink the timing — it's a guide, not a contract.

### Open (2 min) — *the personal hook*
A confession, a contradiction, something true about you that the audience will recognize in themselves. Not your bio. Not your company. **You.**

> *"I have a confession. I am not a very patient person."*

One line. Pause. Let the room come to you.

### Act 1 — The Gap (3 min)
The way things used to be. The pain. The reason ideas died, projects stalled, frustrations accumulated. This is where you build empathy with the audience. They've felt this too.

End Act 1 with something quiet: *"That felt normal. That was just how it worked."*

### Act 2 — The Shift (3 min)
The turn. Something changed. Tools, technology, your own perspective. State it cleanly:

> *"The bottleneck moved."*

Don't over-explain. The audience is smart. They know what you mean.

### Act 3 — The Builds (8 min, the meat)
The longest section. Stories of what you've actually done with the new way. Concrete examples. Real artifacts. Not theory.

Three to five stories is the sweet spot. Each one:
- A frustration (the human moment)
- The build (what you did)
- The takeaway (why it mattered)

Don't recite them. Tell them like you're remembering them.

### Act 4 — The Honest Part (3 min)
The part most talks skip. The doubt. The failure. The thing you're still figuring out. This is where the audience trusts you — because you stopped selling.

> *"Speed is not the same as wisdom."*

If you're not willing to say something here that costs you a little, the talk won't land.

### Close (1 min)
The mic drop. One or two lines. Slow down for them.

> *"The tools changed. The instinct is still yours."*

Pause. Walk off. Don't explain.

---

## The headline pattern

Every slide that has a headline uses the same trick: **bold-then-dim**.

> **Spec-driven development** *at scale.*
> **One spec.** *Full transparency.*
> **The tools changed.** *The instinct is still yours.*

The first phrase carries weight. The second fades to gray. This gives every headline a built-in narrative — anchor + extension. It's the most consistent visual identity in the deck.

In HTML:
```html
<h1>Anchor. <span class="dim">Extension.</span></h1>
```

Use it everywhere. Don't fight it.

---

## Punctuation in the deck

A 20-minute deck without rhythm is just a wall of text. Use these to break it up:

### Quote slides
A single bold statement. No subtitle. No supporting text. Just the line, taking up the whole slide.

Use one to open. Use one to close. Maybe one in the middle as a turning point.

### Dark slides
Black background, white text. Reserved for moments that matter:
- The pivot ("The bottleneck moved.")
- The mic drop at the end

Two or three per deck max. More than that and the emphasis stops working.

### Breakers
A single line that punctuates the end of a section before the next one starts. Often a question or a quiet declarative.

> *"That felt normal. Until it wasn't."*
> *"But isn't this just chaos?"*

Use them between Act sections. They give the audience a beat to absorb before you push forward.

---

## Show, don't tell

For build stories (Act 3), use the **product slide → collage slide** pair:

- **Slide A** (product slide): the text. Number, hook, headline, description.
- **Slide B** (collage slide): full-bleed image or video. The thing in action.

Read the copy → advance → image lands. Brutal punch.

If you have video, use it. Even a five-second loop of the actual product is more memorable than three sentences of description.

---

## Common mistakes

### 1. Too many builds
You're proud of your work. You want to show all of it. But more isn't better. Three solid stories beat ten thin ones. Pick the ones with the strongest emotional hook.

### 2. Skipping the honest part
This is the biggest mistake in tech talks. Everyone wants to look smart. Nobody wants to look uncertain. But the honest part is where the audience decides whether they like you. Without it, you're a brochure.

### 3. Talking about your company
The audience didn't show up to hear about your company. They showed up to hear something true. Mention your role at the start, then stop. Spend the rest of the time on ideas, not branding.

### 4. Trying to be funny
If you're naturally funny, jokes will appear. If you're not, don't force them. A clear, calm delivery beats a forced punchline.

### 5. Reading the slides
The slide is the punchline. You're the setup. If you read the slide, the audience has already absorbed it before you finish. Talk to the audience. Glance at the slide.

---

## A formula that works

If you don't know where to start, this works:

```
1. Confess something true about you.
2. Show the world before the change (the pain).
3. Show what changed.
4. Tell three to five concrete stories of what you've done.
5. Admit one thing you're still wrong about.
6. Close with one line you've practiced.
```

Six beats. Use them. Skip them. Reorder them. They're a starting point, not a script.

---

## On the closing line

Spend more time on your closing line than any other line in the deck.

It should be:
- **Short.** One sentence, or two short ones.
- **Memorable.** The kind of thing that fits on a t-shirt.
- **True.** If it's a slogan, the audience can smell it.

Practice saying it out loud. Slow down for it. Then walk off.

Examples that worked:

> *"The tools changed. The instinct is still yours."*
> *"Coding is solved. The orchestration around it is not."*
> *"What gets specced is what gets built."*

You'll know yours when you find it.

---

## One more thing

The deck doesn't make the talk. The talk makes the talk.

The deck supports it. The deck is the page numbers. The deck is the punctuation. But the words coming out of your mouth, said with conviction, are the actual product.

Spend 80% of your prep on the script. 20% on the slides.

If you flip that ratio, your talk is going to look great and feel hollow. The audience will clap politely and forget it tomorrow.

Make them feel something instead.
