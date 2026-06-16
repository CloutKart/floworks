# Floworks AI — Blog Landing

A single, self-contained landing page for the Floworks AI blog.

- **One file:** `index.html` (HTML + CSS + vanilla JS inline; the only external resource is Google Fonts).
- Neomorphism + liquid-glass UI, orange brand theme, light mode.
- 26 posts split into **Case Studies / AI Strategy / Versus / Tools** sections, with real thumbnails embedded inline.
- Interactive hero (cursor-reactive orange gradient), **click ripple** on cards, and the **"Meet Alisha"** agent-team constellation (Alisha + Jesse / Linda / Sam).
- Fully responsive (1440 / 1024 / 768 / 375), respects `prefers-reduced-motion`.

## Run locally

Open `index.html` directly, or serve it:

```bash
python3 -m http.server 8080
# → http://localhost:8080
```

## Deploy

Static site — **no build step**. On Vercel, use framework preset **Other**, with the output/root being the repository root (it serves `index.html`).
