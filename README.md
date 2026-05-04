# Survival Analysis Portfolio

**Oluwatobi Elegbede** — MSc Biostatistics (Survival Analysis, ML, Epidemiology, Clinical Trials)

---

## Project 1: Kaplan‑Meier Analysis of Lung Cancer Survival

**Notebook:** `01_KM_lung_dataset.ipynb`

- **Data:** 228 lung cancer patients (`lifelines.datasets.load_lung()`)
- **Methods:** KM curves, log‑rank test, risk tables, confidence bands
- **Key results:** Median survival 310 days; females survive longer (log‑rank p ≈ 0.0013)
- **Limitations:** Univariate only → next: Cox regression

---

## Run this project

```bash
git clone https://github.com/ElegbedeOluwatobi/survival_ml_portfolio.git
cd survival_ml_portfolio
pip install -r requirements.txt
jupyter notebook
