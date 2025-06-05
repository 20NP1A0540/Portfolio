# Stress Detection and Analysis Using NLP and Machine Learning

## Overview
This project involves analyzing a dataset of Reddit posts labeled for stress and non-stress content. The main goal is to build and evaluate multiple machine learning models to classify text data into stressed vs non-stressed categories. The project uses Natural Language Processing (NLP) techniques for text preprocessing and feature extraction, followed by training different classifiers with TF-IDF vectorization.

## Features
- Data exploration and visualization of class distributions.
- Text preprocessing including cleaning, stopword removal, and lemmatization.
- Feature extraction using TF-IDF vectorization.
- Model training and evaluation using multiple classifiers:
  - Logistic Regression
  - Multinomial Naive Bayes
  - Decision Tree
  - K-Nearest Neighbors (KNN)
  - Random Forest
  - AdaBoost
- Cross-validation for robust model performance evaluation.
- Visualization of model performance comparisons.
- WordCloud visualizations for commonly used words in stressed vs non-stressed posts.
- Prediction example on new custom texts.

## Data
The dataset `stress.csv` should contain columns including at least:
- `text`: The Reddit post text content.
- `label`: Binary label indicating stress (1) or no stress (0).
- `subreddit`: The subreddit the post belongs to (used for exploratory visualization).

## Installation and Setup
1. Install Python 3.7+.
2. Install the required libraries:
