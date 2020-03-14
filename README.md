# IDMIL Master Proposal Template (LaTeX)

Find IDMIL references in: https://gitlab.com/idmil/administrative/template-latex-references-bibtex

## Instructions

Choose between both following options: with or without Overleaf.

## With Overleaf

- Create an Overleaf project
- Upload all files from this repository
- Create a new repository under https://gitlab.com/idmil/theses/
following this naming convention for the repository name: master-proposal-{firstname}-{lastname}-{catchy-title}
- Mirror overleaf into your new gitlab repository

## Without Overleaf

- Fork this template into a new repository under https://gitlab.com/idmil/theses/
following this naming convention for the repository name: master-proposal-{firstname}-{lastname}-{catchy-title}
- To compile:
```
pdflatex main.tex
biber main
pdflatex main.tex
```