# Customer Churn Analysis for Telcom
**Executive Summary:**

Using Python (pandas, matplotlib, seaborn), I analyzed telecom customer churn data to identify key drivers of customer attrition and revenue loss. After discovering that month-to-month contracts, short tenure, and higher monthly charges were strongly linked to churn, I recommend the team implements few adjustments that will lead to reduce churn:

1. Implementing long-term contract incentives
2. Early customer engagement strategies
3. Targeted retention campaigns

**Business Problem:**

Customer churn directly affects profitability, growth, and long-term sustainability. Companies care about churn because acquiring new customers is far more expensive than retaining existing ones. The purpose of this project is to understand which customers are most likely to leave and what factors influence their decision. By identifying churn drivers, the company can take proactive steps to improve retention and reduce financial losses.

**Methodology:**

1. Cleaned and preprocessed the telecom customer churn dataset using Python.

2. Performed exploratory data analysis (EDA) to examine churn patterns across tenure, contract type, demographics, and monthly charges.

3. Compared churned vs. retained customers to identify high-risk segments and key drivers of attrition.

**Skills:**

Python: Pandas, Numpy, Seaborn, Matplotlib, Exploratory Data Analysis

**Results and Recommendation:**

The analysis was conducted on 7,043 telecom customers, with an overall churn rate of 26.54% (1,869 customers). Customers on month-to-month contracts show 42% churn, compared to 11% for one-year and 3% for two-year contracts, making contract type the strongest driver. Customers with less than 12 months tenure are significantly more likely to churn.

Fiber Optic users have 42% churn, compared to 19% for DSL users. Customers paying via Electronic Check show over 45% churn, the highest among payment methods. Additionally, customers without Tech Support or Online Backup services have noticeably higher churn rates. Overall, contract type, tenure, internet service, and payment method are the key churn drivers.

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/18c9e1a3-7eba-44ba-8f14-630eb104ee58" />
<img width="400" height="400" alt="Screenshot 2026-03-10 152917" src="https://github.com/user-attachments/assets/eed70062-b947-4e04-a6ac-d5a4b8c6c3ca" />
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/f330ecb6-691b-4b82-9786-de1fdc159d06" />
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/600107b9-bb7d-45e3-8f84-80a412f8a198" />

The largest revenue impact will come from reducing churn among high-risk customer segments, I recommend the following strategic actions:

1. Offer incentives for customers on month-to-month contracts to switch to one-year or two-year plans through discounts or bundled services.

2. Launch an early engagement program targeting customers within their first 6–12 months to improve onboarding experience and strengthen retention.

3. Provide loyalty discounts or value-added bundles for Fiber Optic customers to address higher churn risk within this segment.

4. Promote Tech Support and Online Backup add-ons to increase customer stickiness and perceived service value.

5. Encourage customers using Electronic Check to switch to automatic payment methods through small billing incentives.

I believe these initiatives will directly address the highest churn drivers, improve customer lifetime value, stabilize recurring revenue, and reduce customer acquisition costs over time.




