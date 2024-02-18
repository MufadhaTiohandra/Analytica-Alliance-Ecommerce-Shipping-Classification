# FINAL PROJECT E COMMERCE SHIPPING - ANALYTICA ALLIANCE
Data source : https://www.kaggle.com/datasets/prachi13/customer-analytics
<details>
  <summary>Table of Contents</summary>
  <ul>
    <li> <a href="#project-overview">Project Overview</a> </li>
    <li> <a href="#exploratory-data-analysis">Exploratory Data Analysis</a> </li>
  </ul>
</details>

<h2 id="project-overview">PROJECT OVERVIEW</h2>
• Stage 1 : We focus on Data Exploration, Exploratory Data Analysis, Business Insight and Visualization <br>

Overall Project : <br>
• Seek insight from the dataset with Exploratory Data Analysis <br>
• Performed data cleansing, data processing, data engineering to prepare data before modeling <br>
• Built a model to predict whether the shipping deliveries will be received late or on time by the customers <br>
• Developt  recommendations & benefit analysis based on insights and model prediction 
<br>

<h2 id="exploratory-data-analysis">EXPLORATORY DATA ANALYSIS</h2>

| Variable | Type | Definition | Example |
| ----------- | ----------- | ----------- | ----------- |
| ID | Nominal | Customer ID Number | 10, 15, 10995, 10996
| Warehouse_block | Nominal | Warehouse to Store the Product | A, B, C, D, F
| Mode_of_Shipment | Nominal | Mode of Product Shipping | Flight, Road, Ship
| Customer_care_calls | Discrete | Number of Calls Made | 1, 2, 5, 6
| Customer_rating | Ordinal | Company Rating by Customers | 5: Best - 4: Better - 3: Neutral - 2: Bad - 1: Worst
| Cost_of_the_Product | Discrete | Cost of Product in US Dollars | 177, 216, 236, 182
| Prior_purchases | Discrete | Number of Prior Purchase | 3, 2, 6
| Product_importance | Ordinal | Product Importance Parameter | Low, Medium, High
| Gender | Nominal | Customer Gender | Male, Female
| Discount_offered | Discrete | Product Discount in US Dollars | 65, 10, 16
| Weight_in_gms | Continous | Product Weight in grams | 4953, 5676, 2171
| Reached.on.Time_Y.N | Nominal | Target Variable, 1: NOT reached on time - 0: REACHED on time | 1, 0

1. Outliers Detected on Discount Offered and Prior Purchase Feature
   
![Images](https://github.com/MufadhaTiohandra/Analytica-Alliance-Ecommerce-Shipping-Classification/assets/94730568/6ff850d2-a13a-43ef-8be4-b1108f5a38f7)

3. More confirmed late arrivals compared to on-time deliveries
   
![Boxplot](https://github.com/MufadhaTiohandra/Analytica-Alliance-Ecommerce-Shipping-Classification/assets/94730568/d9a5773b-ef81-4f73-8608-72d2c1e8f916)

5. Discount offered have a high correlation with arrived late
   
![heatmap](https://github.com/MufadhaTiohandra/Analytica-Alliance-Ecommerce-Shipping-Classification/assets/94730568/e0ee6c95-9f11-4f12-b292-04dc8dc1ecf6)

7. No product with a discount of more than 10% arrived on time and no product with a weight in the 2000-4000 gram range arrived on time.
   
![bins](https://github.com/MufadhaTiohandra/Analytica-Alliance-Ecommerce-Shipping-Classification/assets/94730568/2de1a4a4-f187-4e35-a0b4-698c146bcca1)

Get our full inisght on : [EDA - Analytica Alliance](https://docs.google.com/presentation/d/1FjsYrF5-k3cZLdpHrZiYj6bBl5EcXvom/edit?usp=sharing&ouid=108521517441269973255&rtpof=true&sd=true)





