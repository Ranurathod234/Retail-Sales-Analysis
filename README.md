# 📊 Retail Sales Dashboard (Excel / Power BI)

## Problems and Background
The retail industry thrives on data, yet many organizations fail to fully leverage it for decision-making.  
Our company’s historical sales data presents an opportunity to uncover insights that can improve revenue growth, cost management, and customer retention.  

### Key challenges observed
- **Lack of Visibility:** Sales performance across categories, segments, and regions is scattered, making it hard to align strategies.  
- **Profitability Concerns:** Discounts, returns, and shipping inefficiencies reduce margins despite steady sales.  
- **Customer Behavior Gaps:** Heavy reliance on a small set of customers creates risk, while repeat purchase behavior is not well understood.  
- **Operational Inefficiency:** Delivery durations and high shipping costs in certain states highlight logistics challenges.  
- **Data Fragmentation:** Without a unified dashboard, stakeholders rely on siloed reports, slowing decision-making.  

The problem is not just analyzing sales figures, but transforming them into actionable insights that guide leadership, sales managers, finance teams, and marketing toward smarter, data-driven strategies.  

---
<details>
  <summary>📊 Overview </summary>

  ![Dashboard 1](https://res.cloudinary.com/dzz2nken6/image/upload/v1755945711/Sales_Dashboard_page-0001_deplvr.jpg)

</details>

<details>
  <summary>📊 Sales Analytics </summary>

  ![Dashboard 2](https://res.cloudinary.com/dzz2nken6/image/upload/v1755945763/Sales_Dashboard_page-0002_ooufif.jpg)

</details>

<details>
  <summary>📊 Return Analytics </summary>

  ![Dashboard 3](https://res.cloudinary.com/dzz2nken6/image/upload/v1755444118/Sales_Dashboard_page-0003_agoop5.jpg)

</details>

<details>
  <summary>📊 Shipping Efficiency </summary>

  ![Dashboard 4](https://res.cloudinary.com/dzz2nken6/image/upload/v1755444117/Sales_Dashboard_page-0004_aync2c.jpg)

</details>

<details>
  <summary>📊 Customer Insights</summary>

  ![Dashboard 5](https://res.cloudinary.com/dzz2nken6/image/upload/v1755444119/Sales_Dashboard_page-0005_qiprv8.jpg)

</details>

**Live dashboard:** [Power BI Report Link](https://app.powerbi.com/view?r=eyJrIjoiYjhmOTc1MTQtNTFjZC00ZjEzLTg0MDItZmQwYmEwMTkwNWQ3IiwidCI6IjU5NTk0MTdlLTBlOTEtNDdkMi1iYmNiLTkyZjdjZDEwNmNiYyJ9&pageName=ad03817960aa16440e03&utm_source=chatgpt.com)  

---

## Solution
- Collect and clean sales, returns, and shipping data for accuracy.  
- Define key KPIs: Total Sales, Gross Profit, Return Rate, Average Delivery Duration, Average Order Value, Customer Lifetime Value (CLV).  
- Create interactive dashboards in Excel and Power BI with slicers, drill-downs, and comparative visuals.  
- Analyze sales trends, category performance, return behavior, and logistics costs.  
- Apply business concepts such as Pareto Principle (80/20), customer segmentation, and profitability analysis.  
- Provide stakeholders with narrative insights and recommendations for profitability, retention, and operational efficiency.  

---

## Project Scope

### Objective
To analyze historical sales data and design a retail dashboard that identifies revenue drivers, profitability risks, and customer insights.  

### Process
- Data collection, cleaning & preparation.  
- KPI selection and metric design.  
- Dashboard development (Excel → Power BI).  
- Insight generation and storytelling.  
- Documentation and final presentation.  

---

## Data Collection
- **Source:** Public dataset from Kaggle (Retail Sales, Returns, and Shipping) – [Dataset Link](https://www.kaggle.com/datasets/kunalmalviya06/retail-sales-returns-and-shipping-dataset)  
- **Files Used:** Orders, Returns, and Shipping datasets covering product categories, customer information, regional sales, and delivery details.  
- **Scope of Data:** 4 years of transactions, 10K+ rows across different regions and customer segments.  

---

## Data Cleaning
1. **Handling Missing & Invalid Values**  
   - Filled missing delivery durations using median values.  
   - Removed rows with incomplete transaction IDs or customer IDs.  
2. **Standardization**  
   - Converted date columns to a consistent `YYYY-MM-DD` format.  
   - Standardized categorical labels (e.g., "CA" → "California").  
3. **Deduplication**  
   - Removed duplicate sales and return entries to avoid double-counting.  

---

## Data Preparation
1. **Integration:** Merged Orders, Returns, and Shipping datasets into a single relational model.  
2. **Feature Engineering:** Created calculated fields for Profit Margin %, Return Rate, Avg. Shipping Cost, and Customer Lifetime Value (CLV).  
3. **Pre-Aggregation:** Built PivotTables and summary tables to validate numbers before importing into Power BI.  

---

## Stakeholders
- **Executives (CXOs):** Strategic alignment.  
- **Sales Managers:** Product and regional performance.  
- **Finance:** Profitability, discounts, returns.  
- **Logistics:** Shipping cost & delivery duration.  
- **Marketing:** Customer segmentation and retention insights.  

---

## Methodology
- **Data Modeling:** Integration of Orders, Returns, and Shipping datasets.  
- **Data Cleaning:** Removal of duplicates, handling null values, and standardizing date formats.  
- **Analytics:** Created calculated fields (DAX/Excel formulas) for KPIs.  
- **Visualization:** Used Power BI and Excel to design interactive visuals (bar charts, matrices, trend lines, Pareto analysis).  
- **Iterative Review:** Regular reviews ensured alignment with stakeholder needs.  

---

## Goals and KPIs
- **Revenue Growth:** Total Sales ($2.3M).  
- **Profitability:** Gross Profit ($286.4K), Profit Margin %.  
- **Efficiency:** Average Delivery Duration (3.96 days), Avg. Shipping Cost per Order ($45.05).  
- **Returns Management:** Return Rate (15.97%), Sales Lost to Returns ($180.5K).  
- **Customer Value:** CLV (if calculable), Sales by Segment & Region, Top 20% Customer Contribution.  

---

## Technical Processes
- **Tools:** Excel, Power BI, DAX, PivotTables.  
- **Features:** Drill-down reports, dynamic slicers, KPI cards, trend analysis.  
- **Datasets:** Orders, Returns, Shipping Cost.  
- **Outputs:** 5-page dashboard covering Overview, Sales Analytics, Return Analytics, Shipping Efficiency, and Customer Insights.  

---

## Business Concepts Used
- **Pareto Analysis (80/20 Rule):** The Top 20% customers contribute the majority of sales.  
- **Customer Segmentation:** Consumer, Corporate, and Home Office are analyzed separately.  
- **Return Analysis:** Linking categories/products with profitability erosion.  
- **Discount Analysis:** Impact of discounts on margin and revenue leakage.  
- **Operational Efficiency:** Shipping cost and delivery time optimization.  

---

## Recommended Analysis
- **Sales:** Technology ($836K) leads sales, but Furniture and Office Supplies are close contributors. Balanced strategy needed.  
- **Returns:** 800 total returns, concentrated in California & New York, with furniture driving losses. Targeted return-reduction required.  
- **Shipping:** California incurred $54K shipping costs, mostly Standard Class. Opportunity to renegotiate logistics contracts.  
- **Customers:** Top 20% customers drive >70% sales. Repeat purchases are low, requiring loyalty campaigns.  
- **Profitability:** Aggressive discounting and high returns dilute profit margins; focus should shift from volume to margin optimization.  

---

## Conclusion
This project demonstrates how sales data, when structured into a unified dashboard, can transform raw transactions into an actionable strategy.  
Key challenges such as returns, discounting, and shipping costs must be tackled to protect margins.  
Customer retention emerges as a critical growth lever, as dependence on a small customer base creates risk.  

By equipping stakeholders with interactive dashboards and clear insights, the business is better positioned to make data-driven decisions that enhance profitability, improve customer experience, and streamline operations.  


