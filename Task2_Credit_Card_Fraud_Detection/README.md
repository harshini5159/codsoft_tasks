# CODSOFT_TASK2
Credit Card Fraud Detection using Machine Learning
#  Credit Card Fraud Detection

##  Project Overview

This project is developed as part of the **CodSoft Machine Learning Internship**.

The objective of this project is to build a Machine Learning model that can classify credit card transactions as **Fraudulent** or **Legitimate** based on transaction details. Fraud detection is one of the most important real-world applications of machine learning in the banking and finance industry.

---

##  Objective

Develop a Machine Learning model to detect fraudulent credit card transactions using **Logistic Regression**.

---

##  Dataset

The dataset contains historical credit card transaction records with various customer and transaction-related features.

**Files Used**

* `fraudTrain.csv` – Training dataset
* `fraudTest.csv` – Testing dataset

**Target Variable**

* `is_fraud`

  * `0` → Legitimate Transaction
  * `1` → Fraudulent Transaction

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook / Kaggle Notebook

---

##  Machine Learning Algorithm

* Logistic Regression

---

##  Project Workflow

### 1. Import Required Libraries

Imported all necessary Python libraries for data analysis, visualization, preprocessing, and machine learning.

### 2. Load the Dataset

Loaded the training and testing datasets into Pandas DataFrames.

### 3. Explore the Dataset

Performed basic exploratory data analysis by checking:

* Dataset shape
* Column information
* Missing values
* Duplicate values
* Statistical summary

### 4. Data Preprocessing

Prepared the dataset by:

* Removing unnecessary columns
* Encoding categorical features
* Separating features and target variable

### 5. Train the Model

Trained a Logistic Regression model using the training dataset.

### 6. Make Predictions

Predicted whether transactions in the test dataset were fraudulent or legitimate.

### 7. Evaluate the Model

Evaluated the model using:

* Accuracy Score
* Classification Report
* Bar Graph Visualization

### 8. Sample Prediction

Tested the trained model using sample transactions to verify its predictions.

---

##  Results

The Logistic Regression model successfully classified credit card transactions into:

*  Legitimate Transactions
*  Fraudulent Transactions

The model was evaluated using standard machine learning performance metrics.

---

##  Project Structure

```text
CODSOFT_TASK2/
│── Credit_Card_Fraud_Detection.ipynb
│── README.md
```

---

##  Future Improvements

* Random Forest Classifier
* Decision Tree Classifier
* XGBoost
* Feature Engineering
* Hyperparameter Tuning
* Handling Imbalanced Data using SMOTE

---

##  Learning Outcomes

Through this project, I learned:

* Data preprocessing techniques
* Feature encoding
* Logistic Regression
* Fraud detection using Machine Learning
* Model evaluation
* Data visualization
* GitHub project documentation

---

## Acknowledgement

This project was completed as part of the **CodSoft Machine Learning Internship** to gain practical experience in applying Machine Learning techniques to real-world fraud detection problems.

