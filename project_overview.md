# Project Overview

This project focuses on the analysis of product sales performance within the beauty retail sector. The core objective was to develop a dashboard that enables the evaluation of key financial indicators across multiple brands, assisting in assortment and strategy management at the product level.

The dashboard helps monitor the following business goals:

- Assess the performance of the current assortment
- Identify opportunities for adding new brands and supporting existing ones
- Optimise the assortment by phasing out underperforming products

**Key tracked metrics:**

- Total revenue  
- Sales volume  
- Average product price  
- Product buyout rate (number of purchased items ÷ number of orders)

The analysis covers various product categories, product types, brands, and countries of origin. One of the key performance indicators is to ensure monthly revenue growth of at least 5%. The target buyout rate is set at **95%**.

---

# Business Context and Strategy

To achieve the set targets, promotional mechanics such as discounts, bundles, and cross-selling are introduced to stimulate demand. Simultaneously, assortment analysis is conducted to identify and remove low-performing products and introduce items aligned with market trends and customer preferences.

The dashboard is designed to support decision-making across multiple roles:

- Product managers  
- Brand managers  
- Analysts  
- Marketers  

It tracks monthly performance and highlights deviations from previous periods. Any significant drop or failure to meet the **Satisfaction Index** target becomes a trigger for deeper investigation.

---

# Operational Use and Monitoring

The unified dashboard serves as a single point of truth, eliminating the need for manual data collection from different sources each month. It ensures easy access to up-to-date information and becomes a key tool during monthly meetings with the CEO, conducted via Zoom.

During these sessions, the team analyses current performance, identifies key trends, formulates hypotheses, and plans next steps. The first priority is to evaluate whether the company is meeting its revenue growth target of **5% month-over-month** — both overall and across specific categories and brands.

If metrics fall short of plan, the dashboard helps identify problem segments — categories or brands experiencing the sharpest decline. For such cases, the team develops marketing initiatives: promotions, discounts, or cross-sells to boost demand. If a brand consistently shows low sales and buyout rates, discontinuation is considered.

---

# Price Sensitivity and Product Performance

The dashboard also supports the analysis of price sensitivity in relation to product buyout rate. For high-priced items with low buyout percentages, the team designs discount strategies aimed at stimulating demand.

---

# Data Specifics

The data is stored in two Excel sheets and includes the following fields:

## Sheet: `Products`

- **SKU** — unique product ID  
- **Category** — product category  
- **Product type** — specific product type or subcategory  
- **Brand** — product brand  
- **Price (December)** — average product price in December 2023  
- **Price (November)** — average product price in November 2023  
- **Sales (December)** — quantity sold in December 2023 (including returns)  
- **Sales (November)** — quantity sold in November 2023 (including returns)  
- **Revenue (December)** — total revenue in December 2023  
- **Revenue (November)** — total revenue in November 2023  
- **Buyout rate (December)** — share of purchased items out of total ordered in December  
- **Buyout rate (November)** — same metric for November  
- **Country** — country of origin  

## Sheet: `Dynamic`

- **Brand** — product brand  
- **Month** — start date of the reporting month  
- **Sales** — monthly sales volume (including returns)  
- **Revenue** — monthly revenue  
- **Buyout rate** — share of purchased items out of total ordered for the month  