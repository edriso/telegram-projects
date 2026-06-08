# Telegram Projects Landing Page

A simple, single-page site that lists a family of free Telegram channels and bots.

## Features

- One static `index.html`, no build step and no dependencies.
- Bilingual: Arabic and English, with Arabic as the default.
- The language choice is remembered in the browser.
- Works on mobile and desktop.

## Run it

Open `index.html` in any browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000

## Deploy

Any static host works (GitHub Pages, Netlify, Cloudflare Pages). Just publish this folder.

## Edit the content

All the text and links live in two arrays near the bottom of `index.html`:

- `I18N` holds the interface strings for `ar` and `en`.
- `PROJECTS` holds each project: icon, name, description, and links.

Add or change a project by editing the `PROJECTS` array.
