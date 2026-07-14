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
Cairn Coffee's first year in operation saw it generate $74,428.00 in revenue and $53,182.00 in profit, resulting in an overall profit margin of 71.5%. Cairn Coffee saw promising growth from Q1-Q2, fueled largely by the opening of the farmer's market in May. Q3, however, saw a dramatic decline in revenue stemming from a sharp drop in November sales, before recovering in Q4. A closer look at product sales numbers reveals coffee beans as the apparent profit engine, responsible for 59% of total profits, with bean subscriptions alone accounting for 32%. A similar profit distribution appears at the channel level, where the two top-performing channels (Online and Downtown Shop) combine to account for 78% of total profit. 

![Year 1 Dashboard](https://github.com/ArmandoDominguez97/Cairn-Coffee-Co.-Year-1-Sales-and-Profit-Analysis/blob/491feb6decd309a197e6b77417eabf396f0f99f1/Visualizations/Cairn_Coffee_Dashboard.png)
[Click Here](https://public.tableau.com/app/profile/armando.dominguez/viz/CairnCoffeeYear1SalesAnalysis/Dashboard12) to view the full interactive version of the dashboard

### Month-over-Month & Quarterly Trends

As previously mentioned, Cairn Coffee showed a solid profit yield of $53,182 with a 71.5% profit margin. A deeper look at the numbers on a quarterly and month-to-month basis reveals the following narrative:
- The first quarter delivered a promising beginning, with month-over-month profit growth exceeding 50% from April through June. This trajectory can be attributed to both the opening of the farmer's market in May and the subsequent spike in cold brew demand during the summer. Q1 also established coffee beans as Cairn's signature product category, contributing more than half of the total profit in April alone. This share would prove to hold steady throughout the rest of the year.
- Q2 built on the momentum of Q1 and proved to be the most profitable quarter of year 1. July stood out as the single strongest month of the year, driven mainly by a peak in cold brew demand. Profits in August and September retreated to levels consistent to the end of Q1, suggesting that July's peak reflects seasonal demand rather than a sustained upward trend.
- Q3's performance is defined by a dramatic decline in revenue and profit during the month of November, following the farmer's market closure at the end of October. This closure removed a seasonal revenue stream, with the impact felt most directly on cold brew demand. However, November also saw a decline in sales for all other products as well. December offered a meaningful recovery, driven in large part by a peak in coffee bean demand. Even so, November's steep underperformance was enough to pull Q3 down to the weakest quarter of the year.
- Q4 largely carried forward the momentum of December, with coffee bean demand holding close to its end-of-year high and overall profitability reflecting a near-full recovery from the November dip. That said, performance outside of coffee beans and cold brew remained flat, with all other product categories showing little meaningful growth throughout the year. Addressing that unevenness should be a priority heading into year 2, especially for the months where cold brew demand softens.

### Product and Category Performance

A review of product and category performance reveal pretty uniform transaction volumes, but when looking at profit and units sold, signifant differences emerge.
- Coffee beans have proven to be the company's only consistent profit engine, selling the most total units (2120) while contributing 59% of the Cairn's total profit during the first year. Bean Subscriptions in particular, generated nearly a third (32%) of all profit, and were the main driver behind the company's resurgance in December of 2025. Another thing to note, one major reason why coffee beans generate their profit is because of their price, which is higher than all other categories per unit. Given their popularity, as well as the fact that they share the lowest profit margins, raising their price to more closely resemble the margins of other products could improve efficiency.
- Cold brew beverages have demonstrated promise as another profit engine, but their potential appears to be seasonal. Despite selling nearly as many total units (2033) as beans, the overwhelming majority of that bulk was moved during the summer months when the farmer's market was open. During that time, Cold brews became responsible for as much as 29% of total profit. The month of November shows what can happen every fall, when the demand of cold brew falls without a suitable alternative to take it's place. 
- Espresso beverages were the third most profitable product category, generating 11% of the total profit of Cairn's Coffee. Their performance showed little variance throughout. However, based on how close they were in profit to cold brews, and the hotter nature of espresso beverages, I believe that they have untapped potential as a winter seasonal analogue to cold brew products in the summer. 

