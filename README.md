# Customer_Churn_DL__003

# Comparative Analysis of Machine Learning and Deep Learning Models for Customer Churn Prediction Using TensorFlow

##  Aim

To build and compare **Machine Learning** and **Deep Learning** models for predicting customer churn and analyze their performance using standard evaluation metrics.

---

##  Scope

This practical covers:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Implementation of Machine Learning models
- Implementation of a Deep Learning model using TensorFlow
- Performance comparison of different models
- Result visualization
- Project documentation using GitHub

---

## Dataset

### Telco Customer Churn Dataset

| Attribute | Details |
|---|---|
| **Source** | IBM Dataset |
| **Domain** | Telecommunications |
| **Problem Type** | Binary Classification |
| **Target Variable** | Churn |

### Target Variable

- **Yes** – Customer Left
- **No** – Customer Retained

---

##  Libraries Required

The following Python libraries are used in this practical:

- **TensorFlow**
- **Scikit-learn**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**

---

##  Practical Description

Customer churn prediction is one of the most common business problems in **telecommunications, banking, insurance, and subscription-based services**.

Organizations use predictive models to identify customers who are likely to discontinue their services. By identifying these customers in advance, organizations can take **proactive retention measures**, improve customer satisfaction, and reduce customer loss.

In this practical, the **Telco Customer Churn Dataset** is used to develop a customer churn prediction system. The dataset contains information about customers, their services, account details, and whether they have left the company.

The practical involves:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Handling missing values
- Removing duplicate records
- Encoding categorical variables
- Normalizing numerical features
- Splitting the dataset into training and testing sets

---

##  Machine Learning Models

The following Machine Learning classification models are implemented:

1. **Logistic Regression**
2. **Decision Tree Classifier**
3. **Random Forest Classifier**
4. **Support Vector Machine (SVM)**

In addition, a **Deep Neural Network (DNN)** is developed using **TensorFlow**.

---

##  Evaluation Metrics

All models are evaluated using the following performance metrics:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **ROC-AUC Score**
- **Training Time**
- **Prediction Time**

Confusion matrices and performance graphs are also generated to visualize and compare the results.

---

#  Model Performance Comparison

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC | Training Time (s) | Prediction Time (s) |
|---|---:|---:|---:|---:|---:|---:|---:|
| **Logistic Regression** | 0.8081 | 0.6900 | 0.5747 | 0.6271 | **0.8615** | 0.1605 | **0.0020** |
| **Decision Tree** | **0.8095** | 0.7471 | 0.4861 | 0.5890 | 0.8494 | **0.0322** | 0.0039 |
| **Random Forest** | 0.8074 | 0.7039 | 0.5418 | 0.6123 | 0.8491 | 0.5738 | 0.0207 |
| **Support Vector Machine** | 0.8017 | **0.7479** | 0.4430 | 0.5564 | 0.8265 | 5.6170 | 0.4569 |
| **Deep Neural Network** | 0.8067 | 0.6783 | **0.5924** | **0.6324** | 0.8598 | 9.8424 | 0.2643 |

---

#  Results Analysis

Based on the experimental results:

-  **Decision Tree** achieved the highest **Accuracy of 80.95%**.
-  **Logistic Regression** achieved the highest **ROC-AUC score of 0.8615**.
-  **Support Vector Machine** achieved the highest **Precision of 0.7479**.
-  **Deep Neural Network** achieved the highest **Recall of 0.5924**.
-  **Deep Neural Network** also achieved the highest **F1-Score of 0.6324**.
-  **Logistic Regression** had a very low prediction time of **0.002 seconds**.
-  **Decision Tree** had the lowest training time of approximately **0.0322 seconds**.
-  **Deep Neural Network** required the highest training time at approximately **9.8424 seconds**.
-  **SVM** required considerably more training and prediction time compared with the other traditional Machine Learning models.

---

#  Best Performing Model

Based on **ROC-AUC**, **Logistic Regression** is the best-performing model with a score of:

###  ROC-AUC = 0.8615

Although the Decision Tree achieved slightly higher accuracy, Logistic Regression achieved the **highest ROC-AUC score** and also provided excellent computational efficiency.

The **Deep Neural Network** performed particularly well in terms of **Recall and F1-Score**, making it a useful alternative when identifying potential churn customers is the primary objective.

Therefore, based on the overall results of this experiment:

> **Logistic Regression is considered the best-performing model.**

---

#  Conclusion

This practical demonstrated the application of **Machine Learning and Deep Learning techniques for customer churn prediction** using the Telco Customer Churn Dataset.

Four Machine Learning models and one Deep Neural Network were trained and evaluated using multiple performance metrics.

The results show that different models perform better according to different evaluation metrics:

- **Decision Tree** → Best Accuracy
- **Logistic Regression** → Best ROC-AUC
- **SVM** → Best Precision
- **Deep Neural Network** → Best Recall and F1-Score

Considering **ROC-AUC, prediction performance, and computational efficiency**, **Logistic Regression** can be considered the best overall model for this experiment.

This project demonstrates how predictive analytics can help organizations identify customers who are likely to churn and support **proactive customer retention strategies**.

---


