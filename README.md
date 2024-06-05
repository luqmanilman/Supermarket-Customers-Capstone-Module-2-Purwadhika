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

Conclusion:

1. The Highest and Lowest sales rate
* From the bar chart "Supermarket Highest and Lowest sales rate", it is evident that 'Wines' has the highest sales rate, followed by 'Mnt Meats', while 'Fruits' has the lowest sales rate.

2. Segmenting Each Customer Based on RFM Score (Recency,Frequency,Monetary)
* The most distribution from the segment of customers is "Need Attention" who has the most distribution than the other. and the lowest distribution is Hibernating.
* The bar chart "Average Spending Produtcs by Each Segment" shows the spending patterns, but it could be further enhanced by explicitly showing which products are most popular in each segment.

3. Distribution Each Segment Based by Income
* The "Segment by Income" scatterplot shows the income distribution across different segments.

4. Analyze the Supermarket Campaign by Segment Related to Sales Rate
* The "Pie Chart Campaign" and "Distribution of Campaign per Batch" provide some insights, but a more detailed analysis of sales rates pre- and post-campaign could strengthen this.
* The segmented bar charts give an overview, but adding a comparative analysis of revenue changes per campaign batch would provide more depth.

Recommendations:

1. Enhance Product Focus in Campaigns:
* Highlight High-Selling Products
* Revitalize Low-Selling Products
2. Optimize Customer Segmentation:
* Personalize Offer Based on RFM Scores
* Target High-Value Segments
3. Leverage Income Data for Better Targeting:
* Income-Based Campaign
4. Enhance Campaign Effectiveness Analysis:
* Track Campaign Impact
* Optimize Campaign Batches
5. Increase Engagement Through Personalized Campaigns:
* Multi-Channel Engagement
* Loyalty Programs
6. Focus on Customer Retention:
* Engage At-Risk and Hibernating Customers
* Improve Customer Experience
7. Data-Driven Decision Making:
* Continuous Monitoring
* A/B Testing
