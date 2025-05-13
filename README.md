# Cirrhosis_Patient_Survival_ML

# Overview

This project aims to predict the survival status of patients with cirrhosis using machine learning techniques. The dataset includes clinical features such as age, drug type, and various biomarkers, with the goal of classifying patient outcomes into three categories: C (censored), CL (censored due to liver transplant), and D (deceased). The project leverages Python libraries like Pandas, Scikit-learn, and XGBoost to preprocess data, train models, and generate predictions.

This work was developed as part of a Kaggle competition: Multi-Class Prediction of Cirrhosis Outcomes.

# Features:

Data Preprocessing: Handles missing values, encodes categorical variables, and scales numerical features using a ColumnTransformer pipeline.

Exploratory Data Analysis (EDA): Analyzes dataset characteristics, including distributions and missing data patterns.

Modeling: Evaluates multiple classifiers (Decision Tree, Random Forest, Gradient Boosting, XGBoost) with hyperparameter tuning via GridSearchCV or RandomizedSearchCV.

Prediction: Generates probability scores for test data and prepares a submission file in the required format.
