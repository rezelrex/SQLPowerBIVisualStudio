# Business Intelligence Report: Wide World Importers Sales Performance Analysis

This repository contains the Power BI report and supporting materials for an analysis of Wide World Importers' sales performance. The report provides key insights into sales and profit trends, geographic distribution, product performance, and customer segmentation to inform strategic decision-making.

## Report Period

[Specify Data Range, e.g., 2013-2016]

## Executive Summary

This report analyzes Wide World Importers' sales performance from [Start Year] to [End Year], focusing on overall trends, geographic distribution, product performance, and customer segmentation. Key findings indicate sales growth from 2013-2015, followed by a decline in 2016. Profit trends largely mirrored sales, although the profit decline post-2015 was less pronounced, suggesting potential cost management efforts. Sales are heavily concentrated in North America, with Texas, Pennsylvania, and California being the top-performing states. Analysis reveals a discrepancy between top-selling products (dominated by packaging materials) and top-profit-generating products. A significant portion of customers falls into an 'Unknown' category, highlighting a potential data gap. Recommendations include investigating the sales decline, optimizing product strategy based on profitability, focusing geographic efforts, and improving customer data capture and segmentation.

## Introduction

### Purpose

The purpose of this report is to provide WWI management with insights into the company's sales performance based on an analysis of the WideWorldImportersDW data warehouse.

### Scope

This analysis covers sales data from [Start Year] to [End Year], examining trends over time, performance across different geographic regions (primarily US states), sales and profitability by product, and basic customer segmentation. Sales figures are based on revenue excluding tax unless otherwise specified.

### Methodology

The analysis was conducted using Microsoft Power BI to connect to the WideWorldImportersDW database. Data was imported from relevant Fact and Dimension tables (Fact.Sale, Dimension.Date, Dimension.City, Dimension.StockItem, Dimension.Customer). Key metrics such as Total Sales (excluding tax) and Total Profit were calculated, and various visualizations were created to identify trends and patterns.

## Technologies Used

* Microsoft Power BI
* SQL Server (for the WideWorldImportersDW database)

## Data Source

The data for this report comes from the **WideWorldImportersDW** data warehouse.

## Key Findings & Analysis

### Overall Sales and Profit Trends

* **Sales Trend:** WWI experienced a period of slow but steady sales growth between 2013 and 2015. However, this trend reversed in 2016, with sales beginning to decline.
* **Profit Trend:** Profit followed a similar trajectory, increasing slowly from 2013 to 2015 before declining. Notably, the rate of profit decline from 2015 to 2016 appears slightly less steep than the rate of sales decline during the same period. This could suggest successful cost-cutting measures or changes in product mix impacting overall margins positively relative to the sales drop.

### Geographic Performance

* **Regional Concentration:** Sales are predominantly concentrated within North America.
* **Top Performing States:** The top three US states contributing the most to total sales revenue are Texas, Pennsylvania, and California, respectively.

### Product Performance Analysis

* **Top Selling Products:** The highest volume of sales revenue comes primarily from packaging materials. The top 5 products by sales revenue are:
    1.  Air Cushion Machine (Blue)
    2.  32mm Anti static bubble wrap (Blue) 50m
    3.  10mm Anti static bubble wrap (Blue) 50m
    4.  20mm double sided bubble wrap 50m
    5.  32mm double sided bubble wrap 50m
* **Top Profit Generating Products:** There is a notable difference when ranking products by total profit generated, indicating varying profit margins. The top 5 products by profit are:
    1.  20mm double sided bubble wrap 50m
    2.  Air Cushion Machine (Blue)
    3.  32mm Anti static bubble wrap (Blue) 50m
    4.  10mm Anti static bubble wrap (Blue) 50m
    5.  [You need the 5th item from your analysis here]
* **Implication:** High sales volume does not automatically equate to high profit contribution.

### Customer Segmentation Insights

* **Dominant Segments:** A large portion of sales (36.8%) is attributed to customers categorized as 'Unknown' within the Buying Group or Category dimension.
* **Key Known Segments:** Following the 'Unknown' group, the most significant customer segments identified are 'Tailspin Toys' (31.6%) and 'Wingtip Toys' (31.4%).

## Discussion

The analysis highlights a sales decline starting in 2016 that requires investigation into its root causes. While profit decline was less steep, its sustainability needs confirmation. Over-reliance on a few states presents a geographic risk. The difference between top-selling and top-profit products necessitates strategic product review. The large 'Unknown' customer segment is a critical data gap hindering targeted strategies.

## Recommendations

Based on the analysis, we recommend the following actions:

1.  **Investigate Sales Decline (High Priority):** Conduct further analysis to pinpoint the drivers of the sales decline and examine external/internal factors.
2.  **Validate Profit Trend:** Analyze cost structures and product mix changes to confirm reasons for the slower profit decline and ensure sustainable cost management.
3.  **Optimize Product Strategy:** Analyze the profitability of top-selling items, explore pricing/cost reduction for packaging materials, and promote high-profit items.
4.  **Refine Geographic Focus:** Maintain focus on top states while analyzing lower-performing ones for growth opportunities or reasons for underperformance.
5.  **Improve Customer Data & Segmentation (High Priority):** Implement processes to capture 'Unknown' customer data and develop targeted strategies for key known segments.

## Conclusion

WWI experienced growth up to 2015, but the subsequent sales decline requires attention. Strategic decisions regarding product mix, geographic focus, and especially customer understanding are crucial for navigating future challenges and returning to a growth trajectory. Addressing the customer data gap and optimizing product profitability should be key priorities.
