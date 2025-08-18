# Financial Overview Dashboard

## Purpose

This dashboard provides a comprehensive visual analysis of product sales in the beauty category. It helps stakeholders:

- Monitor total revenue, sales, average price, buyout rate, and Revenue MoM
- Track trends across category, brand, product, country, and month
- Evaluate assortment effectiveness and identify underperforming segments
- Support decision-making on promotional mechanics and assortment optimisation

---

## Business Context

The dashboard was created to assist product, brand, and marketing teams in monthly business review meetings. It helps evaluate whether the company is meeting its 5% monthly revenue growth target and maintaining the 95% buyout rate goal.

When metrics fall short, the dashboard helps identify underperforming segments for deeper analysis or promotional action (discounts, bundles, etc.). Price sensitivity is assessed using scatter plots showing the relation between average price and buyout rate.

---

## File Structure

```
.
├── financial_overview.twbx        # Tableau packaged workbook
├── project_overview.md            # Full business and data context
├── how_to.md                      # Internal documentation for using the dashboard
├── data.xlsx                      # Source data: two sheets (Products, Dynamic)
└── assets/
    ├── dashboard_canvas.pptx.jpg  # Visual planning of dashboard structure
    ├── financial_overview.png     # Screenshot of final dashboard
    └── how_to.png                 # Screenshot of the How-To guide
```

---

## Key Metrics

- Revenue (December, November)
- Sales (December, November)
- Price (December, November)
- Buyout Rate
- Revenue MoM

---

## Dimensions

- Category  
- Brand  
- Product  
- Country  
- Month  

---

## Data Sources

- `Products` (sheet in `data.xlsx`): contains SKU, category, brand, product type, sales, price, revenue, and buyout rate per product
- `Dynamic` (sheet in `data.xlsx`): contains month-level brand dynamics: revenue, sales, buyout rate

Connection type: Manual import

---

## Calculations

- Revenue MoM and Buyout Rate are calculated using manually aggregated expressions
- Custom parameters are used for flexible filtering
- Top N filters are handled using RANK() fields in scatter plots

---

## Dashboard Structure

- Top section: KPI blocks (Revenue, Sales, Buyout Rate)
- Line charts: Metric dynamics by month
- Bar chart: Top products by average price
- Table: Detailed breakdown by brand, category, and product
- Scatter plot: Average price vs buyout rate
- Pie charts: Revenue shares by category and country (with "Other" group)
- Map: Average product price by country
- Bubble chart: Sales volume by brand

---

## Filters

- Category  
- Brand  
- Country  
- Month  

---

## Usage Guide

The project includes:

* `dashboard_canvas.pptx.jpg` for structural overview
* `project_overview.md` for full business context
* `how_to.md` and How-To tab inside Tableau for internal onboarding

---

## Tableau Public Link

Access the dashboard live on [Tableau Public](https://public.tableau.com/app/profile/artemietu/viz/financial_overview_17501448537580/FinancialOverview?publish=yes)

---

## Author

Artemie Țurcanu — Data Analyst