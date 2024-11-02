
![LITA logo M011](https://github.com/user-attachments/assets/a85af7d1-fd38-40b0-a61d-6421dfd60a64)

### Project Title:-My First Data Analysis Project with Ladies in Tech (Incubator Hub) – 2024.
---
### Quick Access
- [Project Progress Overview](#project-progress-overview)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Cleaning and Preparations](#data-cleaning-and-preparations)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Data vislization](#data-visualization)
- [Future goals](#future-goals)
- [Classwork:- Text Cleaning in Power BI](#classwork:-text-cleaning-in-power-bi)
- [Lecturers](#lecturers)
- [Certifications](#certifications)

### Project Progress Overview
- I have successfully worked on multiple data analysis projects, each focusing on different aspects of data manipulation, visualization, and insight generation. These include:

- Sales Performance Analysis for a Retail Store: In this project, you analyzed sales data to uncover key insights such as top-selling products, regional sales performance, and monthly trends. You also built an interactive Power BI dashboard that visualized these metrics.

- Subscription Service Data Analysis: Focused on customer segmentation, tracking subscription types, and analyzing trends in cancellations and renewals. This led to the creation of a dashboard that provided key insights into customer behavior and subscription lifecycles.

### Data Sources
The primary dataset used for this project is sales.csv, which is an open-source dataset. This data is freely available and can be downloaded from various online repositories such as Kaggle, FRED, or other open data platforms. These sources provide a wide range of datasets for analysis and are accessible to the public for educational and research purposes.

### Tools Used
- Microsoft Excel 
Extensive experience using Excel for
1. data cleaning,
2. analysis,
3. and visualization.
I’ve used pivot tables to explore sales data, calculated metrics such as average sales and total revenue by region, and performed basic statistical analysis.
     
- SQL(Structured Query Language)
Strong command of SQL for
1. data extraction,
2. transformation, 
3. and reporting.
I’ve written complex queries to analyze sales performance, and identify trends

- Power BI 
I’ve developed interactive dashboards using Power BI to visualize insights from SQL queries and Excel analyses. Which has made my dashboards highlight important business metrics, making data-driven decision-making easier.

  Data Visualization: Skilled in using visualizations to communicate data insights effectively, including bar charts, line graphs, and slicers to filter data.
     
- GITHUB
For Portfolio Building
Which will explain who I am, what I do, and what I am passionate about.

 ### Data Cleaning and Preparations
 In the initial phase of the Date cleaning and preparations, we perfrom the following action;
 1. Data loading and Inspection
 2. Handling missing var
 3. Data cleaning and

### Exploratory Data Analysis
EDA involves exploring and analyzing the dataset to uncover patterns, trends, and insights that help answer key business questions. The primary objectives during this phase include:

- What is the overall sales trend?
By examining sales data over time, we can identify trends such as growth or decline in sales. This analysis helps in understanding seasonality, the impact of promotions, or other external factors affecting sales performance.

- Which products are the top sellers?
This question focuses on identifying the best-performing products by analyzing metrics like total revenue, sales volume, and customer preferences. Understanding which products are in demand can help in optimizing inventory, marketing, and production strategies.

- What are the products with peak sales?
Analyzing which products experience peak sales during certain periods helps pinpoint factors contributing to these spikes, such as special promotions, seasonal demand, or external events. This insight can inform future marketing efforts and inventory planning.

### Data Analysis
In this phase, we use various tools and techniques to derive insights from the data. Below are examples of some basic SQL queries and DAX expressions used during the analysis:

#### Example SQL Query:
This query retrieves all records from Table1 where the LITA_DB column is marked as TRUE:
```SQL
SELECT * FROM TABLE 1
WHERE LITA_DB = TRUE;
```

#### Example DAX Expression:
In Power BI, DAX expressions were used to create calculated columns or measures. For instance, to calculate the total sales for a product, we used a simple DAX formula:

```dax
Total Sales = SUM(Sales[Amount])
```

### Data visualization
#### Example Excel:
![SalesData](https://github.com/user-attachments/assets/3c848216-6793-44ff-b88a-95ca9bf8ae2b)

#### Example SQL:
![SQL](https://github.com/user-attachments/assets/5b4c4921-9503-465e-b9f7-16c436bf9d1e)

#### Example PowerBI:
![PowerBI Class](https://github.com/user-attachments/assets/222e376a-484f-4d7e-961c-cdb1ca6251ca)
![PowerBI Class 1](https://github.com/user-attachments/assets/36a685a3-624d-48f4-9ad9-cce6c3cddfda)


### Future goals

- Learning advanced SQL functions for more complex queries.
- Enhancing data visualization skills by incorporating more advanced features of Power BI.

## Classwork: Text Cleaning in Power BI
### Objectives:
- Understand how to handle text data within Power BI.
- Perform basic text transformations to clean up the dataset.
- Use Power Query Editor to apply text cleaning techniques.

### Key Tasks:
1. Removing Unwanted Characters(Null)
2. Changing Case and promoting headers
3. Trimming Extra Spaces
4. Splitting Columns
   All done in the Tranfrom data.

![Text Cleaning 2](https://github.com/user-attachments/assets/c5076978-f772-4aec-89ac-2d4a76a83327)
![Text Cleaning 3](https://github.com/user-attachments/assets/6a67e590-2313-4138-b16e-769900d19fae)
![Text Cleaning 4](https://github.com/user-attachments/assets/72532359-e353-46c8-adcd-6d786b0f31ad)


## First Project on Salesdata
### Key Tasks:
- Top-selling Products 
- ⁠Regional Performance 
- ⁠Monthly Sales trends
  
### Excel
Average sales
```Excel
=AVERAGEIF(C2:C7501, "Gloves", H2:H7501)
```
Total Revenue
```Excel
=SUMIF(D1:D50000,"South",H1:H50000)
```
![Excel First Project](https://github.com/user-attachments/assets/444e447a-a5b8-486e-82b1-b7623231051d)
![PivotTable 1](https://github.com/user-attachments/assets/cb25449e-f20a-456b-891c-a16a003129b3)
![PivotTable 2](https://github.com/user-attachments/assets/573befd5-aa7b-42bc-9d84-5d3206576feb)
![PivotTable 3](https://github.com/user-attachments/assets/c67a8829-6585-4685-a973-f5fddfcd4667)

### SQL
```SQL
SELECT (*) FROM [dbo][SALESDATA]
```
```SQL
SELECT Product, SUM(Quantity *UnitPrice) As [TOTAL SALES]
From where I saved it
Group by Product 
Order by [TOTAL SALES] DESC;
```

![SQL First Project 1](https://github.com/user-attachments/assets/5d8b7214-3a9f-4200-878a-3d8716290fc3)
![SQL First Project 2](https://github.com/user-attachments/assets/57a90769-3bdf-44ce-a0eb-b1ed6bd8e81d)
![SQL First Project 3](https://github.com/user-attachments/assets/35369b75-61e6-475a-888a-f8504e5d6cea)
![SQL First Project 4](https://github.com/user-attachments/assets/34ba6e2a-58a2-4187-bcaa-828e4c195326)
![SQL First Project 5](https://github.com/user-attachments/assets/c05b61e5-acfb-4f46-a38f-06492fc4becb)

### PowerBI
![Updated project 1](https://github.com/user-attachments/assets/40129e40-67f2-44d7-8b3f-123ba7089942)

## Summarize Key Metrics
- Total Sales: Reflects the overall revenue or total sales by calculating Quantity * UnitPrice.
- Top-Selling Products: Highlights the products with the highest sales or revenue, with standout items including Gloves, Hat, Jacket, Shirt, Shoes, and Socks.
- Top Regions: Identifies the regions with the highest sales, providing insights into geographic performance across South, East, North, and West.
- Customer Segments: Insights into customers unique identifier such as their ID's numbers(Cus1141, Cus1234, Cus1288, Cus1417).
- Order ID: It is used any time they purchase an item(1006, 1012, 1018, 1006).
- Order Date:- Show when they purchased an item(6/30/2023, 6/30/2024)

![image](https://github.com/user-attachments/assets/964d0257-9f7d-45ad-8395-6fcd56e61adb)

							
## Identify Trends
### Monthly Sales Trends: Seasonal patterns reveal notable sales fluctuations over the year.

- Upward Trend: Sales show a positive trend, with a significant increase reaching 2.75M in the first quarter, suggesting a strong start to the year. 📈 :up
- Decline Periods: Sales experience noticeable declines in March, April, September, and December, which could be attributed to factors like marketing strategy, store location, or limited understanding of evolving market trends, customer preferences, and e-commerce opportunities. :📉 🔻

### Product Best Sold: Shoes is the best sold products in South or Sock is the less popular products over time.

![image](https://github.com/user-attachments/assets/3b644c32-faf2-4e72-9b0b-d2a735c54ceb)

![image](https://github.com/user-attachments/assets/995c7e7f-e115-4c91-b7da-57fe930ac297)





## My Analysis 
### Based on Research: "What Month Has the Highest Sales?"
Traditionally, the peak months for retail sales are November and December, driven by the holiday season. The period from Thanksgiving through New Year’s Day sees a surge in consumer spending, as people shop for gifts, decorations, and holiday essentials.

To capitalize on these peak sales months, retailers should consider implementing targeted strategies, such as 
- Seasonal promotions, 
- Special holiday campaigns,
- Enhanced inventory management,
- Personalized marketing, such Giveaways, Rebranding on the best selling product 

   Leveraging these tactics can help maximize revenue during high-demand periods.



## Second Project on CustomerData
### Key Tasks:
- understand customer behavior,
- track subscription types,
- identify key trends in cancellations and renewals
  
### Excel 
![Second Project](https://github.com/user-attachments/assets/35fdf9e0-164c-4af1-acb4-149d766f7da4)

### SQL
![SQL Second Project 1](https://github.com/user-attachments/assets/25f874c7-2755-4fcd-8d06-486e2829e4df)
![SQL Second Project 2](https://github.com/user-attachments/assets/27bbe088-226f-4063-bcbd-113068097c1c)
![SQL Second Project 3](https://github.com/user-attachments/assets/3ff586dd-067e-4fb9-896a-5c0fbd47c9f3)
![SQL Second Project 4](https://github.com/user-attachments/assets/be893588-4edd-4fd3-beb3-01188f60b334)
![SQL Second Project 5](https://github.com/user-attachments/assets/ceb2cde2-8bab-40a5-8d53-b5d5b33f2b2c)
![SQL Second Project 6](https://github.com/user-attachments/assets/29a90955-7f1d-4cf9-aae3-c38f4e6a4a1d)

### PowerBI


## Summarize Key Metrics
- CustomerID	201, 202, 215,216
- CustomerName		John	, Jane, Paul, Grace
- Region	North, South, East, West
- SubscriptionType	Basic, Premium, Standard
- SubscriptionStart	1/31/2022, 2/28/2022, 3/31/2023, 4/30/2023
- SubscriptionEnd	1/31/2023, 2/28/2023, 3/31/2024, 4/30/2024
- Canceled	FALSE, TRUE
- Revenue	
- duration 365, 366
					
![image](https://github.com/user-attachments/assets/baf44594-058f-4322-a555-ced00e4c0cb7)



  ## Lecturers 
  - Excel:-Muhsin Hameed(Senior BI Conslutant/ Trainer)
  - SQL:-Femi Ayodele(MCT)(IB Developer/ Data Analyst)
  - PowerBI:-Temidayo TeeDee(Data Instructor)
    
## Certifications
