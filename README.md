# Adidas-Case-study-
Adidas case study contains dataset that is solved using excel functions 

I recently worked on a data analysis project for Adidas using Excel to explore key insights from a dataset that included sales details such as sales_id, retailer, retailer_id, invoice_date, region, state, city, product, price_per_unit, units_sold, total_sales, operating_profit, and sales_method. The goal was to analyze sales performance and extract actionable information through various Excel functions.

I started by utilizing the LOOKUP function to link sales IDs with the respective retailers and their products, allowing a quick overview of sales records. To evaluate profitability, I applied the IFS function, which provided an efficient way to check if the operating profit exceeded 900. For values above 900, the output was labeled "profitable," while profits under 900 were flagged as "profit is less, need improvement," highlighting areas where attention was required.

I then filtered the dataset to display only the results for the online sales method, providing a more focused view of this segment. By using the AVERAGE function, I calculated the average total sales specifically for online transactions, giving a clear understanding of online sales performance.

In terms of regional categorization, I used text functions to simplify region names by representing South East as SE, West as W, South as S, Northeast as North, and Midwest as Mid, which enhanced readability in the analysis. Additionally, I replaced the term “outlet” with “branch” throughout the dataset to maintain consistency in terminology.

This project provided valuable insights into the sales and profitability metrics for Adidas and showcased the power of Excel in driving data-driven decision-making. The combination of logical functions like IFS, LOOKUP, FILTER, and text manipulation techniques allowed for a comprehensive and interactive analysis of the data.
