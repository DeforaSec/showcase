# DeforaSec Showcase — Agent Instructions

This is **Sajan Ghimire**'s (`@SajanGhimire1`) personal portfolio for DeforaSec security research.

## Structure
- `research/` — Security write-ups (use `RESEARCH_TEMPLATE.md`)
- `tools/` — Security scripts (each must have its own README)
- `contributions/` — OSS contribution tables
- `_layouts/` — Jekyll layout (custom dark theme with nav)
- `assets/` — CSS (`style.css`) and images
  - `assets/img/logo.png` — Org logo (shown in header)
  - `assets/img/photo.png` — Founder photo (shown on About page)

## External profiles
- **Medium** (research write-ups): `https://medium.com/@inksecghiwir3`
- **LinkedIn**: `https://www.linkedin.com/in/54j4n/`
- **X/Twitter**: `https://x.com/QuietEcho18`
- **Hall of Fame**: Etherscan, Bugcrowd (Afterpay #52), ArcGIS Trust Center

## Key files
- `README.md` — GitHub repo front page
- `index.md` — Website landing page (Jekyll)
- `services.md` — Service offerings (VAPT, Web, Mobile, Tooling)
- `research.md` — Write-up archive
- `contributions.md` — OSS contribution summaries
- `about.md` — Company profile + Hall of Fame
- `CONTRIBUTING.md` — Community contribution guide
- `_config.yml` — Jekyll/Pages config (`baseurl: /showcase`)
- `AGENTS.md` — This file

## Build / Deploy
- No local build command — GitHub Pages auto-builds on push to `main`
- Site URL: `https://deforasec.github.io/showcase/`
- Layout is custom CSS — edit `_layouts/default.html` and `assets/css/style.css`
- Add logo to `assets/img/` with filename `logo.png` (site references it)

## Conventions
- All research submissions must follow `research/RESEARCH_TEMPLATE.md`
- No hardcoded secrets or unsafe defaults in tools
- Contributions table uses the format in `OSS_CONTRIBUTIONS.md`
- New website pages need front matter: `layout: default` and a `title:`
