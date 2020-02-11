# Jekyll Quickstart Themed
> A barebones Jekyll static site which uses a theme

- Github Pages website -[michaelcurrin.github.io/jekyll-quickstart-themed/](https://michaelcurrin.github.io/jekyll-quickstart-themed/)

## Structure

A Jekyll site on Github Pages will render using the following:

- Config file - `_config.yml`
- Homepage
    - `index.md`
    - `index.html`
    - `README.md`
    
If neither of the index files exist, then the `README.md` will be used and is sufficient and it requires no YAML metadata.

For other pages (whether markdown or index), they will default to have **no** Jekyll processing. So you probably want to set YAML metadata. 

The minimum would be empty metadata.

```
---
---
Content
```

But metadata helps, especially give the theme's styling using a layout.

```
---
layout: home
title: My homepage title
---
Content goes here.
```

## Create your own

To set up your own site:
- Click the _Use as Template_ button above, or
- Start from scratch
    1. Create a new repo.
    1. Go to Settings of repo
    1. Github Pages section.
    1. Choose a branch e.g. master.
    1. Choose a theme. This will create a config and `README.md` (this overwrote my existing `README.md` though).
    1. Optionally create an `index.md` file.
