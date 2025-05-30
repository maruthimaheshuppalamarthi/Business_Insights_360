# 📊 Business Insights 360

**Business Insights 360** is an interactive Power BI dashboard that provides a comprehensive view of key business performance metrics including Sales, Marketing, Finance, and Stakeholder insights. It helps stakeholders make data-driven decisions with ease.

---

## 📌 Features

- 📈 **Overall Report**: Summarized KPIs across all departments.
- 💼 **Executive View**: High-level insights for decision-makers.
- 💸 **Finance View**: Revenue, cost, and profit analysis.
- 📊 **Sales View**: Performance by region, category, and product.
- 📢 **Marketing View**: Campaign performance and engagement.
- 🤝 **Stakeholder Request View**: Stakeholder-specific data.

---


## ⚙️ Technical Implementation & Project Management

* Connected Power BI to MySQL and Excel, transformed data by establishing a data pipeline (ETL) using Power Query.
* Performed Data Modelling to establish relations by snowflake schema and initial Data validation against benchmark values.
* Utilized DAX to create calculated columns and measures, and built a dynamic dashboard with KPIs for sales, finance, marketing, and supply chain.
* Published a report on Power BI service for User Acceptance Testing (UAT) and Data validation through Excel Analyze.
* Incorporated stakeholder feedback to create an Executive Dashboard, resolved quality issues, optimized dashboard performance, and deployed the dashboard to Power BI service with gateway setup to MySQL Database and local Excel files for Automatic Data Refresh.
* Applied various Project Management Skills including Project Charter, Stakeholder Mapping Analysis, and Kanban board for task assignment to improve productivity.
* Designed dashboards with up to three levels of analysis, enabling stakeholders to ask "why" questions regarding top-performing products, markets, customers, percentage changes and trends in P&L metrics, and supply chain forecast accuracy for inventory management, which collectively improved overall business performance.
* Created intuitive dashboards (Views), specifically targeted to various departments to give an overview of the company's performance.

---

## 📈 Detailed View Features

### Key Features in Finance View:
* The Profit and Loss Statement explains various P&L Metrics from Gross Sales to Net Profit. "BM" indicates the benchmark, which is either Last Year or the Target, selectable through a provided Slicer.
* KPIs for Net Sales, Gross Margin %, Net Profit %.
* Net Sales Performance Trend in comparison with Target/Last Year, which can be selected Dynamically.
* Top / Bottom Product and Top / Bottom Customers based on Net Sales.

### Key Features in Sales View:
* **Unit Economics 1**: Net Sales vs Total Post Invoice Discount Amount and Pre-Invoice Discount Amount given by the Company.
* **Unit Economics 2**: Total Cost of Goods Sold (COGS) spent by the Company to derive the actual Gross Margin.
* Customer and Product Performance analysis based on Net Sales, Gross Margin, and Gross Margin %.
* Performance Matrix analysis for Market, Customer, and Region based on Net Sales and Gross Margin %.
* Sales Trend Tooltip for every single Customer based on Net Sales and Gross Margin %.

### Key Features in Marketing View:
* **Unit Economics**: Operational Expenses spent for Product are subtracted to get the actual Net Profit scenario.
* Performance Matrix analysis for Segment, Category, and Product based on both “Net Sales & Net Profit %” and “Net Sales & Gross Margin %” by using a dynamic toggle button.

### Key Features in Supply Chain View:
* KPIs for Forecast Accuracy, Net Error, ABS Error.
* Risk Factor analysis.
* Accuracy vs Net Error Trend analysis.
* Key Metrics for both Customer and Products based on FA%, FA% LY, Net Error, Net Error%, Risk Factor.

### Key Features in Executive View:
* Report Page for the Top Level Management of the Company who want to check on all key metrics and KPIs.
* Market Share Trend analysis for AtliQ and other competitors.
* Revenue analysis by Division and Channel.
* Top 5 Products and Top 5 Customers by Revenue.
* Key Insights by Sub Zone with Revenue Contribution % analysis.


---

## 🖼️ Preview

### 🔹 Finance View
![Finance View](visuals/Finance%20view.gif)


### 🔹 Sales View
![Sales View](visuals/Sales%20view.gif)


### 🔹 Marketing View
![Marketing View](visuals/Marketing%20View.gif)


### 🔹 Supplychain View
![Supplychain View](visuals/Supplychain%20view.gif)


### 🔹 Stakeholder View
![Stakeholder View](visuals/Stakeholder%20view.gif)





---

