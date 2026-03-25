# Christopher Antwi — Personal Academic Website

Personal research portfolio built with [Quarto](https://quarto.org).

**Live site:** https://christopher-antwi.github.io

## Structure

```
├── index.qmd          # Homepage / About
├── research.qmd       # Research & working papers
├── projects.qmd       # Working projects
├── cv.qmd             # Curriculum vitae
├── _quarto.yml        # Site configuration
├── custom.scss        # UO brand styling
├── styles.css         # Additional overrides
└── docs/              # Rendered output (GitHub Pages source)
```

## Local development

```bash
# Install Quarto: https://quarto.org/docs/get-started/
quarto preview
```

## Deploy

```bash
quarto render
git add docs/
git commit -m "Update site"
git push
```

GitHub Pages is configured to serve from the `docs/` folder.
