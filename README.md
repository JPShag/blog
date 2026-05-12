# JPShag Blog

This repository contains a Jekyll blog configured for GitHub Pages.

## Stack

- Jekyll `~> 4.3`
- Minima theme
- Plugins:
  - `jekyll-feed`
  - `jekyll-seo-tag`
  - `jekyll-sitemap`

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000/blog/`.

## Publish on GitHub Pages

This repository already includes a GitHub Actions workflow at:

- `.github/workflows/pages.yml`

To publish:

1. Push to `main`.
2. In GitHub repo settings, open **Pages**.
3. Set **Source** to **GitHub Actions**.

## Posting

Create posts in `_posts/` with filenames in this format:

`YYYY-MM-DD-title.md`
