# pact-site

The public programme page for PACT, served by GitHub Pages from this repository.

- `index.html` — the page. Self-contained: no external requests, no dependencies, no tracking.
- `PACT_Programme_Overview.pdf` — the same material as a four-page document, for attaching to email.
- `.nojekyll` — tells GitHub Pages to serve the files as they are.

The software this page describes lives in
[pact-commit](https://github.com/ahmedrazaumer1/pact-commit) and
[pact-pool](https://github.com/ahmedrazaumer1/pact-pool).

## Editing

Change `index.html`, commit, push. GitHub Pages redeploys in about a minute.

## Custom domain

Add a file named `CNAME` containing the bare domain, then point a CNAME record at
`ahmedrazaumer1.github.io`.
