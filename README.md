# Framingham Heart Study - Cardiovascular Disease Prediction

This repository contains a Jupyter Notebook for our final project in a machine learning course. The project aims to predict cardiovascular disease using the Framingham Heart Study dataset. We explored various machine learning algorithms and preprocessing techniques to find the most effective method for accurate predictions.

## Dataset

We utilized the [Framingham Heart Study dataset](https://www.kaggle.com/datasets/shreyjain601/framingham-heart-study) available on Kaggle. The dataset includes various health-related features to predict the risk of cardiovascular disease.

## Project Overview

Our project focuses on comparing the performance of different machine learning models under various data splitting, imbalance handling, and hyperparameter tuning scenarios. The scenarios include:

- **Data Splitting Ratios**: 1:9, 2:8, and 3:7 proportions for testing and training data.
- **Imbalance Handling Techniques**:
  - Imbalanced Data (original dataset)
  - Undersampling
  - Oversampling using SMOTE
- **Hyperparameter Tuning**: Testing models with and without hyperparameter tuning.
- **Machine Learning Algorithms**:
  - Decision Tree
  - Random Forest
  - k-Nearest Neighbor (k-NN)
  - Extreme Gradient Boosting (XGBoost)
  - Support Vector Machines (SVM)

## Results

The main findings from our experiments are as follows:

- **Optimal Preprocessing**: The best preprocessing technique for this dataset was oversampling using SMOTE, which effectively handled class imbalance.
- **Best Model**: The Random Forest algorithm provided the highest accuracy for cardiovascular disease prediction when using SMOTE, a 9:1 training/testing data split, and hyperparameter tuning.
- **Impact of Hyperparameter Tuning**: Hyperparameter tuning significantly improved model performance in most cases. However, the impact varied across different scenarios, with some scenarios showing improvements, declines, or no change in performance.

## Conclusion

Our study demonstrates that careful preprocessing and hyperparameter tuning are crucial for optimizing machine learning models in predicting cardiovascular disease. The Random Forest algorithm, in particular, showed superior performance under the tested conditions.
