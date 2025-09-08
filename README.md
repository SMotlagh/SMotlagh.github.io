
# my-research-site

A GitHub Pages project site using the Cayman theme with Markdown pages and a simple blog.

## Quick start

1. Create a public repo named `my-research-site` under your GitHub account `SMotlagh`.
2. Upload everything from this folder to the repo.
3. Go to Settings → Pages and choose Deploy from branch: `main` and `/ (root)`.
   - Alternatively, if asked, enable the GitHub Actions workflow GitHub suggests for Pages.
4. Your site will be published at: `https://smotlagh.github.io/my-research-site/`

## Customize

- `_config.yml`: set `title`, `description`, and replace `google_analytics` with your real ID or remove it.
- Replace `EMAIL_HERE` in the nav links across pages.
- Put your CV at `assets/pdf/CV.pdf` (replace the placeholder).

## New pages

Create a new file with front matter:
```markdown
---
layout: page
title: "My Page"
permalink: /my-page/
---

Content here.
```

## New posts

Add a Markdown file under `_posts/` named `YYYY-MM-DD-title.md` with front matter:
```markdown
---
layout: post
title: "My first post"
date: 2025-09-08
---

Post content.
```

## Optional: MathJax

To render LaTeX, add MathJax to your layout or include file. I can wire this for you on request.
