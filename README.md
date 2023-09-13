# Credit-Rating-Classification-and-Investment-Grade-Prediction.
Credit Rating and Investment Grade Prediction using Machine Learning. Includes Logistic Regression, Neural Networks, and Analysis.

## 1. INTRODUCTION
<p align="justify">
The aim of this project is to classify a firm's credit rating into one of 16 categories and predict whether a firm is considered investment grade or not. The dataset comprises 1700 observations of 26 financial and accounting metrics for various firms across different industries. The last column denotes the credit rating according to Moody's, while the second-to-last column indicates whether the assets are of investment grade or not, with '1' indicating investment grade and '0' indicating otherwise.

To accomplish this, the dataset is divided into training and test sets in an 80%:20% ratio. Three different approaches are employed:

1. Linear Regression Approach with Ridge and Lasso Regularization to predict investment grade.
2. Logistic Regression Approach with Ridge and Lasso Regularization to predict investment grade.
3. A Neural Networks-based approach to classify the firm's rating into one of the rating categories and predict investment grade.
The report discusses the methodology and parameters selected for each model, providing insights into the effectiveness and suitability of each approach for solving this problem.
</p>


## 2. METHODOLOGY
In this project, we explore two distinct approaches for preparing the credit rating classification model: one with the inclusion of dummy variables and another without the use of dummy variables. Each approach is described below:

1. Model Preparation with Dummy Variables
In this approach, we include dummy variables in the dataset to represent categorical data, specifically the credit ratings. The process involves converting the categorical rating column into a set of binary columns, each corresponding to a unique rating category. These binary columns serve as input features for the model.


2. Model Preparation without Dummy Variables
In this alternative approach, we construct the credit rating classification model without incorporating dummy variables. Instead, the model relies solely on the original numerical features provided in the dataset.
