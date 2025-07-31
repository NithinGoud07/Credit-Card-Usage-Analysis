# Credit-Card-Usage-Analysis
Project Overview
This project analyzes credit card transaction data to uncover spending patterns, regional trends, high-value customers, and customer segmentation insights. It aims to provide actionable recommendations for financial institutions and product teams to improve offerings and targeting.

🔎 Business Problem & Objective
Identify key patterns across demographics, regions, and card types.

Pinpoint high-spending customers and transaction clusters.

Support strategic decisions for credit card product design and marketing.

🛠 Tools & Technologies
Languages: Python (pandas, NumPy), SQL (if applicable)

Visualization: matplotlib, seaborn,plotly and Power BI 

Other: Jupyter notebooks

📂 Dataset Summary
List the files used and the fields they include:

transactions.csv: Customer IDs, dates, amounts, card type, categories

customers.csv: Demographics such as age, gender, income, city

Additional metadata files as needed.

⚙️ Data Preprocessing
Clean missing or inconsistent entries (e.g. age <18 replaced with mean, outliers capped based on limits)

Feature engineering: compute utilization rate, monthly/weekly aggregates, payment ratios

Merge datasets where appropriate into a final analytic table

Handle categorical encoding or normalization

📈 Exploratory Data Analysis (EDA)
Transaction trends over time (monthly/weekly spend by region or card type)

Customer age-group and gender spend analysis

Region-wise heatmaps to show spending intensity

Correlation matrix among features — e.g. income, age, spending frequency, utilization

🎯 Customer & Transaction Insights
High‑Spending Customers: Top 10–20 users by total spend or repayment amount (like high_spending_customers.csv) 
GitHub
+1
GitHub
+1
GitHub
+7
GitHub
+7
GitHub
+7
GitHub
+1
GitHub
+1
GitHub

Regional Patterns: Average spend by city/region

Card-specific behavior: Frequency and volume by card brands or types

💡 Findings & Recommendations
Demographic insights: E.g. younger age groups (late 20s) show higher usage; salaried IT professionals may have higher activity 
GitHub

Card Strategy: Promote rewards for frequently used categories (e.g. travel, dining)

Product personalization: Target segments with tailored offers or fees

Regional campaigns: Focus on cities that show spending spikes (e.g. Mumbai or specific metros) 
GitHub
+10
GitHub
+10
GitHub
+10
GitHub

🚀 How to Run
Clone the repository

Install dependencies:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn sqlalchemy
(or list Power BI, SQL if we use dashboards)

Place datasets in /data/ directory

Run the notebook or script:

bash
Copy
Edit
python credit_card_usage_analysis.py
or open analysis.ipynb in Jupyter

Outputs: charts, aggregated tables, top-customer CSVs, dashboards

📁 Repository Structure
