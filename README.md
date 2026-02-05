# Molecular Dynamics (MD) Simulation for TLR4-MD2 Complex by $\beta$-Sesquiphellandrene

This repository contains the full code for our project on **A Multi-Scale Systems Neuropharmacology Framework** integrating molecular dynamics simulations with mechanistic differential equation modeling to elucidate the neuroprotective mechanism of _Aframomum melegueta_.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1GglWlc1rf8LJaTjjcY1J0y2Drnoqd9SN)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18468770.svg)](https://doi.org/10.5281/zenodo.18468770)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> **Publication:** Integrated In Vivo and In Silico Analysis Reveals _Aframomum Melegueta_ Neuroprotection Against LPS-Induced Memory Impairment Through TLR4/MD-2 Modulation.

---

## Overview

This repository contains the source code and computational models associated with our study on the interaction between **$\beta$-Sesquiphellandrene** (a key bioactive from *Aframomum melegueta*) and TLR4/MD-2 signaling in the context of LPS-induced neuroinflammation.

By bridging **Molecular Dynamics (MD)** simulations with a **Systems Pharmacology ODE model**, we demonstrate that $\beta$-sesquiphellandrene functions as a competitive lipid mimic. It occupies the hydrophobic pocket of the TLR4-MD2 complex via steric occlusion, silencing the downstream NF-$\kappa$B cascade and driving a supranormal "synaptic rebound" (128% of baseline).

## Quick Start

The core computational model and figure generation scripts are available as a Jupyter Notebook. You can run the analysis directly in your browser using Google Colab:

**Click the badge below to run the model:**
<br>
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1GglWlc1rf8LJaTjjcY1J0y2Drnoqd9SN)

---

## 📂 Repository Structure

```bash
├── data/
│   ├── LICENSE                     # MIT License File
│   └── ame_mdsimulation.py         # Main Analysis Code in Python File Format
│
├── notebooks/
│   └── AME_MDsimulation.ipynb      # Main Analysis Code (Colab-compatible)
│
└── README.md
```
## Citation

If you use this code, or model, or our md simulation dataset in your research, please cite our publication, dataset, and this code on Zenodo:
[Author Names]. (2026). Integrated In Vivo and In Silico Analysis Reveals _Aframomum Melegueta_ Neuroprotection Against LPS-Induced Memory Impairment Through TLR4/MD-2 Modulation. [Journal Name to be updated soon]. DOI: [will be updated soon] <br>
Oladele, T. S., Iteire, K. A., Ogunmiluyi, O. E., Adebisi, K. A., Siyanbade, A. J., Sulaiman, K. A., Leko, B. J., & Ijomone, O. M. (2026). Code for Integrated In Vivo and In Silico Analysis Reveals _Aframomum Melegueta_ Neuroprotection Against LPS-Induced Memory Impairment Through TLR4/MD-2 Modulation (v1.0.0). Zenodo. https://doi.org/10.5281/zenodo.18487283 <br>
Oladele, T. S., Iteire, K. A., Ogunmiluyi, O. E., Adebisi, K. A., Siyanbade, A. J., Sulaiman, K. A., Leko, B. J., & Ijomone, O. M. (2026). Dataset for Molecular Dynamics Simulation of TLR4/MD-2 Complex with β-Sesquiphellandrene (v1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.18468770
