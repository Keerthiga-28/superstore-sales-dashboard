# Superstore Sales & Profit Analysis

An Excel and Tableau project that analyses sales and profit for a retail store, to find which regions, products and years drive the business, and where it loses money.

**Live dashboard:** https://public.tableau.com/app/profile/keerthiga.mouttayan/viz/SuperstoreSalesandProfitAnalysis_17956074746570/SalesDashboard

![Dashboard](Sales%20Dashboard.png)

## Business questions
1. Which regions sell the most?
2. Which product categories and sub-categories are actually profitable?
3. How have sales changed from 2014 to 2017?

## Tools used
- Excel / Power Query: data cleaning
- Excel pivot tables: analysis
- Tableau Public: dashboard

## Data cleaning
- Source: Superstore sample dataset (Kaggle), 9,994 rows and 21 columns
- Fixed mixed date formats by re-importing with the US date locale
- Converted Sales, Quantity, Discount and Profit from text to numbers
- Found and removed 1 duplicate order line, leaving 9,993 rows
- Checked for missing values and found none

## Key insights
- **Regions:** West and East bring in about 61% of total sales. South is the weakest region.
- **Categories:** Technology has the highest sales (about 36%). Furniture makes about 32% of sales but only about 6% of profit, a margin of about 2.5% compared with about 17% for the other two categories.
- **Loss-makers:** Tables (-17,725), Bookcases (-3,473) and Supplies (-1,189) lose money.
- **Discounts:** Tables and Bookcases have the highest average discounts in Furniture (26% and 21%), which is a likely factor in their losses. Binders have a 37% average discount and are still profitable, so discounting does not explain everything.
- **Trend:** Sales dipped slightly in 2015, then grew strongly. Total sales rose about 52% from 2014 to 2017.

## Recommendation
Review discount levels on Tables and Bookcases, and look at whether pricing or costs also play a part.

## Files
- `superstore_cleaned.xlsx`: cleaned data and pivot tables
- `Sales Dashboard.png`: dashboard screenshot
