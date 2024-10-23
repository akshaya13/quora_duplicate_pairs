# Quora Duplicate Question Detection

This project processes the Quora Duplicate Question dataset using Bag of Words (BOW), feature extraction, and preprocessing techniques to identify duplicate questions.

## Files Overview
1. initial_EDA.ipynb
* Description: Performs basic Exploratory Data Analysis (EDA) on the dataset. This script helps understand the distribution of data, missing values, question pairs, and any initial patterns or trends.
* Key Outputs: Data visualizations, summary statistics.

2. only_bow.ipynb
* Description: Applies Bag of Words (BOW) for feature extraction and trains a Random Forest model without any data preprocessing. This is a baseline model to evaluate performance.
* Key Outputs: Model evaluation metrics, predictions.

3. bow-with-basic-features.ipynb
* Description: Performs BOW feature extraction combined with basic features available in the dataset (e.g., question length, word overlap). This script also trains a Random Forest model.
* Key Outputs: Enhanced model performance, feature importance, evaluation metrics.

4. bow-with-preprocessing-and-advanced-features.ipynb
* Description: Incorporates advanced preprocessing techniques like stemming/lemmatization, stop word removal, and generates new advanced features. This script applies BOW and outputs the final model results.
* Key Outputs: Final model performance with advanced features, improved accuracy, predictions.

## Dataset
The Quora Duplicate Question dataset can be found [here](https://www.kaggle.com/c/quora-question-pairs). Ensure you have downloaded the dataset and placed it in the correct directory before running the scripts.