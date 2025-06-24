# 🎓 Profession Prediction using Machine Learning

This project focuses on predicting an individual's profession using machine learning classification techniques. It applies both 🌳 Random Forest and 📈 Logistic Regression algorithms to evaluate model performance, particularly on **small-sized datasets**.

The main aim is to understand how ML algorithms behave when trained on **limited data** with many features, and how this affects model accuracy and generalization.

---

## 🧠 Project Objective

The goal of this project is to build a machine learning model that can accurately classify or predict a person's profession based on various attributes such as interests, skills, education, or personality traits.  

Such a system can serve as a prototype for larger applications like career recommendation tools, recruitment screening systems, or educational counseling platforms.

---

## 📊 Dataset Summary

- **Total Records (Rows)**: 100  
- **Total Features (Columns)**: 25  
- **Target Variable**: `profession` (categorical, multi-class)  
- **Key Features**: 
  - `primary_interest`  
  - `secondary_interest`  
  - Other attributes such as skills, test scores, preferences, etc.

The dataset was synthetically or manually prepared and contains a mix of categorical and numerical variables. Since the dataset is **small and high-dimensional**, it serves mainly as an experimental learning resource.

---

## 🧪 Experiment Motivation

Machine Learning models generally require a **large amount of data** to perform well and generalize effectively. In this project, we deliberately used a **small dataset (100 rows, 25 columns)** to observe how traditional ML models like Random Forest and Logistic Regression behave under data constraints.

We aim to:
- Highlight issues like **overfitting**, **low variance**, and **high bias**  
- Show how **dataset size** impacts model training and accuracy  
- Learn model behavior with limited data

---

## 🧠 ML Models Used

### 🌳 Random Forest Classifier
- An ensemble-based algorithm that builds multiple decision trees and merges them to get more accurate and stable predictions.
- Works well with high-dimensional data but is sensitive to data quantity.

### 📈 Logistic Regression
- A simple linear model used for classification tasks.
- Useful as a baseline model and helps understand the data through feature weights.

---

## 📉 Model Performance

Due to the limited size of the dataset, both models showed **poor accuracy** and failed to generalize well to unseen data. This is expected in small datasets, especially with many input features and multiple target classes.

- **Reason for low accuracy**:  
  - High number of features vs. very few samples  
  - Not enough training data to learn patterns  
  - Risk of overfitting to noise in the training set

> 🔬 **This experiment demonstrates the importance of data quantity and quality in building reliable ML models.**

---

## 🛠️ Tools & Technologies

- Python 🐍  
- Pandas, NumPy for data manipulation  
- Scikit-learn for ML models and preprocessing  
- Category Encoders (for Target Encoding)  
- Matplotlib/Seaborn for visualization

---

## This was an experiment with a small dataset where model performance was low due to limited rows, class imbalance, and high cardinality. The goal was to practice feature engineering and model building using Random Forest and encodings like Ordinal/Target
## Accuracy 
### RandomForestClassifier : 25%
### logisticRegression :20%
