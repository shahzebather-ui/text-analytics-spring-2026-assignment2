# Assignment 2: Text Classification — IMDB Sentiment Analysis

**Student:** [Your Name]  
**Date:** March 2026  
**Dataset:** IMDB Movie Reviews (Binary Classification)

## Overview
Binary sentiment classification of 50,000 IMDB movie reviews 
as positive or negative using supervised machine learning.

## Dataset Details
- Source: Kaggle IMDB Dataset
- Size: 49,582 reviews (after removing 418 duplicates)
- Classes: Positive (25,000) / Negative (25,000)
- Distribution: Perfectly balanced 50/50

## Best Model Results
- Model: Logistic Regression + TF-IDF
- F1 Score: 0.90
- Precision: 0.90
- Recall: 0.90

## Model Comparison
| Criteria | LR + TF-IDF | NB + TF-IDF |
|----------|-------------|-------------|
| F1 Score | 0.90 ⭐ | 0.86 |
| Speed | Fast | Very Fast |
| Interpretability | High | Medium |
| Imbalance Handling | Good | Limited |
| Scalability | High | High |

## Important Class
Both classes are equally important. Negative sentiment 
is slightly more critical for business use cases.

## Custom Inference Summary
- 14/20 correct
- Model struggled with sarcasm and mixed signals
- Out of domain examples partially handled

## Recommendation
Logistic Regression + TF-IDF is recommended for deployment 
due to highest F1 score (0.90), good interpretability, 
and fast training time.
