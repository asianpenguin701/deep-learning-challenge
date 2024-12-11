# deep-learning-challenge
## Overview of the Analysis
The purpose of this analysis is to build a deep learning model capable of predicting the success of charity funding applications. The goal is to preprocess the data, design, train, and evaluate a neural network to identify the most effective model configuration for accurate predictions.

## Results
### Data Preprocessing
**Target Variable(s)**:
  - IS_SUCCESSFUL: This binary column indicates whether the funding application was successful (1) or not (0).

**Feature Variable(s)**:
  - All other variables in the dataset, excluding EIN and NAME, which include categorical and numeric predictors relevant to the success of funding applications.

**Removed Variable(s)**:
  - EIN and NAME: These identifiers are neither features nor targets and do not contribute to the predictive power of the model.
