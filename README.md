# Dataset for SQD and DMET-based Quantum Simulations

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC--BY--4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19185862.svg)](https://doi.org/10.5281/zenodo.19185862)

## DOI
https://doi.org/10.5281/zenodo.19185862

## Overview
This repository contains datasets supporting the results presented in:

**"Towards Chemically Accurate and Scalable Quantum Simulations on IQM Quantum Hardware: A Quantum-HPC Hybrid Approach"**

The datasets include:
- SQD(LUCJ) simulations
- SQD(LCNot-UCCSD) simulations
- 1D and 2D Potential Energy Surface (PES) scans
- DMET-SQD simulations for ligand-like molecules and Amantadine
- IQM Sirius hardware calibration data

---

## Authors
- Anurag K S V  
- Ashish Kumar Patra  

**Affiliation:** Qclairvoyance Quantum Labs Pvt. Ltd.

---

## Dataset Structure

### SQD Results
- `data/SQD(LUCJ)/`
- `data/SQD(LCNot-UCCSD)/`

Each molecule contains:
- `raw.csv` — Raw sampled data 
- `final1.csv` — Results using ε_s = 10⁸ (samples_per_batch)
- `final2.csv` — Results using ε_s = √|symmetry space|

Each configuration includes **3 independent runs**.

---

### PES Scans

#### 1D PES
- H2, HeH+ (STO-3G, 6-31G)
- LiH, BeH2 (STO-3G)

#### 2D PES
- H2O (STO-3G)

---

### DMET-SQD (LUCJ)
- 8 ligand-like molecules:
  - HOCN (cyanic acid)  
  - CH₃NO (formaldehyde oxime)  
  - CH₅NO (methoxyamine)  
  - C₂H₃NO (methyl isocyanate)  
  - C₂H₅NO (acetaldehyde oxime)  
  - CH₄N₂O (urea)  
  - NOCl (nitrosyl chloride)  
  - HOSCN (hydroxythiocyanate)  

- Amantadine (C₁₀H₁₇N)

Stored as `.txt` files containing:
- Input configurations  
- Fragment definitions  
- Convergence details  
- Energy outputs  

---

### Hardware Data
- IQM Sirius calibration data (`.json`)  
- Obtained from the IQM Resonance Platform

---

## Reproducibility
The datasets provided here are sufficient to reproduce all plots and numerical results reported in the paper.

The simulation code is proprietary and not publicly available.

---

## Units
- Energy: Hartree
- Distance: Å

---

## License
This dataset is licensed under the Creative Commons Attribution 4.0 International (CC-BY 4.0).

---

## Citation
If you use this dataset, please cite:

Anurag K S V, Ashish Kumar Patra (2026).  
*Dataset for SQD and DMET-based Quantum Simulations*.  
Zenodo. https://doi.org/10.5281/zenodo.19185862