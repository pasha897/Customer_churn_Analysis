Customer Churn EDA Project
    Overview
This project is an Exploratory Data Analysis (EDA) of customer churn data from a telecom company. 
The goal is to analyze and understand the factors that contribute to customer churn (customers leaving the service).

  Key Components
1) Data Loading and Initial Exploration
2) The dataset is loaded from a CSV file containing customer information with 21 columns and 7043 rows.
3) Initial exploration includes checking the data structure, missing values, and basic statistics.
   
    Data Cleaning
1) The TotalCharges column is cleaned by replacing empty strings with "0" and converting to float.
2) The SeniorCitizen column is transformed from binary (0/1) to categorical ("No"/"Yes").

    Visualizations
1) Churn Distribution: A countplot shows the distribution of churned vs. retained customers.
2) Churn Percentage: A pie chart displays the percentage of churned customers (26.54% churned, 73.46% retained).
3) Churn by Gender: A countplot compares churn rates between male and female customers.

    Key Findings
1) The dataset has no missing values after cleaning.
2) About 26.54% of customers churned, indicating a significant portion of the customer base is leaving.
3) The churn rate appears slightly higher among males than females, though the difference is not substantial.

    Tools Used
1) Python libraries: Pandas, NumPy, Matplotlib, Seaborn
2) Jupyter Notebook for interactive analysis

This EDA provides a foundation for understanding customer churn patterns and can guide further analysis to reduce churn rates.
