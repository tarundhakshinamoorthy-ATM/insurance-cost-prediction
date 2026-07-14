# Insurance Cost Prediction using Machine Learning

## Overview

This project focuses on predicting individual health insurance charges using various machine learning regression algorithms. The objective is to analyze the factors that influence insurance costs and build a predictive model capable of estimating medical expenses based on customer information such as age, BMI, smoking status, number of children, gender, and residential region.

The project follows a complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), model development, performance evaluation, hyperparameter tuning, and model comparison.

---

## Problem Statement

Insurance companies need accurate estimates of healthcare expenses to determine appropriate insurance premiums. This project aims to develop a regression model that predicts insurance charges based on demographic and lifestyle-related features.

---

## Dataset Information

* **Dataset:** Insurance Cost Prediction Dataset
* **Records:** 1,338
* **Features:** 7
* **Target Variable:** `charges`

### Features

* Age
* Sex
* BMI
* Children
* Smoker
* Region
* Charges (Target)

---

## Project Workflow

* Import required libraries
* Load and inspect the dataset
* Perform Exploratory Data Analysis (EDA)
* Analyze missing values and duplicate records
* Study numerical and categorical features
* Perform correlation and outlier analysis
* Encode categorical variables using One-Hot Encoding
* Split the dataset into training and testing sets
* Train multiple regression models
* Compare model performance
* Perform hyperparameter tuning
* Select the best model for production
* Save the trained model

---

## Machine Learning Models Used

* Linear Regression
* Ridge Regression
* Lasso Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Regressor
* XGBoost Regressor

---

## Model Evaluation Metrics

The models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## Final Model Performance

**Best Model:** Tuned Gradient Boosting Regressor

| Metric   |   Value |
| -------- | ------: |
| MAE      | 2495.56 |
| RMSE     | 4233.42 |
| R² Score |  0.9025 |

The tuned Gradient Boosting Regressor achieved the highest predictive performance among all the evaluated models and was selected as the final production model.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Jupyter Notebook

---

## Key Insights

* Smoking status was one of the strongest factors influencing insurance charges.
* Ensemble learning methods significantly outperformed traditional linear regression models.
* Hyperparameter tuning further improved the performance of the Gradient Boosting model.
* Comparing multiple regression algorithms helped identify the most suitable model for production.

---

## Repository Structure

```text
Insurance-Cost-Prediction/
│
├── Insurance_Cost_Prediction.ipynb
├── InsuranceCostPredictionModel.pkl
├── insurance.csv
├── README.md
└── requirements.txt
```

---

## Results

The final model is capable of accurately predicting individual insurance charges based on customer information. With an R² Score of approximately **90%**, the model demonstrates strong predictive performance and can support insurance companies in premium estimation and pricing decisions.

---

## Future Improvements

* Deploy the model using Flask or FastAPI.
* Build an interactive web application using Streamlit.
* Experiment with advanced ensemble models such as LightGBM and CatBoost.
* Perform additional feature engineering to further improve prediction accuracy.

---

## Author

**Tarun Dhakshinamoorthy**

Aspiring Data Scientist | Machine Learning Enthusiast
