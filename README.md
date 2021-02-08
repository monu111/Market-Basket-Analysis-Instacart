##### Market-Basket-Analysis-Instacart

# Objective:

![ret3](https://user-images.githubusercontent.com/29980448/107252752-ab185980-6a5b-11eb-9257-f2db71766919.jpg)


- To predict which previously purchased products will be in a user’s next order.

- The goal predict which products will be in a user's next order. The dataset is anonymized and contains a sample of over 3 million grocery orders from more than 200,000 Instacart users.

- For each user, 4 and 100 of their orders are given, with the sequence of products purchased in each order




# Data set link : https://www.kaggle.com/c/instacart-market-basket-analysis/data



# Observation of exploratory analysis :
**`1. Initially data was segregated & data divided in 6 part which was Order_products__train, order_products__prior, order_df, products_df, aisles_df, departments_df.`**

**`2. There are 206,209 customers in total. Out of which, the last purchase of 131,209 customers are given as train set and we need to predict for the rest 75,000 customers  [in order_df data].`**


**`3. there are no order less than 4 and is max capped at 100 & less orders by the  customers have high number occurrences..`**


**`4. From the observation , 0 and 1th day order are high. seems like saturday and sunday and the  4th day order is less compare to the other days.`**


**`5. From the observation, majority of the order made by daytime(8 to 18)`**

**`6. From the analysis, (0) evenning and (1) morning are the prime time of order.`**

**`7. From the analysis, customer order once in every week day(see peak at 7.0) or once in month (peak at 30.0) & we could also see smaller peaks at 14, 21 and 28 days (weekly intervals). .`**

**`8. From the analysis, on an average 59% of the products in an order are re-ordered products.`**


**`9. From the analysis, most of them are organic products.! Also majority of them are fruits.`**

**`10. From the analysis,  top two Aisle are fresh fruits and fresh vegitables.`**


**`11. From the analysis,  produce & dairy farm is the largest department `**

**`12. From the analysis, Personal care has lowest reorder and dairy egg have higest reorder ratio.`**

**`13. From the analysis, the products that are added to the cart intially are more likely to be reordered again compared to the ones added later.`**

**`14. From the analysis ,reorder reorder ratio was quite high during the early mornings compared to later half of the day.`**



# Modeling :

# Working on it
