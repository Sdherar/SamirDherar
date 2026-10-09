# Samir Dherar portfolio

Static portfolio for https://sdherar.github.io/SamirDherar/. No build system, framework, external fonts, or backend is required.

## Preview and edit

Serve this directory with `python -m http.server 8000`, then open `http://localhost:8000`.

- `index.html`: portfolio content and project disclosures.
- `resume.html`: résumé and browser print/PDF action.
- `style.css`: shared portfolio design and responsive styles.
- `site.js`: top/bottom PCB switching and Aegis disclosure link.
- `assets/`: original photographs, renders, figures, and preview derivatives.

Keep the files together and preserve `.nojekyll`. Relative resource paths support GitHub Pages project hosting under `/SamirDherar/`. Canonical and social-image URLs intentionally point to the production URL.

## Review and publication

The proposed improvements are on `portfolio-improvements`. See [REVIEW.md](REVIEW.md) for the before/after summary, evidence qualifications, checks completed, and browser-testing limitations. Review and browser-test the branch before merging into `main`; merging may trigger the existing GitHub Pages deployment. Do not change the Pages publishing branch to preview these changes.
