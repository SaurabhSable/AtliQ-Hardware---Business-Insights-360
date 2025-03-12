# AtliQ Hardware - Business Insights 360

# Table of Contents  
- [Project Overview](#project-overview)  
- [Datasets](#datasets)  
- [Why Data Modeling?](#why-data-modeling)  
- [Power BI Dashboard Pages](#power-bi-dashboard-pages)  
- [Power BI Techniques Learned](#power-bi-techniques-learned)  
- [Tools & Technologies](#tools--technologies)  
- [Business Concepts Learned](#business-concepts-learned)  
- [Feedback](#feedback)  

## Project Overview
AtliQ Hardware, a rapidly expanding global company, sells computers and accessories through retailers, direct sales, and distributors. Despite its growth, the opening of a new store in America led to unexpected losses, highlighting the need for deeper insights.

With competitors using advanced analytics, AtliQ Hardware saw the value of building strong analytics capabilities. The project aimed to support data-driven decisions across finance, sales, marketing, and supply chain functions using Power BI.

I contributed to this project by applying my learnings from the Codebasics Power BI Course, focusing on creating meaningful dashboards and reports.

🔗 **Live Dashboard:** [Business Insights 360](https://app.powerbi.com/view?r=eyJrIjoiNzQ5MGNjZmMtN2Q3NC00NmNlLWFjNmUtZTQ1M2M3MzgzMzQxIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

---

## Datasets
The analysis used two types of tables:

gdb041:
- **Dimension Tables:** Customer, Market, and Product data.

gdb056:
- **Fact Tables:** Sales and forecast data to analyze trends and improve customer satisfaction while reducing storage costs.

### Data Sources
- `dim_customer`, `dim_market`, `dim_product`
- `fact_forecast_monthly`, `fact_sales_monthly`
- Additional tables: `freight_cost`, `gross_price`, `manufacturing_cost`, `pre_invoice_deductions`, `post_invoice_deductions`

---

## Why Data Modeling?
Data modeling is crucial for building a solid analytical report. It bridges the gap between raw data and valuable insights.

Steps in analysis:
1. **Data Extraction**
2. **Data Cleaning**
3. **Data Modeling** (Key to report performance)
4. **Data Analysis**

This project used a **Snowflake schema** to ensure the dashboard is fast and reliable.

![image](https://github.com/user-attachments/assets/52dd1268-721e-4ec8-a56f-f1fbbe774df3)


---

## Power BI Dashboard Pages

**The dashboard comprises seven pages**

1. **Home Page:** Navigation hub for the dashboard.

![image](https://github.com/user-attachments/assets/1072be6a-d197-478d-afc2-03223171bad0)


2. **Finance Page:** Supports smart financial decisions for business growth.

- <ins>Profit and Loss Statements:</ins> Shows overall financial performance.
- <ins>Top & Bottom Products by Net Sales:</ins> Highlights most/least profitable products.
- <ins>Top & Bottom Customers by Net Sales:</ins> Identifies key revenue-driving customers.

![image](https://github.com/user-attachments/assets/fbacddb3-0229-4286-a05d-5e1a8738e24d)


3. **Sales Page:** Aids in refining sales strategies and maximizing profitability.

- <ins>Customer Performance by Net Sales:</ins> Analyzes sales contributions.
- <ins>Gross Margin & Gross Margin %:</ins> Measures profitability.
- <ins>Additional Sales Metrics:</ins> Uncovers growth opportunities.

![image](https://github.com/user-attachments/assets/1c87c9b3-7eca-4a5a-a774-98d1d3656e74)


4. **Marketing Page:** Boosts brand visibility and customer engagement.

- <ins>Segment Performance by Gross Margin %:</ins> Evaluates market segment profitability.
- <ins>Segment Performance by Net Profit %:</ins> Assesses net profitability by segment.
- <ins>Additional Marketing Metrics:</ins> Helps refine marketing strategies.

![image](https://github.com/user-attachments/assets/09d4b7ed-1b9a-4991-8e17-a90af85f2817)


5. **Supply Chain Page:** Focuses on inventory management and forecast accuracy.

- <ins>Forecast Accuracy:</ins> Measure the precision of demand forecasting to reduce overstock and stockouts.
- <ins>Net Error Analysis:</ins> Compares forecast vs. actual demand.
- <ins>Additional Supply Chain Metrics:</ins> Streamlines operations.

![image](https://github.com/user-attachments/assets/ce06d69a-0033-4ca0-b1f8-ac89bbd4d908)


6. **Executive Page:** High-level view for top management, showing sales, margins, and performance by region and channels.

- <ins>Net Sales:</ins> Quick revenue performance snapshot.
- <ins>Gross Margin % & Net Profit %:</ins> Shows financial health.
- <ins>Revenue by Channel:</ins> Assesses Retail, Direct Sales, and Distributors.
- <ins>Top 5 Customers & Products:</ins> Identifies key growth drivers.
- Supports top management in strategic decision-making.

![image](https://github.com/user-attachments/assets/c7b47007-2d03-4ecd-be15-9644ac9ef48d)


7. **Products Page:** Assess whether customers in the 'Customer Performance' sales view are meeting the Gross Margin (GM) % target.

- <ins>Overall Market:</ins> Displays top & bottom 5 products by GM% growth.
- <ins>Selected Market:</ins> Shows top & bottom 5 products by GM% growth.

![image](https://github.com/user-attachments/assets/3db97e7b-c077-4b5a-aa9f-87b85db998d4)


---

## Power BI Techniques Learned
- Asking critical project questions
- Creating calculated columns and DAX measures
- Data modeling and schema design
- Dynamic visuals and navigation with bookmarks
- Publishing and managing reports in Power BI Service
- Automating data refresh with personal gateways

---

## Tools & Technologies
- **Power BI Desktop**: Visualization & reporting
- **SQL**: Data extraction & transformation
- **ETL & Power Query**: Data integration, transformation, and pipeline creation
- **DAX Studio**: Performance optimization
- **Project Charter**: Planning and documentation

---

## Business Concepts Learned
- Financial Metrics: Gross Margin, Net Profit, COGS, YTD/YTG
- Sales Channels: Direct, Retail, Distributors
- Key Performance Indicators (KPIs) and business terminology

---

## Feedback
Your thoughts and feedback are welcome! Feel free to connect and share insights to continue the data-driven journey!
