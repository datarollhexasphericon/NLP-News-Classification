# Text Classification with Word Embeddings

This repository contains a Jupyter notebook that demonstrates text classification into one of the following categories: `['BUSINESS', 'SPORTS', 'CRIME']`.

## Overview

The notebook utilizes spaCy for text pre-processing, generates word embeddings, and applies various classification algorithms to classify texts into the specified categories. The code is based on an NLP course by Codebasics.

## Data

The dataset used in this notebook consists of two columns:

- **Text**: Descriptions about a particular topic.
- **Category**: The class the text belongs to, which can be one of ['BUSINESS', 'SPORTS', 'CRIME'].

The data source credits: [Kaggle - News Category Classifier](https://www.kaggle.com/code/hengzheng/news-category-classifier-val-acc-0-65).

## Methodology

The notebook follows these steps:

1. **Data Pre-processing**:
   - Load and explore the dataset.
   - Clean and preprocess the text data using spaCy.

2. **Feature Extraction**:
   - Generate word embeddings using spaCy's `en_core_web_lg` model.

3. **Model Training and Evaluation**:
   - Train various classification models including Decision Tree, Naive Bayes, K-Nearest Neighbors, Random Forest, and Gradient Boosting.
   - Evaluate the models using metrics such as classification report and confusion matrix.

## Results

The performance of each classification algorithm is evaluated and compared to determine the best-performing model for the given text classification task.

## Acknowledgements

- The notebook is inspired by the NLP course by Codebasics.
- The dataset is sourced from Kaggle.
