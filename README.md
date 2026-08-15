# E-Commerce Sales Performance & Customer Insights Dashboard

## Project Overview

This project is an **interactive E-Commerce Sales and Customer Insights Dashboard built in Microsoft Excel**.

The purpose of the dashboard is to turn e-commerce order data into a simple and interactive report that helps users understand:

- Overall sales and order performance
- Customer purchasing behavior
- Product popularity
- Customer location
- Delivery performance
- Customer satisfaction
- Recent order trends

The dashboard uses **Pivot Tables, Pivot Charts, KPIs, and interactive filters/slicers** to make the analysis easier to explore.

---

## Business Problem

E-commerce businesses generate a large amount of order and customer data. Looking at raw data makes it difficult to quickly understand sales performance, customer behavior, product demand, delivery performance, and customer satisfaction.

This project organizes the data into an interactive dashboard so that important business questions can be answered more easily.

---

## Project Objective

The main objectives of this project are to:

- Monitor overall sales and order performance
- Understand how customers prefer to purchase
- Identify popular products
- Analyze customer locations
- Understand delivery-time patterns
- Analyze customer satisfaction
- Track recent order trends
- Provide an interactive view that can be filtered by users

---

## Dataset

The project uses an **e-commerce order dataset** containing information related to:

- Orders
- Quantity
- Sales amount
- Products
- Customer gender
- Order mode
- Customer location
- Delivery time
- Customer rating
- Time-based order information

> Note: The original dataset/source details were not provided with the dashboard, so no external dataset source is claimed here.

---

## Dashboard KPIs

The dashboard currently shows the following KPI values:

| KPI | Value |
|---|---:|
| Total Orders | 2,400 |
| Total Quantity | 11,997 |
| Total Amount | $649.0K |
| Average Rating | 2.3 |
| Average Delivery | 4.0 days |

These values represent the current dashboard/filter state.

---

## Business Questions

The dashboard was designed to answer the following questions.

### Sales Performance
- What is the total number of orders?
- What is the total quantity sold?
- What is the total sales amount?
- What is the order trend over the last 13 weeks?

### Customer Behavior
- How do customers prefer to place orders?
- How many items do customers usually buy?
- What is the overall gender distribution?

### Product Analysis
- Which products are popular?

### Geographic Analysis
- Where do customers live?

### Delivery Analysis
- How long does it take to deliver orders?

### Customer Satisfaction
- How satisfied are customers based on their ratings?

---

## Dashboard Components

### KPI Cards

The dashboard contains five main KPIs:

- Total Orders
- Total Quantity
- Total Amount
- Average Rating
- Average Delivery Days

### Weekly Trend

A line chart shows the **trend in the last 13 weeks**, helping users understand recent order and sales movement.

### Order Mode Analysis

The dashboard compares purchasing channels such as:

- App
- Instagram
- Partner App
- Target.com
- Website

### Purchase Quantity Analysis

A chart shows how many items customers purchase in an order, using quantity groups such as:

- 1
- 2
- 3
- 4
- 5
- 6 to 10
- 11+

### Product Popularity

A horizontal bar chart compares products based on purchase volume.

### Gender Analysis

The dashboard shows the distribution of:

- Female
- Male
- Other
- Unknown

It also allows gender behavior to be explored across order modes.

### Geographic Analysis

A map is used to visualize where customers are located.

### Delivery Analysis

A chart shows the distribution of delivery time in days.

### Customer Satisfaction

Customer ratings are shown across different months to understand rating patterns.

---

## Interactive Filters

The dashboard contains interactive filters/slicers, including:

- **Gender**
- **Order Mode**

These filters dynamically update the dashboard visuals and allow users to explore different customer segments.

---

## Key Observations

From the current dashboard view:

- The dashboard reports **2,400 orders** and **11,997 total quantity**.
- The total amount shown is approximately **$649.0K**.
- The average customer rating is **2.3**.
- The average delivery time is **4.0 days**.
- Customers use multiple channels to place orders, including the App, Website, Instagram, Partner App, and Target.com.
- Product demand is not evenly distributed; some products have substantially higher purchase volumes than others.
- Delivery times are concentrated in the lower-day ranges, with fewer orders taking much longer.
- Customer ratings can be compared across months and customer segments.

These observations are based on the dashboard view and should be validated against the underlying data before being used for business decisions.

---

## Recommendations

Based on the dashboard, the following areas could be investigated further:

1. Investigate the reasons behind the relatively low average customer rating.
2. Identify the causes of longer delivery times.
3. Monitor high-demand products for inventory planning.
4. Compare performance across different order channels.
5. Study geographic demand to understand customer concentration.
6. Monitor weekly order trends to identify periods of increasing or decreasing demand.

---

## Tools & Techniques

### Tools

- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Slicers
- Excel Dashboard

### Techniques

- Data summarization
- KPI analysis
- Trend analysis
- Customer behavior analysis
- Product analysis
- Geographic analysis
- Delivery performance analysis
- Customer satisfaction analysis
- Interactive filtering

---

## Project Workflow

The project follows a simple analytics workflow:

```text
Raw E-Commerce Data
        ↓
Data Preparation
        ↓
Data Analysis
        ↓
Pivot Tables
        ↓
Pivot Charts
        ↓
KPIs & Interactive Filters
        ↓
Dashboard
        ↓
Insights & Recommendations
```

---

## Dashboard Preview

Add your dashboard screenshot here:

```text
![E-Commerce Dashboard](images/ecommerce-dashboard.png)
```

If you keep the screenshot in the repository, a recommended folder structure is:

```text
E-Commerce-Analytics/
│
├── README.md
├── E-Commerce-Dashboard.xlsx
├── images/
│   └── ecommerce-dashboard.png
└── data/
    └── dataset.csv
```

---

## What I Learned

Through this project, I practiced how to:

- Convert raw e-commerce data into useful business analysis
- Build KPI summaries
- Use Pivot Tables for multidimensional analysis
- Use Pivot Charts for visualization
- Create interactive slicers
- Analyze customer and product behavior
- Present multiple business views in one dashboard
- Translate business questions into analytical views
- Think about insights and recommendations instead of only creating charts

---

## Future Improvements

Possible future improvements include:

- Adding more advanced KPIs
- Adding profitability analysis
- Adding year-over-year and month-over-month analysis
- Adding customer segmentation
- Adding more detailed geographic analysis
- Rebuilding the project using Power BI
- Connecting the analysis to SQL data
- Adding automated refresh and reporting

---

## Author

**Sadab**

Aspiring Data Analyst | SQL | Excel | Power Pivot | DAX | Power BI

