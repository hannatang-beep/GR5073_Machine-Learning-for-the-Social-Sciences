# Machine Learning for the Social Sciences (GR5073)  
Columbia University · Fall 2024  
Instructor: Instructor: Mazen Asaad, PhD

This repository contains my coursework and applied modeling exercises from the class *Machine Learning for the Social Sciences* (GR5073, Section 001) at Columbia University. The class focused on applying supervised learning techniques to real-world social science data, covering both regression and classification tasks.

## 📘 Contents

### Homework 1: Python Foundations and Visualization
- Data: `mtcars` and California School Districts (`CASchools`)
- Tools: `pandas`, `matplotlib`
- Topics:
  - Data loading from URLs
  - Grouping and summarizing
  - Histograms and scatterplots
  - Interpreting relationships in educational data

### Homework 2: Supervised Learning
- Data: California Test Scores (`Caschool.csv`), UCI Wine Dataset
- Techniques:
  - Linear Regression (OLS), Ridge, Lasso, KNN
  - Cross-validation with `KFold` and `RepeatedKFold`
  - Feature scaling with `StandardScaler`
  - Grid search (`GridSearchCV`) for hyperparameter tuning
- Results:
  - KNN performance improved with scaling
  - Ridge and Lasso showed stable and interpretable performance
  - Built classifiers for red vs. white wine

### Homework 3: Midterm Review
- Data: UCI Spam Classification Dataset
- Models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - K-Nearest Neighbors (KNN)
- Focus:
  - Feature engineering from email text (e.g. frequency of "money", "!", capital letters)
  - Model comparison using cross-validation
  - Insights into which features best predict spam likelihood

## 🧠 Skills Demonstrated
- Applied ML modeling on real datasets
- Model evaluation and interpretation
- Feature selection and scaling
- Use of scikit-learn, seaborn, matplotlib

## 📂 Folder Structure

ml-social-sciences/ 
    ├── hw1_python_intro/
    ├── hw2_supervised_learning/ 
    ├── hw3_midterm_review/ 
    ├── hw4_Text_Models_&_Neural_Networks
    ├── .gitignore
    └── README.md

## 📎 Notes
- All analysis was conducted independently unless otherwise noted.
- Datasets used are publicly available (GSS, UCI ML Repo, AER package).
- For academic integrity, full assignments were uploaded **after course completion**.