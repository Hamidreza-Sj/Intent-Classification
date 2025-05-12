# Audio Intent Classification

## Overview

**Problem Statement:**  
Audio Intent Classification aims to accurately classify audio recordings into one of 7 intent categories.

**Approach:**  
- **Feature Extraction:** Extract Mel-Frequency Cepstral Coefficients (MFCCs) from the audio signals to represent important acoustic features.
- **Classification:** Use two classification strategies:
**1. Classical Machine Learning:** Implement and compare two widely used algorithms—Support Vector Machine (SVM) and LightGBM (a gradient boosting tree-based model)—to build intent classifiers.
**2. Neural Network Model:** Design and train a neural network model for the same classification task to evaluate performance against classical methods.


## Repository Contents

- **development.csv**  
  A development set containing 9,854 recordings with corresponding features and labels.

- **evaluation.csv**  
  An evaluation set comprising 1,455 recordings with features for further testing and validation.

## Dataset

The dataset includes recordings and their corresponding intent labels across 7 different classes. It is available on:

📂 **[Intent Classification Dataset](https://www.kaggle.com/datasets/hamidrezasj/intent-classification-dataset)**

Feel free to explore, download, and use the datasets for your research or projects. If you find this dataset helpful, consider giving it an upvote on Kaggle.
