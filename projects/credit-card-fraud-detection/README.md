# Credit Card Fraud Detection

**Associated with SkillCircle**

## Project Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning.

The objective was to build and compare multiple classification models on highly imbalanced transaction data and identify a model that can effectively detect fraudulent transactions.

---

## Business Problem

Credit card fraud detection is a highly imbalanced classification problem because fraudulent transactions are much fewer than genuine transactions.

In such datasets, accuracy alone can be misleading. A model may achieve high accuracy while still failing to detect fraudulent transactions.

The goal of this project was to build a fraud detection model while focusing on **Precision, Recall, F1-Score, and Confusion Matrix** to properly evaluate fraud detection performance.

---

## What I Did

### 1. Data Exploration

- Explored transaction data and target distribution.
- Analyzed fraudulent and non-fraudulent transactions.
- Examined numerical features and their relationship with fraud.
- Investigated patterns in transaction-related features.

### 2. Data Preparation

- Prepared the dataset for machine learning.
- Separated features and target variable.
- Performed necessary preprocessing before model training.

### 3. Handling Class Imbalance

The dataset was highly imbalanced because fraudulent transactions represented only a very small percentage of total transactions.

To address this problem, **class-weight balancing** was applied to the classification models where supported.

This gives greater importance to the minority fraud class during model training instead of treating every class equally.

The models were then evaluated using fraud-focused metrics rather than relying only on accuracy.

### 4. Model Training

Trained and compared four machine learning models:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

### 5. Model Evaluation

Compared the models using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## Challenges

The biggest challenge was the severe class imbalance in the dataset.

Since fraudulent transactions were much fewer than legitimate transactions, a model could achieve high overall accuracy while still performing poorly on fraud detection.

To address this, class-weight balancing was applied and model performance was evaluated using Precision, Recall, F1-Score, and Confusion Matrix.

---

## Model Comparison

| Model | Accuracy | F1-Score |
|---|---:|---:|
| Logistic Regression | 93.90% | 0.0876 |
| Decision Tree | 97.05% | 0.1994 |
| Random Forest | 98.21% | 0.2783 |
| **XGBoost** | **99.79%** | **0.7062** |

XGBoost achieved the strongest overall performance among the tested models.

---

## Best Model — XGBoost

The final XGBoost model achieved:

- **Accuracy:** 99.79%
- **Precision:** 0.78
- **Recall:** 0.65
- **F1-Score:** 0.7062

The model was evaluated using a confusion matrix to understand correct and incorrect fraud predictions.

The results show that XGBoost provided a stronger balance between precision and recall compared with the other tested models.

---

## Key Insights

- The dataset contained a very small proportion of fraudulent transactions compared with genuine transactions.
- Class imbalance made fraud detection more challenging than a normal classification problem.
- Accuracy alone was not sufficient for evaluating the models.
- Class-weight balancing helped give more importance to fraudulent transactions during training.
- XGBoost achieved the best overall performance among the four tested models.
- The F1-Score of **0.7062** provides a more meaningful measure of fraud detection performance than accuracy alone.

---

## Business Impact

An effective fraud detection model can help financial institutions identify suspicious transactions earlier and reduce potential financial losses.

This type of solution can support:

- Early identification of potentially fraudulent transactions
- Reduction of manual transaction review
- Prioritization of suspicious transactions for investigation
- Improved monitoring of high-risk transactions
- Data-driven fraud prevention

---

## Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **XGBoost**
- **Jupyter Notebook**

---

## Project Workflow

```text
Transaction Data
       ↓
Data Exploration
       ↓
Data Preparation
       ↓
Class Imbalance Analysis
       ↓
Class-Weight Balancing
       ↓
Model Training
       ↓
Model Comparison
       ↓
Precision / Recall / F1 Evaluation
       ↓
Confusion Matrix Analysis
       ↓
Best Model Selection
