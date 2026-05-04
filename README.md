# Survival Analysis Portfolio

**Author:** Oluwatobi Elegbede — MSc Biostatistics (Survival Analysis, ML, Epidemiology, Clinical Trials)

---

## Projects

### 1. Kaplan‑Meier Analysis of Lung Cancer Survival (`01_KM_lung_dataset.ipynb`)
- **Data:** `lifelines.datasets.load_lung()` – 228 lung cancer patients.
- **Methods:** KM curves, log‑rank test, risk tables, confidence bands.
- **Key results:** Median survival 310 days; females have significantly better survival (log‑rank p ≈ 0.0013).
- **Limitations:** Univariate only. Next: Cox regression.

> More projects (Cox PH, Random Survival Forests, DeepSurv) will be added.

---

## Run the code

- **Online:** Open the notebook in [Google Colab](https://colab.research.google.com/).
- **Locally:**  
  ```bash
  git clone https://github.com/yourusername/survival_ml_portfolio.git
  pip install lifelines pandas matplotlib numpy
