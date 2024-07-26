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
   git clone https://github.com/dhruvpal102005/naive-bayes-text-classification.git
   cd naive-bayes-text-classification

2. Install the required dependencies:
   ```sh
   pip install -r requirements.txt

## Usage

Run the Jupyter Notebook to execute the text classification and comparison:
   ```sh
   jupyter notebook naive_bayes_text_classification.ipynb

The notebook includes all steps from loading the dataset to evaluating and comparing the models.

## Results
   The results section in the notebook provides a detailed comparison of the accuracy, precision, recall, and F1-score of both the Scikit-learn model and the custom Naive Bayes implementation. This comparison helps in understanding the differences and performance characteristics of both approaches.

