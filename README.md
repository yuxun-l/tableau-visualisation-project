# Business Performance Dashboards (Tableau)

A Tableau analysis of company sales and profit data from 2020 to 2023, covering five dashboards and a profit forecast through Q4 2025.

> Individual coursework project for **ST2187 Business Analytics, Applied Modelling and Prediction**, SIM-UOL, 2025.

## Table of Contents

- [Overview](#overview)
- [Dashboards](#dashboards)
- [Key Insights](#key-insights)
- [Recommendations](#recommendations)
- [Project Structure](#project-structure)
- [Data](#data)
- [Author](#author)
- [License](#license)

## Overview

This project visualises the company-provided dataset in Tableau to give a clear picture of business performance across products, customers, and markets. It also forecasts future profit and offers recommendations for improving the numbers, based on the patterns found in the data.

## Dashboards

The five dashboards are summarised below. View them in full in [tableau dashboard.pdf](tableau%20dashboard.pdf).

### 1. Profit and Sales Overview

A general view of business performance from 2020 to 2023.
- Profit by country
- Sales by segment
- Profit by year

### 2. Product Analysis

Performance of each product category.
- Sales and profit by category
- Ship mode by category

### 3. Customer Analysis

Insights into customer behaviour.
- Top customers
- Sales and profit of significant customers
- Ship mode by order priority

### 4. Market Analysis

Comparison of performance across markets.
- Profit ratio by market
- Sales by segment and market
- Profit comparison between the United States and Turkey by sub-category

### 5. Profit Forecast

Projection of future performance, with profit forecast up to Q4 2025.

## Key Insights

- **Profit is growing.** Profits rose from 2020 to 2023 and are forecast to keep increasing through 2025.
- **Strong seasonality.** Q4 is the most profitable quarter, driven by holiday gift buying, while Q1 is the weakest.
- **Consumers lead sales.** The Consumer segment accounts for 51.50% of total sales.
- **Three key markets.** APAC, EU, and US together generate 74.66% of total profits from 2020 to 2023.
- **Technology drives profit.** Technology products are the largest profit source thanks to higher profit margins.
- **Shipping preferences.** Standard Class is the preferred ship mode across all categories because of its lower cost. The exception is Critical order priority, where customers prefer First Class or Second Class.

## Recommendations

1. **Launch a New Year sale** to carry the Q4 momentum into Q1, the weakest quarter.
2. **Lower discount rates**, since heavy discounting cuts profit margins too much.
3. **Target Turkey with a tailored marketing strategy.** Turkey has the highest profit loss, so apply the 5Ps marketing mix (product, price, promotion, place, and people) to that market specifically.

## Project Structure

```
├── dataset.xlsx            # Dataset provided for the course
├── tableau dashboard.pdf   # Dashboards exported from Tableau
└── tableau report.docx     # Full written report
```

- [Dashboards (PDF)](tableau%20dashboard.pdf)
- [Full report (Word)](tableau%20report.docx)
- [Dataset (Excel)](dataset.xlsx)

## Data

The dataset was provided as part of the ST2187 course and contains order-level sales and profit records from 2020 to 2023. It has 51,229 rows, each representing one order line, across 24 fields:

| Group | Fields |
|---|---|
| Order | Row ID, Order ID, Order Date, Ship Date, Ship Mode, Order Priority |
| Customer | Customer ID, Customer Name, Segment |
| Location | City, State, Country, Postal Code, Market, Region |
| Product | Product ID, Category, Sub-Category, Product Name |
| Financials | Sales, Quantity, Discount, Profit, Shipping Cost |

The dataset is included as `dataset.xlsx` for reference, and remains the property of its original provider.

## Author

Liu Yu Xun · https://www.linkedin.com/in/yu-xun-liu/

This was completed as an individual project.

## License

The analysis, dashboards, and written content are done by © Liu Yu Xun 2025. The dataset (`dataset.xlsx`) belongs to its original provider and is not covered by this license.
