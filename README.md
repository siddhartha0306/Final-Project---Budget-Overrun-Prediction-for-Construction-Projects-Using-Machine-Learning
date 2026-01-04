# Final-Project---Budget-Overrun-Prediction-for-Construction-Projects-Using-Machine-Learning
Budget Overrun Prediction for Construction Projects Using Machine Learning
Budget Overrun Prediction in Construction Projects using Machine Learning

Project Overview

This project investigates the use of machine learning techniques to predict budget overruns in construction projects using real-world regulatory data. Traditional cost estimation methods often fail to capture complex relationships between project characteristics, leading to inaccurate forecasts. This study applies multiple classification models to identify projects at risk of exceeding their planned budgets.

Dataset

The dataset is sourced from the Gujarat Real Estate Regulatory Authority (GujRERA) and contains project-level information including estimated costs, incurred costs, project type, location, and structural attributes. A binary target variable was created to indicate whether a project experienced a budget overrun.

Methodology

Data cleaning and preprocessing (missing values, encoding, scaling)

Exploratory Data Analysis (EDA) using visualisations

Feature engineering and train–test split (80–20)

Model training and comparison:

Logistic Regression

K-Nearest Neighbours (KNN)

Decision Tree

Neural Network (MLP)

Gradient Boosting Classifier

Model evaluation using Accuracy, Precision, Recall, F1 Score, ROC curves, and Confusion Matrices

 Key Results

The Gradient Boosting Classifier achieved the best overall performance across all evaluation metrics, demonstrating strong capability in identifying construction projects at risk of budget overruns.

Key Insights

Ensemble learning methods outperform linear and distance-based models

Machine learning can support early cost-risk identification

Data-driven approaches offer practical value for construction project management

Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Jupyter Notebook

Repository Structure

Project_Code.ipynb – Full data analysis, modelling, and evaluation pipeline

ProjectInfo_Gujarat.csv – Dataset (or link/source if not included)

Documentation.docx – MSc project report

Future Work

Predict the magnitude of budget overruns

Incorporate time-based and economic variables

Extend the model to datasets from other regions

Deploy the model as a decision-support tool

Disclaimer

This project was developed for academic purposes as part of an MSc Data Science programme. The dataset used is publicly available and contains no personal or sensitive information.
