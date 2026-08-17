# Multi-Label Emotion Classification

A comparative study of traditional statistical models versus deep learning CNNs with GloVe embeddings for multi-label emotion classification on the GoEmotions dataset[cite: 3].

## Project Overview
This project evaluates and compares three modeling paradigms on the GoEmotions dataset:
1. **Baseline**: Multinomial Naive Bayes using Bag-of-Words features
2. **Statistical Model**: Logistic Regression with TF-IDF weighting and class balancing
3. **Deep Learning Model**: Convolutional Neural Network (CNN) combined with pre-trained Twitter-trained GloVe embeddings

## Key Evaluation Findings
* Evaluated using macro and micro precision, recall, and F1-scores to account for severe class imbalance.
* The CNN + GloVe architecture demonstrated superior generalization across both common and rare emotion categories compared to traditional statistical methods.
