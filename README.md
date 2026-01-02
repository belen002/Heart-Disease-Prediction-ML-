# Heart Disease Prediction – Notebook

## Overview
This repository contains a Google Colab–style notebook that demonstrates an end-to-end machine learning pipeline for predicting heart disease using two models: Logistic Regression and Decision Tree.

The notebook covers data cleaning, preprocessing, pipeline-based model training, evaluation using classification metrics and confusion matrices, and model export using joblib for deployment in a web application.

## Dataset
- UCI Heart Disease Dataset  
- Target variable: `num`  
  - 0 → No heart disease  
  - 1 → Heart disease present  

## Models
- Logistic Regression  
- Decision Tree Classifier  

Both models are trained using Scikit-learn Pipelines to ensure proper preprocessing and to prevent data leakage.

## Evaluation
- Accuracy score
- Classification report (precision, recall, F1-score)
- Confusion matrices (visualized and interpreted)
- Feature importance / coefficients analysis

## Files
- `Heart_Disease_Prediction_Final.ipynb` – Complete notebook
- `logistic_regression_model.joblib` – Trained Logistic Regression model
- `decision_tree_model.joblib` – Trained Decision Tree model

## How to Run
1. Open the notebook in Google Colab or Jupyter Notebook
2. Run all cells from top to bottom
3. Trained models will be saved as `.joblib` files

## Author
Belen Berhanu
