# customer_satisfaction_prediction_project

## Abstract

Customer satisfaction prediction plays a crucial role in improving service quality and customer experience. This project uses machine learning techniques to predict customer satisfaction ratings based on support ticket data, including response times, ticket details, and customer demographics. The dataset is preprocessed, cleaned, and analyzed to extract meaningful patterns. Various machine learning models—such as Random Forest, XGBoost, and CatBoost—were applied to predict satisfaction levels accurately. Feature importance analysis reveals key factors affecting satisfaction, enabling organizations to enhance their support workflows. The results show strong predictive performance, demonstrating that machine learning can effectively estimate customer satisfaction and support data-driven decision-making.
<br>
<br>

## Project Overview

This project focuses on building a machine learning system to automatically predict customer satisfaction ratings from support ticket data. The dataset includes multiple features such as customer information, product purchased, ticket type, response time, resolution time, ticket priority, and communication channel.

<b>By predicting the satisfaction rating in advance, organizations can</b>:

<br>1.Identify unhappy customers early</br>
<br>2.Improve service efficiency</br>
<br>3.Prioritize high-impact tickets</br>
<br>4.Build faster and smarter customer support processes</br>
<br>
<br>

## Project Goals

<b>The main objectives of this project are</b>:

<br>To analyze support ticket data and understand what factors influence customer satisfaction.</br>
<br>To preprocess and clean the dataset by handling missing values, encoding categories, and transforming time features.</br>
<br>To build machine learning models that predict customer satisfaction rating or category (Low/Medium/High).</br>
<br>To compare model performance using appropriate metrics such as RMSE, MAE, Accuracy, and F1-score.</br>
<br>To identify the most important features affecting customer satisfaction.</br>
<br>To provide actionable insights for improving customer support quality and reducing dissatisfaction.</br>
<br>
<br>

## Methodology

<b>The methodology used to complete this project includes:</b>

1. Data Collection

<br>Customer support ticket dataset with 17 features.</br>
<br>Includes demographic data, ticket details, time-based metrics, status, and satisfaction rating.</br>

2. Data Preprocessing

<br>Handling missing values</br>
<br>Converting time fields (response time, resolution time) to minutes</br>
<br>Removing irrelevant columns (name, email, description)</br>
<br>Encoding categorical features using Label Encoding or CatBoost encoding</br>
<br>Feature scaling for numerical columns</br>

3. Exploratory Data Analysis (EDA)

<br>Distribution of satisfaction ratings</br>
<br>Correlation between features</br>
<br>Visualizing response and resolution times</br>
<br>Identifying trends in ticket priority and channels</br>

4. Model Development

<b>Models used:</b>

<br>RandomForestRegressor / Classifier</br>
<br>XGBoost</br>
<br>CatBoost (best performance)</br>
<br>Gradient Boosting Models</br>

5. Model Evaluation

<b>Depending on model type:</b>

<br> Classification</br>
<br>Accuracy</br>
<br>Precision, Recall, F1-score</br>

<br>Confusion Matrix</br>

6. Feature Importance Analysis

<br>Identifying top features that influence customer satisfaction</br>
<br>Examples: Time to Resolution, First Response Time, Ticket Priority, Ticket Status</br>
<br>
<br>

## Future Work

<b>The project can be extended in several meaningful ways:</b>

1. Text Analytics

<br>Apply NLP models (TF-IDF, BERT) to analyze Ticket Subject and Ticket Description.</br>
<br>Improve prediction accuracy using text sentiment and topic extraction.</br>

2. Deep Learning Models

<br>Use LSTM or Transformers to understand customer interactions better.</br>
<br>Combine structured and unstructured data.</br>

3. Real-Time Prediction System

<br>Build an API that predicts customer satisfaction in real time.</br>
<br>Integrate it into a customer support dashboard.</br>

4. Customer Risk Scoring

<br>Identify high-risk customers likely to churn.</br>
<br>Automatically trigger alerts for support teams.</br>

5. Ticket Routing Automation

<br>Automatically assign tickets to suitable agents based on predicted satisfaction.</br>

6. Larger Dataset / More Features

<br>Include agent performance metrics</br>
<br>Add customer past history</br>
<br>Improve accuracy with additional data sources</br>
