
# 🛒 E-Commerce Sales Dashboard | Power BI

## 📌 Project Overview

The **E-Commerce Sales Dashboard** is an interactive Power BI dashboard designed to help management monitor and analyze business performance across **sales, profit, products, customer segments, geographical regions, and shipping methods**.

The dashboard provides both **Year-to-Date (YTD)** performance and **Year-over-Year (YoY)** comparison, allowing users to quickly identify growth, decline, trends, and areas that require business attention.

Users can also filter the entire dashboard by **Customer Segment**, including:

* Consumer
* Corporate
* Home Office

---

## 🎯 Business Problem

E-commerce businesses generate large amounts of sales and operational data, making it difficult for management to quickly identify:

* Whether sales and profit are growing or declining
* Which customer segments contribute the most to business performance
* Which product categories and products perform well or poorly
* Which states and regions generate the highest sales
* Which shipping methods are most frequently used
* How business performance changes over time

The objective of this dashboard is to bring these insights into a **single interactive reporting solution** that supports data-driven decision-making.

---

## 💡 Business Questions

This dashboard helps answer the following questions:

### Sales & Profitability

1. What are the current YTD Sales?
2. What is the current YTD Profit?
3. How many products have been sold YTD?
4. What is the YTD Profit Margin?
5. How is the current year's performance compared with the previous year?
6. Is sales and profit performance improving or declining?
7. What is the monthly trend in sales, profit, and quantity?

### Customer Segmentation

8. Which customer segment contributes the most to sales?
9. How does profitability differ across Consumer, Corporate, and Home Office segments?
10. How does product and regional performance change across customer segments?

### Product Performance

11. Which are the Top 5 products based on YTD Sales?
12. Which are the Bottom 5 products based on YTD Sales?
13. Which product categories are performing well?
14. Which categories are showing a decline compared with the previous year?

### Geographical Analysis

15. Which states generate the highest sales?
16. Which region contributes the most to overall sales?
17. Which geographical markets may require additional business attention?

### Shipping Analysis

18. Which shipping method is most frequently used?
19. What percentage of sales/orders is associated with each shipping type?
20. How does shipping-method usage vary across customer segments?

---

# 📊 Dashboard Features

## 1. KPI Analysis

The dashboard provides four major KPIs:

| KPI                   | Purpose                                                                           |
| --------------------- | --------------------------------------------------------------------------------- |
| **YTD Sales**         | Measures accumulated sales from the beginning of the year up to the selected date |
| **YTD Profit**        | Measures accumulated profit during the year                                       |
| **YTD Quantity**      | Measures total quantity sold YTD                                                  |
| **YTD Profit Margin** | Measures profitability relative to sales                                          |

Each KPI also contains:

* **YoY Growth**
* Up/Down trend indicator
* Monthly sparkline

### Example

If YoY Sales shows:

**▼ -1.93%**

it indicates that current-year sales are lower than the previous year's corresponding period.

If it shows:

**▲ 7.49%**

it indicates positive year-over-year growth.

---

# 👥 2. Customer Segment Analysis

The dashboard can be filtered using:

* **Consumer**
* **Corporate**
* **Home Office**

This allows management to analyze the complete dashboard from the perspective of a specific customer segment.

For example, management can select **Corporate** and analyze:

* Sales
* Profit
* Quantity
* Profit Margin
* Product performance
* Regional performance
* Shipping behavior

This helps identify the most valuable customer segments and understand differences in their purchasing behavior.

---

# 📦 3. Category Performance

The **Sales by Category** section provides:

* YTD Sales
* PYTD Sales
* YoY Sales
* Trend indicator

This allows management to identify categories that are:

* Growing
* Declining
* Generating high sales
* Requiring further investigation

For example, a category with negative YoY growth can be investigated further to understand the reason behind the decline.

---

# 🏆 4. Top 5 Product Performance

The dashboard identifies the **Top 5 products based on YTD Sales**.

This helps management identify products that are major contributors to revenue.

Possible business actions include:

* Maintaining sufficient inventory
* Prioritizing high-performing products
* Increasing promotional activities
* Understanding successful product characteristics

---

# 📉 5. Bottom 5 Product Performance

The dashboard also identifies the **Bottom 5 products based on YTD Sales**.

This helps management identify products that may require further investigation.

Possible actions include:

* Reviewing pricing
* Increasing promotions
* Investigating customer demand
* Reviewing product positioning
* Considering portfolio optimization

---

# 🗺️ 6. Geographical Analysis

The dashboard provides state-level and regional sales analysis.

### State-Level Analysis

The map visualizes sales performance across different states.

The **size of the bubble represents the level of sales**:

> Larger bubble → Higher sales
> Smaller bubble → Lower sales

This allows management to quickly identify high-performing geographical markets.

### Regional Analysis

The dashboard also provides YTD Sales by region:

* West
* East
* Central
* South

This helps management understand the contribution of each region to overall sales.

---

# 🚚 7. Shipping Type Analysis

The dashboard provides a breakdown of YTD Sales/orders by shipping type.

This helps management understand:

* Which shipping methods are most frequently used
* Customer shipping preferences
* The distribution of orders across shipping methods
* Potential opportunities for logistics optimization

**Note:** The most-used shipping type is not necessarily the "best" shipping type. Determining the best shipping method would require additional metrics such as shipping cost, delivery time, customer satisfaction, and profitability.

---

# 📈 Key Business Insights

The dashboard enables management to:

### Monitor overall performance

Track YTD Sales, Profit, Quantity and Profit Margin from a single view.

### Identify growth or decline

YoY indicators quickly highlight whether key metrics are improving or declining.

### Understand trends

Monthly sparklines provide a quick view of performance fluctuations throughout the year.

### Identify high-value customers

Segment-level analysis helps identify which customer groups contribute significantly to the business.

### Optimize product strategy

Top and Bottom product analysis helps identify products that should be prioritized or investigated.

### Identify geographical opportunities

State and regional analysis helps identify strong-performing markets and areas that may require additional attention.

### Understand shipping behavior

Shipping analysis provides insight into shipping-method usage and potential logistics optimization opportunities.

---

# 🛠️ Tools & Technologies

### Data & Analytics

* **SQL** – Data querying and validation
* **Power BI** – Data visualization and dashboard development
* **DAX** – KPI, YTD, PYTD, YoY and trend calculations
* **Power Query** – Data transformation and preparation

### Power BI Features Used

* Data Modeling
* Relationships
* DAX Measures
* YTD Calculations
* PYTD Calculations
* YoY Growth
* Conditional Formatting
* KPI Cards
* Sparklines
* Bar Charts
* Donut Charts
* Tables
* Map Visualization
* Interactive Filters/Slicers

---

# 🧮 Key DAX Concepts

Some of the major DAX concepts used in the project include:

```DAX
YTD Sales
```

Used to calculate sales accumulated from the beginning of the year to the selected date.

```DAX
PYTD Sales
```

Used to compare current YTD performance with the corresponding period of the previous year.

```DAX
YoY Sales
```

Used to measure year-over-year sales growth.

```DAX
Profit Margin
```

Used to measure profit as a percentage of sales.

Trend indicators were also created using `UNICHAR()` to display upward and downward icons.

---

# 🔄 Dashboard Flow

```text
                    E-Commerce Data
                           ↓
                    Data Preparation
                           ↓
                    Data Modeling
                           ↓
                    DAX Calculations
                           ↓
              ┌────────────┴────────────┐
              ↓                         ↓
        KPI Performance           Category Analysis
              ↓                         ↓
       Customer Segments          Product Analysis
              ↓                         ↓
       Regional Analysis          Shipping Analysis
              ↓                         ↓
              └────────────┬────────────┘
                           ↓
                 Business Insights
                           ↓
                Data-Driven Decisions


---



tHub-ready** and also gives you a clear structure for explaining the project in an interview.
