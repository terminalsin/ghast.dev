# Jekyll Quickstart Themed
> A barebones Jekyll static site which uses a theme

- Demo site: [michaelcurrin.github.io/jekyll-themed-quickstart/](https://michaelcurrin.github.io/jekyll-themed-quickstart/)


<!-- If editing your own copy of this template, you can deleted the sections below and relace with your own content -->


## Resources

- [Jekyll](https://jekyllrb.com/) homepage
- [Github Pages](https://pages.github.com/) docs
- [Jekyll themes](https://jekyllrb.com/docs/themes/)
- [Jekyll directory structure](https://jekyllrb.com/docs/structure/)


## Jekyll project structure


### Files and directories

A Jekyll site on Github Pages will render if the repo includes the following:

- Config file 
    - `_config.yml`
- Homepage:
    - `index.md` OR
    - `index.html` OR
    - `README.md`
    
If neither of the index files exist, then the `README.md` will be used and is sufficient and it requires no YAML metadata.


No `Gemfile` is needed on Github Pages but is recommended for local use if you have any gems (dependencies), including themes.


### Pages and frontmatter

For other pages (whether markdown or index), they will default to have **no** Jekyll processing. So you probably want to set YAML metadata. 

The minimum would be _empty_ metadata.

```markdown
---
---
Markdown or HTML content goes here.

```

But metadata helps, at least to test a page title and make use of your own layout or a theme's layout. Depending on the theme, you can use `default` or `home` for your base layout.

```markdown
---
# YAML metadata goes here.
title: My homepage title
layout: default
---
Markdown or HTML content goes here.

```


## Create your own

To set up your own site:

### Template

Click the _Use this Template_ button at the top of this repo.

Check your new repo's Settings or _environment_ tab to check the URL of your Github Pages site.


### Create a fresh project

Steps:

1. Create a new repo.
1. Go to Settings of repo.
1. Github Pages section.
1. Choose a branch e.g. master.
1. Choose a theme
    - Use Github UI. This will create a config  file and `README.md` file (warning: this will overwrite an existing `README.md`, which happened me).
    - Create a config file then add `theme:` or `remote-theme:` field.
1. Optionally create an `index.md` file.


## Setup locally

See the [Quickstart](https://jekyllrb.com/docs/) page in the Jekyll docs.


## License

Released under [MIT](/LICENSE).
