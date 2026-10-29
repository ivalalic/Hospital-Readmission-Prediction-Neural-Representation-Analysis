# Hospital Readmission Prediction and Neural Representation Analysis

Master's thesis project in Information Engineering at the Faculty of Organizational Sciences, University of Belgrade.

## Overview

Prediction of hospital readmission within 30 days using classical machine learning and neural networks. In addition to predictive performance, the project analyzes learned internal neural-network representations using **Centered Kernel Alignment (CKA)**, **Representational Similarity Analysis (RSA)**, bottleneck interpretation, and stability across random seeds.

## Notebooks

The original project archive contains twelve notebooks in `notebooks/`:

1. `01_data_understanding.ipynb`
2. `02_data_preprocessing.ipynb`
3. `03_ml_modeling.ipynb`
4. `04_ml_evaluation.ipynb`
5. `05_mlp_modeling.ipynb`
6. `06_mlp_evaluation.ipynb`
7. `07_final_model_comparison.ipynb`
8. `08_representation_extraction.ipynb`
9. `09_cka_analysis.ipynb`
10. `10_rsa_analysis.ipynb`
11. `11_bottleneck_interpretation.ipynb`
12. `12_representation_stability.ipynb`

## Dataset and outputs

The project uses the diabetes hospital encounters dataset (Strack et al.; UCI Machine Learning Repository). The original archive also contains `data/`, `models/`, and `reports/` folders, including trained artifacts and analysis figures.

## Environment

Python and Jupyter; principal libraries include pandas, NumPy, scikit-learn, PyTorch, category_encoders, Optuna, Matplotlib, SciPy, and joblib.

> **Upload status:** README is available; the full original project archive has not yet been committed. This note will be removed once the files are uploaded.
