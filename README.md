# [PYTHON] A/B Testing Promotional Banner Strategies for E-commerce Company

## 1. Introduction
The Ecommerce business offers a group of whitelist customers a special promotion for the membership subscription, currently they show the screen A to customers, and they found that the conversion rate of users buying the subscription is too low.
They suggest changing the content on the banner. The suggestion as below: (Notes: the original price of the subscription package is 199K, and with the promotion, they can buy with 99K)\
Screen A: show a discounted price of paid package (99K)\
Screen B: show a discount amount in price (discount 100K)

## 2. Design A/B Testing
- Hypothesis: Changing the content of the banner will change the conversion rate of users buying the subscription
- Measurable metrics:\
Primary metrics: the conversion rate of users buying the subscription
- Sample pool: All customers in whitelist, splitting the dataset equally and randomly between group 1 (screen A) and group 2 (screen B)
- External factors:\
Customer behavior: some customers may respond better to discount shown (discount 100K) rather than the price of the package (99K).\
Seasonality: if the test is running during low-demand period, both screen may show lower conversion rate, etc.,

### AB testing dataset
|customer_id| group| is_buy|
|------------|--------------|-----------|
|21393799|	2|	0|
|20349278|	2|	0|
|11655915|	2|	0|
|18516581|	2|	0|
|7805171|	2|	0|
