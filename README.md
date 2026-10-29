Data Technician Bootcamp: Excel Data Analysis Portfolio

This repository contains data analysis workbooks, pivot tables, and automated models developed during Week 1 of the Data Technician Bootcamp. The project demonstrates end-to-end data manipulation—from embedding strict UK/EU data governance frameworks to handling, aggregating, and visualizing complex retail datasets.

🛠️ Skills & Functions Demonstrated

• Logical & Conditional Functions: SWITCH (advanced multi-conditional routing), IF.
• Data Aggregation: SUM, SUMIF, AVERAGE, AVERAGEIF.
• Lookup & Data Extraction: VLOOKUP, UNIQUE, DATE, MONTH, YEAR.
• Data Structuring: Sorting, advanced filtering, multi-layered PivotTables, and cross-report Slicers.
• Data Visualization: Interactive PivotCharts, dynamic sales dashboards, and automated conditional formatting.

📁 Repository Structure

⚖️ 1. Data Governance & Compliance

Before working with live production data, a deep-dive analysis into data privacy regulations was conducted to build a "Privacy by Design" framework. This section reviews impacts, breach consequences, and real-world compliance workflows for:
• UK Data Protection Act (DPA 2018) & UK GDPR
• EU GDPR (Ensuring user tracking consent and data-portability rights)
• Freedom of Information Act (FOI) (Meticulous data indexing and legal redactions)
• Computer Misuse Act (Role-based access control and system boundaries)

🛒 2. Retail Sales Performance Analysis

Analyzed a comprehensive retail dataset (retail-sales_dataset.xlsx) to evaluate store performance, revenue metrics, and employee commission tiers.
• Commission Modeling: Calculated absolute totals and targeted averages using SUM and AVERAGE functions.
• Demographic Segmentation: Sorted and filtered transactional records by gender, age groups, and product categories to uncover underlying purchase patterns.
• Interactive Insights: Built dynamic sales charts paired with visual Slicers to allow users to instantly filter performance metrics by demographic attributes.

🚲 3. Global Bike Sales & Regional Markets

Constructed advanced analytical models using multi-national sales data to isolate target demographics and profitability hubs.
• Regional Demographics: isolated consumer distributions (e.g., mapping specific age bands across international markets like Germany).
• Multi-Market Audits: Tracked product shipping across global distribution vectors to identify universal market segments (e.g., pinning down full-market operational data for the United States).
• Profitability Matrices: Grouped nested data by Country, Gender, and Age Group to pinpoint peak revenue generators (e.g., segmenting high-value female adult spend categories).

🔄 4. Automated Volume Categorization

Modeled English county sales data using programmatic logic to dynamically classify performance tiers without manual overhead.
• Pivot Summarization: Built a cross-tabulated PivotTable analyzing Sales Volume with Counties in rows and Product Types in columns.
• SWITCH Logical Engine: Implemented a SWITCH(TRUE, ...) evaluation matrix to automate real-time status tagging based on transaction volumes:excel
=SWITCH(TRUE, C2 > 600, "High", C2 >= 300, "Medium", "Low")

📊 Sample Datasets Processed

• retail-sales_dataset.xlsx (Retail transactions, age groups, and commissions)
• Bike_Sales_Pivot_Lab.xlsx (Global demographic and international revenue data)
• Bike_Sales_Visualizations_Lab.xlsx (Dashboard wireframes and custom charting)
• County_Sales_Performance (Regional UK hardware and tech volume distributions)

