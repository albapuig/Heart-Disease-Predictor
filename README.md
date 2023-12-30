# Heart Disease Predictor
## Overview
This GitHub repository contains the code for a heart disease prediction system using machine learning techniques. The project focuses on comparing different classification algorithms, including Logistic Regression, Random Forest, and XGBoost, to predict the presence of cardiovascular diseases.

## Objective
The main goal of this project is to detect heart diseases through machine learning, providing a tool that aids healthcare professionals in making more accurate predictions for patients. The final product is a web application that serves as a cardiovascular disease prediction tool.

## Methodology
The proposed methodology involves several steps:

- Exploratory Data Analysis (EDA): Initial exploration of the "Heart Disease UCI" database to understand its distribution, scope, and identify any outliers.

- Data Cleaning: Essential data cleaning to ensure accuracy and reliability for modeling and analysis.

- Model Selection: Training and evaluating three different models (Logistic Regression, Random Forest, and XGBoost) to find the best-performing one for heart disease prediction.

- Model Explainability: Employing SHAP (SHapley Additive exPlanations) for model explainability, providing insights into feature importance.

- Web Interface: Developing a web interface with separate pages for users (Model I) and professionals (Model II). Users can input health data, and predictions are made using the selected models.

## Results
- Model I: Logistic Regression outperformed Random Forest and XGBoost with an accuracy of 87%. The Precision-Recall curve had an AUC of 0.93.

- Model II: XGBoost showed a slightly higher F1-Score compared to Random Forest and Logistic Regression.

## Conclusion
The heart disease prediction system demonstrates the effectiveness of machine learning in healthcare. Logistic Regression excels in binary classification, while XGBoost performs well in multiclass scenarios. Future improvements could include integrating medical feedback and implementing live chat for user interaction.
