+++
title = "Olla"
template = "index.html"
page_template = "page.html"
sort_by = "weight"
+++

## What?

A minimal HTML-only [Zola](https://www.getzola.org/) theme

## Why?

I like using [mkdocs](https://www.mkdocs.org/) for documentation. Especially on Python projects combined with [mkdocstrings](https://github.com/mkdocstrings/mkdocstrings) for API docs and [mkdocs-material](https://squidfunk.github.io/mkdocs-material/) for a good looking theme.

However, as with most websites nowadays, it requires copious amounts of CSS and Javascript in order to function properly. I also don't like that, as with all Python projects, you need a Python interpreter, virtualenv, pip, pip dependencies etc.... just to build the site.

My ideal workflow would be to use a static site generator that is just a single binary, taking Markdown for input, and which produces output similar to mkdocs + mkdocs-material. I chose Zola over Hugo because it uses Rust, and it seems that it doesnt yet have the same feature bloat.

## Templates

Im well aware that the content of the index.html and page.html are pretty much duplicated, and probably missing some features. However, I have no interest in frontend work, and have no intention of being interested. Its perfectly functional with just text on a page.

The design of these HTML pages was inspired by the [Ed25519](http://ed25519.cr.yp.to/) website.
