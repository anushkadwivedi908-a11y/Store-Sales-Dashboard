# Store Sales Dashboard (Power BI)

An interactive Power BI dashboard analyzing store sales performance across India — covering revenue trends, top-selling products, payment method preferences, and customer satisfaction.

## Dashboard Preview
![Store Sales Dashboard](dashboard-screenshot.png)

## Key Metrics Tracked
- **Total Sales:** 64M
- **Total Quantity Sold:** 2K units
- **Transactions:** 320
- **Average Sale Value:** 40.38K

## Features
- **Sales by City (Map View):** Geographic breakdown of total sales across major Indian cities (Delhi, Mumbai, Bangalore, Chennai, and more)
- **Sum of Units Sold by Day:** Daily trend line tracking unit sales fluctuations over the month
- **Top 3 Best-Selling Models:** iPhone SE, Galaxy Note 20, and OnePlus 9 ranked by units sold
- **Payment Method Breakdown:** Distribution of transactions across Credit Card, Cash, UPI, and Debit Card (pie chart)
- **Customer Ratings:** Satisfaction distribution across a 1-5 star rating scale
- **Sales by Day of Week:** Revenue trend showing which weekdays perform best
- **Month Filter (Slicer):** Interactive filter to view data for any specific month (Jan-Dec)

## Key Insights
- "Credit Card is the most preferred payment method at 27.81% of transactions"
- "iPhone SE leads as the top-selling model with 7.2K units"
- "Wednesday recorded the highest sales at 11.1M, while Sunday saw the lowest at 7.9M"

## Tech Stack
- Power BI Desktop
- DAX (for calculated measures like AVG, SALESofM)
- Power Query (for data cleaning/transformation)

## Dataset
- **Source:** Taken form an open source kaggle
- **Fields used:** City, Date, Product Model, Payment Method, Transaction ID, Customer Rating, Units Sold, Sales Amount

## How to View
Since this is a Power BI file, you'll need Power BI Desktop (free) to open it interactively:
1. Download [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
2. Clone/download this repo and open `Store Sales Dashboard.pbix`
3. Use the month slicer on the left to filter by month and explore

Alternatively, view the static screenshots above for a quick overview without installing anything.

## What I Learned
- "Building interactive slicers and cross-filtering across visuals"
- "Using DAX to create calculated measures like average transaction value"

## Future Improvements
- "Add year-over-year comparison"
- "Build a predictive sales forecast using Power BI's forecasting feature"

## Author
Anushka - www.linkedin.com/in/anushka-dwivedi-15069933b
