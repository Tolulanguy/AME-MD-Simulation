# Molecular Dynamics (MD) Simulation for TLR4-MD2 Complex by $\beta$-Sesquiphellandrene

This repository contains the full code for our project and publication on **Integrated In Vivo and In Silico Analysis Reveals _Aframomum Melegueta_ Neuroprotection Against LPS-Induced Memory Impairment Through TLR4/MD-2 Modulation**.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1GglWlc1rf8LJaTjjcY1J0y2Drnoqd9SN)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18468770.svg)](https://doi.org/10.5281/zenodo.18468770)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> **A Multi-Scale Systems Neuropharmacology Framework** integrating molecular dynamics simulations with mechanistic differential equation modeling to elucidate the neuroprotective mechanism of _Aframomum melegueta_.

---

## 📌 Overview

This repository contains the source code and computational models associated with our study on the interaction between **$\beta$-Sesquiphellandrene** (a key bioactive from *Aframomum melegueta*) and TLR4/MD-2 signaling in the context of LPS-induced neuroinflammation.

By bridging **Molecular Dynamics (MD)** simulations with a **Systems Pharmacology ODE model**, we demonstrate that $\beta$-sesquiphellandrene functions as a competitive lipid mimic. It occupies the hydrophobic pocket of the TLR4-MD2 complex via steric occlusion, silencing the downstream NF-$\kappa$B cascade and driving a supranormal "synaptic rebound" (128% of baseline).

## 🚀 Quick Start

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
