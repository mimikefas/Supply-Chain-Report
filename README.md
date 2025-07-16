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

## Key Findings from Dashboard

 ## Product Insights
	•	Total Products Tracked: 200
	•	Total Quantity Produced: 387,000 units
	•	Total Quantity in Stock: 128,000 units
	•	Top Product Status:
	•	Active: 68 products (highest count)
	•	Out of Stock: A smaller portion, suggesting possible demand-supply gaps
	•	Top Supplied Product: Happy Life Insights Pro
	•	Highest Revenue-Generating Product: You Are Providing Yourself Basic with ₦6.37 billion
	•	Product Categories by Revenue:
	•	Groceries generated the highest revenue
	•	Followed by Health and Beauty

## Revenue Insights

#  General (All Years Combined)
	•	Total Revenue (Top Location):
	•	Port Harcourt generated the highest revenue at ₦43.98 billion
	•	Top Revenue Product: BLEEF National Poot Pro – ₦13.5 billion
	•	Top Supplier by Revenue: Bowers and Sons – ₦21.64 billion
	•	Best Revenue Month: August – ₦13.97 million
	•	Highest Month-over-Month Growth: July – 356.54%
	•	Worst Month-over-Month Drop: September – −85.04%

# Revenue Insights for 2024
	•	Total Revenue: ₦46.71 million
	•	Top Revenue Product: Dinner Baby Heme  Pro – ₦3.5 million
	•	Highest Revenue Status: Partially Shipped – ₦535.56K
	•	Top Supplier in 2024: Brown Group – ₦3.7 million
	•	Peak Month by Revenue: May – ₦3.65 million
	•	Quarterly Revenue Change: +361,860%
	•	Top Product in May: Believe National Poot Pro

# Revenue Insights for 2025
	•	Total Revenue: ₦12.73 million
	•	Highest Revenue Product: Dinner Baby Heme Pro – ₦3.5 million
	•	Highest Month-over-Month Growth: March – 237.33%
	•	Worst Performing Month: November – −100%
	•	Top Revenue Supplier: Boaz and Sons – ₦21.64 billion
	•	Quarterly Revenue Change: −37.62%

## Customer & Order Insights
	•	Total Orders: 38,000
	•	Total Purchases: 35,750
	•	Total Orders Delivered: 13,000
	•	Top Order Locations:
	•	Port Harcourt – 21,183 orders
	•	Lagos – 7,447 orders
	•	Customer Types:
	•	Old Customers made more orders – 23,469
	•	New Customers – 14,971
	•	Most Frequent Customer: C00001

# Delivery Timing Breakdown:
	•	Early Deliveries:
	•	Orders: 5,357 | Delivered: 3,530
	•	Old Customers: 3,342 | New Customers: 2,015
	•	Late Deliveries:
	•	Orders: 7,496 | Delivered: 5,035
	•	Old Customers: 4,515 | New Customers: 2,981
# By Order Status:
	•	Delivered: 12.8K
	•	Shipped: 6.47K
	•	Returned: 6.4K
	•	Partially Shipped & Processing: ~6.36K each

## Supplier Insights
	•	Total Quantity Supplied: 387,000
	•	Number of Suppliers: 15
	•	Total Supplier Revenue: ₦43.41 billion
	•	Top Supplier by Quantity: Nguyen Matthews – 89,675 units
	•	Top Supplier by Revenue: Bowers and Sons – ₦21.64 billion

# Supplier Ratings Breakdown:

# Ratings Suppliers  Revenue	Top Product	            Quantity Supplied
Excellent   2	    ₦6.72B	Facts Go Something Dulux	4,800
Good	    3	    ₦10.76B	Believe National Poot Pro	7,000
Average	    1	    ₦1.18B	Adira Peach Eco	                11,000
Poor	    4	    ₦17.25B	Cat Shoulder Lease A Echo	117,000
Unknown	    2	    ₦3.58B	Drive Agent 1 Azume Plus	29,000
Unrated	    3	    ₦3.94B	Hand Center Audience Deluxe	111,000

## Insights from the Supply Chain Overview

## Product Insights
	•	Inventory imbalance detected: Out of 387,000 products produced, only 128,000 are still in stock, suggesting high demand — or a mismatch in production vs. consumption cycles.
	•	Active products dominate inventory: 68 products are currently active, showing strong product line availability. However, a notable portion is also out of stock — this could mean some popular products aren’t being replenished quickly enough.
	•	Category focus is clear: Groceries dominate revenue, followed by Health & Beauty. This suggests future promotions and supply efforts should target these segments.
	•	One product heavily leads in revenue: “You Are Providing Yourself Basic” generated ₦6.37B — likely a flagship product. It may need priority in marketing, stock planning, and supplier focus.

## Revenue Insights

# General (Across 2024 & 2025)
	•	Port Harcourt is a strategic revenue hub – ₦43.98B in total revenue signals this location as a key sales driver. Ensuring smooth logistics and supplier availability here could protect revenue flow.
	•	BLEEF National Poot Pro is the revenue leader – ₦13.5B makes it the top product. Any supply delay on this product could have major revenue impact.
	•	Revenue volatility is very high – Month-over-month changes ranged from +356% to −85%, showing unstable demand or external market influences like pricing or competition.
	•	July and August drive peak sales – These may be seasonal periods. Forecasting and stock buildup ahead of these months is advisable.

# 2024 Insights
	•	Explosive growth noticed – 2024 saw quarterly growth over 361,000%, possibly due to a major operational shift, campaign, or new product.
	•	Partially Shipped orders brought high revenue – This suggests customer demand remains even when supply is delayed, but it may also reflect fulfillment challenges.
	•	Top product in 2024 was lower-priced (₦3.5M) – Revenue distribution is wide across many SKUs.

# 2025 Insights
	•	Revenue dropped significantly – Total dropped to ₦12.73M with a −37% quarterly decline, which is concerning. It could be linked to lower demand, supply issues, or external market pressure.
	•	Some months performed very poorly (−100%) – This might indicate either stockouts or data gaps. Worth investigating further.

## Customer & Order Insights
	•	Old customers are more reliable and active – They placed 23,469 orders vs. 14,971 for new customers. Retention strategies seem to be working, and customer loyalty is strong.
	•	Port Harcourt and Lagos dominate orders – These areas may deserve more focus in supply chain planning, warehousing, and marketing spend.
	•	Late deliveries are a concern – Over 7,000 late orders, with 2,416 returns, shows a pain point in logistics. Old customers still remained loyal despite delays — possibly due to brand trust.
	•	Delivery performance affects new customer trust – Late deliveries among new customers could hurt retention, especially without strong onboarding or experience.
	•	High return volume – A return rate this high may point to issues in quality control, wrong shipments, or unmet expectations.

## Supplier Insights
	•	A few suppliers carry most of the load – Nguyen Matthews and Fitzpatrick supply the majority of stock. Heavy dependence on them could be risky if there’s a disruption.
	•	Revenue is concentrated in a few suppliers – Bowers and Sons alone generated ₦21.64B. Strong relationships and contract stability are crucial.
	•	Supplier performance varies by rating – Surprisingly, some “Poor” or “Unrated” suppliers generated billions, suggesting rating doesn’t always align with financial contribution. Review your rating criteria.
	•	Excellent-rated suppliers are underutilized – They supply fewer units, yet generate strong revenue. These suppliers might be more scalable than currently assumed.
	•	Unrated and Unknown suppliers contribute significantly – This points to a data quality issue: important vendors aren’t fully profiled or evaluated.

## High-Level Strategic Takeaways
	1.	Demand is strong, but supply inconsistencies (stockouts, late deliveries) risk losing market share
	2.	A few locations and products drive most of the revenue — protect and invest in them
	3.	Returns and late deliveries are hurting efficiency and possibly customer experience
	4.	Revenue volatility across months shows the need for better sales forecasting
	5.	Supplier rating system may need revision — top revenue suppliers aren’t always rated highest
