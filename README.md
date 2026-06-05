# biowrappers.github.io

<p align="center">
  <img
    src="https://raw.githubusercontent.com/biowrappers/biowrappers.github.io/2f52fe7aa46943a8c6266330cf0929211b4a39e6/biowrappers_logo.png"
    alt="BioWrappers Logo"
    width="220"
  >
</p>

BioWrappers is a collection of lightweight wrappers around common bioinformatics APIs and tools, designed to make them easier to use in reproducible workflows.

This is a minimal Jekyll site for BioWrappers with a Pico CSS base layer and a small set of core pages:

- Home
- Tools
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

## Community

- [Contributing guidelines](.github/CONTRIBUTING.md)
- [License](LICENSE)
