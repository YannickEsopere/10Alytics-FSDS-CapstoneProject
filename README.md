# ConnectTel Customer Churn Prediction

![image](https://github.com/YannickEsopere/10Alytics-FSDS-CapstoneProject/assets/134769052/d22402b3-b618-43e1-8716-422d46382d03)

## Table of Contents
- [Project Overview](#project-overview)
- [Project Objective](#project-objective)
- [Data Sources](#data-sources)
- [Data Preprocessing](#data-preprocessing)
- [Model Building and Machine Learning](#model-building-and-machine-learning)
- [Model Evaluation](#model-evaluation)
- [Observations](#observations)
- [Conclusion](#conclusion)

## Project Overview
ConnectTel enterprise, as a major contender in the telecommunications market, faces a critical challenge of customer attrition. This phenomenon may negatively impact the company’s revenue and competitive edge in the global market.
The customer churn prediction project leverages data analytics and machine learning technologies to predict customer churn probability. The prediction system will also provide valuable insight for the company to implement proactive measures to prevent customer churn and perpetuate customer loyalty.

## Project Objective
The project aims to create a robust customer churn prediction system that accurately forecasts customer churn and provides insight for implementing targeted retention initiatives.

## Data Sources
10Alytics provided the dataset analyzed in this project. The dataset contained features like gender, monthly payment, mode of payment, churn, and other important information depicting the consumption patterns, preferences, and behavior of ConnectTel’s customers relative to their propensity to churn.

## Data Preprocessing
The dataset was thoroughly preprocessed by means of data cleaning to handle missing values, duplicates, feature scaling, and redundant features. An exploratory data analysis (EDA) was carried out to identify relational patterns between the data features. Finally, feature engineering techniques were applied to extract valuable insight from the raw data.

## Model Building and Machine Learning
The supervised machine learning approach was used to build the customer churn prediction model. The training and test datasets were split in a ratio of 80:20, respectively. Six machine learning algorithms were fitted on the datasets for experimentation. The algorithms included:
- **Random Forest Classifier**
- **Decision Tree Classifier**
- **XG Boost Classifier**
- **K-Nearest Neighbors Classifier**
- **Support Vector Classifier (SVC)**
- **Logistic Regression**

The best machine-learning model was selected based on its accuracy and general performance.

## Model Evaluation
The following evaluation metrics were used to gauge the performance of the various machine learning models.
- **Accuracy:** The measure of correct predictions (true positives and true negatives) made by the model.
- **Precision:** The proportion of customers who actually churned relative to all customers who were predicted to churn.
- **Recall:** The proportion of customers predicted to churn relative to those who actually churned.
- **F1-score:** The harmonic mean of precision and recall, which provides a balanced metric evaluation.
- **AUC-ROC:** Quantifies the model’s ability to distinguish between the positive and negative classes.

## Observations
The confusion matrix was used for cross-evaluation of the model performance. The matrix revealed the error value of the various models. The recall value was found to depict the false negatives. This implies that some customers who were predicted not to churn actually churned. Hence, the recall value would most impact the company’s revenue retention and overall business performance.

## Conclusion
The customer churn prediction project demonstrates the effectiveness of machine learning algorithms in predicting customer churn probability to enhance proactive intervention to maintain customer loyalty and secure revenue retention. 

