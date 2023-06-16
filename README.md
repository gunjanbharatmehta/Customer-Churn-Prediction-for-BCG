# PowerCo Churn Prediction Project

Welcome to the PowerCo Churn Prediction Project! This project aims to analyze customer churn in the Small & Medium Enterprise (SME) segment of PowerCo, a leading gas and electricity utility company. By understanding the factors that contribute to churn, we can develop a predictive model to identify at-risk customers and offer them a targeted discount to incentivize them to stay with PowerCo.

## Background

PowerCo operates in a power-liberalized energy market in Europe, which has resulted in increased customer churn, particularly in the SME segment. To address this issue, PowerCo has partnered with BCG to diagnose the underlying causes of churn among their SME customers. One prominent hypothesis suggests that price changes significantly impact churn rates.

## Project Objective

The main objective of this project is to develop a predictive model that can identify SME customers who are more likely to churn based on their price sensitivities. By utilizing this model, PowerCo aims to offer a 20% discount to customers at risk of churning, effectively dissuading them from leaving the company.

## Project Overview
- Task 1: Exploratory Data Analysis

In this task, an exploratory analysis of the dataset was conducted to gain a holistic understanding. Data types, statistics, specific parameters, and variable distributions were examined. This analysis provides essential insights into the dataset.
- Task 2: Hypothesis Testing

To verify the hypothesis that churn is driven by customers' price sensitivities, a measure of price sensitivity was defined and calculated. The correlation between price sensitivity and churn was obtained to assess their relationship. Based on the analysis, the key findings were summarized in a half-page summary or slide. 
- Task 3: Predictive Modeling

A Random Forest classifier was trained on a cleaned and engineered dataset, evaluating its performance in predicting customer churn. The advantages and disadvantages of using a Random Forest were documented for this specific use case.
- Task 4: Summarising

The abstract slide synthesizes the project's findings and presents them to key stakeholders, including the Head of the SME division. This slide emphasizes the most important metrics and the potential impact of the predictive model on the client's bottom line.

## Methodology

To test the hypothesis that churn is driven by price sensitivities, the following approach has been adopted:

1. **Data Collection:** Gather historical data on SME customers, including their usage patterns, billing information, and churn status. This dataset will serve as the foundation for our analysis and modeling.

2. **Data Analysis:** Perform exploratory data analysis (EDA) to gain insights into the relationship between price changes and churn rates. Identify key variables and patterns that may contribute to customer churn.

3. **Feature Engineering:** Transform and engineer relevant features from the dataset to enhance the predictive power of our models. This step may involve creating new variables, normalizing data, and addressing missing or erroneous data.

4. **Model Development:** Develop a predictive model using machine learning techniques, such as logistic regression, decision trees, or ensemble methods. Train the model using historical data and evaluate its performance using appropriate metrics, such as accuracy, precision, recall, and F1 score.

5. **Model Validation:** Validate the predictive model using a holdout dataset or cross-validation techniques to ensure its generalizability and robustness.

6. **Model Deployment:** Implement the predictive model to generate churn predictions for SME customers on the 1st working day of each month. Identify customers at risk of churn and recommend a 20% discount to be offered to these individuals.
