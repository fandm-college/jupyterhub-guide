# F&M JupyterHub Faculty Guide

This repository contains the online faculty guide for F&M JupyterHub, built with the [Just the Docs](https://just-the-docs.com/) Jekyll theme.

## Local preview

Install Ruby and Bundler, then run:

```bash
bundle install
bundle exec jekyll serve
```

Open the local URL printed by Jekyll, usually:

```text
http://127.0.0.1:4000
```

## GitHub Pages

This site is designed to work with GitHub Pages. After committing the files, enable Pages for the repository and configure the source branch in the repository settings.

## Updating screenshots

Screenshots are stored in:

```text
assets/images/screenshots/
assets/images/annotated/
```

When replacing screenshots, keep the same filenames if possible so links do not need to be updated.

## Callouts

The guide uses these Just the Docs callouts:

- `good-to-know`
- `expect`
- `help`
- `optional`
- `recommendation`


## Layout note

All Markdown pages use the Just the Docs `default` layout through `_config.yml` defaults. The home page explicitly uses `layout: home`.

Custom styles are stored in:

```text
_sass/custom/custom.scss
```

This is the Just the Docs-supported location for custom SCSS.
