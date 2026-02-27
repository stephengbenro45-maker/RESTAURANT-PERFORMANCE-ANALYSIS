<img width="1274" height="266" alt="image" src="https://github.com/user-attachments/assets/237facbd-2b23-4ca1-9687-36099edea55a" /># RESTAURANT-PERFORMANCE-ANALYSIS
End-to-end SQL &amp; Power BI analysis to identify operational profit leaks and menu efficiency.

Project Overview
I performed an end-to-end analysis of a restaurant’s performance to solve a critical mystery: Why was the restaurant losing money despite high sales and healthy food margins?
    The Data Reality
After digging into the SQL database and building a Power BI dashboard, I discovered a Net Profit Margin of -12%. For every $1 coming in, the business was actually losing 12 cents. To find the "leak," I answered these tough questions:
* Staff Performance: Tracked Staff Names, IDs, and specific quantities sold.
* Labor Efficiency: Calculated Shift Start/End hours to compare labor spend vs. revenue generated.
* Inventory Integrity: Analyzed Opening vs. Closing stock per item to identify consumption and shrinkage.
* Menu Math: Calculated Margin %, ROI, and Total Cost vs. Selling Price for every item.
* Daily Trends: Broke down Revenue per day to identify which dates were "dragging down" the business.  
   Technical Stack & Data    Modeling
* SQL: Used CTEs, Multi-table Joins, and Complex Aggregations to clean and prep the data.
* Power BI & DAX: Built Waterfall charts, Scatter plots, and Treemaps.
* Data Architecture: Implemented a Many-to-One (*) Star Schema. By connecting a central Calendar Dimension to the transactional Sales Fact Table, I enabled seamless time-intelligence reporting.
  The Discovery & Solution
The "leak" wasn't in the kitchen it was operational. Staff Salaries and Electricity were the massive "blocks" eating the profit.
The Recommendations:
1. Optimize Staffing: Align staff hours with high-traffic days identified in the data.
2. Push the "Stars": Promote high-margin items (like Jollof Rice) over high-cost items (like Grilled Fish).
3. Utility Control: Address the electricity "leak" shown in the expense breakdown
