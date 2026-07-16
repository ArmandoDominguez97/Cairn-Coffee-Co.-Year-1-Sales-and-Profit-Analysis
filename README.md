# Cairn Coffee Year 1 Sales and Profit Analysis
![Cairn Coffee Logo](https://github.com/ArmandoDominguez97/Cairn-Coffee-Co.-Year-1-Sales-and-Profit-Analysis/blob/8090a0189789d1eace216d23fbba3304d820e84c/Screenshot%202026-07-12%20182341.png)
## Table of Contents

## Background
Cairn Coffee, established in 2025, is a small craft coffee company establised and based in West Haven, CT. Cairn Coffee offers a range of products such as coffee drinks, packaged beans and branded merch.

Cairn Coffee sells its products at three physical locations as well as an online e-commerce store. The company recently celebrated it's first full year of operation this past April, and their two owners were looking for insight what has worked for them, what hasn't, and what they should focus on for year 2 based on the sales from year 1. 

Insights and recommendations are provided on the following areas:
- **Sales Trend Analysis:** Evaluation of sales patterns througout the first year in operation, focusing on the total revenue and profit across each month and quarter.
- **Product Performance:** An analysis of Cairn Coffee's products, to identify top-performining products worthy of continued investment, and to uncover products that are lagging significantly, and may require targeted intervention.
- **Channel Comparision:** Cairn Coffee sells it's products through four distinct channels, each evaluated on its contribution to total profit, and operational efficiency.

## Data Structure
- **Source:** This analysis is was done on real sales data for an actual coffee company. For confidentiality purposes, I have replaced the real data with syntheitc "dummy" data and replaced the company's branding as well.
- **Values:** 630 transactions in dataset
- **Duration:** April 2025 - March 2026
- **Scope:** Three physical store locations and one online store across southwestern CT.
  
| Column | Description |
|---|---|
| `Order ID` | Unique transaction identifier |
| `Date` | Date of transaction |
| `Product` | Product that was sold |
| `Category` | Category of sold product |
| `Channel` | Store  |
| `Quantity` | Number of units sold |
| `Unit Price` | Price of individual unit item |
| `Revenue` | Total amount paid by consumer |
| `Cost` | Cost of items for seller |
| `Profit` | Amount earned by seller after subtracting cost of sold items |

## Executive Summary
### Overview of Findings
Cairn Coffee's first year in operation saw it generate $74,428.00 in revenue and $53,182.00 in profit, resulting in an overall profit margin of 71.5%. Cairn Coffee saw promising growth from Q1-Q2, followed by a concerning trough in Q3, before recovering in Q4. As a result, H2 was about 17% less profitable than H1. A look at monthly revenue shows that sales peaked during the summer months, which coincides with the opening of the farmer's market, a seasonal channel that temporarily provided an extra source of revenue. Another crucial finding reveals that Cairn's peak during Q2 and subsequent decline during Q3 coincides with the demand for the company's cold brew beverages; Q2 saw the product category experience a substabtial spike in demand, while Q3 saw demand crater drastically. Luckily, coffee beans have proven the be the main profit engine for Cairn's Coffee, as their spike in sales during Q4 allowed the company to make it's way back towards an upward trajectory.

![Year 1 Dashboard](https://github.com/ArmandoDominguez97/Cairn-Coffee-Co.-Year-1-Sales-and-Profit-Analysis/blob/491feb6decd309a197e6b77417eabf396f0f99f1/Visualizations/Cairn_Coffee_Dashboard.png)
[Click Here](https://public.tableau.com/app/profile/armando.dominguez/viz/CairnCoffeeYear1SalesAnalysis/Dashboard12) to view the full interactive version of the dashboard

### Month-over-Month & Quarterly Trends

![Profit and Revenue Snapshot](https://github.com/ArmandoDominguez97/Cairn-Coffee-Co.-Year-1-Sales-and-Profit-Analysis/blob/7b7cabe884d177d5c78941ae92f6efe07375c908/Visualizations/Revenue%20%26%20Profit.png)

As previously mentioned, Cairn Coffee showed a solid profit yield of $53,182 with a 71.5% profit margin. A deeper look at the numbers on a quarterly and month-to-month basis reveals the following narrative:
- The first quarter delivered a promising beginning, with month-over-month profit growth exceeding 50% from April through June. This trajectory can be attributed to both the opening of the farmer's market in May and the subsequent spike in cold brew demand during the summer. Q1 also established coffee beans as Cairn's signature product category, contributing more than half of the total profit in April alone. This share would prove to hold steady throughout the rest of the year.
- Q2 built on the momentum of Q1 and proved to be the most profitable quarter of year 1. July stood out as the single strongest month of the year, driven mainly by a peak in cold brew demand. Profits in August and September retreated to levels consistent to the end of Q1, suggesting that July's peak reflects seasonal demand rather than a sustained upward trend.
- Q3's performance is defined by a dramatic decline in revenue and profit during the month of November, following the farmer's market closure at the end of October. This closure removed a seasonal revenue stream, with the impact felt most directly on cold brew demand. However, November also saw a decline in sales for all other products as well. December offered a meaningful recovery, driven in large part by a peak in coffee bean demand. Even so, November's steep underperformance was enough to pull Q3 down to the weakest quarter of the year.
- Q4 largely carried forward the momentum of December, with coffee bean demand holding close to its end-of-year high and overall profitability reflecting a near-full recovery from the November dip. That said, performance outside of coffee beans and cold brew remained flat, with all other product categories showing little meaningful growth throughout the year. Addressing that unevenness should be a priority heading into year 2, especially for the months where cold brew demand softens.

### Product and Category Performance

![Category Profit Line Graph](https://github.com/ArmandoDominguez97/Cairn-Coffee-Co.-Year-1-Sales-and-Profit-Analysis/blob/7b7cabe884d177d5c78941ae92f6efe07375c908/Visualizations/Category%20by%20Profit.png) ![Product Breakdown Table](https://github.com/ArmandoDominguez97/Cairn-Coffee-Co.-Year-1-Sales-and-Profit-Analysis/blob/7b7cabe884d177d5c78941ae92f6efe07375c908/Visualizations/Product%20Breakdown.png)

A review of product and category performance reveal the following insights:
- Coffee beans are the company's largest and most consistent profit engine, leading all categories in units sold (2120) while contributing 59% of total profit in year 1. Bean subscriptions were the standout within that category, generating nearly a third of all company profit and serving as the main driver behind the company's resurgence in December. These results occurred despite the fact that beans are the products with the thinnest profit margins, most likely a result of their higher prices in comparison to other categories. Perhaps the company may be able to adjust bean prices to closer resemble the other products, and further strenghten the company's bottom line moving forward.
- Cold brew beverages have demonstrated promise as a secondary profit engine, though one with seasonal limitations. Despite selling nearly as many total units (2033) as beans, the overwhelming majority of that sales volume was concentrated in the summer months, coinciding with the farmer's market being open. During that time, cold brews accounted for as much as 29% of monthly profit. Given the seasonal nature of cold brew sales volume, a potential repeat of November's revenue drop looms without a winter alternative to cold brew's summer demand. 
- Espresso beverages ranked as the third most profitable category, contributing 11% of total company profit with relatively stable performance throughout the year. Given how closely espresso trails cold brew in total profit distribution, and the temperature range of such products, the category seems like the best candidate to serve as a winter counterpart to cold brew's summer dominance. A targeted seasonal strategy around espresso could help make up for lost cold brew demand during the winter months.
-  Merch and drip coffee products both fall to the bottom in terms of sales volume, revenue and profit. However, merch performance may be more useful to view as a gauge for brand equity. A brand's merchandise is most likely purchased by it's most loyal customers. With that said, merch sales will likely grow naturally as a result of new customer acqusition, which depends on the strategies employed to stimulate growth for the other products.
