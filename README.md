Objective

Predict the probability of customer churn

Identify key factors contributing to customer churn

Decide which customers should be targeted for retention based on cost–benefit analysis

Provide interpretable and actionable insights for business decision-making

 Approach

Data Cleaning & Preprocessing

Handled missing values and inconsistent data

Encoded categorical variables and scaled numerical features

Exploratory Data Analysis (EDA)

Analyzed churn patterns across tenure, billing, and service usage

Identified class imbalance and key churn indicators

Feature Engineering

Created meaningful customer behavior features

Improved churn signal quality

Modeling & Evaluation

Trained multiple classification models (Logistic Regression, Random Forest)

Evaluated models using ROC-AUC, precision-recall, and confusion matrix

Cost-Sensitive Decision Logic

Defined business costs for customer churn and retention offers

Applied decision rules to identify customers where retention is profitable

Explainability

Used feature importance and SHAP analysis to explain model predictions

Provided both global and customer-level explanations

 Dataset

Telco Customer Churn Dataset (IBM)

Contains customer demographics, service usage, billing information, and churn labels

Publicly available and widely used for churn analysis

 Tech Stack

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Model Explainability: SHAP

Environment: Jupyter Notebook / JupyterLab

 Key Results

Built a churn prediction model with strong discriminative performance

Identified high-risk customers using probability-based thresholds

Designed a profit-oriented retention strategy using cost-aware logic

Delivered interpretable insights to support real-world decision-making

 Business Impact

Helps businesses reduce unnecessary retention costs

Focuses retention efforts on customers with high financial value

Bridges the gap between machine learning predictions and business decisions

 Future Improvements

Add real-time prediction capability

Integrate a web-based decision dashboard (Streamlit)

Extend decision logic using customer lifetime value (CLV)
