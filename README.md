# Fake News Prediction

This repository contains a project aimed at predicting fake news using Natural Language Processing (NLP) and machine learning techniques. The goal is to classify news articles as either fake or real based on their content.

## Project Overview

Dataset file: https://www.kaggle.com/c/fake-news/data?select=train.csv


### Steps in the Project

1. **Data Loading and Preprocessing**
   - Combined `author` and `title` into a single `content` column.
   - Performed text cleaning (e.g., removing non-alphabetic characters, converting to lowercase).
   - Removed stopwords and applied stemming to reduce words to their root form.

2. **Feature Extraction**
   - Used `TfidfVectorizer` to convert the text data into numerical features suitable for machine learning.

3. **Model Training**
   - Trained a Logistic Regression model to classify news articles as fake or real.

4. **Model Evaluation**
   - Evaluated the model using accuracy and other relevant metrics to assess performance.

## Dependencies

The project uses the following Python libraries:
- `numpy`
- `pandas`
- `nltk`
- `scikit-learn`

