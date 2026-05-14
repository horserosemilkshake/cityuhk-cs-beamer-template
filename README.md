# CityUHK CS Beamer Template

An unofficial Beamer presentation template using the Madrid theme with CityU color styling.

## Included Files

- `main.tex`: Main presentation source file
- `references.bib`: Bibliography entries for the References slide
- `figures/CityU_logo.svg.png`: Logo used on the title page
- `figures/Lenna.png`: Sample image used in the figure example slide

## Build Instructions

Use `pdflatex` + `bibtex` for bibliography support:

```bash
pdflatex -interaction=nonstopmode -halt-on-error main.tex
bibtex main
pdflatex -interaction=nonstopmode -halt-on-error main.tex
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```

## Template Highlights

- 16:9 Beamer layout (`aspectratio=169`)
- Madrid theme with custom CityU color palette
- Numbered captions for figures and tables
- Math/equation template slides
- Combined figure + table two-column example slide
- Auto-breaking references slide via `biblatex`

## Notes

- If references do not appear, run the full build sequence above.