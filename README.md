# Spinmasters Tennis Academy

The official website for **Spinmasters Tennis Academy**, Dubai's home for world-class tennis coaching, competitive leagues, and a community built around the game — based at Al Nasr Sports Centre, Oud Metha.

**Live site:** [spinmasterstennis.ae](https://spinmasterstennis.ae) &nbsp;·&nbsp; [sv62.github.io/spinmaster](https://sv62.github.io/spinmaster/)

## What's here

This is a single-file website — all HTML, CSS and JavaScript (plus every image, embedded as base64) live in `index.html`. There's no build step, no dependencies, and no server required. It's a client-side single-page app: navigation between sections is handled entirely in JavaScript, so the whole site loads once and pages switch instantly.

### Pages

- **Home** — hero, training programs overview, facility gallery, partners, Instagram callout
- **Coaches** — Head Coach spotlight plus a flip-card grid for the coaching team
- **Programs** — detailed breakdown of the Junior Academy, Performance Elite, and Adult programs
- **Tournaments** — SMTL league info, live rankings table, photo highlights, and season winners
- **Player Profiles** — individual profile pages for each ranked player, linked from the rankings table (opens in a new tab)

## Running locally

No build tools needed — just open the file directly:

```bash
open index.html
```

Or serve it with any static file server if you'd rather use a URL than `file://`:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000/index.html
```

## Deployment

The site is published via **GitHub Pages** from the `main` branch, with a `CNAME` file pointing the custom domain (`spinmasterstennis.ae`) at the GitHub Pages host.

## Contact

📍 Al Nasr Sports Centre, Oud Metha, Dubai
📞 054 371 2520
✉️ info@spinmasterstennis.ae
