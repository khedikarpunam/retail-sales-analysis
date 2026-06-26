# Real-World Data Project — Retail Sales Analysis

End-to-end analysis of a real-world retail sales dataset to uncover sales trends, top products, top markets, and key relationships.

## Dataset
`sales_data_sample.csv` — 2,823 retail orders with order details, product line, customer location, deal size, and sales figures.

## What was done
- Cleaned the data (dropped unused contact/address columns, filled missing location data)
- Converted order date to a proper date format
- Statistical summary of quantity, price, sales, and MSRP
- Monthly sales trend analysis
- Sales breakdown by product line, country, and deal size
- Correlation analysis between sales and order details

## Key Insights
- Sales show a clear seasonal spike around November each year, likely driven by holiday shopping.
- Classic Cars is the top-performing product line by total sales.
- USA and Spain are the top two revenue-generating markets.
- Average sales increase from Small → Medium → Large deals (~4x difference between Small and Large).
- Sales is strongly correlated with Price and Quantity (unlike the customer dataset from the EDA project, where correlations were near zero) — because Sales is mathematically derived from price and quantity.

## Tools
Python, Pandas, Matplotlib, Seaborn
