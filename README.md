# Predictive Analytics for Driver Retention: Mitigating Churn at Ola 🚗

## Problem Statement 🎯

Recruiting and retaining drivers poses a significant challenge for Ola, with high churn rates impacting organizational morale and incurring substantial acquisition costs. As a data scientist within Ola's Analytics Department, your focus is on predicting driver team attrition. Using monthly driver data from 2019 and 2020, you aim to forecast whether a driver will leave the company based on various attributes.

**Column Profiling:**
- **MMMM-YY:** Reporting Date (Monthly)
- **Driver_ID:** Unique id for drivers
- **Age:** Age of the driver
- **Gender:** Gender of the driver – Male: 0, Female: 1
- **City:** City Code of the driver
- **Education_Level:** Education level – 0 for 10+, 1 for 12+, 2 for graduate
- **Income:** Monthly average Income of the driver
- **Date Of Joining:** Joining date for the driver
- **LastWorkingDate:** Last date of working for the driver
- **Joining Designation:** Designation of the driver at the time of joining
- **Grade:** Grade of the driver at the time of reporting
- **Total Business Value:** The total business value acquired by the driver in a month (negative business indicates cancellation/refund or car EMI adjustments)
- **Quarterly Rating:** Quarterly rating of the driver: 1, 2, 3, 4, 5 (higher is better)

## What "good" looks like 🏆

1. Import the dataset and conduct exploratory analysis to understand its structure and characteristics.
2. Convert date-like features to their respective data types.
3. Check for missing values and prepare data for KNN imputation.
4. Aggregate data to remove multiple occurrences of the same driver data.
5. Perform feature engineering to create target variables and derive insightful features.
6. One hot encode categorical variables and treat class imbalance.
7. Standardize training data and apply ensemble learning methods with hyper-parameter tuning.
8. Evaluate results using classification report and ROC AUC curve.
9. Provide actionable insights and recommendations based on the analysis.

## Let's Drive Insights! 📈

