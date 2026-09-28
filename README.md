# benyaminbeyzaei.fyi

Source for my personal website, [benyaminbeyzaei.fyi](https://benyaminbeyzaei.fyi), built with [Jekyll](https://jekyllrb.com/).

## Run locally

Needs Ruby 3.4 (installed by [mise](https://mise.jdx.dev/)).

```sh
mise install
bundle install
bundle exec jekyll serve --livereload
```

Then open <http://localhost:4000>. Changes to `_config.yml` need a restart.

## Write a post

Add `_posts/YYYY-MM-DD-title.md`:

```markdown
---
title: Post title
description: One-sentence summary for search results and link previews.
---

Post content in Markdown.
```

## Deploy

Push to `main`. GitHub Actions builds the site and publishes it to GitHub Pages.
