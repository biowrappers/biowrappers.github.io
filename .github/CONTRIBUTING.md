# Contributing

Thanks for contributing to BioWrappers. This repository hosts the BioWrappers
GitHub Pages site, so most changes affect site content, page templates, or the
Jekyll build and deployment flow.

## Before Opening an Issue or Pull Request

- Check the existing issue tracker to avoid duplicates.
- Make sure your branch is based on the latest `main`.
- If you are reporting a site bug, include the affected page URL and a short
  description of what you expected to happen.
- For visual issues, include a screenshot when possible.

## Local Development

Prerequisite:

- Ruby with `jekyll` installed and available on your `PATH`

Run the local site:

```bash
jekyll serve
```

Build the site for verification:

```bash
jekyll build
```

## Contribution Guidelines

- Create a dedicated branch for each change.
- Keep pull requests scoped to one topic when possible.
- Preserve the site's minimal style unless the change explicitly calls for a
  visual redesign.
- Update documentation or content text when the behavior or navigation changes.
- Run `jekyll build` before opening a pull request.

## Pull Request Expectations

Please include:

- A clear summary of what changed
- Any relevant issue reference
- Notes about visual or content changes
- Screenshots for visible UI updates when appropriate

## Questions

If you are unsure whether a change belongs in the site, open an issue first:

https://github.com/biowrappers/biowrappers.github.io/issues
