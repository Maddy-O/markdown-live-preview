# Markdown Live Preview

> A free, fast, single-file Markdown editor with live preview, dark mode, sync scroll, syntax highlighting, and one-click PDF export. Runs entirely in your browser — no sign-up, no backend.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/demo-live-success)](https://maddy-o.github.io/markdown-live-preview/)
[![No Build](https://img.shields.io/badge/build-none-brightgreen)]()
[![Single File](https://img.shields.io/badge/single--file-HTML-orange)]()

**[Live Demo →](https://maddy-o.github.io/markdown-live-preview/)**

---

## Features

- **Live preview** — renders Markdown as you type
- **GitHub Flavored Markdown (GFM)** — tables, task lists, fenced code, strikethrough
- **Syntax highlighting** — powered by [highlight.js](https://highlightjs.org/)
- **Dark mode** — persists across sessions
- **Sync scroll** — editor and preview scroll together
- **PDF export** — save the rendered preview as a PDF
- **Auto-save** — your work is preserved in browser local storage
- **Resizable panes** — drag the divider to adjust split
- **Copy to clipboard** — grab the raw Markdown in one click
- **Zero dependencies to install** — single HTML file, all assets via CDN
- **Responsive** — collapses to stacked layout on mobile

## Quick Start

### Use it online
Just open the [live demo](https://maddy-o.github.io/markdown-live-preview/).

### Run locally
Clone and open `index.html` in any modern browser:

```bash
git clone https://github.com/Maddy-O/markdown-live-preview.git
cd markdown-live-preview
# open index.html — that's it
```

Or serve it with any static server:

```bash
npx serve .
# or
python -m http.server 8000
```

## Tech Stack

| Layer | Library |
|---|---|
| Editor | [Ace Editor](https://ace.c9.io/) |
| Markdown parser | [Marked.js](https://marked.js.org/) |
| Syntax highlighting | [highlight.js](https://highlightjs.org/) |
| PDF export | [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) |
| Fonts | Source Sans 3 + JetBrains Mono (Google Fonts) |

All loaded from CDN — no `npm install`, no build step.

## Project Structure

```
.
├── index.html        # The entire app — markup, styles, and logic
├── robots.txt        # Search engine crawl directives
├── sitemap.xml       # SEO sitemap
├── README.md
└── LICENSE
```

## Deployment

The app is deployed via **GitHub Pages** from the `main` branch.

To enable Pages on your own fork:
1. Go to **Settings → Pages**
2. Source: **Deploy from a branch** → `main` / `(root)`
3. Save — your site will be live at `https://<username>.github.io/markdown-live-preview/`

## Browser Support

Modern evergreen browsers (Chrome, Firefox, Safari, Edge). Requires JavaScript.

## License

[MIT](LICENSE) © Maddy-O
