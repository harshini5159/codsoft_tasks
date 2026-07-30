# CODSOFT_TASK5
# Handwritten Character Recognition using CNN

##  Project Overview

This project implements a **Convolutional Neural Network (CNN)** to recognize handwritten English characters from images. The model is trained using the **English Handwritten Characters** dataset and learns to classify handwritten alphabets and characters by extracting visual features from the images.

---

##  Objective

The objective of this project is to develop a deep learning model that can accurately recognize handwritten English characters from grayscale images using a CNN architecture.

---

##  Dataset

**Dataset Name:** English Handwritten Characters

**Files Used:**

* `english.csv` – Contains image paths and corresponding labels.
* `Img/` – Folder containing handwritten character images.

---

##  Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* OpenCV
* Scikit-learn
* TensorFlow
* Keras

##  Results

The CNN model successfully learned the handwritten character patterns and accurately classified unseen handwritten character images. The training and validation graphs demonstrated effective learning with good generalization performance.

---

##  Model Used

**Convolutional Neural Network (CNN)**

CNN is widely used for image classification because it automatically learns important image features such as edges, curves, and shapes without requiring manual feature extraction.

---
##  How to Run

1. Download or clone the repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook or Kaggle Notebook.
4. Run all notebook cells in sequence.
5. Train the CNN model.
6. Evaluate the model.
7. Predict handwritten characters using test images.
8. Save the trained model.

##  Requirements

* Python 3.x
* NumPy
* Pandas
* Matplotlib
* OpenCV
* Scikit-learn
* TensorFlow
* Keras

##  Conclusion

In this project, a Convolutional Neural Network (CNN) was developed to recognize handwritten English characters from images. The dataset was preprocessed by resizing images, normalizing pixel values, and encoding labels before splitting into training and testing sets. The CNN successfully learned the visual patterns of handwritten characters and achieved good classification performance on unseen data. Finally, the trained model was saved, making it ready for future predictions without retraining.
