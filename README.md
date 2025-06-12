# patient-classification-ML

A machine learning project focused on classifying patient test results into **“Normal”**, **“Abnormal”**, or **“Inconclusive”** based on healthcare data. The project involves end-to-end data analysis, preprocessing, feature reduction, model training, and performance evaluation using advanced optimization techniques.

---

## 🧩 Project Overview

This assignment simulates a real-world diagnostic system by building classification models using a structured healthcare dataset. It explores both dimensionality-reduced and raw data approaches while comparing the effectiveness of various ML algorithms.

---

## 📌 Objectives

- Understand and visualize the healthcare dataset
- Preprocess the data using standard scaling, encoding, and cleaning
- Apply **Principal Component Analysis (PCA)** for dimensionality reduction
- Train and evaluate multiple classification models on both PCA and non-PCA data
- Optimize **SVM with RBF kernel** using **Particle Swarm Optimization (PSO)**
- Measure model performance using:
  - Confusion matrix
  - Precision, Recall, F1 Score
  - Average Accuracy

---

## 🔬 Classification Models Used

- **Logistic Regression**
- **Multi-Layer Perceptron (MLP)**
- **Support Vector Machine (SVM)**  
  - Linear  
  - RBF (optimized with **Particle Swarm Optimization**)  
- **Naïve Bayes**
- **Ensemble Model** (e.g., Random Forest, XGBoost)

---

## ⚙️ Tech Stack

- **Language:** Python 3.x
- **Libraries:**
  - `pandas`, `numpy`
  - `scikit-learn`
  - `matplotlib`, `seaborn`
  - `pyswarms` (for Particle Swarm Optimization)
  - `xgboost` (optional for ensemble methods)

---

## 📊 Performance Evaluation

Each model is evaluated using:
- **Confusion Matrix**
- **Precision, Sensitivity (Recall), F1 Score**
- **Average Accuracy**

The **best-performing model** is selected based on these metrics and reported in the final section of the notebook.

---
