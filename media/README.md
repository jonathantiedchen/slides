# media

Drop your images and videos in this folder.

## Naming conventions

- Lowercase. Hyphens, not spaces.
- Match the slide topic (e.g., `demo.mp4`, `screenshot.png`).
- Match the file extension to the format (`.mp4`, `.png`, `.jpeg`, `.webm`, `.svg`).

## Referencing in the deck

In `deck.html`, use relative paths:

```html
<!-- Image -->
<img src="media/demo.png" alt="Demo">

<!-- Video with controls (best for live talks) -->
<video src="media/demo.mp4" controls loop playsinline></video>

<!-- Video that auto-plays silently as a background loop -->
<video src="media/demo.mp4" autoplay muted loop playsinline></video>
```

## Tips

- **Keep images under 2MB** for fast loads.
- **Keep videos under 30 seconds** unless they're the main attraction. Use short loops.
- **Test on the actual screen** you'll present from. Aspect ratios matter.
- **Use `controls` for videos with sound** — browsers block autoplay-with-sound by default. The presenter clicks play during the talk.
- **Use `autoplay muted loop` for visual demos** where sound isn't needed.

## Don't commit huge files

If your media folder gets big (over 100MB), consider Git LFS or hosting media externally.
