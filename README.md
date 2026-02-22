# Aria.github.io

Personal academic portfolio website for **Arghavan (Aria) Alisoltani, PhD**, built as a single-page static site.

## Project Overview

This repository hosts a responsive personal website with:

- Profile and contact sidebar
- Sticky top navigation
- Highlighted sections for biography, expertise, and professional links
- Custom styling defined directly in `index.html`

## Repository Structure

- `index.html` — Main website page (HTML + embedded CSS)

## Run Locally

Because this is a static site, you can open it directly or serve it locally.

### Option 1: Open directly

Open `index.html` in your browser.

### Option 2: Serve with Python

```bash
python3 -m http.server 8000
```

Then visit:

- <http://localhost:8000>

## Deployment

This repository is suitable for GitHub Pages deployment:

1. Push to the default branch.
2. In repository settings, enable **GitHub Pages**.
3. Set source to the root of the default branch.

## Customization

To update content or style:

1. Edit text and sections in `index.html`.
2. Adjust theme variables in the `:root` CSS block.
3. Commit and push changes.

## License

No license file is currently provided. Add one if you plan to distribute or reuse this project publicly.
