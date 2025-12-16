# 🚀 Live Lab #56 – Hands-On Databricks: Build Your First Churn Prediction Model

This repository contains all materials for **Live Lab #56**, a hands-on, beginner-friendly workshop where we build an **end-to-end customer churn prediction model on Databricks**.

The lab walks step by step from a **raw CSV dataset** to a **trained, evaluated, and registered machine learning model**, using Databricks notebooks and MLflow.

---

## 🎯 Lab Objective

The goal of this lab is to help you understand **how modern machine learning workflows look and feel on Databricks**, without requiring prior experience with large-scale data platforms.

By the end of the lab, you will:
- Understand the **customer churn problem**
- Train your **first machine learning model on Databricks**
- Track experiments and metrics with **MLflow**
- Interpret model performance and feature importance
- See how models are prepared for **real-world deployment**

---

## 🧠 About the Churn Use Case

**Customer churn prediction** is a classic classification problem where we aim to predict whether a customer is likely to leave a service.

Typical business questions include:
- Which customers are most likely to churn?
- What factors drive churn?
- Where should retention efforts be focused?

This makes churn an ideal example to learn:
- Feature engineering
- Binary classification
- Model evaluation
- Threshold tuning
- Experiment tracking

---

## 🧪 What You Will Do in This Lab

### 1️⃣ Environment Setup
- Create a **free Databricks workspace**
- Import and run Databricks notebooks
- Understand the notebook-based workflow

### 2️⃣ Data Loading & Exploration
- Load a **real-world customer churn dataset (CSV)**
- Explore schema, distributions, and churn rate
- Understand which features may influence churn

### 3️⃣ Baseline Model Training (AutoML)
- Use **Databricks ML / AutoML** to:
  - Train multiple baseline models automatically
  - Compare metrics such as AUC and F1-score
- Inspect results in the **MLflow UI**

### 4️⃣ Custom Model Training (XGBoost / LightGBM)
- Train a custom churn model using Python
- Evaluate performance on a held-out test set
- Optimize the decision threshold for business use

### 5️⃣ Model Evaluation & Interpretation
- Analyze:
  - Accuracy, Precision, Recall, F1-score, ROC AUC
  - Confusion matrix
- Understand **what the model learned**
- Interpret feature importance and SHAP values

### 6️⃣ MLflow Tracking & Model Registration
- Track experiments with **MLflow (built into Databricks)**
- Log metrics, parameters, and artifacts
- Register the model for reuse and deployment

---

## 🧰 Tools & Technologies Used

| Tool | Purpose |
|-----|--------|
| **Databricks (Free Edition)** | Unified data & ML platform |
| **Python** | Data processing & model training |
| **MLflow** | Experiment tracking & model registry |
| **XGBoost / LightGBM** | Gradient boosting models |
| **Pandas & NumPy** | Data manipulation |
| **Matplotlib / Seaborn** | Visualization |
| **SHAP** | Model explainability |

> MLflow is already integrated into Databricks – no addition
