# Banking_Domain_Analysis

Explore customer demographics, product usage, and financial behavior using a real-world banking dataset with Python, Pandas, Matplotlib, and Seaborn.

Project Overview
This project analyzes a dataset of 3,000 banking clients to uncover patterns in income, product holding, loyalty, risk, and more. The workflow covers data cleaning, transformation, univariate and bivariate analysis, and insightful visualizations.

Dataset Details
# File: Banking.csv

# Rows: 3,000

# Columns: 25

** Key Features:

1-Client demographics (age, gender, nationality, occupation)

2-Financial products (accounts, loans, deposits, credit cards)

3-Loyalty, risk, and fee structure

4-Product balances and property ownership

** Data Preparation
1- No missing values and all columns are well-typed.

2- Created Income Band: Categorized Estimated Income into Low, Med, and High bands.

3- Explored categorical columns: Used .value_counts() and countplots for all major categorical features.

4- Analyzed numerical columns: Used histograms and correlation heatmaps.

** Exploratory Data Analysis
Univariate Analysis
Categorical Features:

1- Most clients have 1 credit card.

2- Majority are European or Asian nationality.

3- Fee structure is mostly High or Mid.

4- Loyalty classification: Jade is most common.

5- Most clients own 1–2 properties.

6- Income Band: Almost all clients are in the High band.

Numerical Features:

1- Age ranges from 17 to 85 (mean ≈ 51).

2- Estimated income varies widely (mean ≈ 171k).

3- Product balances (deposits, loans, etc.) show high variance.

Bivariate Analysis
1- Countplots with Nationality as hue show how different groups are distributed across key categories.

2- Histograms for each numerical feature reveal skewness and outliers.

Correlation Analysis
Strong correlations:

1- Bank Deposits & Checking Accounts: 0.84

2- Bank Deposits & Saving Accounts: 0.75

Moderate correlations:

1- Checking Accounts & Saving Accounts: 0.46

2- Bank Deposits & Business Lending: 0.44

3- Bank Loans & Business Lending: 0.42

4- Income has weak to moderate correlation with most products.

5- Superannuation Savings is largely independent of other products.

Correlation Heatmap
![Correlation Heatmap Example](https://i.imgur.com/your_heatmap_link.png between all major financial product balances.*

** Key Insights
# Product Bundling: Customers with high bank deposits often have high checking and savings balances.

# Business Customers: Those with large deposits are more likely to use business lending.

# Loyalty & Fee Structure: Most loyal customers (Jade) are in high fee bands.

# Demographics: The dataset is balanced by gender and covers a wide range of occupations and ages.

** How to Run
Upload Banking.csv to your Colab or project directory.

Install requirements (if needed):

python
pip install pandas matplotlib seaborn numpy
Run the notebook or script.

** Dependencies
Python 3.x

pandas

matplotlib

seaborn

numpy

** Conclusion
This analysis provides a foundation for deeper insights into banking customer behavior, risk, and product cross-selling opportunities
