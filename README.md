# Bike-Sales-Analysis-In-Excel
This project analyzes customer data to identify the key factors influencing bike purchases. Using Microsoft Excel, I performed data cleaning, exploratory data analysis (EDA), and built interactive visualizations to generate business insights and recommendations.


🎯 Business Objective

The goal of this analysis is to answer:

What factors influence whether a customer purchases a bike?
How do income, age, gender, and commute distance impact buying behavior?
Which customer segments should be targeted to increase sales?
How can the business optimize pricing and marketing strategies?

📂 Dataset Description

The dataset contains 1,000 customer records with the following features:

Demographics: Age, Gender, Marital Status, Education, Occupation
Financial: Income
Lifestyle: Commute Distance, Cars Owned, Home Ownership
Geographic: Region (Europe, North America, Pacific)
Target Variable: Purchased Bike (Yes/No)
🧹 Data Cleaning Process

To ensure accuracy and consistency:

Removed 26 duplicate records
Standardized categorical values:
Converted M / S → Married / Single
Formatted Income column to currency and removed unnecessary decimals
Checked for missing values (none found)
Ensured consistency across all categorical fields

⚙️ Feature Engineering

Created a new column to improve segmentation:

Age Bucket (using nested IF formula):
Adolescent (<31)
Middle Age (31–64)
Senior (65+)

This enabled clearer analysis of customer behavior across life stages.

🔍 Exploratory Data Analysis (EDA)
1. Income vs Purchase Behavior
Customers who purchased bikes had higher average income
Specially man needs high income

👉 Insight: Income has a moderate positive relationship with bike purchases

2. Commute Distance Trends
Highest purchase rates: 0–1 miles and 2–5 miles
Lowest purchase rate: 10+ miles

👉 Insight: Bikes are primarily used for short-distance commuting

3. Age Group Analysis
Middle-aged customers dominate purchases
Lower engagement from adolescents and seniors

👉 Insight: Middle-aged individuals are the core customer segment

4. Segment-Based Insights
Marital Status + Income
Single customers purchase at lower income levels
Married customers require higher income

👉 Insight: Financial behavior differs by household structure

Regional Differences
Europe: Lower income needed to purchase (~$39K–$46K)
North America & Pacific: Higher income required (~$62K–$65K)

👉 Insight: Regional pricing and affordability vary significantly

Education & Income Trends
Higher education correlates with higher income and purchase likelihood
Graduate degree holders show the highest income levels


📊 Data Visualization

Built interactive dashboards using:

Pivot Tables & Pivot Charts
Slicers (e.g., Marital Status) for dynamic filtering

💡 Key Insights
Income influences purchasing, but is not the only factor
Middle-aged customers are the most valuable segment
Short commute distance strongly increases likelihood of purchase
Marital status impacts spending behavior
Significant regional differences in purchasing power


🚀 Business Recommendations
🎯 Target middle-aged professionals as primary customers
🚲 Market bikes as a short-distance commuting solution
🌍 Adjust pricing strategies based on regional income levels
👥 Segment marketing campaigns:
Singles → affordability-focused
Married → value and long-term benefits
🎓 Focus premium offerings on higher-income, educated customers

🛠️ Tools & Skills Used
Microsoft Excel
Data Cleaning & Transformation
Pivot Tables & Pivot Charts
IF Formulas (Feature Engineering)
Data Analysis & Segmentation
Data Visualization & Storytelling

📈 Project Outcome

This project demonstrates how raw data can be transformed into actionable insights that support:

Better customer targeting
Smarter pricing strategies
More effective marketing decisions

👤 Author

Raisa Basher
BBA in Computer Information Systems
Georgia State University
