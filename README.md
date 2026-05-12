# Fair Naive Bayes

A fairness-aware modification of the Naive Bayes classifier designed to reduce discriminatory predictions in machine learning classification tasks.

## Overview

This project explores fairness in machine learning by modifying the Naive Bayes algorithm to reduce bias related to sensitive attributes such as gender and race.

The model was evaluated on:
- Adult Income Dataset
- COMPAS Dataset

## Metrics

Fairness metrics:
- Disparate Impact
- Equal Opportunity

Performance metrics:
- Accuracy
- F1 Score
- AUC

## Results

### Adult Dataset
- Disparate Impact: 31% → 49%
- Equal Opportunity: 67% → 98%

### COMPAS Dataset
- Disparate Impact: 43% → 62%
- Equal Opportunity: 58% → 76%

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Research Background

This project is based on my master's thesis: "Development of a Fair Naive Bayes Algorithm"
