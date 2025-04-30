# 🥘 Carbonara Proof of Concept

**Bayesian Radiocarbon Calibration with Python**

Carbonara is a proof of concept for a potential Bayesian sequential calibration software.

It aims to become a lightweight, flexible, and open-source alternative to existing radiocarbon calibration programs, built in Python using PyMC. It supports transparent, reproducible modelling of radiocarbon dates with full access to the underlying logic and statistical assumptions.

## 🚀 Run it online

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MartinHinz/carbonara_poc/HEAD?urlpath=%2Fdoc%2Ftree%2Fnotebooks%2Fcarbonara_minimal_example.ipynb)

Click the badge above to launch the demo notebook in Binder — no local installation required.

## 📁 Repository Structure

- `notebooks/` — Jupyter notebooks with examples and demonstration models
- `src/` — Python modules and utilities for calibration and model logic
- `data/` — Example datasets, including the IntCal20 calibration curve
- `binder/` — Environment files for reproducible execution on Binder
- `README.md` — This project description
- `LICENSE` — Project license (default: MIT)

## ⚙️ Local Installation

To run the notebooks locally with all required dependencies:

```bash
git clone https://github.com/MartinHinz/carbonara_poc.git
cd carbonara_poc
conda env create -f binder/environment.yml
conda activate carbonara
jupyter lab
```