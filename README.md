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

1. From the analysis, we know that the highest sales in this supermarket come from the Wines category, totaling 620,402. This is followed by Meats, while Fruits have the lowest sales.
2. From the segment distribution, we know that the "Need Attention" segment is the largest, with 715 customers in it.
3. The distribution of segment income shows that the "Need Attention" segment has the largest bubble, with total spending of 349,649 and an income of 34,073,554.
4. The average spending on wines is the highest in every segment compared to other products.
5. Campaign engagement among customers is low, with only 27.77% of customers participating in campaigns. This suggests that customers pay little attention to the supermarket's campaigns.
6. The distribution of campaign participation shows that the most engagement occurred during the last campaign. This indicates that the last campaign was the most successful compared to other campaigns.


Recommendations:

1. Leverage the Success of the Last Campaign:
* Analyze the elements that contributed to the success of the last campaign. Was it the timing, the type of promotion, the channels used, or the products featured? Use these successful elements as a template for future campaigns.

2. Target the "Need Attention" Segment:
* Since the "Need Attention" segment is the largest, tailor campaigns specifically to engage these customers. Offer personalized promotions and discounts that cater to their preferences and spending patterns.

3. Focus on Popular Product Categories:
* Given that Wines and Meats are the highest-selling categories, create campaigns that highlight these products. Offer special discounts, bundle deals, or loyalty rewards for purchases in these categories to boost sales further.

4. Increase Campaign Awareness and Engagement:
* Since overall campaign engagement is low, invest in better marketing strategies to increase awareness. Use multiple channels such as social media, email newsletters, in-store promotions, and advertisements to reach a wider audience. Consider interactive campaigns that involve customers directly, such as contests, challenges, or referral programs.

5. Highlight Benefits and Incentives:
* Clearly communicate the benefits of participating in campaigns, such as significant savings, exclusive deals, or loyalty points. Make sure these incentives are compelling enough to motivate customers to take part.

6. Utilize Data for Personalization:
* Use customer data to personalize campaigns. Segment customers based on their purchasing behavior, preferences, and demographics to deliver targeted promotions that are more likely to resonate with them.

7. Enhance In-Store Experience:
* Ensure that in-store displays and promotions are attractive and easily noticeable. Use eye-catching signage and product placements to draw attention to the campaigns.

8. Encourage Repeat Participation:
* Design campaigns that encourage repeat participation, such as multi-purchase discounts or loyalty programs where customers earn rewards for continuous engagement.

Tableau Dashboard:
<https://public.tableau.com/views/RFMCustomerSegmentation_17174894733950/DB2?:language=en-GB&:sid=&:display_count=n&:origin=viz_share_link>

Tableau Story:
<https://public.tableau.com/views/Book1_17174891802280/Story1?:language=en-GB&publish=yes&:sid=&:display_count=n&:origin=viz_share_link>
