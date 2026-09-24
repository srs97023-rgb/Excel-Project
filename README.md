# Excel-Project
# 🚲 Adventure Works Sales Analytics: Excel Dashboard

An interactive Excel dashboard that analyzes **$29.4M in Adventure Works sales** across 5 years, 10 sales regions and 18,000+ customers. It turns 60,000+ sales transactions into clear KPIs on revenue, cost, profit, seasonality, top products, customers and regions.

**🔗 Live Dashboard:** [View on Google Sheets]
![Excel Dashboard]

---

## 🎯 Business Problem

Adventure Works sells bikes, components, clothing and accessories worldwide. Raw transaction data makes it hard to answer questions like:

- How much revenue and profit are we generating, and how has it changed year over year?
- Which months and quarters are strongest?
- Which products, customers and regions drive the most sales?
- What is our profit margin, and does it differ by region?

## ✅ Goal of the Dashboard

To give decision-makers one interactive view of sales performance that:

- Tracks the main KPIs: sales, production cost, profit and profit margin
- Reveals seasonality and yearly growth trends
- Highlights top-performing products, customers and regions
- Lets users filter everything by year with a slicer

---

## 🛠️ Tech Stack

- 📊 **Microsoft Excel**: dashboard and reporting layer
- 📂 **Power Query**: importing, cleaning and shaping the data
- 🧠 **Data Model (Power Pivot)**: relationships between fact and dimension tables
- 📈 **Pivot Tables & Pivot Charts**: aggregation and visualization
- 🎚️ **Slicers**: interactive filtering by year
- 🧮 **Excel Formulas**: calculated columns (date parts, quarters, financial periods, full names) and KPI calculations

## 🗂️ Data Source

Adventure Works sample dataset (Microsoft), organized as a star schema:

| Table | Type | Contents |
|---|---|---|
| `Fact_Table` | Fact | ~60,400 sales order lines: quantity, unit price, discount, sales amount, cost |
| `DimProduct` | Dimension | 600+ products with price, cost, color and size |
| `DimProdCategory` / `DimProdSubCategory` | Dimension | Product hierarchy (Bikes, Components, Clothing, Accessories) |
| `DimCustomer` | Dimension | 18,000+ customers with demographics and income |
| `DimDate` | Dimension | Calendar table (day, month, quarter, year) |
| `DimSalesTerritory` | Dimension | Sales regions, countries and groups |

---

## 📊 Dashboard Walkthrough

- **KPI Cards**: total sales, production cost, profit and profit margin at a glance
- **Year Slicer**: filters every visual on the dashboard
- **Yearly Sales vs Production Cost** (combo chart): compares revenue and cost by year
- **Month-wise Sales** (line chart): shows seasonality across the calendar year
- **Quarter-wise Sales Distribution** (pie chart): share of sales by quarter
- **Top 5 Products** (bar chart): best-selling products by sales amount
- **Top 5 Customers** (bar chart): highest-value customers
- **Top 5 Regions** (bar chart): leading sales territories with cost, profit and margin

## 💡 Key Insights

- **Total sales: $29.36M** with a production cost of **$17.28M**, giving a profit of **$12.08M** and a **41.1% profit margin**.
- **2013 was the peak year** at **$16.35M**, more than double the 2012 total of $5.84M. 2010 and 2014 contain only partial data.
- **Q4 is the strongest quarter** with $9.11M (about 31% of sales), and **December is the top month** at $3.21M. Q1 is the weakest at $5.52M (about 19%).
- **Sales grow through the year**, with a clear step up from June onward.
- **Australia is the #1 region** with $9.06M (about 31% of sales), followed by the Southwest US ($5.72M) and the Northwest US ($3.65M).
- **Margins are consistent across regions**, ranging from about 40.7% to 45.0%, so growth depends on volume rather than pricing.
- **All top 5 products are Mountain-200 bikes**, together worth **$6.67M** (about 23% of total sales).
- **Customer sales are widely spread**: the #1 customer contributes only about $43K, so there is little dependence on any single buyer.

## 📈 Business Impact

- **Sales planning:** stock and staff up for Q4, when demand peaks.
- **Product strategy:** the Mountain-200 series is the revenue anchor, so protect its supply and consider promoting related products.
- **Regional focus:** Australia and the US South-West/North-West are the core markets, while Central, Northeast and Southeast contribute very little and need a growth strategy.
- **Customer retention:** target loyalty offers at the top-spending customers.

---

## 📁 Repository Files

- `Excel_Project.xlsx`: complete workbook (data model, pivot tables, KPI cards and dashboard)
- `dashboard.png`: dashboard preview

## 🧠 Skills Demonstrated

Data cleaning • Data modeling (star schema) • Power Query • Pivot analysis • KPI design • Dashboard design • Business storytelling
