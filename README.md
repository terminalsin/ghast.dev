# Jekyll Themed Site Quickstart
> A starter template for a Jekyll site which uses a theme

[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/jekyll-themed-site-quickstart?include_prereleases=&sort=semver)](https://github.com/MichaelCurrin/jekyll-themed-site-quickstart/releases/)
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)


## How use this project

### Add to your repos

[![Use this Template](https://img.shields.io/badge/Use_this_Template-green?style=for-the-badge)](https://github.com/MichaelCurrin/jekyll-themed-site-quickstart/generate)

### View the live demo

[![Site link](https://img.shields.io/badge/GH_Pages-jekyll_themed_site_quickstart-green?style=for-the-badge)](https://michaelcurrin.github.io/jekyll-themed-site-quickstart/)


<!-- If editing your own copy of this template, you can deleted the sections below and relace with your own content -->


## Resources

- [Jekyll resources](https://michaelcurrin.github.io/dev-resources/resources/jekyll/)
- [Jekyll](https://jekyllrb.com/) homepage
- [GitHub Pages](https://pages.github.com/) docs
- [Jekyll themes](https://jekyllrb.com/docs/themes/)
- [Jekyll directory structure](https://jekyllrb.com/docs/structure/)


## Jekyll project structure

### Files and directories

This project is setup to demonstrate use of the _Required_ file structure below.

If you are looking for a template project with more substantial content like multiple pages, see [jekyll-blog-demo](https://github.com/MichaelCurrin/jekyll-blog-demo). If you are looking for use of layouts, see this project - [themeless-jekyll-quickstart](https://github.com/MichaelCurrin/themeless-jekyll-quickstart).

#### Required

A Jekyll site on Github Pages will render if the repo includes the following:

- Config YAML file:
    - `_config.yml`
- Homepage file
    - `index.md` OR
    - `index.html` OR
    - `README.md`

If neither of the **index** files exist, then the `README.md` will be used instead and is sufficient. It requires no YAML metadata so you can just use a standard README approach to content. Note that any content will appear on the site itself (like links to the site and link to the README which will attempt to download from the site if not ignored).

You can add additional pages, themes, layouts and so on to that setup.

#### Optional files

You might be happy with a site that runs only on Github Pages - this could be fine for a simple site or for doc. 

If you do want to install and run locally, you will need to add these to the project. See [MichaelCurrin/jekyll-blog-demo](https://github.com/MichaelCurrin/jekyll-blog-demo) for a complete example.

- `Gemfile`
    - Github Pages installs based on the config file and not the `Gemfile`, so this is optional if not running locally. 
    - But one is recommended for local use if you have any gems (such as plugins and themes).
- `.gitignore`
    - To ignore the built `_site` directory.
    - Ignore the `vendor/` directory of gems.
    - And to ignore the `.bundle` directory if using `bundler` to install.


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

To set up your own site, choose one of these approaches:

### Template

Click the _Use this Template_ button at the top of this repo under [Add to your repos](#add-to-your-repos) section.

Check your new repo's Settings or _environment_ tab to check the URL of your Github Pages site.

### Create a fresh project

Steps:

1. Create a new repo.
1. Go to Settings of repo.
1. Github Pages section.
1. Choose a branch e.g. master.
1. Choose a theme
    - Use Github UI. This will create a config  file and `README.md` file (warning: this will overwrite an existing `README.md`, which happened me).
    - Create a config file, then add theme as`theme: NAME` or `remote-theme: USER/NAME`.
1. Optionally create an `index.md` file.


## License

Released under [MIT](/LICENSE) by [@MichaelCurrin](https://github.com/MichaelCurrin).
## Setup locally

See the [Quickstart](https://jekyllrb.com/docs/) page in the Jekyll docs.


## License

Released under [MIT](/LICENSE).
