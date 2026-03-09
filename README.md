# Reading List

A minimal Jekyll site for tracking daily reading. Hosted on GitHub Pages.

## Setup

1. Create a new GitHub repository named `yourusername.github.io`
2. Push this entire folder to the `main` branch
3. Go to **Settings → Pages** and set source to `main` branch
4. Your site will be live at `https://yourusername.github.io` within a minute

## Adding a new day's readings

Create a new file in `_posts/` with the naming convention:

```
YYYY-MM-DD-readings.md
```

Use this template:

```markdown
---
layout: post
title: "Month Day, Year"
date: YYYY-MM-DD
---

<div class="reading-entry">
  <a href="URL_HERE">Title of the piece</a>
  <span class="tag">topic</span>
  <span class="description">Your one or two sentence note on what it is and why it's interesting.</span>
</div>
```

Repeat the `<div class="reading-entry">...</div>` block for each item you read that day.

## Customisation

- **Site title & description**: Edit `_config.yml`
- **About page**: Edit `about.md`
- **Styling**: Override CSS in `assets/css/style.scss`
- **Theme**: Change `theme:` in `_config.yml` (see [GitHub Pages supported themes](https://pages.github.com/themes/))

## Quick add from GitHub.com

You don't need a local dev environment. Just:
1. Navigate to `_posts/` in your repo on GitHub
2. Click **Add file → Create new file**
3. Name it `2026-03-10-readings.md` (today's date)
4. Paste the template, fill in your readings, commit

The site rebuilds automatically in ~60 seconds.
