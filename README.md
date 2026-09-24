# Madhav-ecommerce-sales-analysis
# Madhav E-commerce Sales Dashboard 

## Project Overview
This project delivers an interactive e-commerce sales and profitability dashboard built in **Power BI** for **Madhav Store**. The primary objective is to track, analyze, and visualize online sales performance across India to help stakeholders understand revenue, profit trends, and customer buying behavior[cite: 5, 7].

## Dashboard Preview
![Madhav E-commerce Dashboard](Dashboard/Screenshot.png)

## Data Architecture & Structure
The project utilizes raw data sourced from Excel and structured across two primary relational tables linked via **Order ID**:
* **Orders Table:** Contains transactional meta-data including Order ID, Order Date, Customer Name, State, and City.
* **Details Table:** Contains financial and product metrics including Amount, Profit, Quantity, Category, Sub-Category, and Payment Mode.

## Key Features & Methodology
* **Data Modeling & Relationships:** Connected multi-table worksheets from Excel into a relational data model in Power BI, writing calculated measures to manipulate raw data for visualization[cite: 6].
* **Interactive Filtering:** Built dynamic parameters using quarter buttons (`Qtr 1` - `Qtr 4`) and a `State` filter to allow user-driven exploration[cite: 4, 6].
* **Visualizations Included:**
  * **KPI Summary Cards:** Total Amount ($438\text{K}$), Quantity ($6\text{K}$), Profit ($37\text{K}$), and AOV ($121\text{K}$)[cite: 4].
  * **Geographic Performance:** High-performing states (Maharashtra, Madhya Pradesh, Uttar Pradesh, Delhi)[cite: 4].
  * **Payment Preferences:** Donut chart breakdown of payment modes (COD, UPI, Debit Card, Credit Card, EMI)[cite: 4].
  * **Profitability Analysis:** Monthly profit trends and sub-category performance (Printers, Bookcases, Saree, etc.)[cite: 4].

## Project Learnings
* Designed and formatted a corporate-grade dark-themed dashboard layout for executive reporting.
* Handled multi-table relational modeling and DAX measures using Power BI.
* Implemented advanced visual variety including bar charts, donut charts, monthly trend lines, and interactive slicers[cite: 6].

## Project Links
* **Repository & Code:** [GitHub Repository](https://github.com/Abhishekjha-90/madhav-ecommerce-sales-analysis)
* **Power BI / Dataset Files:** [Dashboard Folder](https://github.com/Abhishekjha-90/madhav-ecommerce-sales-analysis/tree/main/Dashboard)
