# Black-Friday-Sales-Analysis

Data Files: The analysis is based on four interconnected datasets, each providing a specific piece of information:

orders.csv: The central transactions table, containing a unique order_id for each sale.

order_details.csv: A detailed table linking specific products to their respective order_id and including quantities sold.

product_info.csv: A reference table containing details about each product, such as its name, category, and price. It connects to order_details.csv via a product_id.

order_types.csv: A supplemental table that classifies each order by its sales channel (e.g., online, in-store).


# Methodology and SQL Analysis
Describe the analytical process you followed, emphasizing the use of SQL to join the data and answer specific business questions.

Analytical Process: The core of this analysis involves using SQL to join these datasets into a single, cohesive view. The process can be broken down into the following key steps:

Data Integration: Use JOIN operations to merge the four datasets, primarily linking them through order_id and product_id. This creates a unified table with all the necessary information for analysis.

Sales Performance: Write queries to calculate total sales and average order value.

Product Insights: Analyze which product categories were the most popular and which specific products generated the highest revenue.

Customer Behavior: Investigate purchasing trends, such as the average quantity of items per order or which categories are most frequently purchased together.

Channel Analysis: Compare sales performance and customer behavior across different order types (online vs. in-store).
