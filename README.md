# Recommendation Engine for ![image](https://user-images.githubusercontent.com/94947162/229892259-79b4cfd5-3a50-449e-9aaf-61c7768eed2d.png)

## Background:

• Online Grocery Service allows customers to order groceries from participating retailers, while the shopping is done and delivered by a personal shopper

• Let you shop from local grocery stores online. Example: Loblaws, Walmart, Longo’s etc

• Service offered both via website and app; The company doesn’t stockpile fresh produce in warehouses

• Founded in 2012 in San Francisco Bay Area by Apoorva Mehta (a former Amazon Employee,) helping local grocers to deliver food

• As of 2021, expanded to 5,500 cities and 40,000 stores across North America

• Competitors: Amazon Fresh, Walmart Grocery, Uber eats, DoorDash, Shipt, FreshDirect etc

### Revenue Model:

![image](https://user-images.githubusercontent.com/94947162/229893783-0be4ee75-c1b9-466f-b1ae-d9eead215458.png)


### The key stats of Instacart to give some business context:

1) Lost $25M per month in 2019 versus netted $10M in April 2020 

2) Revenue was boosted during the COVID pandemic. Generated $1.8 billion in revenue in 2021

3) Estimated 9.6 million active users & over 500,000 shoppers

4) In March 2021, valued at $39 billion

### Dataset: 

Over 3 million grocery orders from 200,000 plus users. Each basket contains 4 to 100 items in a order. 

### Challenges & Solutions 

Our objective would be to increase revenue for Instacart.

##### Our Challenges here are: 

• Fierce competition from the start-ups like GoPuff and bigger players like walmart’s own grocery services , eating out its market share

• Bigger players offering groceries at much more affordable price and delivery fee

• Cutting-edge AI technology for service providers like Amazon makes it harder for smaller players like Instacart to flourish

• Needs a strong direction OR pivoting as the pandemic boom fades, decelerating revenue and sales growth

##### There are multiple ways we can solve this problems

• Customized promotion based on understanding consumer behaviors We can do this by Increasing per transactional order volume, Increasing Frequency of shopping, promotional Offers for peak hours and Pool approach for Non peak hours.

• To draw more customer to our platform, For eg  people always buy milk and eggs, by lowering the price of milk and/or eggs, we can attract more people to our platform, and while they are here to purchase milk and/or eggs, we can encourage customers to shop for other items as well, hence, increasing the overall revenue per transaction

• Third, the one I selected for the Modelling would be Recommendation engine. It will directly contribute in helping retailer to serve their customers better by recommending them products based on the model predictions which in return will contribute to increase revenue to retailers by helping them to sell more. More sale by retailers better for Instacart.

### Model: Market Basket Analysis (MBA)

MBA is widely used by grocery stores, banks, and telecommunications among others. Its results are used to optimize store layouts, design product bundles, plan coupon offers, choose appropriate specials etc. The MBA helps us to understand what items are likely to be purchased together.  

One Of the important reason we chose this method, is this method requires lots of data for it to produce any good inference and we have pretty huge dataset for that. 

Eg. People who buy Organic Apples and Bananas also tend to buy Almond Butter. The marketing team at retail stores should target customers who buy Apples, bananas and Almond butter also provide an offer to them so that customer buys a fourth item example Green juice. If a customer buys Apples, bananas and Almond butter and sees a discount offer on Green juice they will be encouraged to spend extra and buy the Green juice and this is what market analysis is all about. It helps us to understand what items are likely to be purchased together. 

### Proposed Solution: Instacart Platform - Insights 

#### The first enhancement suggested was to upsell organic items

![image](https://user-images.githubusercontent.com/94947162/229897896-adbe2192-9fb6-4c55-9bcb-ceb1a0fe5711.png)

Using the MBA, derived at a combination of items with high lift, In the example here, it is with a lift that ranked top 1% of all combination meaning these items are very likely to be purchased together While in this example, there is only 1 item that is organic, the rest are non-organic. The enhanced recommendation engine would suggest 3 more organic items. Effectively upselling the proposed items for the customer

#### The second enhancement suggested was to help our retail partners to sell more by providing recipe of unique food combos 

![image](https://user-images.githubusercontent.com/94947162/229898440-e1ed90bb-d106-40e7-9fe3-3da464fa9b7c.png)

The example shown here is a low ranked lift combo with the bottom 99% of all combination. Meaning that these items are much less likely to be purchased together. By effectively providing the customer with a recipe that uses all the ingredients, in this case, it is the Lemon & Avocado-Banana Smoothie. Platform can prompt the customer to purchase more while helping them to try out unique recipes.
