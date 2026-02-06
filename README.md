## Overview

This repository contains an applied machine learning and fairness analysis project using the **UCI Estimation of Obesity Levels dataset**.  
The objective is to explore how individual behavior, lifestyle, and demographic factors relate to obesity outcomes, and to assess the ethical and public health implications of predictive models.

The project integrates **predictive modeling, unsupervised clustering, and fairness evaluation**, alongside policy-oriented reflection aligned with the UN Sustainable Development Goals.

---

## Dataset

**Name:** Estimation of Obesity Levels  
**Source:** UCI Machine Learning Repository  
**Description:**  
The dataset includes demographic, behavioral, and lifestyle variables such as eating habits, physical activity, technology usage, and transportation modes, with labeled obesity levels.

---

## Methodology

### 1. Data Preparation & Exploration
- Data cleaning and preprocessing
- Encoding of categorical variables
- Feature scaling and outlier handling
- Exploratory analysis of behavioral and demographic patterns

### 2. Predictive Modeling
Two classification models are trained and compared:
- **Logistic Regression** (baseline)
- **Neural Network (MLP with one hidden layer)**

Evaluation metrics:
- Accuracy, Precision, Recall, F1-score
- Confusion Matrix
- ROC Curve (macro/micro-averaged AUC for multiclass)

---

### 3. Clustering & Pattern Discovery
- Unsupervised clustering using **K-Means / Hierarchical Clustering**
- Interpretation of discovered behavioral and demographic groups
- Training a downstream classifier to predict cluster membership

---

### 4. Fairness & Bias Analysis
- Evaluation of demographic bias across sensitive attributes
- Fairness metrics:
  - Demographic Parity Difference
  - Equal Opportunity Difference
- Discussion of ethical implications and bias mitigation strategies

---

### 5. Policy & Social Reflection
A policy-focused reflection connects findings to:
- Behavioral and social drivers of obesity
- Public health interventions and prevention strategies
- **SDG 3 – Good Health and Well-Being**
- **SDG 10 – Reduced Inequalities**

---

## Contributors

This project was completed collaboratively.

- **Muhammad Taqi**
- **[Shayaan Qazi](https://github.com/shayaanhu)**
- **Adina Adnan Mansoor**

---

## Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## Reproducibility
All experiments are reproducible.  
Preprocessing steps, random seeds, and evaluation procedures are fully documented in the notebook.
