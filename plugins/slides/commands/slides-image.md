---
description: Add an image slide to an existing deck. Finds images via the Heyra image library and generates the right component.
---

# /slides-image

Add an image-powered slide to your current deck.

## Usage

- `/slides-image "a dramatic hero shot of abstract architecture"`
- `/slides-image split "team working together" --reverse`
- `/slides-image caption "product screenshot"`

## What the command does

1. Takes the user's image description
2. Fetches matching royalty-free images from the Heyra REST API
3. Presents the top results for the user to pick from
4. Generates the appropriate image slide component using the selected image URL

## How to fetch images

Use web fetch to call the Heyra API. The search is semantic (CLIP-based), so describe the mood and subject.

```
GET https://heyraimg-backend-production.up.railway.app/api/search?q={query}&limit=6
```

Response shape:

```json
{
  "query": "abstract architecture",
  "results": [
    {
      "id": "abc123",
      "filename": "HEYRA212.png",
      "image_url": "https://pub-d84682b173804d50ab71dd0c0672b099.r2.dev/images/HEYRA212.png",
      "thumb_url": "https://pub-d84682b173804d50ab71dd0c0672b099.r2.dev/thumbs/HEYRA212.webp",
      "score": 0.32
    }
  ],
  "total": 6
}
```

Use `image_url` in the slide component's `src` attribute. Present results to the user with their `thumb_url` for preview.

## Component selection

The command auto-detects the best image component, or the user can specify:

| Keyword | Component | Use case |
|---------|-----------|----------|
| `hero` | Hero image slide (27) | Cinematic framed moment |
| `split` | Split slide (26) | Text + image side by side |
| `cards` | Image card row (28) | Three visual items |
| `caption` | Caption slide (29) | Single image with annotation |
| `quote` | Image + quote (30) | Portrait with testimonial |
| `grid` | Photo grid (31) | Four related images |
| `collage` | Collage slide (12) | Full-bleed, no text |

## Options

- `--reverse`: Flip the image to the opposite side (for split and quote components)
- `--dark`: Use dark slide variant where available

## Tips

- Be descriptive with your image search. "abstract minimal architecture" works better than "building"
- The API returns semantic matches. Describe the mood, not just the subject
- For the best results, search for one concept at a time
