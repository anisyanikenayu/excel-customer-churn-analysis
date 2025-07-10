# Analysis Customer Churn using Excel
This project is a hands-on case study based on a real project provided by DataCamp. The goal is to apply foundational Excel skills to solve a real-world business problem. In this case, the objective is to identify and understand the reasons behind customer churn for a fictional telecom provider named Databel.

The workflow involves data validation, exploratory data analysis (EDA), visualization, and dashboard creation.

## Datasets
The dataset is provided in an Excel file containing two worksheets:
- Customer – Contains individual customer-level data related to service usage and subscription status.
- Aggregate – Contains summarized metrics and dimensions to support high-level analysis.

## Datasets Structure
Dimensions:
- Customer ID
- Unlimited Data Plan
- Account Length
- Demographics (Age)
- State
- Churn Category
- Churn Reason
- Grouped GB Consumption

Measures:
- Total Customers
- Churn Rate

## Data Cleaning & EDA Process
Throughout the cleaning and analysis process, I maintained a detailed log of all transformation steps and observations. You can view the full documentation here: [Cleaning & EDA Documentation](https://github.com/anisyanikenayu/excel-customer-churn-analysis/blob/68a2a29cd6b1edc04c906ef32aca21890f811947/cleaning-eda-docs-tracking.xlsx)

## Key Insights from Exploratory Data Analysis
- **Churn Rate:** Out of 6,687 total customers, 1,792 have churned—representing a churn rate of approximately 26.86%, which is relatively high.
- **Top Churn Reason:** The primary churn driver (~44.85%) is from competitor. Many customers get better offers and devices from competitors as their reason for leaving.
- **Demographics & Age Trends:**
    - Senior customers are get highest churning.
    - When broken down by age groups, churn rate increases with age.
    - The 79–88 age group, though small in size, shows the highest churn rate, which may be influenced by natural reason related to age (some of the might have been passed away) or other factors.
- **Unlimited Data Plan Users:**
    - A significant portion of churners had low data usage.
    - Specifically, those using less than 5GB (~34.49%) and 5GB–10GB (~33.59%) are most likely to churn—indicating possible misalignment between plan offerings and actual usage.
- **International Plan Subscribers:** Among customers subscribed to international plans, the state of California (CA) records the highest churn rate, approximately 75%.
- **Customer Account Length Impact:**
    - Customers with an account length of 1–3 years show a high tendency to churn when subscribed to month-to-month contracts, with churn rates exceeding ~70% across each group. This indicates that short-term commitment early in the customer lifecycle correlates with higher churn risk.
    - Starting from 3rd year more, churn is not only associated with month-to-month plans but also observed among customers on one-year contracts, where churn accounts for ~20.83%. This suggests that even medium-term customers may reconsider their commitment after three years.
    - These insights can be leveraged to design loyalty packages targeted at long-term customers (3+ years), such as exclusive incentives for two-year contract upgrades, to increase retention.

## Dashboard Result
![image](https://github.com/user-attachments/assets/84330ea9-1c04-4768-beb4-f38cf0aa0cff)

## Final Thought
This project served as an opportunity to strengthen my data storytelling and analytical thinking using Excel as the primary tool. By blending data cleaning, exploration, and visualization, I was able to uncover patterns that could inform customer retention strategies.
