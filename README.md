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
<img width="1024" height="680" alt="image" src="https://github.com/user-attachments/assets/3f24ca63-f4ad-4979-91a0-25cb3782294a" />

 Visual Dashboard Overview: Q2 Sales by Category & Gender

This sheet showcases a dynamic, interactive retail sales dashboard that connects multi-dimensional transaction data to clean visual reporting assets:
• Interactive Slicers: Connected Product Category, Gender, and Total Sales slicers as operational cross-filters for real-time data drilling.
• Cross-Tabulated Summaries: Built a secondary PivotTable mapping transaction trends across gender divisions, isolating Clothing as the primary performance driver over Beauty and Electronics.
• Clustered PivotCharts: Tied the filtered sub-totals directly to a data-labeled Clustered Column Chart, allowing stakeholders to instantly compare multi-product retail distribution across target demographics.
• Consolidated Reporting: Factored data-cleaning methodologies into a bottom-line summary layout, validating a macro dataset pool totaling 456,000 in total historical sales.

• Bike_Sales_Pivot_Lab.xlsx (Global demographic and international revenue data)
<img width="1106" height="438" alt="Screenshot 2026-10-29 at 11 32 48" src="https://github.com/user-attachments/assets/c9075c41-c207-4ac2-a89c-fc8944d87807" />
<img width="332" height="298" alt="Screenshot 2026-10-29 at 11 31 29" src="https://github.com/user-attachments/assets/15da44e4-0cc4-4713-97cf-3245e868d5ca" />

🚴 Visual Dashboard Overview: Regional Bike Sales & Profitability Analysis

This sheet showcases a comprehensive, cross-tabulated profitability model tracking international bike sales across diverse consumer demographics and regional markets:
• Multi-Dimensional Profit Metrics: Built a robust PivotTable analyzing profit distributions by Country, nested by Customer Gender and cross-referenced against core Age Groups.
• Demographic Insights: Isolates key profitability hubs, highlighting Adults (35-64) in the United States as a massive revenue generator, yielding $46,734.00 in total profit.
• Clustered PivotCharts: Dynamically mapped demographic profit breakdowns directly onto a data-labeled Clustered Column Chart, allowing stakeholders to instantly compare market margins across the three critical age segments (Adults, Young Adults, and Youth).
• Consolidated Reporting Matrix: Successfully audited and organized macro transactional records to validate a global bottom-line profit pool totaling $163,508.00 across 187 major transactions.

• Bike_Sales_Visualizations_Lab.xlsx (Dashboard wireframes and custom charting)
• County_Sales_Performance (Regional UK hardware and tech volume distributions)

