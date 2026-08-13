# Customer_Churn_DL__003
Comparative Analysis of Machine Learning and Deep Learning Models for Customer Churn Prediction Using TensorFlow
Aim

To build and compare Machine Learning and Deep Learning models for predicting customer churn and analyze their performance using standard evaluation metrics.

Scope

This practical covers:

Data preprocessing
Exploratory Data Analysis (EDA)
Implementation of Machine Learning models
Implementation of a Deep Learning model using TensorFlow
Performance comparison of different models
Result visualization
Project documentation using GitHub
Dataset

Telco Customer Churn Dataset

Source: IBM Dataset
Domain: Telecommunications
Problem Type: Binary Classification
Target Variable: Churn
Yes – Customer Left
No – Customer Retained
Libraries Required

The following Python libraries are required for this practical:

TensorFlow
Scikit-learn
Pandas
NumPy
Matplotlib
Seaborn
Practical Description

Customer churn prediction is one of the most common business problems in telecommunications, banking, insurance, and subscription-based services.

Organizations use predictive models to identify customers who are likely to discontinue their services. By identifying these customers in advance, organizations can take proactive retention measures, improve customer satisfaction, and reduce customer loss.

In this practical, the Telco Customer Churn Dataset is used to develop a customer churn prediction system. The dataset contains information about customers, their services, account details, and whether they have left the company.

The practical involves preprocessing the dataset, performing Exploratory Data Analysis (EDA), handling missing values and duplicate records, encoding categorical variables, and normalizing numerical features.

Multiple Machine Learning classification models are then developed, including:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Support Vector Machine (SVM)

A Deep Neural Network (DNN) is also developed using TensorFlow.

All models are evaluated and compared using standard classification metrics such as:

Accuracy
Precision
Recall
F1-Score
ROC-AUC Score

Confusion matrices and performance graphs are also generated to visualize the results. Training time and prediction time are compared to analyze the computational efficiency of each model.


Results Analysis
Based on the experimental results:

Decision Tree achieved the highest accuracy of 80.95%.
Logistic Regression achieved the highest ROC-AUC score of 0.8615.
Support Vector Machine achieved the highest precision of 0.7479.
Deep Neural Network achieved the highest recall of 0.5924.
Deep Neural Network also achieved the highest F1-Score of 0.6324.
Logistic Regression had a very low prediction time of 0.002 seconds.
Decision Tree had the lowest training time at approximately 0.0322 seconds.
The Deep Neural Network required the highest training time at approximately 9.8424 seconds.
The SVM also required considerably more training and prediction time compared with the traditional Machine Learning models.
Best Performing Model
Based on ROC-AUC, Logistic Regression is the best-performing model with a score of 0.8615.


### Author

**Name:** Charan Teja Raipally
**Email:**  raipallycharanteja@gmail.com

