# biowrappers.github.io

BioWrappers is a collection of lightweight wrappers around common bioinformatics APIs and tools, designed to make them easier to use in reproducible workflows.

This is a minimal Jekyll site for BioWrappers with a Pico CSS base layer and a small set of core pages:

- Home
- Projects
- Blog
- About

## Build locally

Prerequisite:

- Ruby with `jekyll` installed and available on your `PATH`

Serve the site locally:

```bash
jekyll serve
```

This starts a local development server with the site available at `http://127.0.0.1:4000/`.

Build the static site without serving it:

```bash
jekyll build
```

The generated site is written to `_site/`.
