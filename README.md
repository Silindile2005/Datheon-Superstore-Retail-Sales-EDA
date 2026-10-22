 Superstore Retail Sales - Exploratory Data Analysis

Datheon Internship  Task 1

Project Overview

This project presents an Exploratory Data Analysis (EDA) of the Superstore Retail Sales dataset using Python. The analysis examines retail sales performance, customer purchasing behaviour, seasonal sales patterns, product category profitability, regional performance, customer segments and discount sensitivity.

The objective is to transform raw retail transaction data into meaningful business insights and provide evidence-based recommendations to support decision-making.

 Technologies Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook
- Git and GitHub

 Dataset

The original dataset contained 10800 records and 21 columns.

After data cleaning and feature engineering, the final dataset contained 9994 records and 25 columns, covering transactions from January 2015 to December 2018.

Preprocessing included removing unrelated records, investigating missing values and duplicates, converting date columns and creating temporal variables.

Analysis Performed

1. Data cleaning and preprocessing
2. Descriptive statistics and outlier detection
3. Customer purchasing behaviour analysis
4. Monthly sales trends and seasonality
5. Product category revenue and profitability
6. Regional and customer segment analysis
7. Discount sensitivity and profitability
8. Business recommendations

Key Results

 Business Indicator  Result 

Total Sales $2297200.86 
Total Profit $286397.02 
Total Orders 5009 
Total Customers  793 
Total Units Sold  37873 
Overall Profit Margin  12.47% 

Key Findings

- Approximately 18.72% of transaction lines generated losses.
- Technology generated the highest category revenue and profit.
- Furniture recorded a low profit margin of 2.49%.
- November recorded the highest average monthly sales.
- West was the strongest-performing region.
- Home Office achieved the highest customer segment profit margin of 14.03%.
- Discounts of 30% or more were associated with negative aggregate profitability at every observed discount level.
 Project Structure

```text
Datheon-Superstore-Retail-Sales-EDA/
├── data/
│   └── superstore_sales_cleaned.csv
├── notebooks/
│   └── Task 1.ipynb
├── reports/
│   └── Superstore_EDA_Report.pdf
└── README.md
```

Installation and Reproducibility

Install Python 3 and Jupyter Notebook, then install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Clone this repository, open `notebooks/Task 1.ipynb` in Jupyter Notebook and run the analysis cells.

The notebook was developed using the original Superstore dataset. To reproduce the entire cleaning process, obtain the original dataset and update the input file path in the notebook.

The cleaned dataset is provided for further analysis, subject to its redistribution permissions.

Business Recommendations

The analysis recommends reviewing high-discount transactions, improving Furniture profitability, monitoring loss-making customers, preparing for seasonal demand fluctuations and investigating regional profitability differences.

Conclusion

This project demonstrates how Python-based exploratory data analysis can identify meaningful patterns in retail sales data and support evidence-based business decisions.

Project: Datheon Internship -Task 1
