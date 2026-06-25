# Breast Cancer Classification using Machine Learning

## Overview

This project implements a Machine Learning model for breast cancer classification using the Breast Cancer Wisconsin dataset provided by Scikit-learn.

The objective is to classify tumors as:

* **Benign (1)** – Non-cancerous
* **Malignant (0)** – Cancerous

A Logistic Regression model is trained and evaluated to predict the diagnosis based on various medical features extracted from breast cell images.

---

## Dataset

The dataset is loaded directly from Scikit-learn:

```python
from sklearn.datasets import load_breast_cancer
```

### Dataset Information

* Total samples: 569
* Features: 30 numerical features
* Classes:

  * Malignant
  * Benign

Examples of features include:

* Mean Radius
* Mean Texture
* Mean Perimeter
* Mean Area
* Mean Smoothness

---

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn

---

## Machine Learning Workflow

### 1. Data Loading

The Breast Cancer Wisconsin dataset is loaded from Scikit-learn.

### 2. Data Preprocessing

* Dataset converted into a Pandas DataFrame
* Target labels added
* Missing values checked
* Statistical analysis performed

### 3. Data Splitting

The dataset is divided into:

* 80% Training Data
* 20% Testing Data

### 4. Model Training

A Logistic Regression classifier is trained using the training dataset.

### 5. Model Evaluation

The model performance is evaluated using Accuracy Score on:

* Training dataset
* Testing dataset

### 6. Prediction System

A predictive system is implemented to classify new patient data as:

* Benign
* Malignant

---

## Results

The model achieves high classification accuracy on both training and testing datasets.

Example output:

```text
Accuracy on training data = 0.95+
Accuracy on test data = 0.94+
```

*(Actual results may vary depending on the environment and Scikit-learn version.)*

---

## Project Structure

```text
breast-cancer-classification/
│
├── breast_cancer_classification.py
├── README.md




## Future Improvements

* Data visualization using Matplotlib and Seaborn
* Feature scaling and normalization
* Comparison with other algorithms:

  * Random Forest
  * Support Vector Machine (SVM)
  * XGBoost
* Cross-validation
* Deployment using Streamlit or Flask

---

## Author
Hind Saada
Developed as a Machine Learning practice project to explore classification techniques and healthcare data analysis.
