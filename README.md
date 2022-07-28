# Analysis-of-Brazilian-Ecommerce-With-ML

# DataSet Description
Brazilian E-Commerce Public Dataset by Olist
Welcome! This is a Brazilian ecommerce public dataset of orders made at Olist Store. The dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers. We also released a geolocation dataset that relates Brazilian zip codes to lat/lng coordinates.

# Dataset Schema

This is real commercial data, it has been anonymised, and references to the companies and partners in the review text have been replaced with the names of Game of Thrones great houses.

# Inspiration on Dataset.
This dataset is massive and contains numerous insights. This dataset's analysis will be based on customer segmentation via product categories. I'll create a clustering model to help segment customers based on a specific set of products using the customer's behavior (such as location, etc.) from the dataset.

# Methodology
## Python Libraries
- Pandas : Used for loading data into a dataframe and used for data wrangling.
-  Seaborn and Matplotlib : Used for basic data visualization.
- Scikit learn – For Machine learning tasks.
- Plotly Visualization Package – For all visualizations (including maps and graphs)
- KModes  Used to Cluster Customer Behaviour.
- Geopy – To retrieve location coordinates.

# EDA 
From the exploratory data analysis we got to found out that there are customers who live as far in Argentina, Portugal and orders product of Olist Market place.

![newplot (1)](https://user-images.githubusercontent.com/73393430/181525245-d55985fd-d658-46b3-b78f-7db65c369202.png)

Also from the EDA we noticed that majority of customers make use of credit cards to order for their goods.
![download (3)](https://user-images.githubusercontent.com/73393430/181525559-3c8b82d8-c025-43e2-bc8c-5e5b85580c63.png)

There are lot's of insights communicated in the Jupyter Notebook.

