# DNPI 3.0 — Engineering plan (published)

Static GitHub Pages site for the **DNPI 3.0 implementation plan** HTML.

## Live site

**https://tthreatt.github.io/dnpi-3.0-engineering/**

## Source of truth (local workspace)

The working document before publish lives alongside your EA project:

`projects/whatIsDynamicNPI30/DNPI-3.0-implementation-plan.html`

(Path relative to the `EA` repo/workspace root.)

## Update and republish

After editing the source HTML, copy it into this repo as `index.html`, commit, and push:

```bash
cp /path/to/EA/projects/whatIsDynamicNPI30/DNPI-3.0-implementation-plan.html \
   /Users/tthreatt/git/dnpi-3.0-engineering/index.html
cd /Users/tthreatt/git/dnpi-3.0-engineering
git add index.html
git commit -m "Update DNPI 3.0 implementation plan"
git push
```

GitHub Pages refreshes in about a minute after push.

## Tech notes

- `.nojekyll` disables Jekyll so the raw HTML is served.
- Mermaid diagrams load from `cdn.jsdelivr.net` in the page head.
