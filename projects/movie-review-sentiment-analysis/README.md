
# Movie Review Sentiment Analysis

**Associated with SkillCircle**

## Project Overview

This project focuses on building a Natural Language Processing (NLP) solution to classify movie reviews as **positive or negative**.

The project uses 50,000 IMDb movie reviews and follows an end-to-end NLP workflow, from text preprocessing and feature extraction to machine learning model training and Streamlit deployment.

---

## Business Problem

Businesses receive large volumes of customer reviews and feedback. Manually reading and classifying this text is time-consuming and difficult to scale.

The objective was to build a system that can automatically analyze movie review text and determine whether the sentiment is positive or negative.

---

## Project Objectives

- Process and clean raw movie review text
- Remove unnecessary words and noise
- Apply stemming and text preprocessing
- Convert text into numerical features using TF-IDF
- Train a machine learning classification model
- Evaluate model performance
- Deploy the solution as an interactive Streamlit application

---

## Dataset

The project uses the **IMDb Movie Review Dataset containing 50,000 reviews**.

Each review is classified into one of two sentiment categories:

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

Converted processed review text into numerical features using **TF-IDF (Term Frequency–Inverse Document Frequency)**.

The model used **unigram and bigram features** to capture individual words as well as combinations of words.

### 4. Model Training

Trained a **Logistic Regression** model to classify reviews as positive or negative.

### 5. Model Evaluation

The model achieved approximately **89% accuracy** on the sentiment classification task.

### 6. Streamlit Deployment

Deployed the trained model using **Streamlit** to create an interactive application.

Users can enter a movie review and receive a predicted sentiment along with prediction confidence.

---

## Challenges

The main challenge was converting unstructured text into meaningful numerical features that could be understood by a machine learning model.

Movie reviews can contain different writing styles, informal language, repeated words, and combinations of positive and negative expressions.

To address this, the project used text cleaning, stop-word removal, stemming, and TF-IDF feature extraction.

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
