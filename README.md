# End-to-End B2B Sales Pipeline & Conversion Dashboard

End-to-End B2B Sales Pipeline and Conversion Dashboard using SQL and Power BI.

## 🎯 Project Objective
This project demonstrates a complete data analytics lifecycle designed to optimize B2B sales operations. By extracting and modeling raw Customer Relationship Management (CRM) data, this analysis provides actionable business intelligence regarding sales funnels, lead conversion rates, agent performance, and quarterly revenue forecasting. 

The goal is to translate complex pipeline datasets into strategic insights that empower sales managers to identify high-value prospects, streamline acquisition cycles, and exceed revenue targets.

## 🛠️ Tools & Technologies
*   **Database Management & ETL:** SQL (MySQL)
*   **Data Visualization & Modeling:** Microsoft Power BI, DAX
*   **Data Preparation:** Python (Pandas), Jupyter Notebooks
*   **Data Sources:** Raw CSV extracts (Accounts, Products, Sales Teams, Sales Pipeline)

## 📂 Repository Structure
*   `1. Data Preparation/`: Contains the raw CSV datasets and the Jupyter Notebook used for initial data cleaning, transformation, and formatting.
*   `2. Data Modelling/`: Includes the `db_creation_crm_sales.sql` script to generate the relational database schema (star schema) and load the cleaned data into fact and dimension tables.
*   `3. Data Analysis/`: Contains the `db_analysis.sql` script featuring advanced SQL queries (CTEs, Window Functions, Aggregations) used to extract initial business insights.
*   `4. Report Creation/`: Houses the final `CRM_sales_report.pbix` Power BI file and a PDF export of the interactive dashboard.

## 📊 Key Business Questions Answered
The SQL analysis and Power BI dashboard address the following critical sales metrics:
1.  **Sales Team Performance:** Which regional offices and individual agents have the highest success rates and generate the most revenue?
2.  **Quarterly Trends:** What is the Quarter-over-Quarter (QoQ) growth in won opportunities and overall sales volume?
3.  **Product Success Rates:** Which product series drive the highest conversion rates, and how do average sales prices compare to suggested retail prices?
4.  **Market Reach & Sector Performance:** Which industries yield the highest win rates, and what is the distribution of active pipeline stages (Prospecting vs. Engaging)?
5.  **Sales Cycle Duration:** What is the average time required to close a won deal versus a lost deal, broken down by product and sector?

## 🚀 How to Run This Project
1.  Clone this repository to your local machine.
2.  Run the `db_creation_crm_sales.sql` script in your SQL environment to build the database and import the CSV files.
3.  Execute `db_analysis.sql` to view the raw data insights.
4.  Open `CRM_sales_report.pbix` in Power BI Desktop to interact with the visualizations and explore the data model.

---
