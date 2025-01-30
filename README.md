# Titanic Survival Prediction and Power BI Dashboard
This project consists of two main components:

1. A Machine Learning Prediction Model to predict passenger survival.
2. A Power BI Dashboard to visualize different aspects of the dataset.

# 1. Prediction Model

## Objective:
The goal of this component is to predict passenger survival using machine learning based on the Titanic dataset from Kaggle.

Steps Taken:
### Data Cleaning & Preprocessing:

Dropping irrelevant columns
Handled missing values.
Outliers handling
Normalization od numerical columns
Converted categorical data into numerical format.
Scaled numerical features for better model performance.
Model Training:

Used the Logistic Regression model to classify passengers as survived (1) or not survived (0).
Evaluated model performance using accuracy metrics.
Prediction Submission:

Generated predictions based on the test dataset.
Submitted results for evaluation.
Files:
📄 Titanic_Predictions.ipynb → Contains the complete code for data preprocessing, model training, and prediction generation.

# 2. Power BI Dashboard
## Objective:
To create a visual representation of Titanic passenger data to understand trends, survival rates, and relationships between key features.

### Steps Taken:
Data Preprocessing (Using Python):

### Cleaned and formatted data specifically for visualization.
Dropped unnecessary columns
Handled missing values and transformed data types.
Feature engineering
Saved the processed dataset for Power BI.
Dashboard Creation (Using Power BI):

Designed interactive charts and graphs to explore survival rates, fares, passenger demographics, and more.
Used bar charts, pie charts, and histograms to present insights clearly.
Files:
📄 Titanic_preprocessed_Data.ipynb → Contains the data cleaning and preprocessing code used for the Power BI dashboard.
🖼️ Titanic_Dashboard.png → Screenshot of the final Power BI dashboard.

Dataset Source:
Kaggle Titanic Dataset

This project provides both a predictive model and a visual analysis of Titanic passengers. Feel free to explore, modify, and contribute! 🚢

