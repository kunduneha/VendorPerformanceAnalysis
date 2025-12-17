# VendorPerformanceAnalysis
**Vendor Performance Analysis**

Data-Driven Insights for Procurement Optimisation & Profitability Enhancement

**Project Overview**

This project delivers a **comprehensive vendor performance evaluation** using transactional sales, purchase, and inventory data to support **strategic procurement decisions, cost optimisation, and profitability improvement**.

**The analysis integrates exploratory data analysis (EDA), statistical testing, and business intelligence techniques to identify:**

- Vendor concentration risks
- High-margin but underperforming brands
- Inventory inefficiencies
- Cost advantages of bulk purchasing

The outcomes are designed to be **actionable for procurement managers, finance teams, and senior stakeholders.**

**Business Objectives**

- Evaluate vendor contribution to overall sales and profitability
- Identify over-dependence on top vendors
- Detect low-sales but high-margin brands for growth opportunities
- Assess inventory turnover and unsold stock risks
- Quantify the financial impact of bulk purchasing strategies

**Datasets Used**

The project uses multiple transactional datasets covering inventory, purchasing, pricing, and sales. 
**Dataset Access (Large Files)**
Due to GitHub file size limitations, the complete raw datasets used in this analysis are hosted externally. 
https://drive.google.com/drive/folders/1nHNVskMAbPeucirnb_XW3z3LC9WXQAw6?usp=drive_link

**Tools & Technologies**

- Python (Pandas, NumPy)
- **Data Visualisation**: Matplotlib, Seaborn
- **Statistical Analysis**: Confidence Intervals, Hypothesis Testing
- **Jupyter Notebook**
- SQL (SQLite) for data extraction & aggregation

**Analytical Workflow**

**Data Extraction & Cleaning**

- Merged multi-source transactional data
- Handled missing values and data inconsistencies
- Created analytical aggregates at vendor and brand levels

**Exploratory Data Analysis**

- Distribution analysis of prices, volumes, and sales
- Vendor and brand concentration assessment
- Identification of outliers and skewness patterns

**Vendor Performance Evaluation**

- Sales contribution analysis
- Profit margin computation
- Vendor ranking by revenue and volume

**Statistical Analysis**

- Confidence interval estimation for pricing
- Hypothesis testing to validate bulk purchase cost benefits

**Visualization & Reporting**

- Business-focused plots saved programmatically
- Executive-ready PDF reports generated

**Key Insights**

**Vendor Concentration Risk:**

The top 10 vendors contribute approximately **65.7%** of total sales, indicating significant dependency risk.

**High-Margin, Low-Sales Brands Identified:**

Several brands show strong profit margins but weak sales volumes, representing targeted marketing and distribution opportunities.

**Bulk Purchasing Advantage Confirmed:**

Statistical testing confirms that larger purchase quantities significantly reduce unit costs, supporting volume-based procurement strategies.

**Inventory Inefficiencies Detected:**

High unsold inventory value highlights opportunities for demand forecasting improvement and inventory rationalisation.

**Visualisations Generated**

- Vendor sales contribution charts
- Purchase vs sales price distributions
- Inventory movement analysis
- Profit margin comparisons
- Confidence interval visualisations

**Future Enhancements**

- Vendor risk scoring model
- Time-series demand forecasting
- Automated ETL pipeline
- Power BI / Tableau dashboard integration
- Supplier performance benchmarking framework

**Power BI Dashboard Development**

The vendor performance insights were operationalised using Power BI to build an interactive, decision-focused dashboard designed for procurement and business stakeholders.

**Key Power BI Activities**

- Designed an **end-to-end Power BI dashboard** to analyse vendor and brand performance across sales, purchases, margins, and inventory metrics.
- Built a **clean data model** by importing and transforming curated datasets and defining relationships to support accurate aggregation and filtering.
  
- Created **DAX measures** to calculate key KPIs, including:
- Total Sales & Total Purchase Value
- Purchase Contribution (%)
- Vendor & Brand-level performance indicators
- Identification of low-performing and high-margin underperforming vendors

- Developed **interactive visuals** such as:
- KPI cards for high-level business metrics
- Bar charts for top and low-performing vendors/brands
- Donut charts to analyse purchase contribution concentration
- Scatter plots to highlight margin vs sales patterns and growth opportunities

- Implemented **slicers and filters** to enable dynamic exploration by vendor, brand, and performance segments.
- Structured the dashboard to support executive-level insights, focusing on vendor concentration risk, procurement efficiency, and profitability optimisation.

Due to Power BI Service tenant restrictions, public web embedding is disabled.
The repository includes dashboard screenshots and the PBIX file for local exploration.

**Business Impact**

- Enabled data-driven vendor evaluation rather than intuition-based procurement decisions
- Highlighted vendor concentration risks and over-dependence on top suppliers
- Identified high-margin but underperforming brands for targeted growth strategies
- Supported cost-optimisation analysis through purchase contribution and volume insights
