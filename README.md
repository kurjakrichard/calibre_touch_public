# Calibre Touch – public website

Static HTML/CSS/JS site for the Calibre Touch app. No build step.

```
├── index.html      Landing page (features, privacy summary, contact)
├── privacy.html    Full privacy policy
├── css/style.css   Styles (colors from the app logo, light + dark mode)
├── js/main.js      Mobile menu + footer year
└── assets/         logo.png (512px) and favicon.png
```

## Preview locally

Open `index.html` in a browser, or serve the folder:

```
python -m http.server 8000
```

then visit http://localhost:8000.

## Publishing

The repository root can be deployed as-is to GitHub Pages, Netlify, or any static host.
For GitHub Pages: Settings → Pages → Deploy from branch → `main` / `(root)`.
