# moshepoliak.com

Personal academic website of Moshe Poliak.

- `site/` holds the whole site as plain HTML and CSS: no build step and no framework. Styles live in `site/assets/site.css`.
- Every push to `main` publishes `site/` to GitHub Pages via `.github/workflows/deploy.yml`.
- To preview locally, run `python3 -m http.server 8642 --directory site` and open http://localhost:8642.
