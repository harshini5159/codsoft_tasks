# CODSOFT_TASK1
Movie Genre Classification using Machine Learning

## Project Overview
The objective of this project is to build a Machine Learning model that predicts the genre of a movie based on its plot summary using Natural Language Processing (NLP) techniques.

##  Objective
To classify movie genres from movie descriptions by applying text preprocessing, TF-IDF feature extraction, and a Logistic Regression classifier.

##  Dataset

The dataset consists of the following files:

* **train_data.txt** – Used to train the machine learning model.
* **test_data.txt** – Used to predict movie genres.
* **test_data_solution.txt** – Used to evaluate the model's predictions.
* **description.txt** – Contains information about the dataset format.

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

##  Machine Learning Algorithm

* **TF-IDF (Term Frequency–Inverse Document Frequency)** for feature extraction.
* **Logistic Regression** for movie genre classification.

## 📋 Project Workflow

1. Import required libraries.
2. Load the dataset.
3. Perform Exploratory Data Analysis (EDA).
4. Preprocess the movie descriptions.
5. Convert text into numerical features using TF-IDF.
6. Train the Logistic Regression model.
7. Evaluate the model using classification metrics.
8. Predict genres for new movie descriptions.
9. Test the model using the provided test dataset.

##  Model Evaluation
The model was evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Classification Report
* Confusion Matrix

##  Results

The trained model successfully predicts movie genres based on plot summaries. The project demonstrates the complete workflow of a supervised machine learning text classification problem.

##  Project Files

```text
CODSOFT_TASK1/
│
├── Movie_Genre_Classification.ipynb
├── README.md
├── requirements.txt
```

##  How to Run

1. Download or clone this repository.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn
```

3. Open the Jupyter Notebook or Kaggle Notebook.
4. Run all cells sequentially.

---

##  Learning Outcomes
Through this project, I learned:

* Text preprocessing techniques
* Natural Language Processing (NLP) basics
* TF-IDF feature extraction
* Logistic Regression for text classification
* Model evaluation techniques
* Building an end-to-end Machine Learning project

##  Acknowledgement

This project was completed as part of the **CodSoft Machine Learning Internship – Task 1**.
