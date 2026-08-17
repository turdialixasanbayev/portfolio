# Turdiali Xasanbayev — Portfolio

A single-page personal portfolio built with HTML, CSS, and a touch of JavaScript, styled as a minimalist, resume-style document.

🔗 **Live site:** [xasanbayev.uz](https://xasanbayev.uz/)

## Overview

A lightweight, responsive one-pager presenting who I am, what I work with, and how to reach me — laid out like a printed résumé: a single centered column, hairline rules between sections, and no decoration beyond what the content needs. Built with no frameworks and no build step, and deployed as static files via GitHub Pages.

## Sections

- **Identity** — name, role, location, and contact links (email, phone, website, GitHub, Telegram)
- **Summary** — a short professional summary
- **Technical Skills** — grouped by category: Languages, Backend & Frameworks, Databases, Infrastructure & DevOps, Tools & Version Control, Engineering Principles
- **Projects** — iqtisodiybilim.uz, ReelGo Bot, xasanbayev.uz
- **Education** — university and program
- **Practical Work & Certifications** — course, self-study, and practice entries
- **Resume** — CV download link
- **Footer** — copyright and location

## Tech Stack

- HTML5 (semantic sections, accessible labels)
- CSS3 (Grid, Flexbox, CSS custom properties, `clamp()` for fluid sizing)
- Vanilla JavaScript (footer year only)
- [Source Serif 4](https://fonts.google.com/specimen/Source+Serif+4), [Inter](https://fonts.google.com/specimen/Inter), and [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) via Google Fonts

## Project Structure

```
portfolio/
├── CNAME
├── cv.pdf
├── index.html
└── README.md
```

All styles are kept inline within `index.html` — no separate CSS file needed for a page this size.

## Design

The layout is built as a plain, professional document rather than a themed interface:

- A single centered column (`~700px` measure), generous whitespace, and hairline dividers between sections — no cards, no shadows, no border-radius
- Pure white background with a grayscale palette only — no accent color, no gradients
- A serif display face (Source Serif 4) for the name and section titles, paired with Inter for body text and JetBrains Mono for labels, roles, and metadata
- No animation beyond a subtle hover state on links; `prefers-reduced-motion` is respected
- Fully responsive: fluid type via `clamp()`, a two-column skills grid that collapses to one column on mobile, and visible focus states throughout

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
