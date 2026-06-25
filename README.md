# GavinGolden.com

Personal website built with Jekyll, hosted on GitHub Pages.

## Structure

- `_writings/` — Essays and longer thoughts
- `_art/` — Photography, drawings, paintings
- `_reflections/` — Work and industry musings
- `_posts/` — Short-form blog posts (optional)

## Adding Content

### New Writing
Create a file in `_writings/my-essay.md`:
```markdown
---
title: "My Essay Title"
date: 2026-06-25
---

Your content here.
```

### New Art
Create a file in `_art/piece-title.md`:
```markdown
---
title: "Artwork Title"
date: 2026-06-25
image: /images/art/filename.jpg
image_alt: "Description"
---

Details about the piece.
```

### New Reflection
Create a file in `_reflections/topic.md`:
```markdown
---
title: "Reflection Title"
date: 2026-06-25
---

Your thoughts here.
```

## Local Development

```bash
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000`

## Deployment

Push to GitHub. GitHub Pages auto-builds Jekyll.
