---
description: Browse and preview images from the Heyra image library. Search, filter, and save URLs for use in slides.
---

# /slides-gallery

Search and browse the Heyra image library.

## Usage

- `/slides-gallery "minimal architecture"`
- `/slides-gallery random`
- `/slides-gallery recent`

## What the command does

1. Fetches images from the Heyra REST API based on the search mode
2. Displays results with thumbnails, filenames, and relevance scores
3. Lets the user pick images to use in their deck

## API endpoints

Base URL: `https://heyraimg-backend-production.up.railway.app`

| Mode | Endpoint | Description |
|------|----------|-------------|
| `"query"` | `GET /api/search?q={query}&limit=6` | Semantic search by description |
| `random` | `GET /api/random?limit=6` | Random selection from the index |
| `recent` | `GET /api/recent?limit=6` | Recently indexed images |

All endpoints return a list of image objects with `image_url`, `thumb_url`, `filename`, and `score` (for search).

Use `image_url` values directly in any slide component's `src` attribute.

## Tips

- Queries are semantic. "warm sunset over water" finds relevant images even if titles differ
- Use this to explore before building a deck, or to find replacement images for specific slides
- The library contains ~1,500 royalty-free images, mostly abstract and design-oriented
