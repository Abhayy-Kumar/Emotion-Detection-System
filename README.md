# Emotion-Detection-System
A machine learning and Natural Language Processing (NLP) project that classifies emotions in text comments. This project utilizes spaCy for text preprocessing, TF-IDF for feature extraction, and implements both Multinomial Naïve Bayes and Random Forest classifiers to analyze and predict emotions from a Kaggle dataset.

## Overview
The goal of this project is to classify text comments into three emotion categories: **joy**, **fear**, and **anger**. The pipeline involves:
- **Data Acquisition**: Downloading a Kaggle dataset containing text comments and corresponding emotion labels.
- **Exploratory Data Analysis (EDA)**: Understanding dataset structure, distribution of emotions, and sample data.
- **Preprocessing**: Utilizing spaCy for tokenization, lemmatization, and stop word removal.
- **Feature Extraction**: Converting text data into numerical features using TF-IDF vectorization.
- **Model Training & Evaluation**: Implementing Multinomial Naïve Bayes and Random Forest classifiers, followed by evaluating model performance using accuracy scores, classification reports, and confusion matrices.
- **Visualization**: Plotting confusion matrices with Seaborn and Matplotlib to visually interpret model performance.


### Dataset link - https://www.kaggle.com/datasets/abdallahwagih/emotion-dataset
