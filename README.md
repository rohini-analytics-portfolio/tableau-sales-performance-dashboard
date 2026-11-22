# Sales Performance Dashboard | Tableau

**🌟 Project Overview**

The Sales Performance Dashboard is a Tableau data analytics project designed to evaluate sales revenue, profitability, order quantity, product subcategory performance, and weekly business trends across multiple years.

The dashboard transforms raw retail transaction data into an interactive executive report that helps users monitor year-over-year (YoY) growth, compare current performance against the previous year (PY), identify top-performing subcategories, and track weekly sales and profit fluctuations[cite: 10].

An interactive collapsible filter panel allows users to slice the dashboard by `Select Year`, `Category`, and `Sub-Category`, making it easy to drill down into specific timeframes and product segments[cite: 10].

**📊 Business Problem**

Retail businesses need clear visibility into how total sales, profit, and unit volume compare against the previous year, which product subcategories drive revenue versus profit, and how performance fluctuates week over week[cite: 10].

Reviewing raw order records manually makes it difficult to spot monthly inflection points, identify unprofitable subcategories, or monitor weekly trends against average benchmarks[cite: 10].

This project addresses that challenge by consolidating year-over-year KPI sparklines, subcategory comparisons, and weekly step-line charts into a single interactive Tableau dashboard[cite: 10].

**🎯 Key Objectives**

1. Monitor overall sales, profit, and quantity performance alongside Previous Year (PY) comparisons and monthly trend sparklines (`Jan`–`Dec`).
2. Compare sales and profit performance across product subcategories (`Chairs`, `Phones`, `Storage`, `Accessories`, `Tables`, `Bookcases`, `Binders`, `Machines`, `Copiers`, `Appliances`, `Furnishings`, `Paper`, `Art`, `Envelopes`, `Labels`, `Supplies`, `Fasteners`).
3. Highlight high-impact or loss-making subcategories using visual indicators.
4. Track weekly sales and profit trends across all 52 weeks against average reference lines (`Avg. ₹9K` for Sales and `Avg. ₹1K` for Profit).
5. Enable interactive filtering using a collapsible filter container (`Select Year`, `Category`, and `Sub-Category`)[cite: 10].

**📁 Data Source**

**Source:** Retail Superstore Sales Dataset (connected in the Tableau workbook)[cite: 10].

**📝 Tools and Technologies**

1. **Tableau Desktop** - Data modeling, calculated fields, KPI sparklines, bullet/bar charts, step-line charts, collapsible filter containers, and dashboard design.
2. **Calculated Fields & Table Calculations** - Year-over-year (YoY) variance calculations, min/max point highlights, and average reference lines.
3. **Interactive Worksheets** - Dedicated sheets for `KPI Sales`, `KPI Profit`, `KPI Quantity`, `Subcategory Comparison`, and `Weekly trends` combined into `Sales Dashboard`[cite: 10].

**🚀 Key Performance Indicators (KPIs)**

The dashboard highlights three primary KPIs (2021 view):

1. **Total Sales:** ₹471K (with monthly trend and YoY comparison)
2. **Total Profit:** ₹62K (with monthly trend and YoY comparison)
3. **Total Quantity:** 8K (with monthly trend and YoY comparison)[cite: 10]

**📈 Dashboard Visualizations**

![Dashboard Screenshot](Images/final_dashboard.png)

**✅ Conclusion**

The dashboard supports data-driven retail decisions by helping teams monitor year-over-year growth trajectories, evaluate subcategory sales versus profitability, track weekly performance against average benchmarks, and filter insights by year and product hierarchy[cite: 10].