# Breast Cancer Wisconsin Diagnostic Prediction Model

This repository contains an in-depth analysis of the Breast Cancer Wisconsin Diagnostic Dataset. The primary objective is to predict the diagnosis of breast cancer as either benign (B) or malignant (M) based on various features.

## Dataset Source

The dataset was obtained from [Kaggle](https://www.kaggle.com/). It includes features that are primarily focused on the characteristics of cell nuclei.

## Preprocessing

- Loaded the dataset using Pandas.
- Removed unnecessary columns (`id` and `Unnamed: 32`).

## Exploratory Data Analysis

- Checked the shape of the dataset.
- Analyzed the distribution of the target variable (`diagnosis`).
- Investigated correlations between numerical features.
- Utilized pair plots and heatmaps for visualization.

## Feature Selection

- Excluded highly correlated features.
- Standardized the dataset.

## Model Training

The following classification models were trained and evaluated:

1. Logistic Regression
2. K-Nearest Neighbors
3. Random Forest
4. Linear Discriminant Analysis
5. Quadratic Discriminant Analysis

## Evaluation Metrics

The models were assessed based on accuracy scores. Hyperparameter tuning was performed for the best-performing model (Linear Discriminant Analysis).

## Results Summary

The final model achieved an accuracy score of 97.37%. Detailed evaluation metrics, including the confusion matrix and classification report, provide insights into the model's performance.

## Conclusion

This project highlights the effectiveness of machine learning techniques in predicting breast cancer diagnosis based on cell nuclei characteristics.

## Contact Information

For any questions or suggestions, please feel free to reach out to [prabathwijethilaka50@gmail.com](mailto:prabathwijethilaka50@gmail.com).
