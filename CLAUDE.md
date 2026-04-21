# CLAUDE.md

## Project Overview

Academic LaTeX paper on **Channel-Interference and Spin-Orbit effects on Quantum Tunneling in Mono-layer Graphene**.

Authors: Eduardo Serna, L. Diago-Cisneros, I. Rodríguez-Vargas.

## File Structure

```
src/            # Active working files (compile from here)
  main02.tex          # Main document to compile
  introduction02.tex
  development02.tex
  alphabeta02.tex
  discussion02.tex
  bib/
    main.bib
    mybibEJS.bib
Base/           # Older/reference versions of files
  main.tex
  introduction.tex
  development02.tex
  discussion-of-results.tex
  alpha-beta-values-en.tex
  main.pdf
assets/         # Images, figures, and reference articles
  templates/    # Document class files (iopjournal)
out/            # Compiled output
```

## Build

Compile `src/main02.tex` (active version). The document class is `iopjournal` from `assets/templates/`.

## Key Topics

- Dirac fermions in monolayer graphene (MLG)
- Rashba spin-orbit interaction (SOIR)
- Channel interference (CI) effects on transmission coefficients
- Quantum transport and spintronics applications
