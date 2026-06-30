Global Tech Retail Sales Analysis - Power BI Dashboard
Executive Summary
This project analyzes 3 years (2022 - 2024) of sales performance for a global electronics retail company operating across 15 countries and 5 regions. Using Power BI, I built an interactive two-page dashboard that surfaces top and underperforming products, regions, sales channels, and sales representatives enabling stakeholders to make data-driven decisions on where to invest and where to course-correct.
Key results from the analysis	
•	Total Revenue: $6.4M | Total Profit: $2.6M | Units Sold: 9K | Orders: 5K
•	Online Store is the strongest revenue channel, generating $2.5M
•	Laptop Ultra Book and Smartphone Pro X are the top two products by both revenue and profit
•	The United States leads all countries in revenue at $1.30M
•	Q1 consistently underperforms compared to other quarters across all three years
Business Problem
The company needed a clear, centralized view of sales performance to answer the following questions:
•	Which products, regions, and channels are driving the most revenue and profit?
•	Which products, countries, and sales reps are underperforming and need attention?
•	Are there seasonal patterns in sales that can inform future planning and promotions?
•	How is the business trending year-over-year - growing, flat, or declining?
Without a consolidated dashboard, this data existed only as raw transactional records, making it difficult for stakeholders to spot trends or make timely decisions.
Methodology
The analysis followed a structured end-to-end process:
1.	Data Collection - Sourced/generated a 5,500-row transactional sales dataset covering Order ID, Date, Product, Category, Price, Quantity, Revenue, Cost, Profit, Country, Region, Sales Channel, and Sales Rep.
2.	Data Cleaning - Used Power Query to handle missing values (nulls in price, quantity, revenue, profit, and sales rep fields), removed duplicate order IDs, and corrected data types.
3.	Data Modeling - Built a relational model connecting the sales table to a custom Date table, enabling time intelligence calculations.
4.	DAX Measures - Created a full measure library covering revenue, profit, margin, YoY growth, running totals, and rankings.
5.	Exploratory Analysis - Explored trends across products, regions, countries, channels, sales reps, and time (monthly/quarterly) to identify patterns.
6.	Dashboard Design - Built a two-page interactive Power BI report: one page highlighting top performers, one page isolating low performers, to give a balanced view of the business.
Tools Used
•	Power BI - Dashboard design, data modeling, visualization
•	Power Query - Data cleaning and transformation
•	Dax - Calculated measures (revenue & volume, profitability, running-totals, YoY growth, rankings)
Results & Business Recommendations
Findings:
•	Channel performance: Online Store drives 39% of total revenue, significantly ahead of Physical Store, Reseller, and Corporate B2B combined relative contribution.
•	Product performance: Laptops and Smartphones are the two strongest categories by both revenue and profit, while Accessories (USB-C Hub, Power Bank) underperform significantly.
•	Geographic performance: North America and Europe lead in revenue; Latin America and parts of Middle East & Africa lag behind.
•	Seasonality: Revenue consistently dips in Q1 across all three years, suggesting a recurring post-holiday slowdown.
Recommendations:
1.	Increase investment in the Online Store channel - it has the highest revenue and profit margin; consider reallocating budget from underperforming Reseller channels.
2.	Re-evaluate low-margin accessory products - consider bundling them with high-performing items (e.g., pairing Wireless Earbuds with Smartphone purchases) rather than selling standalone.
3.	Launch a Q1 promotional campaign - to counter the recurring seasonal dip and stabilize revenue at the start of each year.
4.	Investigate underperforming regions (Latin America, parts of MEA) - determine whether this is a market demand issue or a distribution/marketing gap.
5.	Recognize and study top sales reps’ approaches - identify what top performers are doing differently and standardize it across the team.





Dashboard Report View
Report View 1 – High Performance
 

Report View 2 – Low Performance
 

 

