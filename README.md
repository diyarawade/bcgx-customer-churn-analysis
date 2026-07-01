# BCG X Customer Churn Analysis and Prediction

## Project Overview

This project was completed as part of the **BCG X Data Science Virtual Experience Program on Forage**.

The objective was to analyze historical customer and pricing data to identify the key factors influencing customer churn. The project involved exploratory data analysis (EDA), feature engineering, predictive modeling using a Random Forest Classifier, and presenting business recommendations to support customer retention strategies.

---

## Business Problem

Customer churn has a direct impact on business revenue and customer lifetime value. The client believed that increasing price sensitivity was one of the primary reasons customers were switching to competitors.

The goal of this project was to investigate this hypothesis by analyzing customer behavior and pricing data, developing a predictive machine learning model, and identifying actionable insights to improve customer retention.

---

## Project Objectives

- Perform Exploratory Data Analysis (EDA)
- Analyze customer and pricing data
- Engineer new predictive features
- Train a Random Forest Classification model
- Evaluate model performance using classification metrics
- Identify the most important features influencing churn
- Present business recommendations through an executive summary

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

```
Business Understanding
        ↓
Exploratory Data Analysis (EDA)
        ↓
Feature Engineering
        ↓
Random Forest Classification
        ↓
Model Evaluation
        ↓
Business Recommendations
```

---

## Model Evaluation

The Random Forest model was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix
- Feature Importance

The model achieved approximately **90% overall accuracy** while identifying key factors associated with customer churn. The evaluation also highlighted the challenges of predicting churn in an imbalanced dataset, emphasizing the importance of considering multiple performance metrics beyond accuracy.

---

## Key Outcomes

- Identified important customer and pricing factors influencing churn.
- Created additional engineered features to improve predictive analysis.
- Built and evaluated a Random Forest Classifier.
- Visualized feature importance to understand the strongest predictors of churn.
- Developed business recommendations to support targeted customer retention strategies.

---

## Repository Contents

```
📁 notebooks
   ├── 01_Exploratory_Data_Analysis.ipynb
   ├── 02_Feature_Engineering.ipynb
   └── 03_Churn_Prediction_Model.ipynb

📁 presentation
   └── Executive_Summary.pdf

📁 images
   └── Feature_Importance.png

README.md
requirements.txt
```

---

## Future Improvements

- Improve model recall by addressing class imbalance.
- Perform hyperparameter tuning.
- Compare additional machine learning algorithms such as XGBoost and LightGBM.
- Deploy the model as an interactive web application for real-time churn prediction.

---

## Acknowledgement

This project was completed as part of the **BCG X Data Science Virtual Experience Program** hosted on **Forage**.

It is presented for educational and portfolio purposes and does **not** represent employment, work experience, or an internship with BCG.
