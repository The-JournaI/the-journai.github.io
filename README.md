# Money and Power

A Jekyll blog hosted free on GitHub Pages. No build step on your machine.

## Publish a post
Add a file to `_posts/` named `YYYY-MM-DD-short-title.md`:

```
---
title: Your headline
topic: finance        # finance | business | politics
summary: One sentence under the headline (optional).
---
Your text in Markdown.
```

Commit and push (or use GitHub's **Add file → Create new file** in the browser, which also works from your phone). The site updates in about a minute. The newest post becomes the big one on top.

## Change topics, name, site title
`_data/topics.yml` (the three columns) and `_config.yml`.

## Email signup
Signups go to Buttondown. The username is `newsletter_username` in `_config.yml` (set it to empty to hide the forms).

## Preview locally (optional)
`gem install bundler jekyll jekyll-feed && jekyll serve`
