# Supply-Chain-Overview-Report
## Dataset Information

This dataset was originally shared in a private SQL-based data analysis group. While the initial goal was to explore customer retention and delivery delays, I repurposed it for a full end-to-end Supply Chain Overview Dashboard in Power BI.

Data Source: Group collaboration (not from public repositories like Kaggle)

## Tables and Row Counts:
	•	orders – 38,000 
	•	order_items – 83,780
	•	products – 200
	•	customers – 15,210
	•	suppliers – 15 
	•	locations – Rivers, Abia, FCT, Edo, Cross River, Enugu, Plateau, Kaduna, Kano, Lagos, Imo, Akwa Ibom, Delta

## Data Cleaning & Preparation

Before building the dashboard, the data went through several cleaning and transformation steps:
	•	Removed duplicates and blanks in key fields (e.g. customer ID, order date)
  •	Standardized product and supplier names for consistency
	•	Fixed data types (e.g. converted dates to proper format)
	•	Handled missing values in ratings, delivery status, and product status
	•	Created calculated columns (e.g. delivery status, delivery delays, customerType, shippinglocation)
	•	Merged tables using Power BI relationships and Power Query

 ## Project Summary
This dashboard offers a complete view of the supply chain across four key areas: products, revenue, customer orders, and suppliers. It was designed to identify operational gaps, revenue patterns, and areas for improvement in delivery and supply reliability.

## Product Insights
This session focuses on key metrics related to product availability, supply and performance. It gives a quick snapshot of how the product line-up is doing within the supply chain system.
- 200 products tracked with 387,000 units produced.
- Highest revenue from Groceries, followed by Health & Beauty.
- Top product by revenue: *You Are Providing Yourself Basic* (₦6.37B).
- Most supplied: *Happy live instead Pro*.
- Out-of-stock items remain significant at 128,000 units.

## Revenue Insights
This section highlights revenue performance across locations, products, suppliers, and time. It provides visibility into revenue growth trends and areas of high financial contribution.
- Highest revenue by location: Port Harcourt (₦43.98B).
- 2024 revenue: ₦46.7M (+236,770%) | 2025 revenue: ₦12.7M (−37.62%).
- *Believe National Put Pro* led product revenue (₦13.54B).
- August had highest monthly revenue; July had highest MoM growth (356.54%).

## Customer & Order Insights
This section explores customer behavior and order trends, focusing on who is buying, how often, and how efficiently orders are being fulfilled including both early and late deliveries.
- Total orders: 38,000 | Delivered: 13,000 | Purchases: 35,750.
- Old customers ordered more (23,469) than new (14,971).
- Most frequent customer: C00001.
- Portharcourt and Lagos placed the most orders.
- Delivery delays were common in 2025, especially for new customers.

## Supplier Insights
This section focuses on supplier activity, performance, and contribution to the supply chain in terms of quantity supplied, revenue earned, and product availability. It also considers supplier ratings where available.
- 15 suppliers | 387,000 units supplied | €43.41B revenue.
- Top suppliers by quantity: Nguyen Matthews, Fitzpatrick Ltd, Moore Group.
- Top revenue supplier: Bowers and Sons.
- Supplier ratings reveal performance risks: poor rated suppliers delivered large volumes.
- Unrated and unknown-rated suppliers need evaluation.

## Recommendations
- Investigate 2025 revenue decline and late delivery trends.
- Improve delivery experience for new customers.
- Focus on reliable, high-rated suppliers.
- Track supplier performance consistently.
- Optimize stock for in-demand products.

**Tools Used**: Power BI    
**Focus Area**: Data Analysis | Supply Chain | BI Reporting

2025 Midong Kefas | Data Analyst
