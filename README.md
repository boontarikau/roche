# Roche
# Market Analysis of Roche Pharmaceuticals
# Data source: https://public.tableau.com/app/profile/maxim3927/viz/MarketAnalysisRoche/Sales
## Project Overview
This project focuses on the **Market Analysis of Roche Pharmaceuticals**, a global leader in pharmaceuticals and diagnostics. The analysis explores Roche's performance in oncology, immunology, and personalized medicine markets and addresses challenges in market penetration and competitive positioning.
## Objectives
1. **Discovery**:
   - Understand Roche’s market landscape and trends.
   - Research the performance of competitors in oncology and specialty medicine.

2. **Data Preparation**:
   - Clean and preprocess sales and patient datasets.
   - Handle missing data, duplicates, and ensure data consistency.

3. **Modeling**:
   - Use Exploratory Data Analysis (EDA) to uncover sales patterns, product performance, and regional trends.
   - Build predictive models to forecast sales based on historical data.

4. **Results**:
   - Present key insights and recommendations for marketing strategies.

---

## Key Insights
1. **Sales Contribution**:
   - Specialty business leads with 50.84% of total revenues.
   - Oncology accounts for 44.03%, and others account for 5.12%, indicating growth potential.

2. **Market Share**:
   - Roche contributes 51.01% (Roche Onco: 34.13%, Roche SB: 16.88%), slightly ahead of competitors (48.98%).

3. **Sales Trends**:
   - Highest sales occurred in **June 2020**, with a peak of 24,442 units.

4. **Top Customers & Products**:
   - Top customer: **Cust12**.
   - Highest contributing product: **Prd24** from FAM8.

5. **Regional Insights**:
   - **Moscow** leads with 674 diagnosed patients, followed by Southern (532) and Volga (460).

6. **Product Usage**:
   - Most commonly used product: **Prd21** from FAM8.

---

## Data Modeling
Four machine learning models were evaluated:
1. **Linear Regression**: Best performance (R² = 1.0).
2. **K-Nearest Neighbors (KNN)**: R² = 0.9932.
3. **Random Forest Regression**: R² = 0.9866.


**Conclusion**: KNN and Linear Regression were the most effective models for predicting sales but the data is only 2 years. So, There will be better model for more data.

---

## Recommendations
- Leverage data insights to enhance marketing strategies in underperforming regions.
- Focus on growing market share in competitive regions by targeting high-performing products like **Prd24** and **Prd21**.
- Prioritize emerging markets with tailored product positioning strategies.

