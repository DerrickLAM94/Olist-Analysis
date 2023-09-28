Here is a draft README for a final project on Olist E-commerce Analysis:

# Olist E-commerce Data Analysis

This is the final project for the Data Analytics Bootcamp by XYZ Institute. It provides an analysis of e-commerce data from Olist, an online store in Brazil.

## Project Overview

The Olist dataset contains information on 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allow viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers. 

The main goals of this analysis are:

- Understand customer demographics and purchasing patterns
- Analyze product demand and performance 
- Evaluate Olist's business performance
- Provide data-driven recommendations to optimize operations

## Datasets

The analysis uses the following datasets:

- `olist_customers_dataset` - Demographics of 99k customers 
- `olist_geolocation_dataset` - Geolocation info for customers and sellers
- `olist_order_items_dataset` - Order items info including price and freight performance
- `olist_order_payments_dataset` - Payments info including installments and payment types
- `olist_order_reviews_dataset` - Reviews written by customers 
- `olist_orders_dataset` - Order info including status, purchase date, etc.
- `olist_products_dataset` - Product info including weight, dimensions and photos
- `olist_sellers_dataset` - Seller info including geolocation and metrics

## Analysis

The analysis covers:

- Exploratory Data Analysis
- Customer segmentation
- Product categorization 
- Statistical modelling of customer lifetime value
- Growth opportunities for top product categories
- Geospatial analysis of customer and seller locations
- Interactive dashboards and visualizations

## Recommendations

Based on the analysis, the final presentations provides data-driven recommendations to Olist on:

- Improving customer retention
- Optimize product portfolio and pricing
- Seller performance evaluation
- Supply chain and logistics optimization
- Expansion opportunities in specific regions

The final report, notebooks and presentation provide a comprehensive data study to derive actionable insights for Olist's business.


![WhatsApp Image 2023-09-27 at 3 52 26 PM](https://github.com/DerrickLAM94/Olist-analysis/assets/140989898/caf00f0c-5eea-414a-bfdf-ff2ea0f53e3d)

The dashboard shows that Olist generated total revenue of 16 million dollars from 2016 to 2018 over a 3 year period. We can see that November 2017 had the highest monthly revenue, likely due to Black Friday sales events. However, while Olist has acquired almost 96,000 total customers, only 2,979 of these are repeat customers. This means the number of repeat buyers is very small compared to new customers. Specifically, the total customers metric is 96096, but the repeat customers metric is only 2979. This suggests that while Olist has succeeded in acquiring lots of new customers, most are only making a one-time purchase. Olist appears to be struggling to convert these new customers into repeat buyers. The large difference between total and repeat customers indicates Olist may need to focus more on getting existing customers to purchase again.

-

![WhatsApp Image 2023-09-27 at 3 52 27 PM](https://github.com/DerrickLAM94/Olist-analysis/assets/140989898/c201647b-0f79-489e-95f7-be15d3720453)

In the chart above, we can see Olist has a total of 2,354 active sellers. I broke this down into sellers active for 3 months (1,508 sellers) and 6 months (791 sellers). This shows that a substantial number of sellers are continuously active on Olist for extended periods. The number of active sellers also increased steadily in 2016, indicating Olist is becoming a platform where sellers want to grow their businesses.

Additionally, most sellers have average scores between 4-4.5 out of 5 stars, suggesting generally good performance. However, Olist should watch out for the few sellers scoring just 1-2 stars, as poor seller performance can greatly impact the attractiveness and competitiveness of the platform.

-

![WhatsApp Image 2023-09-27 at 3 52 27 PM (1)](https://github.com/DerrickLAM94/Olist-analysis/assets/140989898/becb36f6-3c11-4e25-af33-62c9fe55cc0d)

In the product analysis, an important insight is how many products are purchased per order. We can see that only 3237 orders included more than one product, out of a total of 99441 orders. This means only 3% of orders contained multiple products.
This is an issue Olist should pay attention to. They likely need to focus on cross-selling and upselling to increase the number of products per order.
The most popular product price range is under $100, with over 70,000 orders in this range. Having low price points can be an advantage, but having over 70% of orders be low priced could hurt Olist's Average Order Value (AOV). Olist should keep an eye on AOV numbers.

-

![WhatsApp Image 2023-09-27 at 3 52 26 PM (2)](https://github.com/DerrickLAM94/Olist-analysis/assets/140989898/dc78dfcf-9274-4601-8cb6-7f69ba3beede)

In the order analysis, the pcs (personal computers) category has the highest Average Order Value (AOV). However, the top selling category, beauty and health, does not even make the top 10 in AOV. This means most people are buying beauty products on Olist due to the low prices, rather than high ticket sizes.

Additionally, we could use tactics like upselling and cross-selling to increase sales of higher AOV products. Since those products already have higher price points, there is more room to improve performance. Additionally, the city with the most orders is Sao Paulo. This is likely because Sao Paulo has the largest population and highest GDP in Brazil, as well as being more economically advanced. Therefore, there is higher demand potential in this region. Olist could focus efforts on Sao Paulo by providing more promotions like free shipping to attract purchasing power in this major market.


-

![WhatsApp Image 2023-09-27 at 3 52 26 PM (1)](https://github.com/DerrickLAM94/Olist-analysis/assets/140989898/efb121a1-cd70-4ef6-8ab1-d85a23e668ed)

The payment analysis shows that credit cards are by far the most popular payment method on Olist, accounting for over 60% of all payments. This prevalence of credit cards is driven by their convenience, security, efficiency, and additional benefits like rewards programs and purchase protection. Credit cards maintain their dominance across all product categories and geographic regions in Brazil. The second most common payment type is boletos, likely popular among customers without access to credit cards. Importantly, higher average order values are associated with credit card payments compared to other methods like boletos. Given this clear link between credit card usage and higher order values, Olist has an opportunity to shift more of its payment volume to credit cards. Potential strategies could include promotions or incentives specifically for credit card users, improving the payment experience for credit cards, or targeted marketing campaigns. If Olist is able to encourage more customers to pay by credit card, it could significantly increase overall order values and revenues.

-

![WhatsApp Image 2023-09-27 at 3 52 25 PM](https://github.com/DerrickLAM94/Olist-analysis/assets/140989898/98e43d44-5693-43ba-82f9-22ad32ef8af7)

The analysis shows ratings and reviews have a clear impact on Olist's sales and reputation. Highly rated products with 4-5 stars make up over 80% of orders and generate the most revenue, indicating a strong positive relationship between high ratings and sales performance. However, low rated 1-2 star products actually have a higher average order value, suggesting customers still buy expensive items despite poor reviews. This indicates buyers prioritize low cost, highly rated products but will spend more on average for expensive, poorly rated items. The overall average rating is a solid 4.5 stars out of 5, pointing to generally positive customer experiences. The extremely low 0.63% order cancellation rate also reflects high satisfaction. However, Olist struggles with customer retention as most buyers only make a one-time purchase. Enhancing the customer experience and service could improve retention. While high ratings drive sales, poor reviews clearly hurt, even for expensive products. Going forward, Olist should focus efforts on improving ratings for low-scored products and on bettering the customer journey to convert more one-time buyers into loyal, repeat customers.

-
Some Insight and Recommandation  

Key Insights:

- Olist's total revenue grew consistently from 2016-2018, peaking in 2018 during Black Friday
- An average of 4,143 orders were placed on Olist per month
- Bed and bath was the most popular product category but had lower average order values
- The number of active sellers increased steadily, indicating Olist is becoming an attractive platform
- Highly rated 4-5 star products generated over 80% of revenue, showing positive correlation between ratings and sales
- Repeat customers accounted for only 6% of total customers

Recommendations:

- Use cross-selling to boost sales of high AOV products like computer accessories
- Implement customer loyalty programs to improve retention
- Apply dynamic pricing for low margin products
- Improve customer service experience to build loyalty
- Optimize credit card payment process to encourage credit card use
- Boost ratings for low-scored products and improve customer experience
