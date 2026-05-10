# Inventory Health Monitor Dashboard

**Supply Chain Analytics | Inventory Optimization | Excel Dashboard**

The Inventory Health Monitor Dashboard is a Supply Chain Analytics and Inventory Optimization project developed to monitor stock health, reorder exposure, inventory movement, and product lifecycle performance across a multi-category inventory portfolio.

This project transforms raw inventory and operational data into actionable business intelligence that supports inventory optimization, stock availability management, replenishment planning, and operational efficiency.

The dashboard was designed to help businesses:

- Monitor inventory health across product categories
- Detect stockout risks and below-threshold inventory
- Analyze inventory turnover performance
- Identify overstock and understock conditions
- Improve inventory visibility and control
- Reduce dead stock and obsolete inventory
- Support data-driven inventory management decisions


##  Project Overview

The primary objective of this project is to evaluate inventory performance and identify operational risks affecting stock availability and inventory efficiency.

Key goals include:

- Monitor inventory status across all SKUs
- Detect products below reorder level
- Evaluate category-level stock coverage
- Analyze inventory turnover distribution
- Identify slow-moving and obsolete inventory
- Improve replenishment visibility
- Optimize inventory allocation and working capital
- Generate actionable inventory insights

---

##  Project Objectives

- Monitor real-time inventory health across all SKUs
- Detect products below reorder levels
- Analyze inventory turnover and movement patterns
- Identify overstock, understock, and discontinued items
- Support data-driven replenishment and inventory optimization

---

##  Methodology

### 1. Data Collection
Sourced from **Kaggle Supply Chain Dataset** containing product, supplier, stock, reorder, sales, and turnover information.

### 2. Data Cleaning & Preparation (in Excel)
- Converted data into Excel Tables
- Standardized date formats
- Reviewed structure and completeness

### 3. Feature Engineering

| Helper Column              | Purpose |
|---------------------------|--------|
| Turnover Rate Distribution | Group turnover into performance ranges |
| Revenue                    | Sales Volume × Unit Price |
| Turnover Band              | Categorize movement performance |
| Total Reorder Value        | Measure replenishment exposure |
| Reorder Value              | Reorder cost per SKU |


---

##  Business Problem



Many organizations struggle with maintaining optimal inventory levels while balancing customer demand, operational efficiency, and working capital.

Without effective inventory monitoring:

- Products fall below reorder thresholds
- Stockouts disrupt customer fulfillment
- Excess inventory increases holding costs
- Slow-moving products occupy warehouse space
- Obsolete inventory ties down working capital
- Inventory planning becomes reactive instead of proactive

This dashboard was developed to provide real-time visibility into inventory health and support proactive inventory management.




---

##  Key Insights

### 1. Inventory Status Distribution
- **Discontinued SKUs** represent ~33.6% of the portfolio (333 SKUs)
- Near-equal split between Active, Backordered, and Discontinued items indicates weak product lifecycle management

### 2. Stock vs Reorder Level
- **Oils & Fats, Beverages, and Grains & Pulses** are operating at or below reorder levels → **High stockout risk**
- **Seafood, Dairy, and Fruits & Vegetables** maintain healthier coverage

### 3. Inventory Turnover Distribution
Evenly spread across turnover bands (1–20 up to 81–100), suggesting limited segmentation between fast and slow movers.

### 4. Stock Concentration
**Fruits & Vegetables** holds the largest share of total inventory — high demand category but also highest exposure to overstock and spoilage risk.

---

##  Strategic Recommendations

- **Immediate Action**: Prioritize replenishment for the **455 SKUs** currently below reorder level
- **Risk Mitigation**: Increase safety stock for vulnerable categories (Oils & Fats, Beverages, Grains & Pulses)
- **Optimization**: Reduce excess stock in Fruits & Vegetables and rationalize the 333 discontinued SKUs
- **Segmentation**: Implement ABC analysis and differentiated policies by turnover band
- **Lifecycle Management**: Launch liquidation or reactivation plan for obsolete inventory


### 4. Analysis & Dashboard
Built using Pivot Tables, Pivot Charts, Slicers, and KPI cards in Microsoft Excel.

---


## Conclusion
This Inventory Health Monitor Dashboard demonstrates how data-driven inventory analysis can improve operational visibility, strengthen replenishment planning, and support more efficient inventory management decisions across the supply chain.
The insights generated from the dashboard provide a strong foundation for reducing stockout exposure, optimizing stock allocation, improving inventory turnover performance, minimizing dead stock accumulation, and enabling more proactive, data-driven inventory decision-making.

---

