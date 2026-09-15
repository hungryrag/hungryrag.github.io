# Supriyo Jana — Portfolio

A single-file, responsive developer portfolio built with a "high-performance systems / observability dashboard" aesthetic — dark theme with emerald/cyan accents, monospace tags, and terminal-inspired UI motifs.

🔗 **Live site:** https://hungryrag.github.io

## Tech Stack

- HTML5 (single file, no build step)
- [Tailwind CSS](https://tailwindcss.com/) via CDN
- [Lucide Icons](https://lucide.dev/) via CDN
- Fonts: [Inter](https://fonts.google.com/specimen/Inter) & [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono)
- Vanilla JavaScript (mobile nav, click-to-copy email, smooth scroll, terminal typewriter effect)

## Sections

- Sticky glassmorphism navbar with mobile menu
- Hero with quick actions (copy email, location, CTAs)
- Key telemetry / impact metrics with sparklines
- Live scrolling log ticker
- Featured engineering highlights (architecture breakdown cards)
- Technical arsenal (masonry-style bento grid of skills)
- Interactive terminal-style contact section
- Footer

## Running Locally

No build step required — just open [index.html](index.html) directly in a browser, or serve it locally:

```bash
npx serve .
```

## Deployment

Hosted via [GitHub Pages](https://pages.github.com/) — any push to the default branch is served directly from `index.html`.

## Updating Content

All content (work history, skills, metrics) lives inline in [index.html](index.html). Update the relevant section and refresh the browser — Tailwind CDN compiles classes on the fly, so no rebuild is needed.
