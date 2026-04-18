📌 Project Overview
This project involves a comprehensive diagnostic analysis of a multi-branch restaurant chain in Egypt. The goal was to identify revenue leakages, analyze customer behavior, and provide actionable insights to optimize operational efficiency across several key domains: Geography, Branch Performance, Refund Analysis, and Customer Tiers.

🚀 Key Business Insights
1. Revenue Leakage Identification (The $700k Discovery)
Insight: Identified that the "Drink" category (Mango, Sugarcane, and Tea) accounted for 82% of total refund value (~$700k).

Action: Rule out branch-specific errors as the trend was uniform across all locations.

Recommendation: Audit the beverage raw material supplier and investigate delivery packaging to prevent oxidation or spillage.

2. Promotional Efficacy (Discount Lift)
Insight: A 10% discount resulted in a 41% increase in Average Order Quantity (7.4 to 10.5 items per basket).

Conclusion: The customer base is highly price-sensitive; discounts are a major driver for increasing "Basket Size."

3. Branch Performance & Market Gaps
Insight: The Assiut branch significantly underperforms Cairo in sales volume and holds the lowest average rating (3.1).

Observation: Despite low ratings, Assiut has the lowest refund rate, suggesting a "silent churn" where customers do not complain but simply stop visiting.

Opportunity: Identified significant "Dead Zones" during Morning and late Evening hours, suggesting a need for a specialized breakfast and "light snack" menu to utilize fixed overhead costs.

🛠️ Technical Implementation
Data Modeling & DAX
Customer Lifetime Value (CLV): Calculated as [AOV] * [Order Frequency] to determine the long-term value of the loyal customer base.

Rating Variance: Implemented STDEV.P measures to identify consistency in customer experience.

Dynamic Tiering: Used SQL and DAX to segment customers into spending tiers (Budget vs. Mid-Range vs. VIP).

Dashboard Architecture
Overview: High-level KPIs including Total Sales (2.90bn), Total Orders (11M), and AOV.

Branch Analysis: Deep dive into regional performance, time-of-day trends, and day-of-week heatmaps.

Refund Diagnostic: A specialized page focusing on "Impact vs. Rate" to pinpoint specific item failures.

Customer Behavioral Profile: Analysis of payment methods, weekend habits, and discount sensitivity.

📈 Final Recommendations
Supply Chain Audit: Focus on the beverage category to recover a potential 24% of lost net revenue currently attributed to refunds.

Regional Relaunch: Conduct a quality audit in the Assiut branch to improve the 3.1 rating and capture missed market share.

Capacity Utilization: Launch a pilot "Morning Breakfast" menu to fill the low-traffic hours identified in the temporal analysis.

💡 Analyst's Note on Data
During the analysis, I identified a high degree of uniformity in customer spending and retention within the dataset. I pivoted the strategy to focus on Tiered Spending Power and Sentiment Inconsistency to ensure the business recommendations remained robust despite data limitations.

You can now copy-paste this! It covers exactly what a hiring manager wants to see: Problem -> Analysis -> Impact. Enjoy your well-earned rest!
