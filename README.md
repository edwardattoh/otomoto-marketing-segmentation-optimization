# Otomoto Marketing Segmentation Model Optimization

## Overview
This repository contains the machine learning pipeline and MLflow experiment tracking records for optimizing the customer marketing segmentation model at Otomoto (Master's Degree Program - Applied Machine Learning for Business Analytics)[cite: 1].

## Repository Structure
- `BAN6440 M6 otomoto_marketing_segmentation.csv`: Original Otomoto customer dataset (3,000 records, 14 features)[cite: 1].
- `Otomoto_Marketing_Segmentation_Optimization.ipynb`: Complete Google Colab Jupyter notebook covering EDA, baseline training, optimization runs, MLflow tracking, and model registration.
- `mlflow.db`: SQLite database tracking all experimental runs, parameters, and evaluation metrics[cite: 1].
- `mlflow_model_comparison_results.csv`: Programmatic summary table comparing pre- and post-optimization results.
- `phase3_model_comparison_dashboard.png`: Visual dashboard of performance metrics and confusion matrices.
- `requirements.txt`: Python package dependencies.

## Key Results
- **Baseline (Vanilla SGD)**: Accuracy = 48.22%, Weighted F1 = 0.4809, Loss = 1.0145[cite: 1].
- **Optimized Winner (AdamW)**: Accuracy = 74.22%, Weighted F1 = 0.7400, Loss = 0.5694 (a **+26.00 pp** accuracy improvement and **43.87%** loss reduction)[cite: 1].
