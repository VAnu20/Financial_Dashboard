# Financial_Dashboard

An interactive Power BI Financial Health Dashboard designed to monitor a company’s financial performance. The project focuses on analyzing P&L, cash flow, sales, and budget data to help stakeholders track key financial KPIs, evaluate profitability trends, monitor cash flow, and assess revenue performance across different products and regions.

## Table of Contents
- [Project Overview](#project-overview)
- [Project Objective](#project-objective)
- [Dataset Used](#dataset-used)
- [Tools & Technology Used](#tools-&-technology-used)
- [Technical Implementation](#technical-implementation)
- [Dashboard – Finacial Dashboard](#dashboard-finacial-dashboard)
- [Key Business Insights/Findings](#key-business-insights/findings)
- [Conclusion](#conclusion)

### Project Overview

This project focuses on building an interactive Financial Dashboard using Power BI to monitor the company’s financial health and key performance indicators. The dashboard integrates important datasets such as Profit & Loss (P&L), Cash Flow, Sales Data, Budget vs Actuals, and Receivables & Payables Aging into a single analytical view. With interactive filters and visualizations, the dashboard allows users to analyze financial performance by time period, region, and product category. It helps stakeholders quickly identify trends in revenue, profitability, cash flow, and operational performance to support better financial decision-making.

### Project Objective

The main objective of this project is to design and develop an interactive Power BI dashboard that allows executives and financial analysts to track the company’s monthly financial performance and key KPIs.

- **Key goals of the project include:**

  - Provide a clear overview of financial performance
  - Track Revenue, Gross Margin, EBITDA, and Net Cash
  - Analyze Budget vs Actual financial performance
  - Monitor cash inflows and outflows
  - Identify top-performing products and regions
  - Track receivables and payables aging
  - Enable interactive filtering and drill-down analysis
  
The dashboard helps stakeholders gain clear visibility into financial performance and supports data-driven strategic decisions.

### Dataset Used 

The primary dataset used for this analysis can be found in the files uploaded to this repository.

### Tools & Technology Used

- **Excel:** For ensuring accuracy and consistency in data for reliable analysis.
- **Power BI:** For designing interactive dashboards.
  
  - Power BI 
  - Power Query	(ETL)
  - DAX (Data Analysis Expressions)	
  - Excel

### Technical Implementation

- **Data Extraction & Cleaning (Power Query)**
  - Standardizing date formats for proper time analysis
  - Handling null or missing values in financial records
  - Cleaning product and region naming inconsistencies
  - Structuring the dataset for monthly financial reporting
  
The dataset was prepared using Power Query to ensure data quality and consistency.

- **Data Modeling**
  - Central Calendar Table for time intelligence
  - Financial data tables connected through many-to-one relationships
  - Relationships established between:
     - Calendar Table → Financial Data
     - Product → Sales Data
     - Region → Sales Data
     
A Star Schema Data Model was implemented to optimize performance and usability.
This structure enables efficient filtering, drill-down capabilities, and dynamic analysis.

### Dashboard - Finacial Dashboard

The Financial Dashboard provides a comprehensive view of the company’s financial performance by consolidating key financial metrics such as revenue, profitability, cash flow, and working capital indicators. The dashboard enables stakeholders to monitor business performance and make data-driven financial decisions.

- **Key Insights Provided**

  - Monitoring of Revenue, Gross Margin %, EBITDA %, and Net Cash 
  - Analysis of Revenue and Profit trends over time 
  - Comparison of Budget vs Actual performance
  - Evaluation of product/service 
  - Assessment of cash flow movements 
  - Monitoring of Receivables and Payables Aging

- **Filters Available**

  - Time Period (Month/Quarter/Year)
  - Region filter 
  - Product Category filter
  - Date Range filter 
  
These filters enable users to interactively explore financial performance and perform drill-down analysis from monthly trends to product or regional level insights.

### Key Business Insights/Findings

The dashboard provided several important insights into the company’s financial performance.
- **Revenue & Profitability**
  - Total revenue reached approximately **$24M**
  - The highest monthly revenue occurred in **November 2024 (~$1.13M)**
  - The company maintained a strong **45.5% Gross Margin**
  - EBITDA margin reached approximately **24.8%**

- **Cash Flow & Liquidity**
  - The company maintained a positive **net cash position of approximately $688K**
  - Stable inflows ensured operational liquidity

- **Product Performance**
  - **Product C** emerged as the **top-performing product**
  - It contributed the largest share of total revenue

- **Regional Performance**
  - **East and North regions** generated the highest sales volumes
  - These regions represent key markets for business growth

- **Budget vs Actual Performance**
  - Actual spending was **20–40% lower than budgeted values**
  - This indicates strong cost control but may also require adjustments to budget forecasts

- **Receivables & Payables**
  - Average receivable period: 51–53 days
  - Average payable period: 61 days

Maintaining a longer payable cycle helps optimize working capital management, though aging balances require monitoring.

### Conclusion

I worked on developing an interactive **Financial Health Dashboard in Power BI** for a client of **The Finance Group** to provide a comprehensive financial monitoring solution. By integrating financial dataset into a dashboard, I enabled stakeholders to monitor key financial KPIs, track revenue and profitability trends, analyze cash flow performance, evaluate budget versus actual financial results, and assess working capital efficiency. This project demonstrates how I used data analytics and business intelligence tools to transform raw financial data into actionable insights that support strategic decision-making.
