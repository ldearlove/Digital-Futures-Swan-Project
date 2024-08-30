# Digital Futures Swan Project

## Contributors - Team White Swan
[Liam Dearlove](https://github.com/ldearlove) |
[Aksha Amod](https://github.com/akshaamod) |
[Egle Duobaite](https://github.com/eedbt) |
[Yassim Jama](https://github.com/YJApps)

## Overview
This repository contains the code and documentation for the Digital Futures Swan Project, developed as part of a collaborative effort to predict customer churn. This project showcases skills in data analysis, machine learning, and data visualization, demonstrating the ability to work with a dataset to derive actionable insights.

The primary goal of this project is to identify customers at risk of churning using a dataset that includes various customer attributes. The final output is a list of the top 500 customers most likely to churn, which can be used to inform targeted retention strategies.

## Contents
This repository contains:
* `Exploratory Work/`: A folder that contains Jupyter notebooks used for initial data exploration by team members.
* `Information Deck/`: A folder that contains the project information deck in both PDF and PowerPoint formats.
* `White Swan.ipynb`: The main notebook containing the project's detailed analysis and model.
* `at_risk_customers.csv`: Output file listing the top 500 customers at risk of churning.
* `Project_logo.png`: The project logo used in the main notebook.
* `remaining_customers.csv`: Output file listing customers not in the top 500 at risk.
* `Swan_Project_Data.csv`: The primary dataset used for analysis and modeling.
  
## Dataset
The dataset for this project was provided as a CSV file, containing various customer attributes relevant to predicting churn. The key data points include:
* Customer IDs
* Demographic information
* Historical purchase data
* Churn Label
* Churn Reason (if applicable)

## Methodology
The project involved several key steps:
1. Data Collection: Importing and preparing the dataset for analysis.
2. Exploratory Data Analysis (EDA): Analyzing the dataset to understand the key factors that influence customer churn.
3. Data Preprocessing: Cleaning and organizing the data to make it suitable for modeling.
4. Modeling: Building a predictive model (both Random Forest and Logisitic Regression were tested) using machine learning techniques, including feature engineering, model training, and evaluation.
5. Prediction: Generating a list of the top 500 customers most likely to churn based on the model's predictions.

## Usage
To run the churn prediciton model:
1. Open the White Swan.ipynb notebook in Jupyter Lab or Jupyter Notebook.
2. Execute the cells sequentially to preprocess the data, train the model, and generate the output files.
3. The final output will include two CSV files:
    * `at_risk_customers.csv`: A list of the top 500 customers most likely to churn.
    * `remaining_customers.csv`: A list of customers not identified as high-risk.

## Acknowledgements
1. Thanks to Digital Futures for the training and support throughout this project.
2. Special thanks to all team members of "White Swan" for their hard work and contributions to this project. The project also leverages various Python libraries such as NumPy, Pandas, Scikit-learn, Seaborn, and Matplotlib for data analysis and modeling.
