# Bahram Behzadian - Personal Website

Personal academic website built with [Quarto](https://quarto.org/).

**Live site:** [buiksat.github.io](https://buiksat.github.io)

## Local Development

### Prerequisites

Install Quarto: https://quarto.org/docs/get-started/

### Preview locally

```bash
quarto preview
```

This starts a local server with live reload at `http://localhost:4000`.

### Build for production

```bash
quarto render
```

Output goes to the `docs/` directory.

## Deployment

The site is deployed via GitHub Pages from the `docs/` folder on the `master` branch.

To deploy changes:

1. Make edits to `.qmd` files
2. Run `quarto render`
3. Commit and push (including the `docs/` folder)

## Structure

```
├── _quarto.yml      # Site configuration
├── index.qmd        # Homepage
├── publications.qmd # Publications page
├── cv.qmd           # CV page
├── styles.css       # Custom styles
├── files/           # PDFs (papers, CV)
├── images/          # Images (profile photo)
└── docs/            # Rendered site (served by GitHub Pages)
```
