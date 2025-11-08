# Bronze → Gold — Quarto Starter

## Quick start
```bash
quarto preview      # live reload
quarto render       # build to docs/
```

- GitHub Pages: Settings → Pages → Source: `main` / `/docs`
- Custom domain: keep `CNAME` at repo root; Quarto copies it into `docs/`

## Files
- `_quarto.yml` — site config (light/dark theme, fonts, CSS)
- `index.qmd`, `blog.qmd`, `about.qmd`, `impressum.qmd`, `privacy.qmd`
- `posts/` — put your articles here
- `images/medal.svg` — logo
- `styles.css` / `fonts.html` — design
- `CNAME` — custom domain mapping
- `.github/workflows/quarto-pages.yml` — optional CI to build & deploy
