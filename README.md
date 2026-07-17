# Employee Attrition Prediction using Logistic Regression

An end-to-end machine learning project that explores employee attrition using Logistic Regression. This project follows the complete workflow of a binary classification problem, including data cleaning, exploratory data analysis (EDA), preprocessing, model training, and evaluation.

## Project Overview

Employee attrition is an important challenge for organizations, as losing experienced employees can increase recruitment costs, reduce productivity, and lead to the loss of valuable experience. In this project, I analyze employee data to explore factors related to employee attrition and build a baseline Logistic Regression model to predict whether an employee is likely to leave the company.

The primary goal of this project is to strengthen my understanding of supervised machine learning, classification workflows, and model evaluation by applying concepts learned through the Machine Learning Specialization to a real-world HR analytics dataset.

## Workflow

The project follows the standard machine learning pipeline:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Train-test split
* One-Hot Encoding of categorical features
* Standardization of numerical features
* Logistic Regression model training
* Model evaluation using:

  * Accuracy
  * Confusion Matrix

## Results

The baseline Logistic Regression model achieved approximately **50% accuracy** after addressing class imbalance using `class_weight="balanced"`.

The exploratory analysis showed that several features (such as monthly income, years at the company, and overtime) exhibited very little difference between employees who stayed and those who left. As a result, the model struggled to clearly separate the two classes.

Although the predictive performance is limited, this project demonstrates the complete workflow of a binary classification problem and highlights the importance of exploratory data analysis, feature quality, and model selection in machine learning.

## Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Repository Structure

```text
employee-attrition-prediction/
│
├── data/
├── notebooks/
├── README.md
└── .gitignore
```

## Future Improvements

* Compare Logistic Regression with Decision Trees and Random Forests.
* Perform feature engineering and feature selection.
* Tune model hyperparameters.
* Evaluate additional classification metrics such as Precision, Recall, F1-score, and ROC-AUC.
* Deploy the best-performing model using Streamlit.

## What I Learned

Through this project, I gained hands-on experience with:

* Cleaning and preparing real-world datasets
* Exploratory data analysis for classification problems
* Preprocessing mixed numerical and categorical features
* Building a Logistic Regression classifier using Scikit-learn
* Applying One-Hot Encoding and feature scaling with `ColumnTransformer`
* Evaluating classification models using accuracy and confusion matrices
* Understanding how feature quality and class imbalance affect model performance
