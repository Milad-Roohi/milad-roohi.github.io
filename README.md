# milad-roohi.github.io

Personal / SiRIUS Lab academic site for **Dr. Milad Roohi** (University of Nebraska–Lincoln).

- **Live:** https://milad-roohi.github.io/ (after Pages is enabled)
- **Lab CMS:** https://sirius.unl.edu/
- **Content source:** Digital Mind `A-Research/82 Website and Social Media/2026-SiRIUS-Website-Content/`

## Design

Single-page static site (HTML/CSS). Visual language is intentionally **different** from peer lab templates (e.g. TALI): navy “observatory” hero, Fraunces + Manrope + JetBrains Mono, teal/star accents, numbered research spine instead of icon cards.

## Update workflow

1. Edit CV (`cv_tp.tex`) and/or website content pack markdown.
2. Update `index.html` publications / news / research blurbs.
3. `git commit` + `git push` to `master`.
4. Optionally mirror key facts into UNL Herbie (`sirius.unl.edu`) manually.

## Local preview

Open `index.html` in a browser, or:

```bash
python3 -m http.server 8000
```
