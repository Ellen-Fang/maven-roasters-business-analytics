# ☕ Maven Roasters Business Analytics & Decision Support

A business analytics and decision support project based on **149,116 transaction records** from Maven Roasters, a coffee shop chain with three locations in New York City.

This project transforms raw transaction data into actionable business insights through **sales analysis, profitability analysis, pricing simulation, inventory optimization, and relational database design** using Microsoft Excel and Access.

## 📌 Project Overview

The goal of this project is not only to analyze historical sales performance, but also to support managerial decision-making.

The analysis focuses on four main business questions:

* How do sales and profitability differ across stores, products, and time periods?
* Which products and categories contribute the most to overall profit?
* How would different pricing strategies affect profitability?
* How can inventory allocation be optimized under a limited budget?

## 📊 Dataset

The dataset contains **149,116 transactions** from January to June 2023 across three Maven Roasters locations:

* Astoria
* Hell's Kitchen
* Lower Manhattan

Key variables include:

`transaction_date` · `transaction_time` · `transaction_qty` · `store_location` · `product_category` · `product_type` · `unit_price`

Additional variables such as **month, hour, revenue, estimated cost, and gross profit** were derived for further analysis.

## 🛠 Tools & Methods

### Microsoft Excel

Excel was used for data processing, analytical modeling, and decision support, including:

* PivotTables and PivotCharts
* Store and product profitability analysis
* Product category analysis
* Time-of-day transaction analysis
* What-If Analysis
* Scenario Manager
* Two-variable Data Tables
* Solver Optimization

### Microsoft Access

A relational database was developed to organize transaction, product, and store information.

The database includes:

* Relational tables
* Store and product management forms
* Parameter queries
* Sales and profitability queries
* Management reports

## 🔍 Key Findings

### 1. Store Performance

The three stores showed relatively balanced profitability.

Total gross profit during the six-month period:

| Store           | Gross Profit |
| --------------- | -----------: |
| Hell's Kitchen  |     $168,917 |
| Astoria         |     $167,253 |
| Lower Manhattan |     $164,764 |

The difference between the highest- and lowest-performing stores was less than **2.5%**, suggesting relatively consistent performance across locations.

### 2. Product Category Contribution

Beverages were the primary source of business value.

* **Coffee:** 40.42%
* **Tea:** 31.37%
* **Drinking Chocolate:** 10.12%
* **Bakery:** 9.86%

Coffee, tea, and drinking chocolate together accounted for approximately **81.91%** of total gross profit.

### 3. Top Profit-Generating Products

The most profitable product types included:

| Product               | Gross Profit |
| --------------------- | -----------: |
| Barista Espresso      |      $68,555 |
| Brewed Chai Tea       |      $61,666 |
| Gourmet Brewed Coffee |      $52,526 |
| Hot Chocolate         |      $50,691 |

These products represent important candidates for inventory prioritization and promotional strategies.

### 4. Peak Business Hours

Transaction activity was concentrated between **8:00 AM and 10:00 AM**.

* 10 AM: 18,545 transactions
* 9 AM: 17,764 transactions
* 8 AM: 17,654 transactions

This suggests that staffing, inventory preparation, and service capacity should be concentrated around the morning peak period.

## 💰 Pricing Scenario Analysis

A pricing simulation was conducted for **Barista Espresso**.

Three scenarios were compared:

| Scenario       | Price | Demand Assumption | Estimated Profit |
| -------------- | ----: | ----------------: | ---------------: |
| Promotion      | $3.00 |              +15% |        $8,630.19 |
| Current        | $3.50 |          Baseline |        $7,504.37 |
| Price Increase | $4.00 |               -5% |        $7,128.49 |

Under the assumptions of the model, the **promotion strategy generated the highest estimated profit**, demonstrating how pricing decisions should consider both margin and demand response rather than price alone.

## 📦 Inventory Optimization

Excel Solver was used to determine an optimal inventory allocation for selected high-selling products.

**Objective**

Maximize total gross profit.

**Constraints**

* Total purchasing cost must remain within the available budget.
* Inventory quantities must remain within historically reasonable minimum and maximum levels.

The optimization results suggest prioritizing high-margin beverage products while maintaining only necessary inventory levels for lower-margin categories.

This converts descriptive analytics into a practical **prescriptive analytics** problem.

## 🗄 Database Design

Microsoft Access was used to construct a relational database with three primary entities:

* **Sales**
* **Products**
* **Stores**

The database supports common managerial tasks such as:

* Monthly revenue analysis by store
* Product category rankings
* Hourly transaction analysis
* Product profitability analysis
* Parameter-based searches
* Store performance reports

## 💡 Business Recommendations

Based on the analysis:

1. **Prioritize high-margin beverage products** in purchasing and inventory allocation.
2. Increase staffing and preparation capacity during the **8–10 AM peak period**.
3. Evaluate promotional pricing based on the combined effect of **price, demand, and gross profit**.
4. Use store-level performance monitoring while maintaining a consistent operating strategy across locations.
5. Integrate historical sales analysis with optimization models to support future inventory and pricing decisions.

## 📄 Full Report

For detailed methodology, analysis, charts, database design, and results:

[View the Full Business Analytics Report](./Maven_Roasters_Business_Analytics_Report.pdf)

## 🎯 Skills Demonstrated

`Business Analytics` · `Data Analysis` · `Excel` · `PivotTables` · `What-If Analysis` · `Solver Optimization` · `Microsoft Access` · `Database Design` · `Decision Support` · `Data Visualization`

## 📁 Project Files

Due to GitHub's file size limitations, the complete Excel and Microsoft Access files are hosted separately on Google Drive.

The folder includes:

- Excel analysis workbook
- Microsoft Access database
- Supporting project files

👉 [View Maven Roasters Project Files on Google Drive](https://drive.google.com/drive/folders/1sXJdP8QGOEB91VV0bqCbVzMS24S50f_f?usp=drive_link)
