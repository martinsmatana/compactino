# COMPACTINO

A planned project landing page — *your tiny genius who packs big topics into modular bricks that click.*

## Stack

- **Plain HTML/CSS/JS** (no build step required)
- **GSAP 3.12** + **ScrollTrigger** (CDN)
- **Lenis** smooth scroll (CDN)
- **canvas-confetti** (CDN)
- **Sonda Trial** font (woff2, local)
- **Cabinet Grotesk** (Fontshare CDN)

## Local dev

Just open `index.html` in a browser. No server needed.

(Or for nicer SPA-style behavior: `python3 -m http.server 8080`)

## Deploy on GitHub Pages

```bash
git init
git add .
git commit -m "compactino landing page"
git branch -M main
git remote add origin https://github.com/<your-user>/<repo-name>.git
git push -u origin main
```

Then in repo Settings → Pages → Source: `main` branch, root.

Site will be live at `https://<your-user>.github.io/<repo-name>/`.

## Folder structure

```
.
├── index.html              # the entire page (HTML + CSS + JS inline)
├── assets/
│   └── img/                # 18 GIFs grouped by background colour
│       ├── black bg/
│       ├── beige bg/
│       ├── cyan/
│       ├── gray bg/
│       ├── light blue bg/
│       ├── light gray 1 bg/
│       ├── light gray 2 bg/
│       ├── light gray 3 bg/
│       ├── light gray 4/
│       ├── pink bg/
│       ├── purple bg/
│       └── white bg/
├── assets-fonts-woff2/     # Sonda Trial (web-friendly woff2)
├── compactino.svg          # original logo SVG (single O, reference)
├── compactino_all.svg      # original logo SVG (full word, reference)
└── README.md
```
