# Heart-Disease-Classification
# Heart Disease Classification Project

## Overview
This project aims to predict the likelihood of heart disease using a dataset of health indicators. We utilize various machine learning algorithms to classify individuals based on their health features.

# Libraries Used
Pandas: For data manipulation
Numpy: For numerical operations
Matplotlib & Seaborn: For data visualization
Scikit-learn: For machine learning algorithms and evaluation metrics

## Dataset
The dataset used is heart_disease_health_indicators_BRFSS2015.csv, which contains various health indicators and whether or not the individual has had a heart disease or attack.

## Data Preprocessing
Data Loading: The dataset is loaded into a DataFrame.
Feature Selection: Unnecessary columns are removed.
Outlier Detection: Outliers are detected and removed using Z-scores for columns such as BMI, Diabetes, Mental Health, and Physical Health.
Data Visualization: Box plots and scatter plots are used to visualize the data and detect any anomalies.
Model Building and Evaluation

## Models Used
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. K-Nearest Neighbors Classifier

## Model Performance
Logistic Regression: Evaluated using accuracy score and classification report.
Decision Tree Classifier: Evaluated using accuracy score and classification report.
Random Forest Classifier: Evaluated using accuracy score and classification report.
K-Nearest Neighbors Classifier: Evaluated using accuracy score and classification report.

## Results
Accuracy, confusion matrix, and classification reports for each model are displayed to assess performance.
Visualizations include the distribution of heart disease cases, age distribution, and gender distribution.

## Instructions to Run
Ensure you have the required libraries installed.
Place the dataset file (heart_disease_health_indicators_BRFSS2015.csv) in the working directory.
Run the script to perform data preprocessing, model training, and evaluation.
