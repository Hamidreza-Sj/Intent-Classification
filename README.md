# Audio Intent Classification

## Overview

**Problem Statement:**  
Audio Intent Classification aims to accurately classify audio recordings into one of 7 intent categories.

**Approach:**  
- **Feature Extraction:**  
  Extract Mel-Frequency Cepstral Coefficients (MFCCs) from the audio signals to capture key acoustic features.

- **Classification:**  
  Two classification approaches are implemented:

  1. **Classical Machine Learning:**  
     Utilize and compare two popular machine learning algorithms—Support Vector Machine (SVM) and LightGBM (a tree-based gradient boosting model)—to build intent classification models.

  2. **Neural Network Model:**  
     Develop and train a neural network to perform the same classification task, allowing for a performance comparison with classical methods.


## Repository Contents

- **development.csv**  
  A development set containing 9,854 recordings with corresponding features and labels.

- **evaluation.csv**  
  An evaluation set comprising 1,455 recordings with features for further testing and validation.

## Dataset

The dataset includes recordings and their corresponding intent labels across 7 different classes. It is available on:

📂 **[Intent Classification Dataset](https://www.kaggle.com/datasets/hamidrezasj/intent-classification-dataset)**

Feel free to explore, download, and use the datasets for your research or projects. If you find this dataset helpful, consider giving it an upvote on Kaggle.
