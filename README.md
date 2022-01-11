# Analysis of E-Commerce Public Dataset by Olist

The objective of this project is to propose an analytical view of olist e-commerce in Brazil. For this we will first go through an exploratory data analysis using graphical tools to create self explanatory plots for better understanding what is behind braziian online purchasing. It also deals with many real-world challenges faced by e-commerce websites that includes predicting customer lifetime value using RFM score and k-means clustering, customer segmentation to increase retention rate and find out best valued customers by segmenting them into homogeneous groups, understand the traits/behaviour of each group, and engage them with relevant targeted campaigns.

# Dataset
Brazilian ecommerce public dataset of orders made at Olist Store. The dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers. Also included is a geolocation dataset that relates Brazilian zip codes to lat/lng coordinates.

#### This dataset have nine tables which are connected with few common attributes. https://www.kaggle.com/olistbr/brazilian-ecommerce

# Approach
We started with EDA and Trend Analysis of Products and Customers to get insights for a business Analyst.
Then we Segmented customers into specific clusters based on Cohort Analysis, RFM Modeling using their purchasing behavior. 
Then we will use machine Learning techniques called K-Means to get more customized and fine tunned groupings.
Then we used uplift/persuasion modeling to identify which customer needs treatment and identify Upselling & Cross Selling Opportunities
Predict Customer Lifetime value (LTV)

# Customer Segmentation and RFM Modeling
Using RFM anaylsis and K-means Clustering, we created the below Clusters or segments of customers to further give targetted recommendation to them.

Potential Loyalists — High potential to enter our loyal customer segments, why not throw in some freebies on their next purchase to show that you value them!

Needs Attention — Showing promising signs with quantity and value of their purchase but it has been a while since they last bought sometime from you. Let's target them with their wishlist items and a limited time offer discount.

Hibernating Almost Lost — Made some initial purchases but have not seen them since. Was it a bad customer experience? Or product-market fit? Let's spend some resources building our brand awareness with them.

Loyal Customers — These are the most loyal customers. They are active with frequent purchases and high monetary value. They could be the brand evangelists and should focus on serving them well. They could be the best customers to get feedback on any new product launches or be the early adopters or promoters.

Champions Big Spenders - It is always a good idea to carefully “incubate” all new customers, but because these customers spent a lot on their purchase, it’s even more important. Like with the Best Customers group, it’s important to make them feel valued and appreciated – and to give them terrific incentives to continue interacting with the brand.
