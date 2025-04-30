# 🥘  Carbonara Proof of Concept
**Bayesian Radiocarbon Calibration with Python**

A proof of concept for a potential bayesian sequential calibration software

Carbonara might develop into a lightweight, flexible, open source alternative to existing calibration programs, built with Python and PyMC. It allows for transparent and reproducible calibration of radiocarbon dates using Bayesian models.

## 🚀 Run it online

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MartinHinz/carbonara_poc/HEAD?urlpath=%2Fdoc%2Ftree%2Fnotebooks%2Fcarbonara_minimal_example.ipynb)

Click the badge above to run the demo notebook in your browser via Binder (no installation needed).

## 📂 Structure

- `notebooks/` — Jupyter notebooks with examples and demos
- `src/` — utility functions and model code
- `data/` — small example datasets
- `binder/` — Binder environment setup
- `README.md` — this file!

## ⚙️ Installation (locally)

```bash
git clone https://github.com/YOUR_USERNAME/carbonara.git
cd carbonara
conda env create -f binder/environment.yml
conda activate carbonara
jupyter lab
```