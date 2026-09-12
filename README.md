# Jane B. Basmayor — Construction VA Portfolio

A single-page portfolio site for construction virtual assistant services, built as static HTML/CSS (no build step, no dependencies).

## Structure

```
.
├── index.html              # the site
└── assets/
    └── images/              # profile photo, project photos, certificates
```

All images are referenced with relative paths, so the site works as-is when opened locally or hosted anywhere that serves static files.

## Viewing it locally

Just open `index.html` in a browser — no server required.

## Publishing with GitHub Pages

1. Push this folder to a GitHub repository (root of the repo, or a `/docs` folder — either works).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Pick the branch (usually `main`) and the folder this content lives in (`/ (root)` or `/docs`), then **Save**.
5. GitHub will publish the site at `https://<username>.github.io/<repo-name>/` within a minute or two.

## Editing

- Content and layout live in `index.html`.
- To swap a photo, replace the corresponding file in `assets/images/` (keep the same filename) or update the `src` path in `index.html`.
- Fonts (Oswald, Karla) load from Google Fonts via the `<link>` tags in `<head>` — an internet connection is needed for those to render; everything else works offline.

## Contact

Jane B. Basmayor, RCE, RMP, CSP, SO2 — janebasmayorb@gmail.com
