# Supply-Chain-Overview-Report
## Project Overview
This project presents a detailed supply chain analysis using Power BI. This project was developed to analyze these critical areas using data to uncover patterns in order fulfillment, supplier behavior, customer demand, and delivery performance  and provide insights that can help businesses make more informed, proactive decisions. This dashboard offers a complete view of the supply chain across four key areas: products, revenue, customer orders, and suppliers. It was designed to identify operational gaps, revenue patterns, and areas for improvement in delivery and supply reliability. 
The data was provided in a collaborative SQL group, focusing on customer retention and delivery issues. Instead of limiting the scope, the dataset was adapted and cleaned to extract insights that support better supply chain management.

## Project Motivation
Many businesses struggle or even shut down due to overlooked supply chain issues—poor product quality, supplier errors, bad transportation systems, or unforeseen disruptions. This dashboard helps bridge that gap by providing visibility into the entire supply chain process, offering actionable insights that can reduce inefficiencies and support smarter decisions.

## Tech Stack
•	Power BI – for cleaning data (Power Query) and visualizing insights

## Dataset Description
The project includes five main tables:
	•	orders 
	•	order_items 
	•	products 
	•	customers 
	•	suppliers

Each table was cleaned and connected using appropriate foreign key relationships, with roles clearly defined across tables (e.g., customer segments, product categories, supplier regions).

 ## ER Diagram
![model supply](https://github.com/user-attachments/assets/49fac88b-5acb-429b-85fb-10d215471992)

## Data Cleaning & Preparation

Before building the dashboard, the data went through several cleaning and transformation steps:
	•	Removed duplicates and blanks in key fields (e.g. customer ID, order date)
        •	Standardized product and supplier names for consistency
	•	Fixed data types (e.g. converted dates to proper format)
	•	Handled missing values in ratings, delivery status, and product status
	•	Created calculated columns (e.g. delivery status, delivery delays, customerType, shippinglocation)
	•	Merged tables using Power BI relationships and Power Query

## Dashboard Segments

 ## Product Insights
	•	Total Products Tracked: 200
	•	Total Quantity Produced: 387,000 units
	•	Total Quantity in Stock: 128,000 units
	•	Top Product Status:
	•	Active: 68 products (highest count)
	•	Out of Stock: 48 products
	•	Top Supplied Product: Happy Life Instead Pro
	•	Highest Revenue Generating Product: You Are Providing Yourself Basic with ₦6.37 billion
 
# Product Categories by Revenue:
	•	Groceries generated the highest revenue
	•	Followed by Health and Beauty
 ![supply pic3](https://github.com/user-attachments/assets/f21a8c6a-1f3b-4afc-9314-8a576f9b3496)


## Revenue Insights

#  General (All Years Combined)
	•	Total Revenue (Top Location):
	•	Port Harcourt generated the highest revenue at ₦43.98 billion
	•	Top Revenue Product: Believe National Put Pro – ₦13.5 billion
	•	Top Supplier by Revenue: Bowers and Sons – ₦21.64 billion
	•	Best Revenue Month: August – ₦13.97 million
	•	Highest Month-over-Month Growth: July – 356.54%
	•	Worst Month-over-Month Drop: September – −85.04%

# Revenue Insights for 2024
	•	Total Revenue: ₦46.71 million
	•	Top Revenue Product: Believe National Put Pro – ₦13.54 billion
	•	Highest Revenue Status: Blank – ₦60.73 billion
	•	Top Supplier: Bowers and sons – ₦21.64 million
	•	Peak Month by Revenue: August – ₦13.98 million
	•	Quarterly Revenue Change: +361,860%
        •        Highest Month-over-Month Growth: July – 356.54%

# Revenue Insights for 2025
	•	Total Revenue: ₦12.73 million
	•	Highest Revenue Product: Dinner Baby Him Pro – ₦3.50 million
	•	Highest Month-over-Month Growth: March – 237.33%
	•	Worst Performing Month: November – −100%
	•	Top Revenue Supplier: Brown Group – ₦3.70 million
	•	Quarterly Revenue Change: −37.62%
        •       Highest Revenue Status: Partially Shipped – ₦5.53 million
        •	Peak Month by Revenue: May – ₦3.65 million
	
 ![supply pic4](https://github.com/user-attachments/assets/2724cbae-190f-44d2-be12-d865abc8335f)

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
 
![supply pic](https://github.com/user-attachments/assets/f1c398c7-cada-4160-8532-236726baafd2)

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
	•	Partially Shipped & Processing: 6.36K each

## Supplier Insights
	•	Total Quantity Supplied: 387,000
	•	Number of Suppliers: 15
	•	Total Supplier Revenue: ₦43.41 billion
	•	Top Supplier by Quantity: Nguyen Matthews – 89,675 units
	•	Top Supplier by Revenue: Bowers and Sons – ₦21.64 billion
 
 ![supply pic2](https://github.com/user-attachments/assets/26b4ee67-df80-4579-a10b-fc1a76962a8c)


# Supplier Ratings Breakdown:

# Ratings Suppliers  Revenue	Top Product	            Quantity Supplied
Excellent   2	    ₦6.72B	Facts Go Something Dulux	48,000
Good	    3	    ₦10.76B	Believe National Poot Pro	70,000
Average	    1	    ₦1.18B	Adira Peach Eco	                11,000
Poor	    4	    ₦17.25B	Cat Shoulder Lease A Echo	117,000
Unknown	    2	    ₦3.58B	Drive Agent 1 Azume Plus	29,000
Unrated	    3	    ₦3.94B	Hand Center Audience Deluxe	111,000

## Key Business Insights 

## Product Insights
	•	Inventory imbalance detected: Out of 387,000 products produced, only 128,000 are still in stock, suggesting high demand — or a mismatch in production vs. consumption cycles.
	•	Active products dominate inventory: 68 products are currently active, showing strong product line availability. However, a notable portion is also out of stock — this could mean some popular products aren’t being replaced quickly enough.
	•	Category focus is clear: Groceries dominate revenue, followed by Health & Beauty. This suggests future promotions and supply efforts should target these segments.
	•	One product heavily leads in revenue: “You Are Providing Yourself Basic” generated ₦6.37B — likely a flagship product. It may need priority in marketing, stock planning, and supplier focus.

## Revenue Insights

# General (Across 2024 & 2025)
	•	Port Harcourt is a strategic revenue hub – ₦43.98B in total revenue signals this location as a key sales driver. Ensuring smooth logistics and supplier availability here could protect revenue flow.
	•	Believe National Put Pro is the revenue leader – ₦13.5B makes it the top product. Any supply delay on this product could have major revenue impact.
	•	Revenue volatility is very high – Month-over-month changes ranged from +356% to −85%, showing unstable demand or external market influences like pricing or competition.
	•	July and August drive peak sales – These may be seasonal periods. Forecasting and stock buildup ahead of these months is advisable.

# 2024 Insights
	•	Explosive growth noticed – 2024 saw quarterly growth over 361,000%, possibly due to a major operational shift, campaign, or new product.
	•	Top product in 2024 was lower priced (₦3.5M) – Revenue distribution is wide across many cities.

# 2025 Insights
	•	Revenue dropped significantly – Total dropped to ₦12.73M with a −37% quarterly decline, which is concerning. It could be linked to lower demand, supply issues, or external market pressure.
	•	Some months performed very poorly (−100%) – This might indicate either stockouts or data gaps. Worth investigating further.
        •	Partially Shipped orders brought high revenue – This suggests customer demand remains even when supply is delayed, but it may also reflect fulfillment challenges.

## Customer & Order Insights
	•	Old customers are more reliable and active – They placed 23,469 orders vs. 14,971 for new customers. Retention strategies seem to be working, and customer loyalty is strong.
	•	Port Harcourt and Lagos dominate orders – These areas may deserve more focus in supply chain planning, warehousing, and marketing spend.
	•	Late deliveries are a concern – Over 7,000 late orders, with 2,416 returns, shows a pain point in logistics. Old customers still remained loyal despite delays possibly due to brand trust.
	•	Delivery performance affects new customer trust – Late deliveries among new customers could hurt retention, especially without strong onboarding or experience.
	•	High return volume – A return rate this high may point to issues in quality control, wrong shipments, or unmet expectations.

## Supplier Insights
	•	A few suppliers carry most of the load – Nguyen Matthews and Fitzpatrick supply the majority of stock. Heavy dependence on them could be risky if there is a disruption.
	•	Revenue is concentrated in a few suppliers – Bowers and Sons alone generated ₦21.64B. Strong relationships and contract stability are crucial.
	•	Supplier performance varies by rating – Surprisingly, some “Poor” or “Unrated” suppliers generated billions, suggesting rating does not always align with financial contribution. Review your rating criteria.
	•	Excellent rated suppliers are underutilized – They supply fewer units, yet generate strong revenue. These suppliers might be more scalable than currently assumed.
	•	Unrated and Unknown suppliers contribute significantly – This points to a data quality issue, important vendors are not fully profiled or evaluated.

 ## Business Questions Answered
	•	What customer type contributes most to revenue?
	•	Which supplier regions are efficient vs problematic?
	•	Are delays more common with new or old customers?
	•	Which products drive the most returns?
	•	What’s the purchase trend over time?

## Review
	1.	Demand is strong, but supply inconsistencies (stockouts, late deliveries) risk losing market share.
	2.	A few locations and products drive most of the revenue — protect and invest in them.
	3.	Returns and late deliveries are hurting efficiency and possibly customer experience.
	4.	Revenue volatility across months shows the need for better sales forecasting.
	5.	Supplier rating system may need revision — top revenue suppliers are not always rated highest.
