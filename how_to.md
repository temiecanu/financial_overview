# 📋 How to?

### **1. General Information**

**Title:**

Financial Overview

**Dashboard Owner:**

Artemie Țurcanu (Data Analyst) — artemie.turcanu@icloud.com

**Purpose:**

This dashboard provides an overview of key product sales metrics in the beauty category: revenue, sales, price, buyout rate, and MoM dynamics. It enables users to:

* Identify the most profitable and underperforming categories
* Track trends by category, brand, country, and product
* Compare metrics between months
* Quickly assess the current sales performance and assortment effectiveness

**Primary Stakeholder:**

Sales and Analytics Department

**Metrics:**

* Revenue (December, November)
* Sales (December, November)
* Price (December, November)
* Buyout Rate
* MoM dynamics

**Dimensions:**

* Category
* Brand
* Product
* Country
* Month

---

### **2. Data Sources and Technical Details**

**Data Sources:**

* **Products** (data.xlsx): includes product category, brand, price, sales, and revenue
* **Dynamic** (data.xlsx): includes brand-level dynamics (month, sales, revenue, buyout rate)

**Join Structure:**

The two sheets from the data.xlsx file — Products and Dynamic — were joined using an inner join on the Brand field. This join ensures that only records present in both tables are included in the visualisations. 
* Join key: Brand
* Join type: Inner join

This join was applied during data source setup in Tableau before building the dashboards.

**Connection Type:**

Manual import

**Calculation Notes:**

* MoM and Buyout Rate are calculated using manually aggregated expressions
* Custom parameters are used for dynamic filtering

---

### **3. Frequently Asked Questions (FAQ)**

**Why is the KPI indicator not showing data for the selected brand?**

The brand’s sales volume might be too small to register on the scale of the chart. The value may be rounded visually to zero — this applies to both revenue and unit sales.

**Why do values on the charts differ from the table values?**

Charts display aggregated and rounded data, while tables reflect precise values. In addition, some charts may show only top-performing categories or brands, whereas tables list the full dataset.

---

### **4. Dashboard Structure**

* **Top section:** KPI blocks (Revenue, Sales, Average Buyout Rate)  
* **Line plots:** Metric dynamics over months  
* **Bar chart:** Top products by average price in the current month  
* **Table:** Breakdown by brand, category, and product  
* **Scatter plot:** Relationship between average price and buyout rate  
* **Pie charts:** Revenue shares by category and country with dynamic grouping  
* **Map:** Average product price by country for the current month  
* **Bubble chart:** Sales volume by brand

**Filters available for:**

* Category
* Brand
* Country
* Month
