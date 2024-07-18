# Capstone Project

Evaluation of Machine Learning Models for Dentistry Dataset

## 1. Introduction
This project aims to evaluate various machine learning models for predicting age based on a dentistry dataset. The dataset includes demographic and dental-related features that are hypothesized to correlate with age.

## 2. Data Preprocessing
###### Data Loading and Initial Cleaning
The dentistry dataset was loaded from 'Dentistry Dataset.csv'. Initial data cleaning involved dropping the 'Sample ID' column if present.

###### Feature Encoding and Normalization
The 'Gender' column was encoded using LabelEncoder. Features were normalized using StandardScaler to ensure all features contribute equally to model training.

## 3. Exploratory Data Analysis (EDA)
###### Correlation Analysis
- Correlation Heatmap between X Features: Visualizes correlations among the normalized features.
- Correlation Heatmap including Y (Age): Shows correlations between features and the target variable, Age.

## 4. Model Selection and Training
###### Models Used
- Logistic Regression: Used for binary classification after converting age to a binary class.
- Decision Tree Classifier: Used to understand the importance of various factors for classification
- Random Forest Classifier: To understand the of various factors in classifications
- XGBoost Classifier: Employed for its boosted ensemble approach, aiming for improved classification accuracy.

###### Model Training
- Each model was trained on the dentistry dataset, utilizing the preprocessed features and the target variable (Age).
- Evaluation metrics such as Mean Squared Error (MSE), R-squared (R²), Precision, Recall, and F1-score were computed to assess model performance.

## 5. Model Evaluation
###### Evaluation Metrics
- Confusion Matrix: Visual representation of model predictions versus actual classifications.
- ROC Curve and AUC: Evaluates model performance across various thresholds.
###### Results
- Logistic Regression: Achieved an MSE of X and an R² of Y.
- Decision Tree Classifier: Showed promising results with Precision, Recall, and F1-score.
- Random Forest Classifier: Demonstrated strong performance in distinguishing age groups.
- XGBoost Classifier: Delivered robust performance with an AUC score of Z.

## 6. Conclusion
Summarize key findings from model evaluations.
Discuss implications for dental practice or future research directions based on the results.

## 7. Future Work
- Propose potential enhancements to the current models or additional features for better age prediction.
- Consider exploring other machine learning techniques or ensemble methods for improved accuracy.

