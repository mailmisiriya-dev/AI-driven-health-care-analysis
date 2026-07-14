#  AI-Driven Healthcare Analytics and Patient Risk Assessment 

##  Project Overview

This project focuses on analyzing healthcare data using **Python**, **Data Analytics**, and **Machine Learning** to uncover meaningful insights and predict patient risk levels.

The prject uses the **Synthea Synthetic Healthcare Dataset**, which simulates realistic electronic health records (EHRs). Through data preprocessing, exploratory data analysis (EDA), interactive visualizations, and a Random Forest classification model, the project demonstrates how healthcare data can support better decision-making.



##  Project Objectives

- Clean and preprocess healthcare datasets.
- Perform Exploratory Data Analysis (EDA).
- Identify healthcare trends and patterns.
- Create interactive visualizations using Plotly.
- Develop a Machine Learning model to predict patient risk.
- Generate actionable healthcare insights and recommendations.



##  Dataset

**Source:** Synthea Synthetic Healthcare Dataset

The project uses four related datasets:

| Dataset | Description |
|----------|-------------|
| Patients | Patient demographics, healthcare expenses, and insurance coverage |
| Encounters | Hospital visits, encounter details, and healthcare costs |
| Conditions | Medical diagnoses and condition history |
| Medications | Prescribed medications and medication costs |



##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly
- Scikit-learn
- Jupyter Notebook

##  Data Preprocessing

The following preprocessing steps were performed:

- Handling missing values
- Duplicate checking
- Date conversion
- Feature engineering
- Age calculation
- Age Group creation
- Condition Status creation
- Medication Status creation



## Exploratory Data Analysis

The analysis includes:

### Univariate Analysis
- Age Distribution
- Gender Distribution
- Race Distribution
- Healthcare Expenses
- Healthcare Coverage

### Bivariate Analysis
- Age vs Healthcare Expenses
- Gender vs Healthcare Expenses
- Visit Year vs Number of Visits
- Age Group vs Healthcare Expenses

### Multivariate Analysis
- Correlation Analysis
- GroupBy Analysis
- Pivot Tables


## Visualizations

The project includes interactive visualizations such as:

- KPI Dashboard
- Bar Charts
- Pie Charts
- Histograms
- Box Plots
- Scatter Plots
- Heatmap
- Line Charts
- Plotly Interactive Dashboard

##  Machine Learning Model

### Algorithm Used

**Random Forest Classifier**

### Features

- Age
- Gender
- Race
- Healthcare Coverage

### Target Variable

- Risk Level (High Risk / Low Risk)

### Model Performance

- **Accuracy:** ~85%
- Confusion Matrix
- Classification Report
- Feature Importance Analysis
- 
##  Key Insights

- Young Adult and Senior age groups represent the largest patient population.
- Healthcare expenses vary significantly among patients.
- Older patients generally incur higher healthcare expenses.
- Healthcare coverage influences patient expenditure.
- Medication costs differ across treatments.
- Patient visits have increased in recent years.
- Age and Healthcare Coverage are the most important predictors of patient risk.

##  Anomalies Observed

- Several patients exhibit exceptionally high healthcare expenses.
- A few younger patients also have relatively high healthcare expenses.
- Early historical encounter records contain very few observations due to the synthetic nature of the dataset.
- Expected missing values exist in columns such as **DEATHDATE** and **STOP**, representing living patients and active medical conditions.

##  Recommendations

- Monitor high-risk patients regularly.
- Focus on preventive care for elderly patients.
- Use healthcare dashboards for decision-making.
- Apply AI models for early patient risk identification.

##  Future Scope

- Use real-world healthcare datasets.
- Compare additional Machine Learning algorithms.
- Develop a Power BI dashboard.
- Build real-time patient risk prediction systems.
- Integrate additional clinical features for improved prediction.


##  Conclusion

This project successfully demonstrates the application of **Data Analytics** and **Machine Learning** in healthcare. Through data preprocessing, exploratory data analysis, visualization, and a Random Forest classifier, meaningful healthcare insights were generated. The model achieved approximately **85% accuracy**, with **Age** and **Healthcare Coverage** identified as the most influential factors in predicting patient risk.



