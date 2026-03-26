# Blog

A personal blog built with [Jekyll](https://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/).

## Setup

### Prerequisites

- [Ruby](https://www.ruby-lang.org/) >= 2.7
- [Bundler](https://bundler.io/)

### Run Locally

```bash
bundle install
bundle exec jekyll serve
```

Then open your browser to `http://localhost:4000`.

### Create a New Post

Add a Markdown file to the `_posts/` directory following this naming convention:

```
YYYY-MM-DD-title-of-post.md
```

Each post requires front matter at the top:

```markdown
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD HH:MM:SS +0000
categories: general
---

Your post content here.
```

## Deployment

Push to the `main` branch and GitHub Pages will automatically build and deploy the site.