## Business Background
Supermarkets face intense competition and need to understand customer behavior to tailor marketing efforts and enhance customer satisfaction. By analyzing detailed customer data on demographics, purchase history, and responses to marketing campaigns, the supermarket aims to segment its customer base and optimize marketing strategies to increase sales and customer loyalty.
# Business Problem
1. Market products and services?
<br><br>
* What products have the highest and lowest sales rate?

2. Segmenting Each Customer based on RFM Score ( Recency, Frequency, Monetary)
* What Category from each segment has a high relation with the amount of products spent?
* Distribution Each segment based by Income

3. Analyze the Supermarket Campaign by Segment related to sales rate?
* How effective the number of campaign received by customers with the level of sales rate of products?
* How effective each campaign batch to each product category revenue?

# Data

Data Dictionaries:

People:
* ID: Customer's unique identifier
* Year_Birth: Customer's birth year
* Education: Customer's education level
* Marital_Status: Customer's marital status
* Income: Customer's yearly household income
* Kidhome: Number of children in customer's household
* Teenhome: Number of teenagers in customer's household
* Dt_Customer: Date of customer's enrollment with the company
* Recency: Number of days since customer's last purchase
* Complain: 1 if the customer complained in the last 2 years, 0 otherwise
  
Products:
* MntWines: Amount spent on wine in last 2 years
* MntFruits: Amount spent on fruits in last 2 years
* MntMeatProducts: Amount spent on meat in last 2 years
* MntFishProducts: Amount spent on fish in last 2 years
* MntSweetProducts: Amount spent on sweets in last 2 years
* MntGoldProds: Amount spent on gold in last 2 years

Promotion:
* NumDealsPurchases: Number of purchases made with a discount
* AcceptedCmp1: 1 if the customer accepted the offer in the 1st campaign, 0 otherwise
* AcceptedCmp2: 1 if the customer accepted the offer in the 2nd campaign, 0 otherwise
* AcceptedCmp3: 1 if the customer accepted the offer in the 3rd campaign, 0 otherwise
* AcceptedCmp4: 1 if the customer accepted the offer in the 4th campaign, 0 otherwise
* AcceptedCmp5: 1 if the customer accepted the offer in the 5th campaign, 0 otherwise
* Response: 1 if the customer accepted the offer in the last campaign, 0 otherwise

Place:
* NumWebPurchases: Number of purchases made through the company’s website
* NumCatalogPurchases: Number of purchases made using a catalog
* NumStorePurchases: Number of purchases made directly in stores
* NumWebVisitsMonth: Number of visits to the company’s website in the last month

# Conclusion and Recommendations
For conclusion, our RFM analysis has provided deep insights into customer segmentation and behavior, allowing us to craft targeted marketing strategies. Key takeaways include:

* High-Value Segments: 'Champions' and 'Loyal Customers' are critical for sustained revenue growth.
* Engagement Opportunities: Significant potential exists in converting 'Potential Loyalists' and re-engaging 'Need Attention' customers.
* Campaign Effectiveness: Tailored campaigns based on RFM segments have shown promising results in improving customer engagement and sales.

Recommendations:

* Enhance Personalization: Continue refining personalized marketing efforts to cater to individual customer preferences.
* Data Quality: Invest in improving the accuracy and comprehensiveness of customer data.
* Re-engagement Strategies: Develop more robust re-engagement strategies for 'At Risk' and 'Hibernating' customers.
* Monitor and Adapt: Continuously monitor campaign performance and adapt strategies based on customer response and changing market dynamics.<br>
