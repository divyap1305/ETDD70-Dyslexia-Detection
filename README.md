# Cross-Task Generalization and Explainable Machine Learning for Dyslexia Detection

## Project Overview
This project explores dyslexia detection using eye-tracking data and machine learning. It focuses on identifying important eye-movement features, evaluating classification models, and studying their generalization across different reading tasks.

## Dataset
The project uses the ETDD70 dataset, containing 70 participants: 35 dyslexic and 35 non-dyslexic participants.

Reading tasks:
- Syllables
- Meaningful Text
- Pseudo Text

Dataset: https://doi.org/10.5281/zenodo.13332134

## Methodology
- Data preprocessing and feature extraction
- Statistical analysis using the Mann–Whitney U test and FDR correction
- Classification using Logistic Regression, Random Forest, and XGBoost
- Participant-grouped cross-validation
- Cross-task generalization evaluation
- SHAP-based feature importance and explainability

## Technologies Used
- Python
- Google Colab
- Pandas and NumPy
- SciPy
- Scikit-learn
- XGBoost
- SHAP

## Project Files
- `ETDD70_Dyslexia_Detection.ipynb` — analysis and machine learning notebook
- `results/` — model evaluation and SHAP visualizations (if uploaded)

## Disclaimer
This is an academic research project and is not intended for clinical diagnosis of dyslexia.
