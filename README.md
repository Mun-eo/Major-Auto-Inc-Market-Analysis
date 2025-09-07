# Major Auto Inc Market Analysis

<h2>Description</h2>

**Project**:

   
In the competitive automotive market, strategic inventory management is crucial for profitability and growth. This project conducts an end to end analysis to investigate car transactions and customer demographics for the mega dealership Major Auto Inc. The corporation is preparing to purchase more inventory for their dealerships across the United States and would like an analysis on their transactions to understand the overall trends in purchases, regional variations in car sales to assess manufacturer performance, Body style preferences, and demographic insights. This report offers actionable recommendations to optimize future inventory purchases and marketing strategies across the corporation’s national dealership network.

**Insights to uncover**:

  1. What’s is the earning gap between male and female buyers?
  2. What car brands are popular among buyers?
  3. What vehicle body style is typically purchased?
  4. What region has the highest car transactions?
  5. What are the sales trends for car transactions for 2022 and 2023
  6. What percentage of male and females are car buyers?
  7. What is the average price of a vehicle?

<h2>Technical Tools Used</h2>

- Excel
- Tableau 

<h2>Understanding the dataset:</h2>
I collected this dataset from kaggle. The dataset consisted of over 20,000 order transactions of various cars purchased per day around the United States. This included the Demographics of the vehicle purchased, Order date, Dealer name, Company, Model and the demographics of buyers such as Customer_name, Gender, and annual income. This dataset was chosen as it provides the information needed to answer the critical questions for the market analysis. I used Excel to clean, analyze the dataset,  then used Tableau to create visualizations and built a dashboard. While the dataset isn’t tied to one dealership or company, it’s a strong sample to understand the market and show how Major Auto Inc can use this type of analysis to make better data-driven decisions.

<h2>Data Cleaning walk-through:</h2>

  
  1. First, I turned the dataset into a table so I can explore the data to understand what inaccuracies are within the cells of the dataset. I found that the data had inaccuracies such as Double√Ç¬†Overhead Camshaft for the description of the Engine.
  2. I turned the columns annual income and price into the currency format from general to get an accurate visualization of the price of the vehicles and Income of each customer.
  3. From there it was best to remove a few columns. The columns I removed were Phone, Dealer_No, and Customer Name as these columns would not be helpful for the analysis.
  4. The engine column had a corrupted cell which was Double√Ç¬†Overhead Camshaft as previously mentioned. To fix this I used Find and Replace to remove √Ç¬† from that cell to return Double Overhead Camshaft.
  5. In the model column, two cars made by Saab 9-3 and 9-5 were turning into the dates Sept 3 and Sept 5. To get around this I added an apostrophe to the 9-3 and 9-5 to prevent it from turning into a date format.
  6. Lastly, I checked and removed any duplicate values within the dataset.


With this the dataset has been cleaned and ready for the next phase of analysis and visualization.


<h2>Data Analysis & Visualization:</h2>
<p align="center">
Identify Customer Preferences  <br/>

Analysis of car transactions from January 2022 to December 2023 using a visualizational model reveals findings on customer preferences. The SUV was the most purchased body style making up 27% of transactions, with the average price being around $28,000. Customers preferred to purchase vehicles from brands such as Chevrolet, Dodge, Ford, Mercedes-Benz and Volkswagen bringing in one-third of transactions. This opens strategic opportunities to increase SUV inventory for Chevrolet, Dodge, Ford, Volkswagen, and Mercedes-benz increasing profits.


<p align="center">
  <img width="472" height="603" alt="Revenue Trend Line Chart" src="https://github.com/user-attachments/assets/a690e15d-ed2d-410d-b565-7c4fd0263033" />

 <p align="center">
Customer Demographics <br/>

 Analysis of customer demographics from January 2022 to December 2023 reveals 13% earning gap between male and female customers where male customers on the high end with $851,184 and female customers on the low end with $755,973. With males making up 79% of customers while females make up 21%. The income values themselves are higher than what we normally see in real life, but what really matters here is the difference between the groups. This could open more doors to uncover how to increase engagement with female customers.

<p align="center">
<img width="519" height="646" alt="Products Bar Chart" src="https://github.com/user-attachments/assets/7bf65562-1743-4798-b670-3459cc53eb7a" />

<p align="center">
Trends in car purchases <br/>

Analyzing historical data revealed a pattern in car transactions in the months of August, September and October. From August to September, car transactions increased by 82%, rising from 810 to 1,475 orders, but then fell in October. The same thing happened in both 2022 and 2023, which shows a clear seasonal pattern. This surge suggests late summer is a key window to stock up on SUVs and push promotions when customers are most active.


<p align="center">
<img width="549" height="646" alt="Cities Bar Chart" src="https://github.com/user-attachments/assets/41844951-038c-457c-9590-b30da7379996" />

<p align="center">
Car Transactions by Location  <br/>

When breaking down sales by state, states like Texas, Wisconsin, and Arizona came out on top, while others had lower sales performance. Since the dataset is looking at raw transaction numbers, it works well to show which regions are moving cars at a higher pace. Regions such as Texas, Wisconsin and Arizona have transactions greater than 3,400 while the other regions have transactions under 3,399. Highlighting where performance is lowest, provides opportunity to implement a marketing experiment within one of the low performing locations.


<p align="center">
<img width="549" height="646" alt="Cities Bar Chart" src="https://github.com/user-attachments/assets/41844951-038c-457c-9590-b30da7379996" />

<h2>Reccomendations</h2>  

  1. To capitalize on the seasonal surge in car transactions, Major Auto Inc should increase inventory of SUV models from top performing brands  such as Chevrolet, Dodge, Ford, Volkswagen, and Mercedes-Benz in late summer to maximize sales and revenue.
  2. Utilize the strong brand preferences and male dominated customer base to develop marketing campaigns with Chevrolet, Dodge, Ford, Mercedes-Benz, and Volkswagen. These collaborative efforts can focus on tailored messaging to further deepen brand loyalty and drive repeat transactions from the core customer demographics.
  3. Conduct a targeted marketing experiment in a  low performing region, such as Washington to measure the impact of promotional incentives. By offering a 0% apr program to a popular brand. Over a three month period, Major Auto Inc can analyze transaction data to see if the marketing strategy improved car transactions, leading to implementation in other low performing regions. 

Overall, this dataset makes it possible to see clear patterns in car buying: who’s buying, what they’re buying, when they’re buying, and where sales are strongest. These insights can guide dealerships on inventory, brand partnerships, and marketing strategies to maximize results.
