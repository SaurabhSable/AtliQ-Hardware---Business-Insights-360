# AtliQ Hardware - Business Insights 360

## 📑 Table of Contents
- Project Overview
- Datasets
- Dashboard Highlights
- Power BI Techniques
- Tools & Technologies
- Business Concepts Learned

## 🌟 Project Overview
AtliQ Hardware, a rapidly expanding global company, sells computers and accessories through retailers, direct sales, and distributors. Despite its growth, the opening of a new store in America led to unexpected losses, highlighting the need for deeper insights.

With competitors using advanced analytics, AtliQ Hardware saw the value of building strong analytics capabilities. The project aimed to support data-driven decisions across finance, sales, marketing, and supply chain functions using Power BI.

I contributed to this project by applying my learnings from the Codebasics Power BI Course, focusing on creating meaningful dashboards and reports.

🔗 **Live Dashboard:** [Business Insights 360](https://app.powerbi.com/view?r=eyJrIjoiMThiMjUzZDAtZTc5NS00ZGIwLWFjZmMtMWYyNzhkMjk1N2YxIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

---

## 📊 Datasets
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

## 🔍 Why Data Modeling?
Data modeling is crucial for building a solid analytical report. It bridges the gap between raw data and valuable insights.

Steps in analysis:
1. **Data Extraction**
2. **Data Cleaning**
3. **Data Modeling** (Key to report performance)
4. **Data Analysis**

This project used a **Snowflake schema** to ensure the dashboard is fast and reliable.

![image](https://github.com/user-attachments/assets/52dd1268-721e-4ec8-a56f-f1fbbe774df3)


---

## 📈 Power BI Dashboard Pages

**The dashboard comprises seven pages**

1. **Home Page:** Navigation hub for the dashboard.

![image](https://github.com/user-attachments/assets/1072be6a-d197-478d-afc2-03223171bad0)


2. **Finance Page:** Supports smart financial decisions for business growth.

- <ins>Profit and Loss Statements:</ins> Shows overall financial performance.
- <ins>Top & Bottom Products by Net Sales:</ins> Highlights most/least profitable products.
- <ins>Top & Bottom Customers by Net Sales:</ins> Identifies key revenue-driving customers.

![image](https://github.com/user-attachments/assets/eb59faf4-4040-41e8-ab68-4e4b2aa5844d)


3. **Sales Page:** Aids in refining sales strategies and maximizing profitability.

- <ins>Customer Performance by Net Sales:</ins> Analyzes sales contributions.
- <ins>Gross Margin & Gross Margin %:</ins> Measures profitability.
- <ins>Additional Sales Metrics:</ins> Uncovers growth opportunities.

![image](https://github.com/user-attachments/assets/1fec7f52-c68b-4e15-a005-e13af99d93ef)


4. **Marketing Page:** Boosts brand visibility and customer engagement.

- <ins>Segment Performance by Gross Margin %:</ins> Evaluates market segment profitability.
- <ins>Segment Performance by Net Profit %:</ins> Assesses net profitability by segment.
- <ins>Additional Marketing Metrics:</ins> Helps refine marketing strategies.

![image](https://github.com/user-attachments/assets/472dada2-123d-472c-8738-a23c4360113a)


5. **Supply Chain Page:** Focuses on inventory management and forecast accuracy.

- <ins>Forecast Accuracy:</ins> Measure the precision of demand forecasting to reduce overstock and stockouts.
- <ins>Net Error Analysis:</ins> Compares forecast vs. actual demand.
- <ins>Additional Supply Chain Metrics:</ins> Streamlines operations.

![image](https://github.com/user-attachments/assets/c5eab4b2-0402-425f-99e2-e6b079c00843)


6. **Executive Page:** High-level view for top management, showing sales, margins, and performance by region and channels.

- <ins>Net Sales:</ins> Quick revenue performance snapshot.
- <ins>Gross Margin % & Net Profit %:</ins> Shows financial health.
- <ins>Revenue by Channel:</ins> Assesses Retail, Direct Sales, and Distributors.
- <ins>Top 5 Customers & Products:</ins> Identifies key growth drivers.
- Supports top management in strategic decision-making.

![image](https://github.com/user-attachments/assets/15098702-5a27-4196-9f71-dae0be4fd3b9)


7. **Products Page:** Assess whether customers in the 'Customer Performance' sales view are meeting the Gross Margin (GM) % target.

- <ins>Overall Market:</ins> Displays top & bottom 5 products by GM% growth.
- <ins>Selected Market:</ins> Shows top & bottom 5 products by GM% growth.

![image](https://github.com/user-attachments/assets/4eafc1f3-237a-42ae-a3af-b492a1bac586)


---

## 🛠️ Power BI Techniques Learned
- Asking critical project questions
- Creating calculated columns and DAX measures
- Data modeling and schema design
- Dynamic visuals and navigation with bookmarks
- Publishing and managing reports in Power BI Service
- Automating data refresh with personal gateways

---

## 🧰 Tools & Technologies
- **Power BI Desktop**: Visualization & reporting
- **SQL**: Data extraction & transformation
- **ETL & Power Query**: Data integration, transformation, and pipeline creation
- **DAX Studio**: Performance optimization
- **Project Charter**: Planning and documentation

---

## 📚 Business Concepts Learned
- Financial Metrics: Gross Margin, Net Profit, COGS, YTD/YTG
- Sales Channels: Direct, Retail, Distributors
- Key Performance Indicators (KPIs) and business terminology

---

## 💬 Feedback
Your thoughts and feedback are welcome! Feel free to connect and share insights to continue the data-driven journey!
