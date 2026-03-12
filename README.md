# Project Overview

This project analyzes home loan applicant data to identify patterns that lead to loan defaults.

Using data analysis, visualization, and machine learning, the project helps predict whether a loan applicant is likely to default.

The analysis helps financial institutions make better lending decisions and reduce financial risk.

# Project Objectives

Perform Exploratory Data Analysis (EDA) on loan data

Identify key factors affecting loan repayment behavior

Build a machine learning model to predict loan default risk

Generate insights to support data-driven decision making
------------
# Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook
---------
# Project Workflow

Data Loading – Import dataset and inspect structure

Data Cleaning – Handle missing values and duplicates

Exploratory Data Analysis – Visualize patterns and relationships

Feature Engineering – Prepare data for modeling

Model Building – Train machine learning models to predict loan default
-------

### Key Factors for Loan Eligibility:

Based on our analysis, customers are more likely to be **eligible for loans** (lower default risk) if they have:

1. **Higher Income**: Customers with stable and higher income are less likely to default
2. **Older Age**: Middle-aged customers (40-50 years) show better repayment behavior
3. **Higher Education**: Better educated customers have lower default rates
4. **Stable Employment**: Longer employment history indicates stability
5. **Owned Assets**: Customers who own cars or property show lower risk
6. **Lower Credit Amount**: Requesting appropriate credit amount relative to income
7. **Previous Good History**: Clean credit bureau history is a strong indicator

### Business Recommendations:

1. **Focus on Income Verification**: Ensure thorough income verification process
2. **Age-Based Policies**: Consider different policies for different age groups
3. **Education as Factor**: Use education as one of the screening criteria
4. **Credit Bureau Check**: Always check credit bureau for previous credit history
5. **Loan-to-Income Ratio**: Maintain healthy loan-to-income ratios
6. **Monitor High-Risk Segments**: Pay special attention to young, low-income applicant

------

This project successfully:

1. **Analyzed** a complex home loan dataset with multiple interconnected tables
2. **Identified** key patterns in customer default behavior
3. **Developed** three different predictive models
4. **Evaluated** models using appropriate metrics (Accuracy and ROC-AUC)
5. **Recommended** Random Forest as the best model for production use
6. **Provided** actionable insights for identifying eligible loan customers

### Future Improvements:

1. Utilize data from all related tables (bureau, previous applications, etc.)
2. Implement advanced feature engineering
3. Handle class imbalance using SMOTE or other techniques
4. Try advanced models like XGBoost or LightGBM
5. Perform hyperparameter tuning for better performance
6. Create a web application for easy prediction

---
**End of Analysis**
---
