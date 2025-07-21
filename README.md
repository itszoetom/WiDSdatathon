# 🧠 WiDS 2024: ADHD Prediction in Women

This repository contains our submission for the **WiDS 2024 Datathon**, focused on using biomedical, cognitive, and demographic data to improve **diagnosis of ADHD in women** — a population that is historically underdiagnosed. Our goal was to develop interpretable and performant models while surfacing gender- and age-related disparities in mental health diagnostics.

## 💡 Motivation

ADHD is significantly underdiagnosed in adult women due to non-traditional symptom presentations, social masking, and systemic bias. This project explores whether machine learning models trained on behavioral and biomedical features can help reduce diagnostic gaps, and which features are most informative for identifying ADHD in women.

---

## 📁 Folder Structure

```bash
model/
├── mk_XGB_model.ipynb          # XGBoost baseline model
├── mk_combo_model.ipynb        # Model stacking: XGB + NN + RF combo
├── mk_nn_model.ipynb           # Basic neural network model
├── pca_age.ipynb               # PCA with age feature engineering
├── pca_nn_model.ipynb          # Multi-output NN model (F1: 0.67)
├── pca_rf_nn.ipynb             # Main model: PCA + RF + NN hybrid
├── submissionXGB.csv           # Submission from XGB model
├── xg_boost.ipynb              # XGBoost tuning and evaluation
