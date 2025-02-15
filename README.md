# neural-networks-with-sklearn

This repository contains an implementation of a **Neural Network Classifier** for predicting gender based on dataset features. The project explores baseline accuracy, hidden layer configurations, and activation functions to optimize classification performance.

## Project Overview
- Objective: Build a **Neural Network** to classify gender based on dataset attributes.
- Dataset: Training and test data are retrieved from an external source.
- Methods Used: Baseline accuracy calculation, neural network training, and model evaluation.

## Dataset
The dataset consists of various demographic and behavioral attributes with **gender** as the target variable.  
## Key Features
- **Baseline Accuracy Calculation**: Determines accuracy if the model predicts the majority class.
- **Neural Network Implementation**: Using `MLPClassifier` from `scikit-learn`, allowing modifications to:
  - Number of hidden layers
  - Hidden nodes per layer
  - Activation function (`sigmoid/logistic`)
  - Optimization algorithm (`lbfgs`)
- **Performance Evaluation**: Comparing model accuracy against the baseline.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/neural-network-classifier.git
   cd neural-network-classifier

