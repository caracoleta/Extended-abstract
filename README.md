# Extended Abstract: Measuring Airport Efficiency

This repository contains the LaTeX source files for an extended abstract on measuring the efficiency of Portuguese and Spanish airports using Data Envelopment Analysis (DEA).

## Files Structure

- `ExtendedAbstract.tex` - Main LaTeX document
- `ExtendedAbstract_*.tex` - Section files (abstract, introduction, background, methodology, results, conclusions, acknowledgments)
- `ExtendedAbstract_ref_db.bib` - Bibliography database
- `images/` - Directory containing figures
- `Makefile` - Build automation

## Methodology

This study applies three main methodological approaches:

1. **Data Envelopment Analysis (DEA)** - Non-parametric efficiency evaluation
2. **Truncated Regression** - Second-stage analysis with bootstrap procedures
3. **Malmquist Productivity Index (MPI)** - Productivity change assessment

## Building the Document

To compile the LaTeX document:

```bash
make
```

Or manually:

```bash
pdflatex ExtendedAbstract.tex
bibtex ExtendedAbstract
pdflatex ExtendedAbstract.tex
pdflatex ExtendedAbstract.tex
```

## Author

Gonçalo Valente Monteiro da Silva  
Instituto Superior Técnico, Lisboa, Portugal

## Date

October 2025