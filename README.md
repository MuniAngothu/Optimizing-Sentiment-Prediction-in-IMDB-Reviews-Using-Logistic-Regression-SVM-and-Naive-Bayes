# Optimizing Sentiment Prediction in IMDB Reviews Using Logistic Regression, SVM, and Naive Bayes

This repository contains the source code, datasets, and documentation for the project **"Optimizing Sentiment Prediction in IMDB Reviews"**, a sentiment analysis study comparing machine learning models to predict movie review sentiments.

## Table of Contents
- [Introduction](#introduction)
- [Motivation](#motivation)
- [Features](#features)
- [System Architecture](#system-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Future Scope](#future-scope)


---

## Introduction

Sentiment analysis is a natural language processing (NLP) task focused on identifying and classifying opinions expressed in text. This project analyzes **IMDB movie reviews** and compares multiple machine learning models, including:
- Logistic Regression
- Support Vector Machines (SVM)
- Multinomial Naive Bayes

The study highlights the efficiency of each model in predicting the sentiment of movie reviews, providing valuable insights for decision-making.

---

## Motivation

The growing volume of user-generated reviews on platforms like IMDB presents an opportunity to apply sentiment analysis techniques to:
- Summarize public opinions on movies.
- Assist users in decision-making by predicting sentiment trends.
- Enhance applications in marketing, product development, and audience analysis.

---

## Features

- **Text Preprocessing**: Cleaning text, removing HTML tags, special characters, and stopwords.
- **Feature Extraction**: Implementing Bag of Words (BoW) and Term Frequency-Inverse Document Frequency (TF-IDF) models.
- **Machine Learning Models**:
  - Logistic Regression
  - Linear Support Vector Machines
  - Multinomial Naive Bayes
- **Hyperparameter Tuning**: Optimizing models for better performance.
- **Visualization**: Generating word clouds and confusion matrices.

---

## System Architecture

1. **Data Loading**: Import IMDB dataset with 50K reviews.
2. **Data Preprocessing**: Clean and normalize text data.
3. **Feature Extraction**: Use BoW and TF-IDF to convert text into numerical vectors.
4. **Model Training and Evaluation**: Train machine learning models and evaluate performance.
5. **Visualization**: Visualize results using word clouds and confusion matrices.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/MuniAngothu/Optimizing-Sentiment-Prediction.git
   cd Optimizing-Sentiment-Prediction
