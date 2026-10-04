# Tuneline landing page

Static one-page site (plain HTML, no build step). "Tuneline" is a working name.

- `index.html` – the whole page (CSS and JS inline, fonts from Google Fonts)
- `vercel.json` – Vercel config (static, clean URLs)

## Deploy on Vercel
1. Put this folder in a GitHub repo (root = this folder).
2. On vercel.com: Add New > Project > import the repo. Framework preset: Other. No build command, output directory: `.` (root).

## Turn on signups
The form shows a "preview only" notice until `FORM_ENDPOINT` near the bottom of `index.html` is set,
for example to a free Formspree form URL (`https://formspree.io/f/...`). Submissions then arrive by email.
