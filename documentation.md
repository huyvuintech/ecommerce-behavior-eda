## Outline
* Objective:
* Executive Summary
* Execution
    + Data cleaning
    + Analysis
    + Visualization
    + Recommendations

## Objective
The purpose of this exercise is to explore the [e-commerce behavioral dataset](https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store) provided on Kaggle by Michael Kechinov.

Some pillars to focus on:
* Key metrics
* Key brands/categories
* Key time of traffic

## Executive Summary

<not yet done>

## Execution
### Data cleaning
This includes the steps taken to clean the data. The steps taken are: 
* Convert datetime format of ```event_time``` to day of month, month of year, and hour cohorts. 
* Replace blank values in ```category_code``` and brand with "not available" values. 
* Add cnt_event column to ```count number``` of events by group of event type by ```hour```, ```category_code```, ```category_id```, ```product_id```, and ```brand```.

### Analysis
Considering focused pillars listed earlier, there are some questions to ask before this exploratory data analysis (EDA):
* What are the conversion rate figures from view to add-to-cart or from add-to-cart to purchase over the month of consideration? 
* What are the key brands or categories that received the highest event or have the highest conversion rate?
* What are the key time period to improve sales campaign?


### Visualizations
Visualizations can be found in [this](https://public.tableau.com/app/profile/quang.huy.vu/viz/E-commerceCustomerBehavior/Topbrands) public Tableau visuals. 


