# Credit Card Fraud Detection

This project focuses on building an effective fraud detection model using machine learning techniques. Fraud has become a significant challenge in various industries, particularly in financial services. Detecting fraudulent transactions is crucial for maintaining the integrity of financial systems, protecting consumers, and minimizing financial losses. However, fraud detection often faces the challenge of imbalanced datasets, where fraudulent transactions are rare compared to legitimate ones.

## Introduction

In this project, I explore the process of creating a robust fraud detection model using a dataset containing credit card transactions made by European cardholders in September 2013. The dataset comprises transactions from two days, with 492 frauds out of 284,807 transactions, making it highly unbalanced. The features in the dataset include numerical variables resulting from a PCA transformation, with 'Time' and 'Amount' being the only non-transformed features. The 'Time' feature represents the seconds elapsed between each transaction and the first transaction in the dataset, while the 'Amount' feature denotes the transaction amount. The response variable 'Class' indicates fraud (1) or non-fraud (0) transactions.

## Data Understanding and Preprocessing

The initial data exploration involves examining the dataset's structure, confirming the absence of null values, and visualizing the class imbalance. I then preprocess the data by scaling the features using StandardScaler and RobustScaler. To address the class imbalance, I create a balanced dataset with equal proportions of fraud and non-fraud transactions.

## Model Building and Evaluation

I experiment with various machine learning algorithms, including Logistic Regression, K-Nearest Neighbors, Support Vector Classifier, and Decision Tree Classifier. Model performance is evaluated using cross-validation and GridSearchCV to find the best parameters for each algorithm. The evaluation metrics include accuracy scores, precision, recall, and F1 score. Finally, I visualize the results to gain insights into model performance.

## Running the Project for Others

To run this project for other people, follow these steps:

### Download the CSV File: Before running the project, users need to download the CSV file containing the data form kaggle(https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/code?datasetId=310&sortBy=voteCount). This file should be placed in the same folder as the project files for easy access.

### Run the Code: Once the CSV file is downloaded and placed in the project folder, users can run the provided Python script or Jupyter Notebook. This script will preprocess the data, train the machine learning models, and evaluate their performance.

### Interpret the Results: After running the code, users can interpret the results, including model performance metrics and visualizations, to gain insights into the effectiveness of the fraud detection model.

Overall, this project demonstrates a comprehensive approach to fraud detection, highlighting the importance of handling imbalanced datasets and choosing appropriate evaluation metrics to build effective models.
