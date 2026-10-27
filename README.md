# 🛒 E-commerce Sales and Delivery Dashboard

## 📌 Project Overview

The **E-commerce Sales and Delivery Dashboard** is a data analytics project designed to monitor sales performance, understand product category contributions, analyze revenue trends, and evaluate delivery performance.

The project transforms e-commerce data into an interactive dashboard that helps users explore key business performance indicators (KPIs), identify trends, compare sales across locations, and support data-driven decision-making.

The dashboard provides a consolidated view of revenue, order volume, average order value, and delivery timelines, making it easier to understand business performance at a glance.

## 🎯 Project Objectives

The primary objectives of this project are to:

- Analyze overall e-commerce revenue performance.
- Monitor the total number of orders.
- Calculate and track Average Order Value (AOV).
- Evaluate average delivery time.
- Compare revenue across product categories.
- Analyze revenue trends over time.
- Explore revenue distribution across customer locations.
- Compare revenue and delivery performance by customer state.
- Provide actionable recommendations to support business growth and operational efficiency.

## 📊 Dashboard Preview

![E-commerce Sales and Delivery Dashboard](images/dashboard.png)

*The dashboard provides an overview of sales performance, product category revenue, geographical distribution, and delivery metrics.*

## 🛠️ Tools and Technologies

- **Microsoft Power BI:** Dashboard development and data visualization, if applicable to the original project.
- **Data Analysis:** Exploration and interpretation of e-commerce sales and delivery data.
- **Business Intelligence:** KPI monitoring, trend analysis, and performance reporting.

*Update this section to reflect the exact tools used in your project. Include Excel, SQL, Python, or Power Query only if you used them during this analysis.*

## 📈 Key Performance Indicators (KPIs)

The dashboard displays the following headline metrics in the current screenshot:

| KPI | Displayed Value | Description |
|---|---:|---|
| Total Revenue | 4.56M | Total revenue represented by the dashboard's current filter selection. |
| Total Orders | 37K | Number of orders represented by the current filter selection. |
| Average Order Value (AOV) | 124.68 | Average revenue per order, subject to the underlying calculation. |
| Average Delivery Days | 8.51 | Average delivery duration in days, based on the available delivery data. |

*Note: These figures reflect the screenshot's current filter settings. Values may change when filters are applied. Confirm the currency and KPI definitions against the source data before publishing.*

## 📉 Dashboard Visualizations

### 1. Revenue by Year

Displays the distribution of sales value across years to help identify changes in revenue performance over time.

**Business questions:**
- How has revenue changed from year to year?
- Which years contributed most to total sales?
- Are there periods of stronger or weaker sales performance?

### 2. Revenue by Product Category

Compares revenue across product categories, including categories displayed as `utilidades_domesticas`, `telefonia`, `Uncategorized`, and `telefonia_fixa`.

**Business questions:**
- Which product categories generate the most revenue?
- Which categories contribute relatively little to sales?
- Are uncategorized products affecting the quality of product reporting?

### 3. Revenue and Average Delivery Days by Customer State

Combines geographical sales performance with delivery duration to support comparisons between customer states.

**Business questions:**
- Which states contribute most to revenue?
- Do delivery timelines vary across locations?
- Which locations may require further operational investigation?

The measures should be interpreted using appropriate chart scales because revenue and delivery days use different units.

### 4. Revenue by Customer City

Uses a doughnut chart to illustrate the distribution of revenue across customer cities.

**Business questions:**
- Which cities account for the largest shares of revenue?
- How is revenue distributed geographically?
- Which cities may offer opportunities for targeted marketing or expansion?

### 5. Revenue Trend Over Time

Displays the progression of total revenue across the years shown in the dashboard.

**Business questions:**
- Is revenue increasing or decreasing over time?
- At what point does revenue growth accelerate or slow?
- What additional analysis could explain the observed trend?

### 6. Interactive Filters

The dashboard includes filters for customer state and month, allowing users to narrow the analysis to selected geographical areas and periods.

These filters support more focused comparisons and help users investigate how performance changes across different segments.

## 🔍 Key Observations

Based on the dashboard screenshot, the following observations can guide further analysis:

- **Sales performance:** The dashboard reports total revenue of 4.56M and 37K orders under the displayed filter selection.
- **Average order value:** The displayed AOV is 124.68, providing a baseline for investigating purchasing behavior.
- **Delivery performance:** The average delivery duration is 8.51 days, which can be compared across customer locations.
- **Product categories:** Revenue appears concentrated in a small number of the displayed product categories. The underlying figures should be validated before quantifying their contributions.
- **Geographical performance:** The city and state visuals allow users to investigate differences in sales contribution and delivery performance.
- **Revenue trends:** The time-based charts provide a starting point for identifying changes in sales over the years shown.

These are preliminary observations from the dashboard. Further analysis of the underlying dataset would be required to establish causes, quantify differences, and confirm business implications.

## 💡 Business Recommendations

Based on the questions the dashboard is designed to answer, the following actions could help improve business performance:

1. **Strengthen high-performing product categories:** Investigate the products, pricing, and customer demand behind the highest-revenue categories.
2. **Improve delivery efficiency:** Examine order processing, dispatch, and shipping performance to identify opportunities to reduce delivery duration.
3. **Investigate geographical differences:** Compare revenue, order volume, and delivery timelines by state and city to identify areas requiring attention.
4. **Improve product categorization:** Review uncategorized products to improve reporting accuracy and product-level decision-making.
5. **Monitor sales trends:** Track revenue and order performance over time to identify growth opportunities and periods that need further investigation.
6. **Explore average order value:** Analyze product combinations, customer purchasing behavior, and order values to identify opportunities to increase spending per order.
7. **Use filters for targeted decisions:** Review individual months and states to investigate changes in performance instead of relying exclusively on overall totals.

These recommendations should be prioritized after validating the underlying data and confirming the specific causes of the observed patterns.

## 🧮 KPI Definitions

The following are standard definitions that can be used to validate the dashboard calculations against the source data.

### Total Revenue

The sum of the revenue measure for the selected orders.

**General formula:**

`Total Revenue = SUM(Revenue)`

Confirm whether the dataset uses product price, order revenue, or another sales measure.

### Total Orders

The number of distinct orders included in the analysis.

**General formula:**

`Total Orders = DISTINCTCOUNT(Order ID)`

If each row already represents one unique order, a row count may be appropriate instead.

### Average Order Value (AOV)

Average revenue per order.

**General formula:**

`AOV = Total Revenue / Total Orders`

The numerator and denominator should use consistent filters and definitions.

### Average Delivery Days

The average number of days taken to deliver eligible orders.

**General formula:**

`Average Delivery Days = AVERAGE(Delivery Days)`

The delivery duration should be calculated using valid order and delivery dates, where available.

*These formulas describe standard KPI definitions. They are not confirmation of the exact formulas implemented in the report.*

## 📂 Suggested Repository Structure

```text
ecommerce-sales-delivery-dashboard/
│
├── README.md
├── images/
│   └── dashboard.png
├── data/
│   └── ecommerce_dataset.csv
└── ecommerce_dashboard.pbix
```

The dataset and Power BI file shown above are examples of possible filenames. Replace them with your actual filenames and omit any files you do not have or cannot share.

## 🚀 How to Explore the Project

1. Open the dashboard screenshot in the `images` folder.
2. Review the KPI cards to understand the headline performance metrics.
3. Explore revenue by year and product category.
4. Compare revenue across customer cities and states.
5. Use the state and month filters to investigate specific segments.
6. Review the underlying project file, if available, to inspect the calculations, data model, and visualizations.

## 📚 Skills Demonstrated

This project demonstrates the following data analytics and business intelligence skills:

- KPI reporting and performance monitoring.
- Exploratory data analysis.
- Sales trend analysis.
- Product category analysis.
- Geographical performance analysis.
- Delivery performance monitoring.
- Data visualization and dashboard design.
- Business insight development.
- Data-driven decision-making.

Only list tools and techniques that you actually used in the project.

## ⚠️ Data and Reporting Notes

- KPI values are based on the data and filters used in the dashboard.
- Currency, revenue definitions, and the reporting period should be confirmed from the source dataset.
- The screenshot alone does not establish the exact data source, data-cleaning steps, or formulas used.
- Any dataset shared publicly should be checked for privacy, licensing, and permission to redistribute.
- The displayed visualizations should be validated against the underlying data before making business-critical decisions.

## 👩‍💻 About the Analyst

I am an aspiring data analyst developing practical skills in data analysis, data visualization, and business intelligence.

Through projects like this, I aim to transform raw data into meaningful insights that help businesses understand performance, identify opportunities, and make informed decisions.

I am continuously learning and building my portfolio through hands-on data analytics projects.

## 🤝 Feedback and Collaboration

Feedback, suggestions, and opportunities to collaborate on data analytics projects are welcome.

If you have ideas for improving the dashboard or extending the analysis, feel free to share them.

## ⭐ Project Highlights

- Interactive e-commerce sales and delivery dashboard.
- Revenue and order performance monitoring.
- Product category and geographical analysis.
- Delivery timeline evaluation.
- KPI-driven reporting and business recommendations.

**Thank you for exploring this project!**
# E-commerce-Sales-and-Delivery-Dashboard
The E-commerce Sales and Delivery Dashboard is a data analytics project designed to monitor sales performance, understand product category contributions, analyze revenue trends, and evaluate delivery performance.
