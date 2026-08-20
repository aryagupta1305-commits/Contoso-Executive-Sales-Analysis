# Contoso Executive Sales Data Analysis

An executive-facing Power BI report analyzing global sales performance, with a natural-language Q&A tool and key-influencer analysis.

## Report Pages

- **Executive Sales Overview** — KPI cards for total sales, total discount %, and total quantity, plus sales-by-month trend and region/country filtering
- **Toolkit** — natural-language Q&A visual ("Ask a question about your data"), filterable by continent, sales channel, and month
- **Key Influencers** — analysis of what drives SalesAmount up or down by manufacturer, with a decomposition tree by product category

## Key Findings

- Total sales: **$8.34bn** | Total quantity: **326K units** | Total discount: 12,671.39%
- December (month 12) had the highest sales amount at $785.8M — 40.02% higher than the lowest month (January, $561.2M) — accounting for 9.42% of total annual sales
- Fabrikam, Inc. is the top manufacturer by SalesAmount, followed by Contoso, Ltd. and Adventure Works
- **Key influencer finding:** SalesAmount is most likely to increase when the manufacturer is Fabrikam, Inc. — the single strongest positive influencer identified, followed by Adventure Works, Litware, and Wide World Importers
- Sales data spans multiple channels (Catalog, Online, Reseller, Store) and continents (Asia, Europe, North America), enabling flexible drill-down

## Tools

Power BI, Key Influencers visual, Q&A natural-language query, decomposition tree

## Files in this repo

- `Contoso_Executive_Sales_Analysis.pbix` — the Power BI file
- `screenshots/` — report page exports
