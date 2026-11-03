# Blinkit Sales Analysis Dashboard

A comprehensive Power BI data analytics project evaluating retail sales performance, customer satisfaction, and outlet distribution for **Blinkit (India's Last Minute App)**. Designed to unlock actionable business insights from transactional data.

# Executive Summary Preview
![Blinkit Dashboard Overview](image_SLNoOC.png)


# Business Problem & Project Objective
In the hyper-competitive quick-commerce industry, optimization of inventory, outlet performance, and customer satisfaction is vital. This project explores key metrics across multiple dimensions—outlet sizes, locations, tiers, and product categories—to solve three major operational questions:
1. Which grocery/supermarket outlet types drive the highest revenue volumes?
2. How does product fat content and category layout influence customer buying behavior?
3. What impact do historical outlet establishment years have on current sales growth?

---

# Key Performance Indicators (KPIs) Captured
* **Total Revenue Generated:** $1.20 Million
* **Average Transaction Value (AOV):** $140.99
* **Product Inventory Breadth:** 9K+ Unique items tracked
* **Average Customer Rating:** 3.92 / 5.0

---

# Core Insights Discovered

* **Supermarket Dominance:** `Supermarket Type1` is the undisputed revenue engine, generating **$0.79M** of the total sales—dwarf-matching general grocery stores and other supermarket categories combined.
* **The "Rating 4" Sweet Spot:** A massive chunk of the revenue (**~$976K**) is tied to items holding a solid **4-star rating**, indicating that consistent product quality drives disproportionately higher sales velocity compared to perfect 5-star items.
* **Peak Maturity Trend:** Outlets established around **2018** showed a massive exponential spike in sales volume, providing a benchmark for the scaling timeline of newer fulfillment centers.

---

# Technical Implementation & Architecture

 1. Data Engineering & ETL (Power Query)
* Cleaned and pre-processed transactional data spanning various product types and regional branches.
* Standardized formatting for product attributes (Fat Content tags, Item Categories) and structured financial currencies.

 2. Analytical Data Modeling
* Implemented a highly efficient **Star Schema** layout within Power BI Desktop to handle complex multi-dimensional filtering seamlessly.
* Established relationship flows connecting sales data across **Outlet Dimensions** (Type, Size, Location Tier) and **Product Dimensions** (Fat content, categories, and customer metrics).

 3.  DAX Calculations
* Built dynamic conditional metrics to toggle visualization contexts smoothly.
* Engineered custom calculations for weighted rating breakdowns and granular average order value tracking.

---

# Repository Contents
* `/Data/` - Mock transactional/sales source datasets used for modeling.
* `/Blinkit_Sales_Project.pbip` - **Power BI Project Folder** containing decoupled code, dataset metadata, and semantic layout models for technical inspection.
* `README.md` - Core project documentation and portfolio summary.

