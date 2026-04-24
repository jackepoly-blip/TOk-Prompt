# Scene Generator Prompts — Web App

Static single-page web app that displays all 17 cloned prompts with their images, preserving the exact text from Notion.

**Live demo:** https://webapp-vlkbhvos.devinapps.com/

## Features

- Gallery index grouped by category
- Thumbnail previews (or "META PROMPT" badge for the two tool templates with no thumbnail)
- Full-text search across title, category, description, and prompt body
- Per-prompt detail page with all images, quick description, and the complete prompt
- Copy-prompt-to-clipboard button
- Click any image to view it full-size (lightbox)
- Entirely static — no build step, no server required

## Data sources

The page reads:

- `../data/prompts.json` — structured prompt records (title, category, quick description, full text, image filenames)
- `../prompts/images/*` — the original PNG images downloaded from Notion

## Run locally

From the repo root:

```bash
python3 -m http.server 8765
# open http://localhost:8765/webapp/
```
