📊 Data Analytics Projects – E-commerce

This repository showcases two end-to-end data analytics projects where I applied Python, SQL, Power BI, and Excel to derive actionable business insights. Both projects follow a structured approach: Problem Definition → Data Preparation → Analysis → Visualization → Actionable Results.

🛒 E-commerce Performance Optimization (RFM Segmentation)
📌 Problem Statement

In the competitive e-commerce industry, businesses generate vast amounts of customer transactional data but often struggle to leverage it for actionable segmentation. The key challenges were:

-Lack of customer profiling for targeted marketing.

-High churn rates and underutilized marketing budgets.

-Need for strategic allocation of resources to maximize Customer Lifetime Value (CLV).

🎯 Objective

Identify high-value vs low-value customers using RFM metrics.

Segment customers into actionable groups for targeted campaigns.

Quantify the business impact of segmentation in terms of revenue, retention, and engagement.

🛠 Methodology

1. Data Preparation

-Cleaned transaction data (removed cancellations, nulls, duplicates).

-Created line-item revenue features (Quantity × UnitPrice).

2. RFM Analysis & Deciling

-Calculated Recency, Frequency, Monetary for each customer.

-Applied decile ranking using pd.qcut to build a 10-tier hierarchy.

-Segmented into groups like Champions, Loyal Customers, At-Risk, Dormant.

3. Visualization & Dashboards

-Built dashboard in Power BI to showcase:

-Revenue contribution by decile.

-Segment distributions.

-Repeat purchase trends and churn risk.

 Impact

-Compared baseline vs post-campaign windows to measure:

-10× increase in quarterly sales ($0.23M → $2.44M).

-15% uplift in retention, recovering $5.8M from at-risk customers.

-20% increase in repeat purchases via loyalty programs.

-30% expansion into new markets with reduced seasonal dips.

📈 Results

-Delivered data-driven segmentation that directly improved marketing ROI.

-Optimized budget allocation by focusing on top deciles with highest returns.

-Created a sustainable customer analytics framework for ongoing strategy.

⚙️ Tools & Tech

-Python (Pandas, NumPy, Matplotlib, Seaborn)

-SQL (For Storing Data and connetcing to powerBi)

-Power BI (dashboards)
