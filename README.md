# Power BI Dashboard Portfolio

Three end-to-end Power BI dashboards built to demonstrate practical business analytics skills: data cleaning, data modeling, DAX measures, and dashboard design for real business questions.

Each .pbix file below can be downloaded and opened directly in Power BI Desktop (free) to explore the live, interactive report, including slicers, drill-downs, and cross-filtering.

---

## 1. Retail Sales Overview Dashboard
File: 01_Retail_Sales_Dashboard.pbix

![Retail Sales Overview Dashboard](screenshots/01_retail_sales_dashboard_1.jpg)

Use Case: A retail operations or sales manager needs a single view to track how sales are performing across regions and product categories, spot which segments are underperforming, and see trends over time to plan inventory and promotions.

Highlights:
- KPI cards for key sales metrics (total sales, orders, profit)
- Sales by Category and Region (bar and donut charts)
- Sales trend over time (line chart)
- Region x Category breakdown (matrix)
- Interactive slicers with a one-click filter-reset button (built using bookmarks)

Skills demonstrated: Data import and cleaning, chart selection, cross-filtering, bookmarks and buttons, report formatting.

---

## 2. Marketing Campaign Performance Dashboard
File: 02_Marketing_Campaign_Dashboard.pbix

![Marketing Campaign Performance Dashboard](screenshots/02_marketing_campaign_dashboard_1.jpg)

Use Case: A marketing team running multi-channel B2B campaigns needs to see the full funnel from ad spend to closed revenue, so they can identify which channels and regions convert best and whether campaigns are on track to hit monthly targets.

Highlights:
- KPI cards including a custom Conversion Rate measure (Customers Won divided by Leads)
- Combo chart comparing spend vs revenue trend
- Funnel chart (Impressions to Clicks to Leads to Opportunities to Customers)
- Gauge chart comparing actual revenue against monthly targets
- Channel x Region matrix, treemap, and donut/bar breakdowns
- Modeled relationship between campaign data and a monthly targets table

Skills demonstrated: Data modeling (table relationships), DAX quick measures, combo/funnel/gauge charts, multi-table reporting.

---

## 3. HR Workforce Analytics Dashboard
File: 03_HR_Workforce_Dashboard.pbix

![HR Workforce Analytics Dashboard](screenshots/03_hr_workforce_dashboard_1.jpg)

Use Case: An HR or people-analytics team needs visibility into headcount, payroll, and attrition across departments, built from a raw HR export that arrives messy every reporting cycle and needs to be cleaned before it can be trusted.

Highlights:
- Power Query cleaning: removed duplicates, fixed inconsistent salary formats (currency symbols, blanks, "N/A" text), and parsed multiple mixed date formats (ISO, US, and text dates) into a single valid Hire Date column using a custom Power Query formula
- KPI cards: Total Headcount, Active Payroll, Average Salary, and a DAX-calculated Attrition Rate
- Headcount by Department (bar), Gender split (donut), Hiring trend by year (line)
- Recruitment funnel (Applications to Interviews to Offers to Hires)
- Headcount vs budget gauge, Department x Employment Type matrix, Salary-by-department treemap
- Three interactive slicers (Department, Employment Type, Status)

Skills demonstrated: Power Query data cleaning, custom M formulas for mixed date parsing, DAX measures with CALCULATE, advanced dashboard layout.

---

## How to view these dashboards
1. Download the .pbix file for the project you would like to view.
2. Open it in Power BI Desktop (free download from microsoft.com/en-us/power-platform/products/power-bi/downloads).
3. Explore the visuals, slicers, and interactions directly.

---

## About me
Business Analyst with hands-on Power BI experience across retail, marketing, and HR analytics, covering data cleaning in Power Query, data modeling, DAX measures, and dashboard design aimed at answering real business questions.
