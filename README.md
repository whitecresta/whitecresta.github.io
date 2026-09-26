# chris-perkins-site

Personal research site built with [Quarto](https://quarto.org).

- Add a tool: copy `tools/_template.qmd` to `tools/<name>/index.qmd`, put app files in `tools/<name>/app/`.
- Add a note: create `notes/YYYY-MM-slug/index.qmd`.
- Preview locally: `quarto preview`
- Publishing: pushing to `main` on GitHub builds and deploys via GitHub Pages (Settings > Pages > Source: GitHub Actions).
