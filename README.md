# E.com-Express_Dashboard
EcomExpress Sales Performance Dashboard
An interactive Power BI dashboard to monitor end‑to‑end ecommerce performance for EcomExpress, with a focus on revenue, cancellations, and regional trends.
​

Short description / purpose
The EcomExpress Sales Performance Dashboard provides a single view of total sales, realized revenue, and revenue lost due to order cancellations across India. It helps business teams quickly identify high‑value products, top‑performing states, and categories driving overall growth while tracking cancellation rate over time.
​

Tech stack
Power BI Desktop – Main platform for data modeling and visualization of ecommerce metrics.

Power Query – Used for cleaning, transforming, and shaping raw order and cancellation data before loading into the model.
​

DAX – Custom measures for KPIs such as Total Sales, Total Revenue, Lost by Cancellation, and Cancellation Rate.

Data Modeling – Star-schema style relationships between fact tables (orders, cancellations) and dimension tables (date, product, category, state).

File formats – .pbix for the report file and .png/.jpg for dashboard preview screenshots.

Data source
Order‑level transaction data from the EcomExpress ecommerce platform, including order value, cancellation status, product details, category, and shipping state.

Date dimension storing calendar attributes (day, month, year, quarter) to support time‑series analysis and quarter‑wise revenue trends.
​

Features and highlights
Business problem
EcomExpress needs a clear way to track how much revenue is generated versus how much is lost due to cancellations, and to understand which products, categories, and regions contribute most to performance. Raw transactional tables make it difficult for business users to monitor KPIs or drill down by product and geography.
​

Goal of the dashboard
The goal is to deliver an easy‑to‑use visual tool that summarizes ecommerce KPIs, highlights revenue leaders, and surfaces cancellation impact at a glance. The dashboard supports data‑driven decisions around assortment planning, regional strategy, and operational improvements to reduce cancellations.
​

Walkthrough of key visuals

KPI cards (left panel):

Total_Sales

Total_Revenue

Lost_byCancellation

Cancellation_Rate (shown twice for emphasis and cross‑validation)
These cards instantly communicate overall business health for the selected date range.

Revenue by Product Name (bottom‑left):
Horizontal bar chart listing top products such as MacBook Air, OnePlus 9, Sony Headphones, HP Pavilion, Samsung Galaxy, Dell XPS 13, Apple Watch, Mi Charger, Logitech Mouse, Bose Speaker, iPhone 13, and Realme Cable. This helps identify star products and long‑tail items.

Revenue by State (top‑middle):
Bar chart comparing revenue from major states like Maharashtra, Gujarat, Rajasthan, West Bengal, Tamil Nadu, Karnataka, Delhi, and Telangana, enabling regional performance benchmarking and channel targeting.

Revenue by Category (top‑right):
Bar chart showing revenue split across categories such as Laptop, Mobile, Headphones, Tablet, Accessory, Charger, Mouse, Speaker, and Cable. This is useful for category managers to track mix and growth.

Revenue by Year and Quarter (bottom‑right):
Line chart plotting revenue across key quarters (Jan 2024, Apr 2024, Jul 2024, Oct 2024), making it easy to spot seasonality, growth peaks, or dips over time.

Category navigation buttons (top ribbon):
Button‑style slicers for Accessory, Cable, Charger, Headphones, Laptop, Mobile, Mouse, Speaker, and Tablet to filter the entire report by selected segment and analyze category‑specific trends.

Date range slicer (bottom‑left):
A date slider from 01‑01‑2024 to 06‑11‑2024 allows users to dynamically change the analysis window and instantly refresh all visuals and KPIs.

Business impact & insights

Enables management to see which products and categories drive the bulk of revenue and which states underperform, guiding targeted marketing and inventory allocation.

Quantifies revenue leakage due to cancellations and supports initiatives to improve fulfillment, returns handling, or customer communication.

Helps track quarter‑wise performance so leaders can evaluate the effect of campaigns, sale events, and operational changes on revenue and cancellation behavior.


Screenshots / demo
Show what the dashboard looks like. - [Alt text](https://github.com/username/repo/assets/image.png)
[Dashboard Preview](https://github.com/devkumar90/E.com-Express_Dashboard/blob/main/Screenshot%20Visualization.png)
