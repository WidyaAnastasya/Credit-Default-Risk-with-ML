# Credit-Default-Risk-with-Machine-Learning

## Project Overview 
This is my capstone project in Big Data and Business Intelligence Program at Celerates. The goal of this project is to use a machine learning classifier model to generate data on the probability of default for credit borrowers, and then analyze this data to gain insights. This project is an end-to-end process that focuses on machine learning consisting of data preparation, exploratory data analysis, modeling and lastly evaluation. 

## Background 
Most of the world's credit is issued by banks, which amounts to billions of dollars. Naturally, this comes with significant risks. If a bank issues too many bad loans (defaults), it may go bankrupt, meaning that its liabilities exceed its assets. There is also the risk of the bank's license being revoked. To mitigate these risks, banks could use machine learning to build classification models that group loan applicants into low- and high-risk categories. This allows banks to avoid making loans to borrowers who are more likely to default. Machine learning algorithms are fast and efficient, which is important for banks that need to process a large number of loan applications quickly.

## Technologies
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

## Data 
There are three datasets that need to be combined to form a complete credit default risk dataset, namely:
1. application_history_f
2. application_history_m
3. credit_history

## Data Preprocessing
The data preprocessing process consist of:
1. Unifying data from three sources: application history for females, application history for males, and credit history.
2. Adjusting credit column to numerical data, in which 1 means successfully paid and 0 means default (Label Encoding).
3. Cleaning data by removing empty values (NaN) and duplicate data, and converting all objects into categories.
4. Performing Exploratory Data Analysis (EDA) to find basic insights, such as correlation tables and target distributions.

## Results 
1. Machine Learning Model:
Three classifier methods were used, namely Decision Tree, KNearest Neighbor, and XGBoost. After modeling, the Decision Tree Classifier was found to have the highest F1 score and accuracy, with values of 0.809 and 0.808, respectively. Therefore, it was decided to use this model for credit default risk analysis so that it can be applied to the available test data.
2. Visualizations are carried out using Tableau.
For the resulting interactive dashboard and insights **[click here.](https://public.tableau.com/views/CreditRiskAnalysis-EDA/Story1?:language=en-US&publish=y%20es&:display_count=n&:origin=viz_share_link)** 
