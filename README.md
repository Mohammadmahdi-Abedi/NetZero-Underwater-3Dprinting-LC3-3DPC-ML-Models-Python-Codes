# NetZero-Underwater-3Dprinting-LC3-3DPC-ML-Models-Python-Codes

This repository contains supplementary appendix figures of Python code used in the scientific article on **Next-Generation Net-Zero Composite for Underwater 3D Printing Construction: Hybrid Machine Learning Optimized LC³ with Recycled Rubber**, including all machine learning models developed to predict compressive strength, flexural strength, and yield stress from calcined clay mix compositions.

---

## 📌 Description

These images represent finalized implementations of the following models, developed and tested on a dataset of 287 experimental mix designs:
- **Appendix I** – Artificial Neural Network (ANN)
- **Appendix II** – Linear & Nonlinear Regression (Polynomial)
- **Appendix III** – Hybrid Model: Random Forest + ANN
- **Appendix IV** – Hybrid Model: LightGBM + ANN

---

## 📁 Files in This Repository

| File Name                          | Description                                  |
|-----------------------------------|----------------------------------------------|
| `Appendix_I_ANN_Model.png`        | Optimized deep ANN architecture              |
| `Appendix_II_Regression_Models.png` | Linear and polynomial regression models     |
| `Appendix_III_RF_ANN_Hybrid.png`  | Random Forest + ANN hybrid ensemble          |
| `Appendix_IV_LGBM_ANN_Hybrid.png` | LightGBM + ANN hybrid ensemble               |
| `requirements.txt`                | Python dependencies used in all codes        |

---

## 📄 Dataset

The dataset includes 287 experimental records combining different proportions of:
- Kaolinite
- Montmorillonite
- Illite
- Limestone

Each row includes measured:
- Compressive Strength (MPa)
- Flexural Strength (MPa)
- Yield Stress (Pa)

---

## 🚀 How to Reproduce

To run the codes shown here:

1. Set up Python 3.8+ environment
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Use `.keras` or `.pkl` model outputs (not included here) to reproduce predictions if desired.

---

## 📘 Citation

If you use this code or figures, please cite the related publication (DOI will be added after Zenodo release).

---

## 🔗 License

This repository is released under the **MIT License**.
