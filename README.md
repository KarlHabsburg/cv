# CV - Marc Borer

[![Build CV PDF](https://github.com/marcborer/cv/actions/workflows/build-pdf.yml/badge.svg)](https://github.com/marcborer/cv/actions/workflows/build-pdf.yml)

LaTeX CV with automated PDF builds via GitHub Actions.

## Download

**[Download Latest CV (PDF)](https://github.com/marcborer/cv/releases/latest/download/Lebenslauf.pdf)**

## How It Works

1. Edit `Lebenslauf.tex` and push to `main`
2. GitHub Actions compiles the LaTeX to PDF using [tectonic](https://tectonic-typesetting.github.io/)
3. The PDF is published as a GitHub Release asset at a stable URL

## Local Build

```bash
# Using tectonic
tectonic Lebenslauf.tex

# Or using latexmk
latexmk -pdf Lebenslauf.tex
```

## License

Content is personal. LaTeX template license may vary.
