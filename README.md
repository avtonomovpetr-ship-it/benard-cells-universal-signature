# Bénard Cells in Brains, Markets, and Senates

This repository contains the code and preprint for the paper: 
**"Bénard Cells in Brains, Markets, and Senates: Constrained Network Reconstruction Reveals a Universal Signature of Collective Organization"**

## Contents
- `preprint.pdf`: The full compiled paper.
- `main.tex`: LaTeX source code for the preprint.
- `fmri_analysis.ipynb`: Python code for reconstructing fMRI brain networks.
- `equities_analysis.ipynb`: Python code for reconstructing S&P 500 market networks.
- `senate_analysis.ipynb`: Python code for reconstructing US Senate voting networks.

## Method
The code applies Non-Negative Least Squares (NNLS) combined with a spatially weighted L1 penalty to eliminate negative (implausible) connections and reveal local, energy-minimizing "Bénard cell" structures across three domains.
