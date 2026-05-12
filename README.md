# AtomCode 100B — Incentive Plan Page

Single-file static landing page. No build step.

## Deploy to GitHub Pages

1. Create a new repo (e.g. `atomcode-100b`).
2. Drop the contents of this `dist/` folder at the repo root (or push to a `gh-pages` branch).
3. In **Settings → Pages**, set source to the branch that holds `index.html`.
4. Visit `https://<your-user>.github.io/<repo>/`.

That's it — `index.html` ships everything inline (CSS, JS, SVG, fonts via system stack).

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```
