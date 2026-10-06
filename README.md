# milad-roohi.github.io

Personal / SiRIUS Lab academic site for **Dr. Milad Roohi** (University of Nebraska–Lincoln).

- **Live:** https://milad-roohi.github.io/
- **Default branch:** `site-2026`
- **Lab CMS:** https://sirius.unl.edu/
- **Content source:** Digital Mind `A-Research/82 Website and Social Media/2026-SiRIUS-Website-Content/`

## Structure

A static multi-page site. Each page is one self-contained HTML file with inline CSS. There is no build step or framework.

**Nav (synced on every page):** People · Research · Publications · Teaching · Service · News (+ Openings CTA).

| Page | Contents |
| ---- | -------- |
| `index.html` | Landing: lab overview, why the name, collaborators, latest news, join |
| `research.html` | Research pillars, theme areas, testbeds, funded projects |
| `publications.html` | Selected journal publications (published and accepted) |
| `people.html` | PI, postdocs, students, alumni |
| `teaching.html` | Courses, Teaching Fellows / USDA Systems Thinking Fellow; mentoring → People |
| `service.html` | Editorial & national leadership, conferences, community, review, selected talks |
| `news.html` | News by year |
| `openings.html` | How to join the lab |
| `assets/` | `sirius-logo.png` (logo only; no headshots) | `sirius-logo.png` (logo only; no headshots) |

Old single-page links (`index.html#publications`, `#research`, `#funding`, `#about`, `#news`, `#theme-*`, `#fund-*`, `#pub-*`) are forwarded to the new pages by a small script in the `<head>` of `index.html`.

## Update workflow

1. Edit the CV (`cv_tp.tex`) and/or the website content pack markdown.
2. Update the relevant page (`publications.html`, `news.html`, `people.html`, `research.html`, `teaching.html`, `service.html`, …). The nav and footer are repeated in each file, so keep them in sync.
3. `git commit` and `git push` to `site-2026`.
4. Optionally mirror key facts into UNL Herbie (`sirius.unl.edu`) manually.

## Local preview

Open `index.html` in a browser, or:

```bash
python3 -m http.server 8000
```
