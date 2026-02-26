📌 Executive Summary
Project Sentinel is a strategic data audit designed to identify and quantify "Profit Leaks" within a SaaS/Telecom subscription model. By integrating SQL-based data architecting, Python-driven feature engineering, and Power BI executive dashboards, this project provides a decision-support tool to reduce customer churn and optimize Net Recurring Revenue (NRR).

🛠️ Tech Stack & Skills
Data Processing: Python (Pandas, NumPy)

Database Logic: SQL (Star Schema, CTEs, Window Functions)

Business Intelligence: Power BI (Advanced DAX, What-If Parameters, Row-Level Security)

Analysis Techniques: RFM Segmentation, Unit Economics, Root Cause Analysis

📊 Business Problem
The organization observed high Gross Sales but stagnant Net Profit. The objective was to investigate:

Retention Health: What is the actual Churn Rate across different contract types?

Revenue Erosion: Which service combinations (e.g., Fiber Optic + Month-to-Month) contribute most to Critical Revenue Risk?

Financial Impact: How much annual revenue can be recovered by converting high-risk users to stable contracts?

🚀 Key Insights & Impact
Identified "The Smoking Gun": Discovered that Fiber Optic users on Month-to-Month contracts have a churn rate 3x higher than the company average.

Quantified Risk: Isolated $185K in Monthly Recurring Revenue (MRR) currently sitting in the "Critical Risk" segment.

Strategic Solution: Built a What-If Simulation showing that a modest 20% conversion of high-risk users would result in $108K+ in annual saved revenue.

📁 Project Structure
data/: Contains the raw and cleaned datasets (e.g., Telco_Churn_Cleaned.csv).

notebooks/: Jupyter Notebooks detailing the Python cleaning pipeline and Exploratory Data Analysis (EDA).

dashboard/: The .pbix file containing the Executive Revenue Console.


📸 Dashboard Preview
Top-Down Logic: The header provides immediate financial KPIs, the sidebar allows for interactive "What-If" goal setting, and the Decomposition Tree enables autonomous root-cause analysis for stakeholders.

💡 How to Use
Clone the repository.

Run the Python script in /notebooks to see the data transformation logic.

Open the Power BI file in /dashboard to interact with the visual segments.
