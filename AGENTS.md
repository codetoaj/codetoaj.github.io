# AGENTS.md

## What this repo is

Deployment-only GitHub Pages repo for the portfolio site at `codetoaj.github.io`. Default branch is `master`; a push to `master` publishes the site. No CI workflow is used.

## Gotchas

- There is **no source code here**. The repo contains only `index.html` and `404.html`. There is no `package.json`, no node_modules, no build tooling checked in.
- `index.html` is a self-contained single-page portfolio (vanilla HTML/CSS/JS, no external JS dependencies beyond Google Fonts). It replaced an earlier React/MERN app whose source lives in a separate (unlisted) repo; the old `app.bundle.js` was removed and is not needed here.
- `404.html` is a Firebase-generated 404 page (leftover from an early deploy); it was lightly restyled to match the portfolio.
- Do not run build/test/lint commands here; there is nothing to build or test in this directory.
