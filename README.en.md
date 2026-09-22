**Contents:**

- [Chinese](README.md)
- [English](README.en.md)
- [Japanese](README.ja.md)

# Handheld Matrix — Handheld Console Comparison Dashboard

A pure front-end comparison dashboard for handheld gaming consoles, with full specs for 8 popular handhelds built in — so you can pick the right device by budget, weight, battery life, and screen preferences.

**How to use:** just open `index.html`. No build step, no account — all computation and rendering happen locally in your browser.

## Features

- **Multi-dimension spec cards**: price, weight, battery, screen (size / type / refresh rate / resolution / color gamut), and hardware, all at a glance
- **Fuzzy search**: Fuse.js search with aliases (e.g. SD, Deck)
- **Slider filters**: nouislider filtering by price and key specs
- **Visualization**: Chart.js charts and a radar comparison panel
- **MATRIX COMPARE**: select multiple devices and compare them side by side
- **Poster export**: export the comparison as a PNG with html2canvas
- **Details**: card 3D tilt + glare (vanilla-tilt), Lucide icons, dark / light themes

## Data

Device specs live in `devices.json`. To add a new handheld, just add an entry — the page reads it automatically.

## License

MIT
