# Turdiali Khasanbayev — Portfolio

A single-page personal portfolio built with HTML, CSS, and a touch of JavaScript, styled after a code editor / terminal window.

🔗 **Live site:** [xasanbayev.uz](https://xasanbayev.uz/)

## Overview

A lightweight, responsive portfolio card presenting who I am, what I work with, and how to reach me — laid out like an open editor window, from the path breadcrumb at the top down to a live status bar at the bottom. Built with no frameworks and no build step, and deployed as static files via GitHub Pages.

## Sections

- **Path bar** — breadcrumb (`~/turdiali/portfolio.py`) with encoding/read-only badges
- **Profile** — avatar, name (`$ whoami`), and role
- **Skills** — Python, Django Framework, Django Rest Framework, Linux, PostgreSQL, Deployment (nginx && gunicorn), Git (GitHub && GitLab), API testing (Unit && Postman && Swagger)
- **Projects** — iqtisodiybilim.uz, xasanbayev.uz, ReelGo Bot
- **CV** — resume download
- **Contact** — email, Telegram, GitHub, phone
- **Status bar** — git branch, Python version, encoding, live clock, footer copyright

## Tech Stack

- HTML5 (semantic sections, accessible labels)
- CSS3 (Grid, Flexbox, CSS custom properties, `clamp()` for fluid sizing)
- Vanilla JavaScript (footer year + live status-bar clock)
- [Font Awesome](https://fontawesome.com/) for icons
- [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) + [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts

## Project Structure

```
portfolio/
├── apple-touch-icon.png
├── CNAME
├── cv.pdf
├── favicon.ico
├── index.html
├── me.jpg
├── preview.png
└── README.md
```

All styles are kept inline within `index.html` — no separate CSS file needed for a page this size.

## Design

The layout takes cues from code editors and terminals:

- A single "editor shell" card: path bar on top, a line-number gutter on wide screens, a status bar on the bottom
- A dark slate background with amber, teal, and green accents borrowed from a terminal color scheme
- Monospace (JetBrains Mono) for headings and structural labels, paired with Inter for body text
- Section headers styled like code (`import skills`, `ls projects/`, `open cv.pdf`, `exec contact.sh`)
- A fixed-ratio avatar frame with `object-fit: cover`, so any photo crops cleanly without breaking the layout
- Fully responsive: fluid type via `clamp()`, grid collapses to a single column on mobile, gutter hides below 860px, visible focus states, and reduced-motion is respected

## Preview

![Portfolio Preview](/preview.png)

The site features a code-editor-inspired design with a dark, minimal aesthetic. It showcases skills, projects, and contact information inside a single, responsive "editor window."

## Running Locally

No build tools required. Clone the repo and open `index.html` directly in a browser, or serve it locally:

```bash
git clone https://github.com/turdialixasanbayev/portfolio.git
cd portfolio
python3 -m http.server
```

Then visit `http://127.0.0.1:8000`.

## SEO & Sharing

The page includes meta tags for search engines and social previews (Open Graph + Twitter Card), along with a canonical URL and a custom favicon.

## Deployment

Deployed automatically via **GitHub Pages** from the repository root.

## Contact

- ✉️ Email: [xasanbayevturdiali7@gmail.com](mailto:xasanbayevturdiali7@gmail.com)
- 💬 Telegram: [@turdialixasanbayev](https://t.me/turdialixasanbayev)
- 🐙 GitHub: [@turdialixasanbayev](https://github.com/turdialixasanbayev)

## License

This project is open source and available for personal reference. Feel free to fork it for your own portfolio, but please don't reuse the personal content as-is.
