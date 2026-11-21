# EdVyro Task 2 – Data Quality and Exploratory Analysis

## 📌 Project Overview

This project focuses on assessing data quality, cleaning a customer churn dataset, and performing Exploratory Data Analysis (EDA) using Python.

The objective is to identify data quality issues, prepare a clean dataset, analyze customer churn patterns, and derive meaningful insights from the data.

## 🎯 Objectives

- Inspect dataset structure and data types.
- Identify missing values and duplicate records.
- Detect invalid values and potential outliers.
- Clean and validate the dataset.
- Perform exploratory data analysis.
- Compare churned and retained customer groups.
- Generate visualizations and summarize findings.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## 📂 Project Files

| File | Description |
|---|---|
| `TASK 2.ipynb` | Notebook containing data profiling, cleaning, analysis, and visualizations |
| `customer_churn_cleaned.csv` | Cleaned customer churn dataset |
| `README.md` | Project documentation |

## 📊 Dataset Information

- Total Records: 15
- Total Columns: 11
- Dataset Domain: Customer Churn Analysis

### Dataset Features

- CustomerID
- Gender
- Age
- TenureMonths
- SubscriptionType
- MonthlyCharges
- TotalCharges
- ContractType
- SupportTickets
- PaymentMethod
- Churn

## 🔍 Data Quality Assessment

The dataset was checked for:

- Missing values
- Duplicate records
- Duplicate customer IDs
- Invalid numerical values
- Inconsistent total charges
- Outliers using the IQR method
- Extra whitespace in text columns

### Assessment Results

| Quality Check | Result |
|---|---|
| Missing Values | 0 |
| Duplicate Rows | 0 |
| Duplicate Customer IDs | 0 |
| Invalid Numeric Values | 0 detected |
| Inconsistent Total Charges | 0 |
| IQR-Based Outliers | 0 detected |
| Extra Whitespace | 0 |

## 🧹 Data Cleaning

The original dataset was preserved, and a separate cleaned dataset was created.

The cleaning process included:

- Checking missing values
- Checking duplicate records
- Validating numerical values
- Checking total charges consistency
- Removing unnecessary whitespace from text columns
- Validating the cleaned dataset

No records were removed because no significant data quality issues were identified.

## 📈 Exploratory Data Analysis

The analysis explored:

- Customer churn distribution
- Customer age
- Customer tenure
- Monthly charges
- Support tickets
- Contract types
- Customer group comparison

## 💡 Key Findings

- Total Customers: 15
- Churned Customers: 7
- Retained Customers: 8
- Churn Rate: 46.67%
- Retention Rate: 53.33%
- Average Customer Age: 39.07 years
- Average Tenure: 18.8 months
- Average Monthly Charges: ₹84.66
- Average Support Tickets: 2.53

### Customer Group Comparison

Customers who churned had an average tenure of 7 months, while retained customers had an average tenure of 29.12 months.

Churned customers had an average of 4.29 support tickets, compared with 1 support ticket among retained customers.

In this sample, all month-to-month contract customers churned, while no one-year or two-year contract customers churned.

## ⚠️ Limitations

The dataset contains only 15 customer records. Therefore, the findings are descriptive and should not be generalized to a larger customer population.

The analysis does not establish causal relationships between customer characteristics and churn.

## 📝 Conclusion

The dataset passed the data quality checks, with no missing, duplicate, invalid, inconsistent, or IQR-based outlier records detected.

The cleaned dataset was prepared for further analysis. Exploratory analysis highlighted differences between churned and retained customers in tenure, support tickets, and contract type.

## ▶️ How to Run

1. Clone or download this repository.
2. Open `TASK 2.ipynb` in Google Colab or Jupyter Notebook.
3. Upload `customer_churn_cleaned.csv` if required.
4. Run the notebook cells sequentially.

---

**Project completed as part of EdVyro Task 2 – Data Quality and Exploratory Analysis.**
