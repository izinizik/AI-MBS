# AI-Powered fMRI Prediction of Bariatric Surgery Outcomes

This repository contains Jupyter notebooks for the study:

**"Deep Brain Phenotyping for Metabolic-Bariatric Surgery: An AI-Powered fMRI Approach to Advance Prediction of Treatment Success"**  
Falkowski et al., 2025

## Project Overview

Metabolic-bariatric surgery (MBS) is effective for obesity, but predicting patient response remains challenging. This project explores whether preoperative resting-state fMRI can improve such prediction using machine learning.

### Key elements:
- 5 ML algorithms: Logistic Regression, SVM, Random Forest, XGBoost, and MLP
- Nested Leave-One-Out Cross-Validation
- SHAP analysis for model interpretability

All datasets used in this project are available at: https://osf.io/879ka/

## Notebooks Included

- `classic_stat.ipynb`: Classical statistical comparisons (e.g., t-tests, PCA)
- `multi_models.ipynb`: Machine learning pipeline and evaluation
- `shap_MLP.ipynb`: Interpretation of MLP model using SHAP values

