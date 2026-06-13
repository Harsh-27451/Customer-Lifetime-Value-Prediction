#  Customer Lifetime Value Prediction

Predicting Customer Lifetime Value (CLTV) for an insurance company using Machine Learning, feature engineering, and ensemble models.

---

##  Overview

This project focuses on predicting the **Customer Lifetime Value (CLTV)** of insurance customers based on demographic, policy, and claim-related information. Accurate CLTV estimation enables businesses to identify high-value customers and provide personalized services.

The solution employs advanced feature engineering and gradient boosting algorithms to build a robust and interpretable predictive model.

---

##  Problem Statement

Insurance companies aim to segment customers into different tiers based on their lifetime value. The objective of this project is to predict the CLTV of customers using historical customer and policy data.

---

##  Dataset

* **Training Data:** ~90,000 records
* **Test Data:** ~60,000 records
* **Target Variable:** `cltv`

### Features Include

* Gender
* Area
* Qualification
* Income
* Marital Status
* Vintage
* Claim Amount
* Number of Policies
* Active Policy
* Type of Policy

---

##  Tech Stack

* Python
* Pandas
* NumPy
* Scikit-Learn
* CatBoost
* XGBoost
* LightGBM
* Matplotlib
* Seaborn
* Optuna

---

##  Workflow

1. Data Preprocessing
2. Exploratory Data Analysis
3. Feature Engineering
4. Model Selection
5. Cross Validation
6. Hyperparameter Tuning
7. Prediction Generation

---

##  Models Evaluated

* Linear Regression
* Random Forest
* XGBoost
* LightGBM
* CatBoost

CatBoost was selected due to its superior predictive performance and robustness.


## Key Highlights

Feature engineering to capture customer behavior

Model comparison using multiple ensemble techniques

Cross-validation for robust performance estimation

Hyperparameter tuning for improved generalization

Interpretable predictions for customer segmentation

---

## Future Improvements

* SHAP-based feature importance analysis
* Ensemble stacking
* Streamlit deployment
* Model explainability dashboard


## Author

**Harsh Jha**

