# Customer-Shopping-Behavior-Analysis
Transactional retail data analysis with feature engineering, SQL business queries, and interactive Power BI dashboard development.End-to-End Data Analytics Project | Python • SQL • Power BI

1. Project Context
In highly competitive retail environments, understanding what drives customer spending, loyalty, and product performance is critical. 
This project analyzes 3,900 customer transactions to uncover behavioral insights and generate data-driven commercial strategies.

2. Business Objectives
• Identify high revenue customer segments
• Evaluate discount effectiveness
• Analyze subscription value contribution
• Understand demographic spending patterns
• Detect product pricing dependency

3. Dataset Overview
• Transactions: 3,900
• Features: 18
• Categories: Accessories, Clothing, Footwear, Outerwear

4. Data Preparation & Feature Engineering (Python)
• Data cleaning and preprocessing were performed using Pandas to ensure data reliability .   
• Imputed missing review ratings using the median rating per product category.
• Renamed columns into snake case format for consistency.
• Created age group variable through age binning.
• Derived purchase frequency days metric.
• Removed redundant column promocode used.
• Cleaned dataset was loaded into PostgreSQL for structured querying.

6. Data Preparation & Feature Engineering
• Median imputation for missing ratings
• Created age cohorts and purchase frequency metrics
• Customer lifecycle segmentation (New / Returning / Loyal)
• MySQL integration for scalable querying

7. Key Insights
• Young Adults are the highest revenue contributors
• Express shipping users show higher purchase intent
• Certain products show ~50% discount dependency
• Loyal customers dominate the customer base
• Non‑subscribers generate higher total revenue due to population size

8. Business Analysis Using SQL
• Revenue Contribution by Gender - Male customers generated significantly higher total revenue compared to female customers
 igh-Spending Discount Users

• High-Spending Discount Users - 839 customers were identified who used discounts but still spent above average.
 
• Top 5 Products by Rating – Found products with the highest average review ratings.
 
• Subscribers vs. Non-Subscribers – Compared average spend and total revenue across subscription status.
 
• Discount-Dependent Products – Identified 5 products with the highest percentage of discounted purchases.
 
• Shipping Type Comparison – Compared average purchase amounts between Standard       and Express shipping.
 
• Customer Segmentation – Classified customers into New, Returning, and Loyal segments based on purchase history.
 
• Top 3 Products per Category – Listed the most purchased products within each category.
 
• Repeat Buyers & Subscriptions – Checked whether customers with >5 purchases are more likely to subscribe.
 
• Revenue by Age Group – Calculated total revenue contribution of each age group.
 

8. Dashboard in Power BI 
Finally, we built an interactive dashboard in Power BI to present insights visually.
 

9. Strategic Recommendations
• Improve subscription benefits to increase CLV
• Optimize discount allocation using product elasticity signals
• Target high‑value demographics for marketing ROI uplift
• Promote top‑rated products for conversion improvement
• Strengthen loyalty incentives for retention growth

10. Project Takeaways
This project demonstrates strong capability in data cleaning, SQL analytics, dashboard storytelling, KPI interpretation, and business strategy translation.



# 8. Tools & Technologies

Python (Pandas, Data Cleaning, Feature Engineering)

PostgreSQL (Business Querying & Aggregations)

Power BI (Dashboard & Visualization)

# 9. Project Outcome

This project demonstrates the ability to:

Perform structured exploratory data analysis

Translate business questions into SQL insights

Build meaningful KPIs and strategic recommendations

Develop decision-support dashboards

Communicate insights through data storytelling
