# Spinmasters Tennis Academy

The official website for **Spinmasters Tennis Academy**, Dubai's home for world-class tennis coaching, competitive leagues, and a community built around the game — based at Al Nasr Sports Centre, Oud Metha.

**Live site:** [spinmasterstennis.ae](https://spinmasterstennis.ae) &nbsp;·&nbsp; [sv62.github.io/spinmaster](https://sv62.github.io/spinmaster/)

## What's here

All HTML, CSS and JavaScript live in `index.html`; images live in `img/` and are referenced by absolute path (e.g. `/img/hero.jpg`), so each page only downloads the images it shows. There's no build step and no dependencies. It's a client-side single-page app: navigation between sections is handled in JavaScript, so pages switch instantly.

### URLs

Pages have clean URLs — `/coaches`, `/programs`, `/tournaments`, `/other-services`, `/player/<slug>` and `/coach/<slug>`. GitHub Pages has no real file at those paths, so `404.html` and the small `index.html` stubs in each page folder forward the visitor to `/?route=<path>`, and the app restores the original URL and opens the right page. Old `#tournaments` / `#player=<slug>` links are converted automatically.

To add a new top-level page, add it to `PAGE_NAMES` and `PAGE_TITLES` in `index.html`, copy one of the stub folders, and add it to `sitemap.xml`.

### Pages

- **Home** — hero, training programs overview, facility gallery, partners, Instagram callout
- **Coaches** — Head Coach spotlight plus a flip-card grid for the coaching team
- **Programs** — detailed breakdown of the Junior Academy, Performance Elite, and Adult programs
- **Tournaments** — SMTL league info, live rankings table, photo highlights, and season winners
- **Player Profiles** — individual profile pages for each ranked player, linked from the rankings table (opens in a new tab)

## Running locally

No build tools needed — just open the file directly:

Serve the folder with any static file server (images use absolute paths, so opening `index.html` via `file://` won't show them):

```bash
python3 -m http.server 8000
# then visit http://localhost:8000/
```

## Deployment

The site is published via **GitHub Pages** from the `main` branch, with a `CNAME` file pointing the custom domain (`spinmasterstennis.ae`) at the GitHub Pages host.

## Contact

📍 Al Nasr Sports Centre, Oud Metha, Dubai
📞 054 371 2520
✉️ info@spinmasterstennis.ae
