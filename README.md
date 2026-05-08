# kwanlada-srijomkwan.com

Personal website for Kwanlada Srijomkwan. Plain HTML/CSS/JS — no build step.

## Local preview

Open `index.html` in a browser, or run a local server:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Editing

- All content lives in `index.html`.
- Profile photo: `assets/headshot.jpg`
- CV PDF: `assets/cv.pdf`
- Artwork images: `assets/art/`
- Custom domain: configured via `CNAME`

## Deploy

This site is hosted on GitHub Pages and served at <https://kwanlada-srijomkwan.com>. See `SETUP-GUIDE.docx` (one folder up) for full deployment instructions.

After making changes, just commit and push — GitHub Pages auto-deploys.

```bash
git add .
git commit -m "Update site"
git push
```
