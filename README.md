Project Overview:
Target Corporation, one of the largest retail chains in the United States, operates through hypermarkets, discount department stores, and e-commerce platforms. With growing competition from Walmart, Amazon, and Costco, retaining loyal customers has become a crucial challenge.
Target collects extensive data from customer transactions, loyalty memberships, and online interactions, but its current reporting lacks analytical depth to:

● Understand why customers are churning.
● Identify loyal vs. at-risk customers.
● Measure the impact of loyalty tiers, promotions, and influencer-driven campaigns.
● Guide region- and channel-specific retention strategies.

I have developed an interactive Customer Retention Analytics Dashboard in Power BI using Target’s
customer data that will:

● Consolidate customer demographics, purchase history, store/e-commerce performance, and loyalty data.
● Enable dynamic segmentation of high-value, repeat, and churned customers.
● Provide actionable insights to improve retention, loyalty engagement, and regional strategies.

Dataset Description: 

1. Customer_Demographics.csv 
Columns: Customer_ID, Age, Gender, Region, Income_Level, Membership_Since, Preferred_Channel (Store/Online)
2. Customer_Transactions.csv
Columns: Transaction_ID, Customer_ID, Store_ID, Product_Category (Groceries, Electronics, Apparel, Home & Living), Transaction_Date, Amount, Promotion_Applied (Yes/No)
3. Store_Locations.csv
Columns: Store_ID, Store_Type (Supercenter, Neighborhood Market, Sam’s Club, Online), Region, Opening_Year
4. Loyalty_Program.csv
Columns: Customer_ID, Loyalty_Tier (Basic, Plus, Premium, Elite), Points_Earned, Points_Redeemed
5. Churn_Labelled_Customers.csv
Columns: Customer_ID, Last_Purchase_Date, Churn_Flag (0 = Active, 1 = Churned), Churn_Reason (Inactivity, Competitor, Low Engagement)

Dataset Link: https://drive.google.com/file/d/1NyQL12A4oyxuDVrV3iXqiNnLPv5ATfpL/view
