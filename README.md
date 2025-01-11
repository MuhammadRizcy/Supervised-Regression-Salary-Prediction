# Supervised Regression Salary Prediction
This repository contains a machine learning project aimed at predicting salaries using supervised regression models. The project explores multiple regression techniques, evaluates their performance, and provides insights into their applicability for salary prediction.
## Project Description
The project involves predicting salaries based on various features using supervised learning regression models. The workflow includes:

<ul>
  <li>Data Ingestion: Loading and inspecting the dataset</li>
  <li>Exploratory Data Analysis (EDA): Analyzing patterns and distributions in the data.</li>
  <li>Data Preparation: </i>
<ul>
    <li>Checking for duplicate records.</li>
    <li>Handling missing values (none found in the dataset).</li>
    <li>Encoding categorical variables (not applicable in this dataset).</li>
  </ul>
  <li>Model Training and Evaluation: Training various regression models, such as Linear Regression, Decision Trees, and Random Forest, and evaluating their performance on training and test datasets.</li>
  </ul>

## Goals
<ol>
  <li>Build and evaluate regression models to predict salaries.</li>
  <li>Compare the performance of different regression algorithms.</li>
  <li>Identify and address issues like overfitting and underfitting.</li>
  <li>Provide actionable insights for improving model performance.</li>
</ol>

## Insight
<ol>
  <li>Linear Regression:</li>
  <ul type = "disc">
    <li>The linear regression model equation: y = 1641.366 + 103.197x.</li>
    <li>The model shows moderate performance but may not capture complex patterns in the data.</li>
  </ul>
  <li>Decision Tree:</li>
  <ul type = "disc">
    <li>The model exhibits overfitting, with a significant performance gap between training and test datasets. This suggests the need for tuning hyperparameters or using ensemble methods.</li>
  </ul>
  <li>Random Forest:</li>
  <ul type = "disc">
    <li>While Random Forest performs well on the training data (low Mean Squared Error, MSE), it still shows signs of overfitting with a noticeable gap in test performance.</li>
  </ul>
</ol>

## Advice
<ol>
  <li>Use techniques like cross-validation to assess model performance more robustly.</li>
  <li>Implement hyperparameter tuning for models like Decision Trees and Random Forest to mitigate overfitting.</li>
  <li>Experiment with additional features or engineered variables that may improve predictive performance.</li>
  <li>Consider trying advanced regression techniques, such as Gradient Boosting or XGBoost, for potentially better results.
  </li>
</ol>

If you have any suggestions or feedback, please don't hesitate to contact to me in direct message on LinkedIn and email.
Email : muhammadrizcy2@gmail.com and LinkedIn : https://www.linkedin.com/in/muhammad-rizcy-/

