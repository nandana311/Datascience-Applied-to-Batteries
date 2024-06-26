﻿# Datascience-Applied-to-Batteries

This project focuses on classifying battery performance using various machine learning algorithms including XGBoost, K-Nearest Neighbors, Support Vector Machines, Bagging Classifier, and Decision Trees. The dataset includes various features related to battery performance metrics.

# XGBoost.ipynb
## Project Structure

- `data_preprocessing.ipynb`: Jupyter notebook for data loading and preprocessing.
- `model_training.ipynb`: Jupyter notebook for model training and evaluation.
- `model_evaluation.ipynb`: Jupyter notebook for model evaluation and prediction.

## Dataset

The dataset used in this project includes various battery performance metrics, and is provided as a CSV file. The dataset includes features such as:

- `soc`
- `max_temp`
- `min_temp`
- `iqr_current`
- `variance_current`
- `std_current`
- `kurtosis_current`
- `sum_current`
- `median_current`
- `mean_current`
- `median_volt`
- `mean_volt`
- `mode_volt`
- `label`

## Getting Started

### Prerequisites

Ensure you have the following packages installed:

- `numpy`
- `pandas`
- `matplotlib`
- `xgboost`
- `imblearn`
- `sklearn`

You can install these packages using pip:

```sh
pip install numpy pandas matplotlib xgboost imbalanced-learn scikit-learn
