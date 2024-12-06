# **Coffe-Sales-Dashboard-Maven-Analytics**
Dynamic Coffee Sales Dashboard with Excel Pivot Tables and Charts.

## **Introduction**

The project goal is to create a dynamic dashboard to analyze sales data for a fictional coffee shop franchise in New York, Maven Roaster, and obtain useful insights to help the business.

From the Maven Analytics project brief:
> You've recently become a franchise owner at Maven Roasters, a coffee shop chain with three locations in New York City.
> To better understand purchase behavior and streamline operations, you've collected  transactional data from Jan-Jun 2023.

The Project assignment: 
>To better understand purchase behavior and streamline operations, you've collected transactional data from Jan-Jun 2023.
>Your goal is to transform the data into a dynamic dashboard that franchise owners can use to identify patterns, trends, and opportunities for the business.

Objectives:
>1. Profile and prepare the raw data for analysis.
>2. Explore the data with Excel Pivot Tables.
>3. Build a dynamic dashboard to visualize patterns and trends.


## **Dataset**

The dataset is a single table with eleven fields and 149116 entries. 

Here's a breakdown of the various fields grouped by type:

| Transaction      | Store      | Product |
|----------------|----------------|----------------|
|transaction_id  |store_id	      |product_id	 |
|transaction_date|store_location	|unit_price |
|transaction_time|                |product_category|
|transaction_qty |                |product_type|
|                |                |product_detail|

The Dataset collects data from January to June 2023.

The three stores' fictional locations are Astoria, Hell's Kitchen, and Lower Manhattan.

The following calculated columns were added to prepare data for analysis:

1. Revenue
2. Transaction_Month	
3. Transaction_Dayweek
2. Transaction_hour	


## **Key Findings**

1. **+104%** in Revenue from **$81,678** in January to **$166,486** in June
2. **7-10** am are peak hours for transactions 
3. Tea and Coffee are the most popular product categories, while 
4. Saturday is the least for transaction numbers in general, while if we look at the single store, we can see different patterns. Astoria and Hell's Kitchen have their lowest transaction numbers on Saturday, while Lower Manhattan on Sunday.
5. The most popular products are Brewed Chai Tea, Gourmet Brewed Coffee, and Barista espresso.
6. Scone is the top seller for bakery products, with a total revenue of $36,866. It's in the Top 10 of products per number of transactions.

## **Impact**

1. Improved staff shift management by identifying peak hours, enabling the allocation of additional personnel to handle increased demand.
2. Reduced customer waiting time during busy periods by aligning staffing levels with peak usage trends.
3. Identified the top-selling bakery product, providing insights into customer preferences and guiding the development of similar products to better meet customer tastes.


## **Disclaimer**

This project uses a dataset provided by Maven Analytics. I do not own or claim any rights to the dataset. All rights to the data belong to Maven Analytics. This analysis is conducted purely for educational and non-commercial purposes.




This is a guided project 
