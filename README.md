# Customer-Spending-Behavior


## Project Objective

The objective of this project is to analyze customer demographics, behavior, and subscription patterns using Excel and Tableau to identify key drivers of churn, segment high-risk groups, visualize engagement trends, and deliver actionable insights for improving retention and optimizing offerings.


## Dataset

https://github.com/anmolsodhi848-wq/Customer-Spending-Behavior/blob/main/Customer%20Spending%20Analytics.xlsx


## KPIs (Key Performance Indicators)

1. Churn Rate: Percentage of customers who have left within a given period.
2. Customer Retention Rate: Percentage of customers retained over time.
3. Average Monthly Spend: Mean spending per customer per month.
4. Customer Lifetime Value (CLV): Estimated total revenue from a customer during their relationship.
5. Customer Tenure: Average duration (in years or months) a customer stays subscribed.
6. Last Login Frequency: Average time since last login, indicating engagement level.
7. Churn Rate by Segment: Churn percentages segmented by age group, gender, region, and subscription type.
8. Subscription Upgrade/Downgrade Rate: Percentage of customers changing subscription tiers.


# Process

1. **Data Extraction & Cleaning:** Imported the raw sales dataset from MS Excel, removed duplicates, standardized date formats, corrected missing values, and ensured consistency across fields such as product categories, regions, and payment methods.
2. **Feature Engineering & Transformation:** Derived analytical fields such as Total Sales, Profit, Gross Margin, Discount Applied, Shipping Expense, and Average Order Value. Categorized data by month, quarter, region, and customer segments for deeper insights.
3. **Exploratory Data Analysis (EDA):** Performed trend analysis across sales, customer segments, product categories, and regions. Identified patterns in profit contribution, discount impact, sales channel efficiency, and seasonal variations.
4. **Dashboard Development & KPI Mapping:** Designed interactive dashboards to visualize KPIs, sales trends, regional performance, product ratings, and customer behavior. Mapped KPIs to business outcomes for quick decision-making.


# Dashboards

1. **Customer Demographics Overview**
   <img width="1812" height="723" alt="image" src="https://github.com/user-attachments/assets/a31bb613-f825-4d21-b159-afa50cae672d" />

2. **Customer Spending Behavior**
   <img width="1807" height="722" alt="image" src="https://github.com/user-attachments/assets/985c96c3-43a2-4773-81e6-b08bbc2aaf16" />

3. **Customer Subscription Behavior**
   <img width="1817" height="723" alt="image" src="https://github.com/user-attachments/assets/ee7c0402-8a6c-402b-affc-37d887507b99" />


## Project Insights

1. **Customer Demographics**
   1. Gender distribution is relatively balanced, with a slight male majority; however, the “Other” segment is also significantly represented, indicating an inclusive customer base.
   2. Age distribution shows the highest customer concentration between 40–50 years, highlighting this segment as the core target audience.
   3. Regional customer spread is fairly even, with the East leading slightly in overall customer count.

2. Subscription & Customer Behavior
   1. Basic plan has the highest adoption (347 users), followed closely by Premium and Standard, indicating strong demand for entry-level plans.
   2. Subscription distribution is consistent across regions, suggesting regional preferences do not heavily influence subscription choice.
   3. Churn rate appears minimal across all subscription types, pointing to good customer retention and satisfaction with service offerings.

3. **Spending Behavior Insights**
   1. Avg. Monthly Spend is highest in the East region, though differences between regions are small, indicating uniform spending patterns nationwide.
   2. Average spending across subscription tiers is nearly identical, suggesting customers with higher-tier plans do not necessarily spend significantly more monthly.
   3. Males exhibit the highest total monthly spend, followed by females and those in the “Other” category, indicating slight gender-based spending variations.

4. **Age vs Monthly Spend**
   1. Spending remains stable across most age groups, with no drastic peaks except one outlier at age 43 indicating a high-value customer.
   2. Overall, older age groups (50+) maintain steady spending, showing they are valuable long-term customers.


## Conclusions
The analysis reveals a stable and well-distributed customer base with consistent spending patterns across demographics and regions. Subscription adoption is healthy, churn is minimal, and customer satisfaction appears strong. The strongest revenue potential lies in targeting middle-aged customers and optimizing offerings for the large Basic subscription segment. While regional spending differences are minor, strategic micro-campaigns in higher-performing areas can unlock incremental gains. Overall, the customer landscape shows strong fundamentals with clear opportunities for targeted growth and value maximization.


## Future Scope

1. Deploy Predictive Modeling (CLV, churn prediction, segmentation).
2. Automate reporting with ETL pipelines feeding dashboards.
3. Build an interactive Streamlit dashboard for real-time analytics.
4. Integrate A/B testing insights for marketing optimization.


## Recommendations

1. Focus marketing efforts on customers aged 40–50, the core demographic.
2. Introduce upsell campaigns for Basic plan subscribers (largest base).
3. Investigate high-value outlier customers for retention and brand evangelism.
4. Launch micro-targeted campaigns in the East region, where spending is slightly higher.
