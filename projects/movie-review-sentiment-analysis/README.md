# Movie Review Sentiment Analysis

**Associated with SkillCircle**

## Project Overview

This project focuses on building a Natural Language Processing (NLP) solution to classify movie reviews as **positive or negative**.

The project uses **50,000 IMDb movie reviews** and follows an end-to-end NLP workflow, from text preprocessing and feature extraction to machine learning model training and Streamlit deployment.

---

## Business Problem

Businesses receive large volumes of customer reviews and feedback. Manually reading and classifying this text is time-consuming and difficult to scale.

The objective was to build a system that can automatically analyze movie review text and determine whether the sentiment is positive or negative.

The project aimed to:

- Process and clean raw movie review text
- Identify sentiment from unstructured text
- Convert text into numerical features
- Train a machine learning classification model
- Evaluate model performance
- Deploy the solution as an interactive application

---

## Project Objectives

- Clean and preprocess movie review text
- Remove unnecessary words and noise
- Apply stemming and text preprocessing
- Convert text into numerical features using TF-IDF
- Use unigram and bigram features for text representation
- Train a machine learning classification model
- Evaluate classification performance
- Deploy the trained model using Streamlit

---

## Dataset

The project uses the **IMDb Movie Review Dataset containing 50,000 reviews**.

The reviews are classified into two sentiment categories:

- **Positive**
- **Negative**

The dataset was used for text preprocessing, feature extraction, model training, and evaluation.

---

## What I Did

### 1. Text Cleaning

- Cleaned the raw movie review text.
- Removed unnecessary text elements.
- Converted text into a consistent format.
- Removed stop words to reduce noise.

### 2. Text Preprocessing

Applied **stemming** to reduce words to their root forms and improve consistency during text analysis.

### 3. Feature Engineering

Converted the processed review text into numerical features using **TF-IDF (Term Frequency–Inverse Document Frequency)**.

The model used **unigram and bigram features** to capture both individual words and combinations of words.

### 4. Model Training

Trained a **Logistic Regression** classification model to classify reviews as positive or negative.

### 5. Model Evaluation

Evaluated the model using classification performance metrics.

The model achieved approximately **89% accuracy** on the sentiment classification task.

### 6. Streamlit Deployment

Deployed the trained sentiment analysis model using **Streamlit** to create an interactive application.

Users can enter a movie review and receive a predicted sentiment along with prediction confidence.

---

## Results

- **Dataset:** 50,000 IMDb movie reviews
- **Task:** Binary sentiment classification
- **Feature Extraction:** TF-IDF
- **N-grams:** Unigrams + Bigrams
- **Model:** Logistic Regression
- **Accuracy:** 89%
- **Deployment:** Streamlit

The deployed application also provides prediction confidence for individual review predictions.

---

## Business Impact

Automated sentiment analysis can help businesses process large volumes of customer feedback more efficiently.

This type of solution can be used to:

- Automatically classify customer reviews
- Identify positive and negative feedback
- Reduce manual review effort
- Monitor customer sentiment at scale
- Support customer feedback analysis and decision-making

---

## Live Demo

The trained sentiment analysis model was deployed as an interactive Streamlit application.

👉 **[Movie Review Sentiment Predictor](https://movie-sentiment-predictor.streamlit.app/)**

---

## Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **NLTK**
- **TF-IDF**
- **Logistic Regression**
- **Jupyter Notebook**
- **Streamlit**

---

## Project Files

| File | Description |
|---|---|
| `Movie Review .ipynb` | Data preprocessing, NLP, feature extraction, model training, and evaluation |
| `Movie_Review_Report.pdf` | Detailed project report |
| `Movie_review_sentiment_analysis.docx` | Project documentation |

> **Note:** The original IMDb dataset is not included in this repository because of its file size.

---

## Future Improvements

- Experiment with transformer-based NLP models.
- Improve classification performance through hyperparameter tuning.
- Add support for more detailed sentiment categories.
- Expand the application with additional text analytics and visualizations.

## Challenges

The main challenge was converting unstructured text into meaningful numerical features that could be understood by a machine learning model.

Movie reviews can contain different writing styles, informal language, repeated words, and combinations of positive and negative expressions.

To address this, the project used text cleaning, stop-word removal, stemming, and TF-IDF feature extraction before model training.

---

## Solution

The project follows an end-to-end NLP pipeline:

```text
Raw Movie Reviews
       ↓
Text Cleaning
       ↓
Stop Word Removal
       ↓
Stemming
       ↓
TF-IDF Feature Extraction
       ↓
Logistic Regression
       ↓
Model Evaluation
       ↓
Streamlit Deployment
