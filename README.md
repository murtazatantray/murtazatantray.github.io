# murtazatantray.github.io

Personal academic homepage of **Muhammad Murtaza Tantry** — Ph.D. Research Scholar at
Vellore Institute of Technology (VIT), working on Physics-Informed Neural Networks (PINNs)
for the boundary layer flow of viscoelastic fluids.

🔗 **Live site:** https://murtazatantray.github.io/

## About this template

A lightweight, self-contained academic theme built with **plain HTML, CSS, and vanilla
JavaScript** — no Jekyll, no Ruby, no build step, no external framework. It is fast,
accessible, responsive, and ships with a light/dark theme.

```
├── index.html            # the whole site (single page, sectioned)
├── assets/
│   ├── css/style.css     # design tokens + all styling (light & dark)
│   ├── js/main.js        # theme toggle, mobile nav, scroll reveal, back-to-top
│   └── pdf/MM_Tantry_CV.pdf
├── robots.txt
├── sitemap.xml
├── .nojekyll             # tells GitHub Pages to serve files as-is (no Jekyll build)
└── .github/workflows/deploy.yml
```

## Editing content

All content lives in `index.html`, organised into clearly labelled sections
(About, Research, Publications, Education, Skills, Honors/Talks/Training, Contact).
Edit the text directly — no templating language to learn.

- **Colours & fonts:** change the CSS variables at the top of `assets/css/style.css`.
- **Portrait:** the hero shows an `MMT` monogram by default. To use a real photo, drop it at
  `assets/img/profile.jpg` and follow the commented snippet in the `hero__portrait` block of
  `index.html`.
- **CV:** replace `assets/pdf/MM_Tantry_CV.pdf`.

## Local preview

No build tools needed — just serve the folder:

```bash
python3 -m http.server 8080
# then open http://localhost:8080
```

## Deployment

Pushing to `main` triggers `.github/workflows/deploy.yml`, which copies the static files
to the `gh-pages` branch that GitHub Pages serves. Ensure the repository's
**Settings → Pages → Build and deployment → Source** is set to **Deploy from a branch**,
branch **`gh-pages`** (root).
