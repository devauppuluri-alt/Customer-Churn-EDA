# Customer Churn Analysis using Python

## 1. Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on a Customer Churn Classification dataset using Python. The main objective is to understand customer behavior, identify churn patterns, and discover useful insights through data preprocessing, statistical analysis, and data visualization.

## 2. Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## 3. Dataset Information

- **Original Dataset:** 262 rows and 14 columns
- **Duplicate Records Removed:** 12
- **Final Cleaned Dataset:** 250 rows and 11 columns
- **Target Variable:** Churn
- **Data Type:** Numerical and Categorical

### Dataset Features

The dataset contains customer information such as:

- Age
- Tenure Months
- Contract Type
- Internet Service
- Total Charges
- Monthly Charges
- Tech Support
- Customer ID
- Gender
- Churn
- Payment Method

## 4. Project Files

- **Customer_Churn_EDA.ipynb** – Final Google Colab notebook containing data preprocessing, analysis, visualizations, and results.
- **customer_churn_cleaned.csv** – Cleaned dataset obtained after preprocessing.
- **univariate_4_visualizations.png** – Output of four univariate visualizations.
- **bivariate_4_visualizations.png** – Output of four bivariate visualizations.
- **multivariate_4_visualizations.png** – Output of four multivariate visualizations.

## 5. Data Preprocessing

The following preprocessing steps were performed:

1. Imported the required Python libraries.
2. Loaded and inspected the original dataset.
3. Checked dataset dimensions, column names, data types, and statistical summaries.
4. Identified and removed 12 duplicate records.
5. Removed redundant monthly charges columns.
6. Standardized inconsistent categorical values.
7. Checked and handled missing values.
8. Validated numerical columns.
9. Checked numerical features for outliers using the IQR method.
10. Verified the final dataset for missing values and duplicate records.
11. Saved the cleaned dataset as a CSV file.

**Final Result:** 250 records and 11 columns with no remaining missing values or duplicate rows.

## 6. Exploratory Data Analysis

A total of **12 visualizations** were created under three categories.

### A. Univariate Analysis – 4 Visualizations

1. Age Distribution – Histogram
2. Customer Distribution by Contract Type – Count Plot
3. Distribution of Monthly Charges – Box Plot
4. Customer Churn Distribution – Pie Chart

### B. Bivariate Analysis – 4 Visualizations

5. Customer Tenure vs Churn – Box Plot
6. Contract Type vs Customer Churn – Count Plot
7. Monthly Charges vs Total Charges – Scatter Plot
8. Customer Age vs Churn – Box Plot

### C. Multivariate Analysis – 4 Visualizations

9. Correlation Heatmap of Numerical Features
10. Tenure vs Monthly Charges by Churn and Contract – Scatter Plot
11. Churn Rate by Internet Service and Tech Support – Heatmap
12. Churn Rate by Contract Type and Payment Method – Heatmap

## 7. Key Findings

- Total cleaned customer records: **250**
- Customers who churned: **59.2%**
- Customers who stayed: **40.8%**
- Month-to-month contracts were the most common contract type.
- Visualizations helped identify patterns between customer characteristics and churn behavior.
- Churn-rate heatmaps helped compare customer groups based on internet service, technical support, contract type, and payment method.

## 8. Final Conclusion

Exploratory Data Analysis was successfully performed on the cleaned customer churn dataset. Data preprocessing and 12 visualizations helped identify important customer behavior patterns. The analysis showed a churn rate of 59.2%, highlighting the importance of customer retention strategies. These insights can support better business decisions and improve customer satisfaction.

## 9. How to Run the Project

1. Clone or download this GitHub repository.
2. Open the `Customer_Churn_EDA.ipynb` notebook in Google Colab or Jupyter Notebook.
3. Upload `customer_churn_cleaned.csv` to the working environment.
4. Execute the notebook cells in order.
5. Explore the generated visualizations and analysis results.

---

**Project:** Customer Churn Analysis using Python  
**Category:** Exploratory Data Analysis (EDA)  
**Environment:** Google Colab
