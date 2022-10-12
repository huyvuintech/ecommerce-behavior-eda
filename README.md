# E-commerce customer behavior exploratory data analysis
This repository is created to store data analysis on E-commerce sample data available on Kaggle

## About dataset

This dataset is made available by MICHAEL KECHINOV on Kaggle [here](https://www.kaggle.com/datasets/mkechinov/ecommerce-events-history-in-cosmetics-shop). 

This file contains behavior data for 5 months (Oct 2019 – Feb 2020) from a medium cosmetics online store.

Each row in the file represents an event. All events are related to products and users. Each event is like many-to-many relation between products and users.

Data collected by [Open CDP](https://rees46.com/en/open-cdp) project. Feel free to use open source customer data platform.

### Data fields: 
* ```userid``` represents the user who involved in the event. 
* ```usersession``` represents an unique id of the event.
* ```eventtype``` represents the event type: view, add-to-cart, purchase, remove from cart.
* ```productid``` represents the product id involved in the event. 
* ```categorycode``` represents the category code involved in the event.
* ```categoryname``` represents the name of the category code involved in the event. 
* ```event_time``` represents the datetime of the event.
* ```price``` represents the price of the product involved in the event. 


## Documentation outline:
* Executive summary
* Objectives
* Business Objectives
* Execution:
  + Data cleaning
  + Analysis
  + Visualization
  + Insights
  + Recommendations

## Executive Summary:

Recommendations: 
* Key campaign period: last 5 days of the month, with the focus on 0 am - 2 am and 10 am - 4 pm timeframe. 
* For high-value products: focuses on figuring out promotional tactics to convert from cart to purchase (for example, using discounts/exclusive deals with bundle deals) using further analyses on customer behaviors/price competitiveness analyses. 
* For low-value products: focuses on increasing in exposure via advertising, campaign landing pages, key digital assets to draw more traffic. 

Key insights: 
* Key shopping time focuses on the last 5 days of the month, and customers love staying up late (0 am - 2 am) to get the deals they want. They save products to cart and make purchase later on in the day (10 am - 2 pm / 4 pm).
* For high-value products: high view session counts, yet low conversion rate due to higher price range. 
* For low-value products: high conversion rate due to necessity with moderate session counts. 
