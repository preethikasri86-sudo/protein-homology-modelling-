# FoldLab — Protein Modelling Workbench

**Web app:** https://preethikasri86-sudo.github.io/protein-homology-modelling-/

FoldLab is an interactive browser-based workspace for the early stages of protein comparative (homology) modelling.

## Features
- Paste a protein sequence or upload a FASTA file.
- Validate standard amino-acid symbols.
- Calculate sequence length, estimated molecular mass, GRAVY score and amino-acid composition.
- Export a cleaned FASTA file.
- Open an NCBI BLASTP search for template discovery.
- Follow a guided workflow to build and validate a comparative model using external tools.

## Important scope
This repository currently provides the interactive frontend. BLASTP searches are performed by NCBI, and comparative model generation is performed through an external modelling service such as SWISS-MODEL. The app does not currently run its own modelling server or generate 3D coordinates locally. It does not fabricate template hits, structures or validation scores.

## Run locally
Open `index.html` in a modern browser. No build step or dependencies are required.

## Deployment
GitHub Pages is configured through `.github/workflows/pages.yml`. The app is published from the `main` branch.
