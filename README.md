# Nexora — Animated Consulting Firm (Demo)

A **single-file, dependency-free** showcase website for a fictional strategy &
technology consulting firm — built to be **fast and highly animated**.

> ⚠️ Demo/showcase project. "Nexora" is a fictional brand; content is illustrative.

## Why it's fast
- **One `index.html`** — HTML, CSS and JS are all inlined.
- **Zero external requests**: no jQuery/frameworks, no CDNs, no web-font download
  (system font stack), no image files — all visuals are CSS gradients, inline
  SVG, and `<canvas>`.
- Result: essentially instant load; nothing to block first paint.

## Animations
Preloader intro · animated mesh-gradient hero · particle constellation ·
custom cursor · magnetic buttons · gradient shimmer headline · scroll-reveal ·
animated counters · tilt/glow cards · marquee · sticky shrinking glass nav ·
back-to-top. All respect `prefers-reduced-motion`.

## Run locally
```bash
python3 -m http.server 8001
# open http://localhost:8001
```

## Deploy
It's a static file — host anywhere. This repo is set up for **GitHub Pages**
(Settings → Pages → deploy from `main` / root).
