# Portfolio
Business Intelligence and Data Analytics Portfolio by **Guilherme Oliveira - Lisbon, Portugal**

*Below are projects meant to demonstrate data manipulation skills necessary for Business Intelligence and Data Analyst roles, such as planning, data cleansing and modelling, data analysis and  visualization using industry-standard tools such as R, MySQL and Power BI.*

## [Project 1 - E-Commerce Sales Business Review](https://github.com/jgcoliveira/ECommerce--Sales-Business-Review)

**Sales Data BI project using using Excel and MySQL 8.0 for data cleaning and modelling and PowerBI for visualization**

- Database Construction - created a dedicated MySQL schema and multiple tables with the necessary columns and datatypes, then loaded the .csv raw data into those tables, modelled the data by defining the inter-table relationships.
- Data Cleaning - Cleansed the data by assessing the logical relationships between the various attributes and understanding the business context, then searching for inconsistencies and data errors and taking the appropriate corrective measures.
- Power BI Report - Linked the mySQL database to Power BI, created a data model, performed the necessary calculations using DAX. Created sucessful visualizations that allow potential stakeholders to extract insights and answer business questions.

### Overview
#### Analyse monthly evolution, discover which states represent the majority of sales and purchases, find out what are the best-selling product categories.
![v2 0_Overview_1](https://user-images.githubusercontent.com/78386715/125784023-e5dc7b71-374c-4eaf-8301-1d466c4f260d.PNG)

### State
#### Get an in-depth look of every state's sales performance, find out what are the best-selling product categories, discover where the orders are being shipped from.
![v2 0_State_1](https://user-images.githubusercontent.com/78386715/125784199-03a1502f-ccf3-40c5-9abd-f40b9bbcacdd.PNG)

### Payment Operations
#### See the number of payments made per period, analyse them according to their popularity.
![v2 0_Payment_Methods_1](https://user-images.githubusercontent.com/78386715/125784446-2ad314ff-d695-43c5-a650-2443440c329a.PNG)

### Delivery Operations
#### Track the average delivery time and number of delays throughout time and according to buyer state.
![v2 0_Delivery_Average_1](https://user-images.githubusercontent.com/78386715/125784658-ee46bd8f-1681-4bba-84cf-7341d19dbdc4.PNG)

## [Project 2 - Bike Share Service Users](https://github.com/jgcoliveira/Bike-Share-Service)


**Bike Sharing Service Data BI project using using R (tidyverse packages) for data cleaning, manipulation and visualization**
*All tasks were performed using R tidyverse packages via the RStudio IDE*

- Data Colection and Preparation - Collected and combined data from multiple .csv files into a single one by making sure they all had common columns, with the same type of observations and data types.
- Data Cleaning and Manipulation - Cleaned the data by inspecting it, detecting anomalies (such as unwanted characters, inconsistent data, useless observations) and then proceeding to using R's multiple cleaning tools (janitor, skymr, dplyr).
- Summary Analyisis, Findings and Visualizations - created pipes to wrangle the cleaned data and perform a descriptive summary analysis, then proceeded to visualize those same statistics by plotting graphs using ggplot2.

### Total Number of Rides per Weekday, User Type
#### See the number of rides made throughout the week, their evolution and how they vary from user member to casual user.
![image](https://user-images.githubusercontent.com/78386715/135473312-bc8930bb-8ede-47a5-be11-8a4c8b5a9780.png)


### Average Ride Duration per Weekday, User Type
#### See the average ride time per weekday, its evolution throughout the week how it varies from user member to casual user.
![image](https://user-images.githubusercontent.com/78386715/135474165-5cf3d75b-5ddd-4e18-83ae-f9e8107ace48.png)

### Total Number of Rides per Hour, User Type
#### See the number of rides made throughout the day, their evolution and how they vary from user member to casual user.
![image](https://user-images.githubusercontent.com/78386715/135475120-ca90ab8e-b4bd-4434-a615-436cb3d69015.png)
