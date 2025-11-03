# Data-Visualization-R | June 2020

# Task
Analyze the data, determine two significant findings (practical and
statistical) related to profitability, create a professional quality
visual(s) for each finding, and provide a brief write up of your findings and recommendations in
a memo using best practices

# Deliverables
The TA .Rmd is the Technical Appendix containing the EDA that my partner and I used to explore and analyze the data.
The Memo .Rmd is a write-up of ou findings and recommendations of how to strategize.

# Data
the data is in “mtp_off_mate.csv”,
which includes the following variables:
1. Order ID: Each order ID is unique, but may contain several products
2. Order Date: Date the order was placed
3. Ship Date: Date order was shipped
4. Ship Mode: Shipping method
5. Customer ID: Each customer has a unique ID, but can make more than one order
6. City, State, Postal Code: For the location of each sale in continental US
7. Region: Sales region in the United States (Central, East, South, West)
8. Product ID: Product ID code
9. Product Name: Name of product sold
10. Segment: Customer segment (Consumer, Corporate, Home Office)
11. Category: Type of product sold (Furniture, Office Supply, Technology)
12. Sub-Category: Detailed type of product sold
13. Revenue = Price * Quantity (though the dataset does not include Price)
14. Quantity = number of units of the specific product sold for that order
15. Discount: Percent discount from full Price. Large discounts are used to clear inventory.
16. Profit = Revenue – Cost (not including shipping or tax, both passed directly to customer)
Each observation is for the sale of a specific product from an order that may contain multiple
products. The Order ID variable links products from the same order. The customer ID identifies
unique customers that may have multiple orders.

