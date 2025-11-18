Superstore Orders Analysis in Excel


Author: Miguel Mora

Tools Used: Microsoft Excel (Tables, PivotTables, PivotCharts, Dashboarding)

Dataset: Superstore-style sales dataset (clean, structured)



📖 Introduction

This project analyzes sales, profit, and shipping performance to identify key operational insights. The goal was to convert a structured dataset into an organized analytical workflow that includes KPI calculation, PivotTable-driven exploration, and an interactive Excel dashboard.
The project demonstrates practical skills in data analysis, business insights, KPI creation, and dashboard design—core abilities for junior data roles.


🧹 Data Preparation

The dataset required minimal cleaning, but several steps were taken to prepare it for analysis:

Converted the raw dataset into a structured Excel Table for better formula handling and PivotTable automation.

Removed the product_name column, as it was not necessary for the KPI and performance analysis.

Created a new calculated field:
=DAYS([@[ship_date]],[@[order_date]])
to evaluate shipping efficiency by mode.

Ensured all date fields were in proper date format to allow grouping by year and month.


📊 Analysis Workflow

Multiple PivotTables and PivotCharts were created and organized in dedicated sheets:

Yearly Analysis: Sales and profit trends over 2011–2014.

Category & Subcategory Analysis: Identification of best and worst performers.

Shipping Mode Analysis: Total orders, sales, profit and average delivery times.

KPI Sheet: Aggregated metrics, including total sales, profit, discount averages, and top/bottom categories.

Finally, all visuals and KPIs were integrated into a clean, interactive dashboard supported by slicers.


📈 Key KPIs

- Total Sales: $12,642,905

- Total Profit: $1,469,035

- Total Orders: 51,290

- Total Quantity Sold: 178,312

- Average Discount: 14.29%

- Average Delivery Time: 3.97 days

- Shipping Speed by Mode:

- First Class: 2.18 days

- Second Class: 3.23 days

- Standard Class: 5.00 days


💡 Insights


1. Category Performance

Top-Selling Category: Technology

Sales: $4.74M

Profit: $663K

Weak Categories:

Tables: –$64,083 profit (significant loss)

Furnishings: $46,000 profit (low performer)

These two categories represent major improvement areas—either pricing, discounting, or sourcing strategies require review.

2. Subcategory Highlights

Best Performer: Copiers

Profit: $258,568

28% of total category profit

Most consistent performers: Phones, Bookcases, and Chairs.

3. Shipping Efficiency

Standard Class accounts for most orders (≈60%), but has the slowest delivery time (5 days).

First Class is significantly faster (2.18 days), suggesting potential value in premium shipping for high-priority segments.

4. Sales Evolution

The highest-performing year was 2014, both in sales ($4.3M) and profit ($504K), showing a steady upward trend across the four-year period.


🧭 Conclusion

This project demonstrates the full lifecycle of an Excel-based analysis:

preparing data using tables and formulas,

calculating KPIs,

building multi-angle analysis sheets with PivotTables,

and creating an interactive dashboard to support decision-making.

The insights reveal profitable areas (Technology, Copiers) as well as critical issues such as the negative profitability of Tables and the weak performance of Furnishings, which are essential findings for any business looking to optimize product strategy.

This Excel project reflects the analytical thinking, attention to detail, and data-driven approach required for junior data analyst roles, while showcasing practical skills in transforming structured data into clear, actionable business intelligence.
