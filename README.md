# Toys and Models / SQL - Powerbi
#### by Halil Ibrahim Celikel & Mai Tran & Nicolas Ortuno

![Model Train](model_train.png)

## Summary of the Project

In this project, we were commissioned by a company selling models and scale models. The company already had a database that lists employees, products, orders, and much more. We were invited to browse and discover this database to create a dashboard which the director could refresh each morning to have the latest information in order to manage the company.

According to the directives, our dashboard should revolve around these 4 main topics: sales, finance, logistics, and human resources. Here are the indicators that should be present in our dashboard: 

~~~~~
- Sales: The number of products sold by category and by month, with comparison and rate of change compared to the same month of the previous year.
- Finances: 
  -	The turnover of the orders of the last two months by country. 
  -	Orders that have not yet been paid
- Logistics: The stock of the 5 most ordered products.
- Human Resources: Each month, the 2 sellers with the highest turnover.
~~~~~

## The diagram of the database

Here is the diagram of the database:
![Diagram](diagram.png)

## SQL queries

***1. Sales***

- Sales of February 2024

![Sales_February](queries/sales_feb_2024.png)

- Proportion of products sold in February 2024

![Proportion_February](queries/dist_produit_february24.png)

- Total sales by category for January and February 2024

![Proportion_February](queries/total_sold_feb_jan.png)

- Comparison of sales by category for January-February 2023 - 2024

![Comparison_23_24](queries/comparison_23_24.png)

- February sales compared with January 2024

![Comparison_Feb_Jan_2024](queries/evolution_jan_feb.png)

- Evolution of sales in January-February 2024 compared to 2023

![Evolution_Feb_Jan_2023_2024](queries/evolution_23_24.png)


***2. Finances***

- The turnover of the orders of the last two months by country.

![Sales by Country 2024](queries/sales_comp_jan_fev.png)

- Sales by country

![Sales by Country total](queries/sales_country.png)

- Orders that have not yet been paid : This can't be achieved because of the modelling of the database.


***3. Logistics***

- The stock of the 5 most ordered products since the start of the business

![stock_five_produits](queries/stock_most_ordered_models.png)

- The stock of the 5 most ordered products for January - February 2024

![stock_five_produits_2024](queries/stock_most_ordered_models2024.png)


***4. Human Resources***

- Top two sellers by month since the start of business

![Top_two_sellers](queries/top_2_salesman_month.png)


## Screenshots of the Dashboard

- Sales dashboard

![Sales](dashboard/sales.png)

- Finance dashboard

![Finances](dashboard/finance.png)


- Human resources & Stocks dashboard

![Rh_Stocks](dashboard/RH_Stock.png)















