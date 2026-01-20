# AllLife Bank — Personal Loan Prediction Pipeline

## Executive Summary
Retail banks face significant inefficiencies when marketing personal loan products due to low conversion rates and poorly targeted campaigns. This project applies supervised machine learning techniques to predict which customers are most likely to accept a personal loan offer, enabling more focused outreach and improved campaign effectiveness.

The work demonstrates a full machine learning pipeline, from exploratory analysis and feature engineering through model training, tuning, and evaluation, with an emphasis on **balanced performance and business-aligned decision metrics**.

---

## Business Objective
Develop a predictive classification system that:
- Identifies customers with a high likelihood of purchasing a personal loan
- Improves marketing efficiency by reducing untargeted outreach
- Balances recall and precision to control false positives and missed opportunities

The objective is to support **data-driven marketing decisions**, not merely to maximize accuracy.

---

## Data Overview
- Historical retail banking customer data from AllLife Bank
- Mixed numeric and categorical features, including:
  - Demographics
  - Account and financial attributes
  - Product engagement indicators
- Moderately imbalanced target variable representing loan acceptance

---

## Analytical / Technical Approach

### 1. Data Preparation
- Data cleaning and preprocessing
- Handling of missing values and categorical variables
- Feature engineering and feature selection to improve signal quality

### 2. Modeling Strategy
- Baseline modeling using Logistic Regression
- Tree-based models including Decision Trees and Random Forests
- Iterative model refinement through pruning and hyperparameter tuning

### 3. Evaluation Methodology
- Performance evaluation using:
  - Accuracy
  - Precision, Recall, and F1-score
  - Confusion matrices
  - ROC-AUC
- Emphasis on **balanced performance** rather than raw accuracy, particularly in the presence of class imbalance

---

## Key Findings
- Logistic regression provides a strong and interpretable baseline for binary classification.
- Decision trees and random forests improved performance but required careful tuning to control overfitting.
- Balanced accuracy and ROC-AUC were more reliable indicators of real-world performance than accuracy alone.
- Over-pruning increased recall at the expense of excessive false positives, highlighting the need for threshold and complexity tradeoffs.

---

## Limitations
- Model performance is constrained by the available feature set and historical customer behavior.
- Marketing response behavior may change over time, reducing model stability.
- The system is designed for **decision support**, not automated customer targeting.

---

## Next Steps
- Threshold optimization aligned with campaign cost and conversion tradeoffs
- Feature expansion using behavioral and temporal signals
- Integration into a campaign scoring or CRM workflow
- Ongoing monitoring and retraining as customer behavior evolves

---

## Repository Structure
- `notebooks/` — End-to-end data analysis, modeling, and evaluation
- `README.md` — Project overview, methodology, and findings

---

## View Modeling
[![Open In GitHub](https://img.shields.io/badge/Open%20in-GitHub-black?logo=github)](https://github.com/CGM-AIML/ML-Modeling/blob/main/notebooks/ML_Project_Full_Code_Notebook_Christopher_Gonzalez_Mejias.ipynb)

---

## Project Context
This project was completed as part of the **Machine Learning** course in the  
**UT Austin / Great Learning Post Graduate Program in AI & ML (2025–2026)** and has been refactored for **portfolio-grade presentation**.

🔗 [View Personal Loan Project in ePortfolio](https://www.mygreatlearning.com/eportfolio/christopher-gonzalez-mejias)
