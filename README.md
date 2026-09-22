# Titanic-ML-Classification
# Titanic Survival Prediction using Logistic Regression

This repository contains a binary classification model built to predict passenger survival on the Titanic using the classic Kaggle dataset. This project was developed entirely in Google Colab using Python and Scikit-Learn.

 Project Overview
The goal of this project is to analyze passenger data (age, gender, ticket class, etc.) and apply Machine Learning to predict whether a given passenger survived the disaster.

 Tech Stack & Concepts
* **Language:** Python
* **Environment:** Google Colab
* **Libraries:** Pandas, NumPy, Scikit-Learn
* **Algorithms:** Logistic Regression, Feature Scaling (`StandardScaler`), One-Hot Encoding, Data Imputation

 Workflow & Methodology
1. **Data Cleaning:** Handled missing values in the `Age` and `Embarked` columns using median/mode replacement. dropped non-contributing features (`Cabin`, `Name`, `Ticket`).
2. **Feature Engineering:** Converted categorical text data into numerical format using One-Hot Encoding.
3. **Data Splitting:** Divided the data into an 80% training set and a 20% validation set.
4. **Model Training:** Scaled the features for optimal performance and trained a Logistic Regression classifier.

Results
* **Validation Accuracy:** [Insert your exact accuracy percentage here, e.g., 80.4%]
* Features like passenger gender (`Sex_male`) and ticket class showed the highest predictive impact on survival outcomes.

How to Run
You can run this notebook directly in your browser by clicking the "Open in Colab" badge at the top of the notebook file inside this repository.
