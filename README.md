# Tableau Superstore Dashboard

This project features an **interactive Tableau dashboard** created using the **Sample Superstore** dataset. It allows users to analyze key business metrics such as Sales, Profit, and Order Volume across different regions, years, and product categories.

---

## 📌 Project Objective

To build a visually appealing and interactive dashboard using Tableau that allows stakeholders to monitor key performance metrics and derive actionable insights for improving profitability and operational efficiency.

---

## ❓ Business Questions Answered

- Which are the top 5 products based on Sales, Profit, and Order Volume?
- What are the sales and profit trends across categories and sub-categories?
- How do different regions and years compare in terms of performance?
- What is the return rate, and where is it highest?
- How can the business identify areas for growth and reduce low-profit products?

---

## 🛠️ Process Overview

1. Imported the **Sample Superstore** dataset into Tableau.
2. Created calculated fields:
   - **Profit Margin = SUM(Profit) / SUM(Sales)**
   - **Return Rate = SUM(Quantity Returned) / SUM(Quantity Ordered)**
3. Used **parameter controls** to allow dynamic switching between Sales, Profit, and Order KPIs.
4. Designed **Top 5 Product charts** using INDEX() filtering.
5. Applied **filter actions** across visuals and added interactive slicers for Region and Year.
6. Used **containers and toggle buttons** to organize layout and provide a hide/show filter option.

---

## 📊 Dashboard Features

- **Left Panel**:
  - Company logo
  - Region and Year filters
  - Toggle button to hide/show filters

- **Main Dashboard**:
  - 3 KPI cards: Total Sales, Profit Margin, Return Rate
  - Interactive charts:
    - Sales/Profit/Orders by Category (clickable)
    - Trends by Year, Region, Sub-Category
    - Top 5 Products (always visible regardless of filter)
  - Parameter selector for switching KPI across all charts

---

## ✅ Insights and Conclusion

After going through the dashboard and analyzing the data from the Superstore dataset, a few clear patterns stood out that could help the business make better decisions:

1. **High sales don’t always mean high profits**  
   Some sub-categories—like Tables—are pulling in strong sales numbers, but when you look at the profit margin, they’re either very low or even negative. This could mean that products are being sold at a discount too often, or that the cost to deliver them is too high. It's worth reviewing the pricing strategy or supplier costs for these items.

2. **Technology seems to be the most profitable category**  
   Products like Phones and Accessories aren’t just selling well—they’re also bringing in a solid profit margin. These could be strong candidates for targeted promotions, bundles, or upselling strategies.

3. **Regional performance isn’t consistent**  
   The West and East regions are doing well overall, but the South and Central regions are trailing behind in both profit and return metrics. It may help to dig deeper into customer behavior or shipping issues in these regions to figure out why performance is lagging.

4. **Returns are concentrated in certain product types**  
   Items like Chairs and Tables show higher return rates, which might point to quality concerns or mismatched expectations. Looking into product feedback or delivery conditions could reduce return costs and improve the customer experience.

5. **Top-selling products aren’t always the most valuable**  
   Some products appear in the top 5 for sales but don’t show up when sorted by profit. That suggests the company may want to re-balance their focus—either by improving margins on high-volume items or pushing products that already have better returns.

6. **Profit margins vary from year to year**  
   The data shows some fluctuation in profit margins over time. This could be tied to market conditions, seasonal shifts, or internal cost controls. Consistent tracking and forecasting would help stabilize profitability.

---

## 📁 Files in This Repo

- `https://github.com/DatawithSandhra/Analytics_report/blob/main/Tableau_assign_github.twbx` – Tableau workbook
- `` – Original brief and requirements
- `dashboard_preview.png` – Optional screenshot (add if available)

---

📌 *Created by Sandhra Maria Mathew for portfolio and learning purposes.*
