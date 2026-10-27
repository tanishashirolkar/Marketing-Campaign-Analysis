# Marketing Campaign Performance & Customer Conversion Analytics Using Python

## Project Overview

This project focuses on analyzing the performance of bank marketing campaigns using Python. The objective is to understand customer characteristics, identify patterns in campaign responses, and discover factors associated with higher term-deposit subscription rates.

Using Exploratory Data Analysis (EDA), data cleaning, feature engineering, and data visualization, this project converts raw marketing data into meaningful insights that can support data-driven marketing decisions.

## Project Objectives

- Analyze customer demographics and account-related information.
- Calculate the overall customer conversion rate.
- Compare conversion rates across customer segments.
- Understand the relationship between campaign contact patterns and customer responses.
- Analyze the impact of previous campaign outcomes and contact methods.
- Identify patterns across campaign months.
- Develop business recommendations based on the analysis.

## Technologies and Tools

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook
- **Development Tool:** Visual Studio Code
- **Version Control:** Git and GitHub

## Dataset Information

**Dataset:** Bank Marketing Dataset (`bank-full.csv`)

**Source:** [UCI Machine Learning Repository – Bank Marketing](https://archive.ics.uci.edu/dataset/222/bank+marketing)

- **Total Records:** 45,211
- **Total Columns:** 17
- **Target Variable:** `y`
- **Target Categories:** `yes` and `no`

The dataset contains customer demographic information, account details, campaign contact information, previous campaign outcomes, and the customer's final response to a term-deposit offer.

## Project Workflow

### 1. Data Loading and Understanding

- Imported the required Python libraries.
- Loaded the dataset using Pandas.
- Examined the dataset dimensions, column names, data types, and sample records.
- Used descriptive statistics to understand numerical variables.

### 2. Data Cleaning and Preparation

- Checked for missing values and duplicate records.
- Examined categorical columns containing `unknown` values.
- Retained `unknown` categories for analysis rather than removing potentially useful records.
- Created a numerical conversion indicator from the target variable `y`.
- Prepared suitable groups for customer age, account balance, and campaign contact analysis.

### 3. Exploratory Data Analysis (EDA)

Performed 12 exploratory analyses to investigate customer responses and campaign performance:

1. Customer response distribution and overall conversion rate
2. Conversion rate by job category
3. Conversion rate by marital status
4. Conversion rate by education level
5. Customer age distribution and conversion rate by age group
6. Conversion rate by contact method
7. Conversion rate by number of campaign contacts
8. Conversion rate by previous campaign outcome
9. Account balance distribution and conversion rate by balance group
10. Conversion rate by housing loan status
11. Conversion rate by personal loan status
12. Conversion rate by campaign month

### 4. Data Visualization

Used Matplotlib and Seaborn to create charts that make customer patterns and campaign performance easier to understand.

Visualizations include categorical comparisons, histograms, and conversion-rate charts.

### 5. Key Insights

- The overall conversion rate was approximately **11.70%**.
- Students and retired customers showed comparatively high conversion rates among job categories.
- Customers with tertiary education had a higher conversion rate than customers with secondary or primary education.
- Customers contacted through cellular phones had a higher conversion rate than those contacted through telephone.
- Customers with a successful previous campaign outcome showed a substantially higher conversion rate.
- Customers without housing or personal loans showed higher conversion rates than customers with those loans.
- Customers contacted fewer times during the current campaign generally showed higher conversion rates than those contacted repeatedly.
- Conversion rates varied considerably across campaign months, suggesting that campaign timing deserves further investigation.

*These findings describe patterns in the dataset. They do not establish that any single factor directly causes a customer to subscribe.*

### 6. Business Recommendations

- Prioritize further analysis of customer segments with higher observed conversion rates.
- Use previous campaign outcomes to help inform future campaign targeting.
- Evaluate cellular contact performance and investigate why contact method is associated with different response rates.
- Review repeated contact strategies to avoid unnecessary customer outreach.
- Investigate campaign-month performance alongside the number of customers contacted in each month.
- Test targeted campaign strategies and measure their results before implementing them broadly.

## Project Structure

```text
Marketing-Campaign-Analysis/
│
├── Data/
│   └── bank-full.csv
│
├── Notebooks/
│   ├── marketing_campaign_analysis_v2.ipynb
│   └── marketing_campaign_analysis_v2.html
│
└── README.md
```

## How to Run the Project

1. Clone or download this repository.
2. Install Python and Jupyter Notebook.
3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

4. Ensure the dataset is available in the `Data/` folder.
5. Open the notebook in Jupyter Notebook or Visual Studio Code.
6. Run the notebook cells to reproduce the analysis.

## Conclusion

This project demonstrates the use of Python libraries for data cleaning, exploratory data analysis, feature preparation, and visualization. The analysis identifies customer segments and campaign characteristics associated with different conversion rates, providing a foundation for more informed marketing decisions.

## Author

**Tanisha Shirolkar**

- [GitHub](https://github.com/tanishashirolkar)
- [LinkedIn](https://www.linkedin.com/in/tanisha-shirolkar-2004d08)
