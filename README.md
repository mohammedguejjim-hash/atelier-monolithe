# Atelier Monolithe — Awwwards-style Architecture Template

A single-page, award-calibre website template for an architecture studio.
Built with hand-written HTML/CSS/JS — no framework, no build step.

**Live demo:** https://mohammedguejjim-hash.github.io/atelier-monolithe/

## ✨ Signature effects

- **Preloader** — counter 0→100 with curtain reveal
- **Ink cursor** — dot + trailing ring that morphs into a "VOIR" badge on interactive elements
- **Hero** — giant display typography reveal over a parallax image
- **Blueprint section** — architectural floor plan that *draws itself* as you scroll (SVG stroke animation, scroll-scrubbed)
- **Projects** — editorial list where the project image follows your cursor on hover
- **Manifesto** — word-by-word text reveal on scroll
- **Stats** — animated counters
- **Lenis** buttery smooth scrolling + GSAP ScrollTrigger throughout
- Film-grain overlay, marquee strip, hide-on-scroll nav

## 📁 Structure

```
atelier-monolithe/
├── index.html          # the whole site (markup + styles + scripts)
├── README.md
└── assets/
    └── img/
        ├── hero.jpg
        ├── projet-villa.jpg
        ├── projet-riad.jpg
        ├── projet-culturel.jpg
        ├── projet-musee.jpg
        └── studio.jpg
```

## 🛠 Customize

| What | Where |
|---|---|
| Texts (French) | `index.html` — search the section comments |
| Images | replace files in `assets/img/` (keep the same names) |
| Colors | CSS `:root` in `index.html` — `--paper`, `--ink`, `--accent`, `--blue` |
| Contact email | search `bonjour@atelier-monolithe.ma` in `index.html` |
| Projects | duplicate an `<a class="projet">` block, change `data-img`, title, meta |

Libraries load from CDN (GSAP 3.12, ScrollTrigger, Lenis 1.1, Google Fonts). If they fail to load, the site gracefully degrades to a fully readable static page.

## 🚀 Deploy

Any static host works. For GitHub Pages: repo Settings → Pages → Deploy from branch → `main` / root.

---
*Template crafted as an original interpretation of Awwwards-level interaction patterns. All copy and imagery are AI-generated originals.*
