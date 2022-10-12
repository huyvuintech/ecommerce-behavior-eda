## Outline
* Objective:
* Executive Summary
* Execution
    + Data cleaning
    + Analysis
    + Visualization
    + Insights
    + Recommendations

## Objective
The purpose of this exercise is to explore the [e-commerce behavioral dataset](https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store) provided on Kaggle by Michael Kechinov.

Some pillars to focus on:
* Key metrics
* Key brands/categories
* Key time of traffic

## Executive Summary

<in progress>

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

	
#### 1. Conversion rate figures
Overall, view to add-to-cart conversion rate recorded high at 57.05% while add-to-cart to purchase conversion rate was low (23.99%), which results in view to purchase conversion rate recorded at 13.69%. 

![Overall Sales Conversion Rate from Nov-2019 to Jan-2020](https://github.com/huyvuintech/ecommercesample/blob/main/1.%20Overall%20Sales%20Conversion%20Rate.png)

#### 2. Key brands/categories

##### In terms of key brands, key brands with highest event count differed from ones with highest conversion rate. 
![Key brands with highest event count vs. ones with highest conversion rate](https://github.com/huyvuintech/ecommercesample/blob/main/6.%20Brand%20specifics.png)

When we looked further to brands' price range, ones with highest conversion rate had lower price range (<$50) while the other one had various price points (from $1 to $200).
![Brands price range](https://github.com/huyvuintech/ecommercesample/blob/main/7.%20Top%20brand%20prices%20landscape.png)					


From these charts, we acknowledged two groups: 
* Brands with highest event count had various price points from low to high, which drawed more consideration from customers. However, these products were trendy as traffic were attracted by these brands. 
* Brands with highest conversion rate had low price points, which were easier for customers to make purchase decisions. These are essentials with high needs and low price, which led to higher conversion rate. 

																											  
##### In terms of key categories, highest event category was Appliances while highest conversion rate went to Apparel and Stationery. 
			
![Key categories](https://github.com/huyvuintech/ecommercesample/blob/main/8.%20Top%20categories%20by%20event%20count%20%26%20conversion%20rate.png)

This chart showed the same trend in customers behavior: 
* Appliances had a variety of price points from low to high which raised more consideration from buying. 
* Apparels and Stationery were low-valued with various models/types which were easier to make purchase decisions. 
 
#### 3. Key time period
	
From a time-series lense, Nov 2019 was the peak time where all conversion rate figures climaxed. This makes sense as November have two big online shopping events in America which are Black Friday and Cyber Monday. 
	
![Time-series Sales Conversion Rate from Nov-2019 to Jan-2020](https://github.com/huyvuintech/ecommercesample/blob/main/2.%20Time-series%20Sales%20Conversion%20Rate.png)

In November 2019, all conversion rates increased throughout the month as the events came close. Plus, key shopping hours were during 0 am - 2 am and 9 am - 4 pm.
	
![November 2019 daily/hourly trends](https://github.com/huyvuintech/ecommercesample/blob/main/3.%20November%20trends.png)
	
Meanwhile, in December 2019, Christmas season played a critical part in shopping behaviors. People tend to shop before the gathering season and shopping behaviors decreased throughout the month.
	
![December 2019 daily/hourly trends](https://github.com/huyvuintech/ecommercesample/blob/main/4.%20December%20trends.png)

In January 2020, shopping trends focused in the last couple days of the month and peaked from 27 to 28 of the month. Key shopping hours were also 0 am - 2 am and 9 am - 2 pm. 
	
![January 2020 daily/hourly trends](https://github.com/huyvuintech/ecommercesample/blob/main/5.%20January%20trends.png)

### Visualizations
Visualizations can be found in [this](https://public.tableau.com/app/profile/quang.huy.vu/viz/E-commerceCustomerBehavior/Topbrands) public Tableau workbook. 

### Insights

    
### Recommendations

	
