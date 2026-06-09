# DevelopersHub AI/ML Engineering Internship Tasks

This repository contains the AI/ML internship tasks completed as part of the DevelopersHub Corporation AI/ML Engineering Internship Program. The projects focus on data analysis, visualization, classification, and regression techniques using real-world datasets and machine learning models.

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab
* GitHub

---

# Task 1: Exploring and Visualizing the Iris Dataset

## Objective

The objective of this task was to explore, analyze, and visualize the Iris dataset to understand feature distributions, relationships between variables, and patterns among different flower species.

## Dataset

Iris Dataset

## Activities Performed

* Loaded and inspected the dataset using Pandas.
* Analyzed dataset structure and summary statistics.
* Used `.info()` and `.describe()` for data exploration.
* Generated scatter plots to study relationships between features.
* Created histograms to visualize feature distributions.
* Used box plots to identify variation and potential outliers.

## Key Findings

* The dataset contains 150 flower samples and 5 attributes.
* Three flower species are included: Setosa, Versicolor, and Virginica.
* Petal-related features provide strong separation between species.
* Visualizations revealed clear patterns and distributions within the dataset.

## Skills Demonstrated

* Data Loading and Exploration
* Descriptive Statistics
* Data Visualization
* Exploratory Data Analysis (EDA)

---

# Task 2: Stock Price Prediction

## Objective

The objective of this task was to predict the next-day stock closing price using historical stock market data.

## Dataset

Yahoo Finance (AAPL Stock Data)

## Model Used

Linear Regression

## Features

* Open
* High
* Low
* Volume

## Target

* Close Price

## Evaluation Metrics

* Mean Absolute Error (MAE): 0.74
* Root Mean Squared Error (RMSE): 0.99
* R² Score: 0.99

## Key Findings

* The model achieved very high accuracy in short-term prediction.
* Stock prices showed strong correlation with historical values.
* Linear Regression performed well for this regression task.

---

# Task 3: Heart Disease Prediction

## Objective

The objective of this project was to develop a machine learning model capable of predicting the likelihood of heart disease based on patient medical information.

## Dataset

Heart Disease UCI Dataset

## Data Preprocessing

* Handled missing values using statistical techniques.
* Converted categorical variables into numerical values using Label Encoding.
* Created a binary target variable for classification.
* Prepared data for machine learning model training and testing.

## Exploratory Data Analysis (EDA)

* Analyzed feature distributions and patient characteristics.
* Visualized heart disease class distribution.
* Examined correlations among medical attributes.
* Investigated factors influencing heart disease prediction.

## Model Used

* Logistic Regression

## Evaluation Metrics

* Accuracy Score
* Confusion Matrix
* Classification Report
* ROC Curve
* ROC-AUC Score

## Results

| Metric         | Score  |
| -------------- | ------ |
| Accuracy Score | 79.89% |
| ROC-AUC Score  | 87%    |

## Conclusion

The Logistic Regression model demonstrated strong predictive performance in identifying heart disease risk. With an accuracy of 79.89% and a ROC-AUC score of 87%, the model effectively distinguished between patients with and without heart disease. This project highlights the practical application of machine learning in healthcare analytics and disease risk assessment.

## Skills Demonstrated

* Binary Classification
* Data Preprocessing
* Healthcare Data Analysis
* Model Evaluation
* Feature Analysis

---

# Task 6: House Price Prediction

## Objective

The objective of this project was to predict house prices using property-related features such as area, bedrooms, bathrooms, stories, parking availability, and furnishing status.

## Dataset

House Price Prediction Dataset

## Data Preprocessing

* Checked and verified dataset quality.
* Encoded categorical variables using Label Encoding.
* Prepared numerical and categorical features for training.
* Split the dataset into training and testing sets.

## Exploratory Data Analysis (EDA)

* Examined the distribution of house prices.
* Analyzed relationships between property features and price.
* Visualized feature correlations using heatmaps.
* Investigated influential factors affecting house prices.

## Model Used

* Linear Regression

## Evaluation Metrics

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

## Results

| Metric                         | Value     |
| ------------------------------ | --------- |
| Mean Absolute Error (MAE)      | 979,680   |
| Root Mean Squared Error (RMSE) | 1,331,071 |
| R² Score                       | 0.65      |

## Conclusion

A Linear Regression model was developed to estimate house prices based on property characteristics. The model achieved an R² score of 0.65, indicating that approximately 65% of the variation in house prices was explained by the selected features. Property area, parking availability, air conditioning, and furnishing status were among the most influential factors affecting price predictions. The model demonstrated reasonable predictive performance and provides a solid baseline solution for real estate price estimation.

## Skills Demonstrated

* Regression Modeling
* Feature Engineering
* Data Preprocessing
* Model Evaluation
* Real Estate Data Analysis

---

# Repository Structure

DevelopersHub-AI-ML-Internship

├── Task1_Iris_Visualization.ipynb

├── Task2_Stock_Price_Prediction.ipynb

├── Task3_Heart_Disease_Prediction.ipynb

├── Task6_House_Price_Prediction.ipynb

└── README.md

---

# Author

AI/ML Engineering Internship Project

DevelopersHub Corporation
