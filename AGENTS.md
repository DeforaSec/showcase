# DeforaSec Showcase — Agent Instructions

This is **Sajan Ghimire**'s (`@SajanGhimire1`) personal portfolio for DeforaSec security research.

## Structure
- `research/` — Security write-ups (use `RESEARCH_TEMPLATE.md`)
- `tools/` — Security scripts (each must have its own README)
- `contributions/` — OSS contribution tables
- `_layouts/` — Jekyll layout (custom dark theme with nav)
- `assets/` — CSS (`style.css`) and images

## Key files
- `README.md` — GitHub repo front page
- `index.md` — Website landing page (Jekyll)
- `research.md`, `tools.md`, `contributions.md`, `about.md` — Website section pages
- `CONTRIBUTING.md` — Community contribution guide
- `_config.yml` — Jekyll/Pages config (`baseurl: /showcase`)
- `AGENTS.md` — This file

## Build / Deploy
- No local build command — GitHub Pages auto-builds on push to `main`
- Site URL: `https://deforasec.github.io/showcase/`
- Layout is custom CSS (not midnight theme) — edit `_layouts/default.html` and `assets/css/style.css`
- Add logo to `assets/img/` with filename `logo.png` (site references it)

## Conventions
- All research submissions must follow `research/RESEARCH_TEMPLATE.md`
- No hardcoded secrets or unsafe defaults in tools
- Contributions table uses the format in `OSS_CONTRIBUTIONS.md`
- New website pages need front matter: `layout: default` and a `title:`
