# FoldLab — Protein Homology Modelling

> **🌐 Live website: [Open FoldLab](https://preethikasri86-sudo.github.io/protein-homology-modelling-/)**

[![Visit Website](https://img.shields.io/badge/Visit-Live%20Website-2ea44f?style=for-the-badge)](https://preethikasri86-sudo.github.io/protein-homology-modelling-/)

A responsive educational website introducing protein homology (comparative) modelling.

## Website sections
- Introduction to target proteins, templates and predicted structures
- Five-stage homology modelling workflow
- Illustrative sequence alignment
- Interactive amino-acid sequence format checker
- Model validation concepts: Ramachandran plots, RMSD, clashes and stereochemistry
- Links to BLAST, UniProt, RCSB PDB, SWISS-MODEL, ChimeraX and MolProbity

## Run locally
Open `index.html` in a web browser. No build tools or dependencies are required.

## Publish with GitHub Pages
The repository includes a GitHub Actions workflow in `.github/workflows/pages.yml`. In the repository, open **Settings → Pages** and select **GitHub Actions** as the build and deployment source if it is not already selected. The workflow will publish the site after a push to `main`.

## Scientific note
This is an educational explainer, not a production homology-modelling engine. The sequence checker validates standard one-letter amino-acid symbols only; it does not perform BLAST searches, select templates, build coordinates or validate a real structure. The workflow and validation graphics are conceptual.

## External resources
- [NCBI BLAST](https://blast.ncbi.nlm.nih.gov/Blast.cgi)
- [UniProt](https://www.uniprot.org/)
- [RCSB Protein Data Bank](https://www.rcsb.org/)
- [SWISS-MODEL](https://swissmodel.expasy.org/)
- [UCSF ChimeraX](https://www.cgl.ucsf.edu/chimerax/)
- [MolProbity](http://molprobity.biochem.duke.edu/)
