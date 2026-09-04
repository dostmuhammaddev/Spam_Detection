# Spam Email Detection Analysis

## Project Overview
This project implements a machine learning pipeline to detect spam emails using the `spam_email_dataset.csv`. It includes data cleaning, feature engineering (TF-IDF for text and Min-Max scaling for numeric data), and model comparison.

## Dataset
The dataset contains email metadata and content, labeled as either 'spam' (1) or 'ham' (0).

## Models and Performance
We compared two primary classification algorithms:

1. **K-Nearest Neighbors (KNN)**: 
   - Hyperparameters were tuned using cross-validation.
   - Optimized K: 2
   - Achieved approximately 86% accuracy.

2. **Multinomial Naive Bayes**:
   - This model performed exceptionally well on the processed text data, achieving near 100% accuracy in this specific evaluation.

## How to Use
1. Ensure `spam_email_dataset.csv` is in the root directory.
2. Run the notebook cells sequentially to reproduce the analysis and performance reports.

## Requirements
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib/Seaborn
