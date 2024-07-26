# Text Classification with Naive Bayes

This project demonstrates text classification using the Twenty Newsgroups dataset with both a pre-built Multinomial Naive Bayes model from Scikit-learn and a custom Naive Bayes implementation from scratch. The aim is to compare the performance of the custom implementation with the Scikit-learn model.

## Overview

The project is divided into the following steps:

1. **Load and Preprocess Data:**
   - Download the Twenty Newsgroups dataset using `fetch_20newsgroups` from Scikit-learn.
   - Preprocess the text data into numerical features using `TfidfVectorizer`.

2. **Multinomial Naive Bayes with Scikit-learn:**
   - Train a Multinomial Naive Bayes model using Scikit-learn's `MultinomialNB`.
   - Evaluate the model on the test data using accuracy, precision, recall, and F1-score.

3. **Custom Naive Bayes Implementation:**
   - Implement a Naive Bayes classifier from scratch.
   - Train the custom Naive Bayes model on the training data.
   - Evaluate the custom model on the test data using the same metrics as the Scikit-learn model.

4. **Comparison:**
   - Compare the performance of the Scikit-learn model with the custom implementation.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/naive-bayes-text-classification.git
   cd naive-bayes-text-classification
