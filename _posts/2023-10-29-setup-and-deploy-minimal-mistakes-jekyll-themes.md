---
title: Setup and deploy Minimal-mistakes jekyll themes
date: 2023-10-29 15:20 +0100
category:
    - jekyll
    - minimal mistakes
tag:
    - jekyll
    - minimal mistakes
---

# Setup

Download the following files and folder:
- `_data`
- `config.yml`
- `index.html`
- `Gemfile1` create when run `jekyll new <name>`
- `Gemfile2` from starter template

Modify `Gemfile1` by adding plugin from `Gemfile2`, change gem theme to minimal mistakes, add plugin compose


Modify `config.yml`

    Set name, url, baseurl, sass: quite_deps:true (for hiding warning), search: true, defaults: post: value: toc: true tock_sticky:true; them, skin

Note: not use github-page plugin;

Copy the workflow github action from al-folio to a folder name `.github/workflows`

run
```bash
bundle
bundle exec jekyll serve
```

