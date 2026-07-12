# Turdiali Xasanbayev — Portfolio

A single-page, macOS/iOS-inspired personal business card website built with vanilla HTML, CSS, and JavaScript.

🔗 **Live site:** [turdialixasanbayev.github.io/portfolio](https://turdialixasanbayev.github.io/portfolio/)

## Overview

This is a lightweight, responsive portfolio site designed to look and feel like a native macOS window — complete with a traffic-light title bar, a translucent Dock-style contact bar, and a bento-grid layout for skills. No frameworks, no build step — just static files deployed via GitHub Pages.

## Sections

- **Hero** — name, role, and avatar
- **Skills** — Python, Django/DRF, FastAPI, Linux
- **Projects** — featured work with short descriptions
- **Contact** — email, Telegram, Instagram, GitHub, and phone
- **Footer**

## Tech Stack

- HTML5
- CSS3 (Flexbox, Grid, custom properties, backdrop blur)
- Vanilla JavaScript
- [Font Awesome](https://fontawesome.com/) for icons

## Project Structure

```
portfolio/
├── index.html
├── favicon.ico
├── favicon-512.png
├── preview.png
└── README.md
```

## Design

The interface borrows core visual patterns from Apple's macOS and iOS design language:

- Window chrome with red/yellow/green traffic-light buttons
- Rounded corners and soft, layered shadows
- A blurred, floating Dock for social/contact links
- A minimal, neutral color palette with a single blue accent

## Running Locally

No build tools required. Clone the repo and open `index.html` directly in a browser, or serve it locally:

```bash
git clone https://github.com/turdialixasanbayev/portfolio.git
cd portfolio
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

Deployed automatically via **GitHub Pages** from the repository root.

## Contact

- ✉️ Email: [xasanbayevturdiali92@gmail.com](mailto:xasanbayevturdiali92@gmail.com)
- 💬 Telegram: [@turdialixasanbayev](https://t.me/turdialixasanbayev)
- 🐙 GitHub: [@turdialixasanbayev](https://github.com/turdialixasanbayev)

## License

This project is open source and available for personal reference. Feel free to fork it for your own portfolio, but please don't reuse the personal content as-is.
