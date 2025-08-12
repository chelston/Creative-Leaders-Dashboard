# Creative Bootcamp – Ads Dashboard

A single-file HTML dashboard (React + Babel CDN) for forecasting paid media results across Instagram, Facebook, and LinkedIn, plus an Excel/CSV learner tracker.

## Run locally
Open `index.html` in your browser.

## Deploy

### GitHub Pages (no build)
1. Create a new repo (public).
2. Upload `index.html` to the root.
3. Settings → Pages → Build and deployment → Source: **Deploy from a branch** → Branch: `main` / root.
4. Wait for Pages to publish, then visit the URL.

### Netlify
- Drag-and-drop the folder at https://app.netlify.com/drop or run:
```
netlify deploy --prod --dir=.
```
(Requires `npm i -g netlify-cli` and login.)

### Vercel
- Run:
```
vercel --prod
```
(Uses static output; no framework config required.)

