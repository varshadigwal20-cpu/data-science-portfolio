
# Food Delivery ETA Prediction

**Associated with SkillCircle**

## Project Overview

This project focuses on predicting food delivery time using Machine Learning and Deep Learning.

The objective was to analyze delivery-related data, engineer meaningful time and contextual features, train multiple prediction models, and identify the model that performs best at estimating delivery time.

The project was built on **45,593 records**.

---

## Business Problem

Food delivery time depends on several factors such as order timing, delivery conditions, traffic-related factors, weather, and other operational variables.

Accurately estimating delivery time can help businesses improve delivery planning, customer communication, and operational efficiency.

The objective was to build a machine learning solution that could predict delivery time from the available order and delivery-related features.

---

## Project Objectives

- Analyze delivery-related data
- Clean and prepare the dataset
- Perform exploratory data analysis
- Engineer meaningful features
- Train multiple regression models
- Compare model performance
- Identify the best-performing prediction model
- Evaluate prediction accuracy using regression metrics

---

## What I Did

### 1. Data Cleaning

- Cleaned and prepared the delivery dataset for analysis.
- Handled missing values using appropriate imputation methods.
- Prepared numerical and categorical variables for model training.

### 2. Feature Engineering

Created additional features to capture useful delivery patterns, including:

- **Order Hour**
- **Festival Indicator**

These features were created to help the models capture time-based and contextual factors that may influence delivery duration.

### 3. Exploratory Data Analysis

Performed EDA to understand relationships between delivery time and the available features.

The analysis focused on identifying patterns that could help explain variations in delivery duration.

### 4. Data Preparation

- Encoded categorical variables.
- Scaled numerical features where required.
- Prepared the final feature set for regression modelling.

### 5. Model Training

Built and compared four prediction models:

- Linear Regression
- Random Forest
- XGBoost
- Artificial Neural Network (ANN)

### 6. Model Evaluation

Compared the models using regression evaluation metrics, including:

- R² Score
- Mean Absolute Error (MAE)

---

## Challenges

The main challenge was predicting delivery time because delivery duration can be influenced by multiple factors simultaneously.

Another challenge was identifying useful features that could capture time-based and contextual delivery patterns.

Feature engineering, particularly the creation of **Order Hour** and **Festival Indicator**, was used to provide the models with additional information that could help improve prediction performance.

---

## Model Results

| Model | R² Score / MAE |
|---|---:|
| Linear Regression | R² = 0.446 |
| Random Forest | R² = 0.752 |
| **XGBoost** | **R² = 0.778** |
| ANN | **MAE = 4.02 minutes** |

Among the tested models, **XGBoost achieved the highest R² score of 0.778**.

The ANN model achieved an **MAE of approximately 4.02 minutes**, meaning its average absolute prediction error was around four minutes.

---

## Key Insights

- Delivery time prediction is influenced by multiple operational and contextual factors.
- Time-based features such as **Order Hour** can help capture delivery-time patterns.
- The **Festival Indicator** provides additional contextual information that may affect delivery duration.
- Tree-based models performed better than Linear Regression on this dataset.
- **XGBoost achieved the best R² score among the tested models.**
- The ANN model produced an average absolute error of approximately **4.02 minutes**.

---

## Business Impact

An accurate delivery-time prediction system can help food delivery businesses:

- Improve delivery time estimates
- Support better delivery planning
- Improve operational efficiency
- Set more realistic customer expectations
- Potentially improve customer satisfaction

The model can serve as a decision-support tool for estimating delivery times based on available order and delivery conditions.

---

## Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **XGBoost**
- **TensorFlow / Keras**
- **Jupyter Notebook**

---

## Project Workflow

```text
Raw Delivery Data
       ↓
Data Cleaning
       ↓
Exploratory Data Analysis
       ↓
Feature Engineering
       ↓
Order Hour + Festival Features
       ↓
Categorical Encoding
       ↓
Feature Scaling
       ↓
Model Training
       ↓
Model Comparison
       ↓
Regression Evaluation
       ↓
Best Model Selection
