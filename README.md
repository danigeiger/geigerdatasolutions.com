# Geiger Data Solutions

Source files for [geigerdatasolutions.com](https://geigerdatasolutions.com), built with [Quarto](https://quarto.org/).

## Pages

- `index.qmd` — home page and featured projects
- `portfolio.qmd` — detailed project portfolio
- `services.qmd` — analytics and data science services
- `about.qmd` — professional background, education, and technical focus
- `contact.qmd` — contact links
- `styles.css` — custom site styling
- `_quarto.yml` — navigation, site metadata, output, and footer configuration
- `CNAME` — GitHub Pages custom domain
- `favicon.svg` — lightweight site icon

## Local preview

From the repository directory:

```bash
quarto preview
```

## Render

```bash
quarto render
```

Rendered files are written to `_site/`.

## Publish workflow

After editing the source files:

```bash
quarto render
git add .
git commit -m "Update Geiger Data Solutions website"
git push origin main
```

The repository's GitHub Pages configuration should point to the deployment method already used for the site. If GitHub Pages is configured to serve a branch/folder rather than a Quarto GitHub Action, keep that existing deployment setting consistent.
