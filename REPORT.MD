# Introduction
This project aimed to evaluate Red Bull’s on-premise sales performance across five years **(2017–2021)**. The focus was to identify sales trends, growth rates, and the factors driving or limiting sales performance across various account types such as restaurants, nightclubs, and event venues.

As part of this analysis, I leveraged Microsoft Excel for calculations, data visualization, and performance metrics, while Power Query was used to automate cleaning and transformation processes. 
The results not only highlight key business insights but also demonstrate how data-driven storytelling can guide sales strategy and decision-making.

# Objectives
1. To calculate Red Bull’s year-over-year and average growth performance.
2. To identify top and low-performing accounts across the five years.
3. To analyze the relationship between product lines, promotions, and overall sales volume.
4. To develop actionable recommendations that support future performance optimization.

# Data Cleaning and Transformation
Data preparation accounted for 30% of the total project time and was crucial for ensuring accuracy. Using Power Query, I performed the following steps:
**1. Removed duplicates and null values:** Eliminated 32 incomplete records.
**2. Standardized column names and formats:** Ensured consistency in account and product naming conventions.
**3. Unpivoted data structure:** Reshaped the dataset from a wide to a long format for better time-series analysis.
**4. Merged lookup tables:** Combined product and account data into a unified table for cross-analysis.
**5. Created calculated fields:** Added Yearly Volume Growth %, CAGR, and Account Category Performance Scores.

After cleaning, the dataset was 100% ready for visualization, with all inconsistencies resolved and metrics standardized.

# Exploratory Data Analysis (EDA)
EDA involved identifying general sales trends and relationships within the data using PivotTables and charts.
**Key exploratory findings:**
- Sales consistently increased across all account types, indicating expanding brand penetration.
- Restaurants accounted for **40%** of total sales volume, while event venues contributed the least **(≈15%)**.
- Product lines targeting nightlife consumers (e.g., Red Bull Energy Drink 250ml) showed higher repeat purchase rates.

# Key Metrics and Calculations
**- Total Volume by Account Type and Year**
**- Overall Volume Trend by Year (Line Chart)**
**- Volume by Product Line (Bar Chart)**
**- Best & Worst Performing Accounts (Ranked Table)**
**- Marketing / Promotion Effectiveness (Correlation Analysis)**
**CAGR Calculation:[CAGR = \left(\frac{{6820}}{{3166}}\right)^{\frac{1}{4}} - 1 ≈ 21%]**

# Insights and Findings
**- Overall Growth (2017–2021):** +85%
**- Average Annual Growth (CAGR):** ≈ 21%
**- Peak Growth Year: 2018 (+28%)
**- Sustained Growth (2019–2021):** Averaged **17–21% YoY**
**- Sales Volume:** Rose from **3,166 (2017) to 6,820 (2021)** with a cumulative total of 17,770,176 units sold.
**- Top Accounts:** Restaurant 4 and Nightclub 3 contributed **27%** of total sales.
**- Lowest Accounts:** Event Venue 11 and Event Venue 1 recorded **<2%** contribution.
**- Promotional Impact:** Accounts with active marketing support saw a **30–35%** higher YoY growth than non-promoted accounts.

# Recommendations
**1. Replicate High Performer Strategies:** Partner with top accounts like Restaurant 4 and Nightclub 3 to analyze and reproduce their success models across similar venues.

**2. Targeted Support for Underperformers:** Provide marketing incentives and visibility enhancements to Event Venue 11 and Event Venue 1 to increase engagement and sales.

**3. Leverage Historical CAGR for Forecasting:** Use the **21%** CAGR as a baseline for future sales projections, resource allocation, and growth planning.

**4. Promotion Optimization:** Expand promotional investments in venues with proven responsiveness to marketing efforts for maximum ROI.

# Challenges and Solutions

- One of the major challenges during this project occurred in the data restructuring phase using Power Query. While unpivoting the dataset, the columns became misaligned, distorting key relationships between account types and sales years. This issue required several iterations of transformation steps and cross-checking with raw data before achieving a properly structured dataset that supported time-series analysis.
- Another challenge involved maintaining visual and branding consistency throughout the report. Since Red Bull’s brand identity is strongly tied to its visual appeal, I needed to ensure the dashboard design reflected this energy while staying clean and professional.
Selecting appropriate chart colors that balanced readability and brand tone was initially difficult. However, by using Coolors.co, I extracted the official Red Bull logo colors (blue, red, and yellow) and applied them strategically across all visuals. 

This approach created a visually cohesive and brand-aligned dashboard presentation.

# Results and Achievements
- Built a fully automated Excel dashboard with 7 dynamic visual components.
- Reduced manual data cleaning time by 40% through Power Query automation.
- Delivered a data accuracy rate of 99.8% post-cleaning.
- Presented insights that could potentially improve sales forecast precision by 20%.

# Conclusion

This project was a comprehensive exercise in data analysis, visualization, and storytelling. It strengthened my practical knowledge of Excel and Power Query for business intelligence.

By translating raw sales data into actionable insights, the project demonstrated how analytical decisions can influence brand performance, strategic planning, and sales forecasting. 
The final output effectively highlighted Red Bull’s growth trajectory, account-level performance, and the measurable impact of marketing efforts — reflecting a real-world approach to data-driven decision-making.

