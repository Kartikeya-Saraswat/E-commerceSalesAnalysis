# E-Commerce Sales Analysis Project 👩‍💻

🎯 𝑨𝒃𝒐𝒖𝒕 𝒕𝒉𝒆 𝒑𝒓𝒐𝒋𝒆𝒄𝒕 - 

- In this project, we have analyzed an Indian Ecommerce store dataset.
- dataset is from Kaggle, and consists of 3 CSV files- List of Orders, Order details, Sales target.
- List of Orders - This dataset contains purchase information including Order ID, Date of Purchase and customer details.
- Order Details - This dataset contains order ID, price, quantity, profit, category and subcategory of product. 
- Sales target - This dataset contains sales target amount and date for each product category.


🎯 𝑷𝒓𝒐𝒋𝒆𝒄𝒕 𝑫𝒊𝒓𝒆𝒄𝒕𝒐𝒓𝒚 - 

- This Project Repository consists of - 
- SQL In Depth Analysis - Analysed the dataset by writing complex SQL Queries to gain insights.
- Power BI Dashboard - live Interactive Dashboard for visualizing the insights.
- Alteryx Workflows - Used in RFM Analysis to calculate score for customer segmentation.

## 𝐒𝐐𝐋 𝐈𝐧-𝐃𝐞𝐩𝐭𝐡 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬 👩‍💻

- Analyzed an e-commerce store dataset by writing SQL Queries to get a holistic view of the e-commerce operations. <br>
- Database Used - MYSQL <br> 
- Some of the functions used -  Aggregrate Functions, Logical Statements, CASE Statement, Subqueries, Common Table Expressions (CTE), Window Functions, and Joins.
- Dataset from Kaggle consisting of 3 CSV files - List of Orders, Order details, Sales target. <br> 
1. List of Orders - This dataset contains purchase information. The information includes ID, Date of Purchase and customer details.<br>
2. Order Details - This dataset contains order ID, with the order price, quantity, profit, category and subcategory of product.<br>
3. Sales target - This dataset contains sales target amount and date for each product category.<br>

## E-Commerce Sales Analysis Dashboard 👩‍💻

► In this project, we have analyzed an Indian E-commerce store dataset. <br>
► Dataset is from Kaggle, and consists of 3 csv files- List of Orders, Order details, and Sales target. <br>
► List of Orders-This dataset contains purchase information. The information includes ID, Date of Purchase and customer details. <br>
► Order Details- This dataset contains order ID, with the order price, quantity, profit, category and subcategory of product.<br>
► Sales target-This dataset contains sales target amount and date for each product category. <br>
► Also, performed RFM Analysis which gives more clarity to the business about it's customers. <br>
► Power BI dashboard - https://www.novypro.com/project/powerbi-23

## 𝗪𝗵𝗮𝘁 𝗶𝘀 𝗥𝗙𝗠 𝗔𝗻𝗮𝗹𝘆𝘀𝗶𝘀? 👩‍💻 <br>

► RFM (Recency, Frequency, Monetary) analysis is a marketing technique used to segment customers based on their purchase behavior. <br>
► It involves analyzing the recency (how recently a customer made a purchase), frequency (how often a customer makes a purchase), and monetary value (how much a customer spends) of their transactions. <br>
► The RFM model assigns a score to each customer in each category (1-5) and then combines the scores to create a composite RFM score. <br>
► Customers are then segmented based on their composite RFM score, with the highest scoring customers considered the most valuable. <be>

## Alteryx Workflows 👩‍💻

- We have used Alteryx for calculating R Score, F Score, and M Score For RFM Analysis and Segmentation of customers. 
- Alteryx is used to automate data processes more quickly and efficiently. It collects, prepares, and blends data that may otherwise be time-consuming or impossible to combine using other tools. 
- Through this, Alteryx provides answers to complex business questions and can help to simplify or automate data processes. 
- This not only saves a significant amount of time, but also helps to prevent errors that may have occurred if the process were done manually.

### 𝘄𝗵𝗮𝘁 𝗶𝘀 𝗥 𝗦𝗰𝗼𝗿𝗲? 𝗛𝗼𝘄 𝘁𝗼 𝗰𝗮𝗹𝗰𝘂𝗹𝗮𝘁𝗲? 

- “R” stands for Recency and refers to how recently a customer has bought. 
- Customer with most recent order are given R_SCORE AS 4
- Formula used - 𝑰𝑭 [𝑴𝒊𝒏 𝒐𝒇 𝑹𝒆𝒄𝒆𝒏𝒄𝒚] = 𝟑𝟔𝟒 𝒐𝒓 [𝑴𝒊𝒏 𝒐𝒇 𝑹𝒆𝒄𝒆𝒏𝒄𝒚] > 𝟐𝟓𝟑 𝑻𝑯𝑬𝑵 𝟏 𝑬𝑳𝑺𝑬𝑰𝑭 [𝑴𝒊𝒏 𝒐𝒇 𝑹𝒆𝒄𝒆𝒏𝒄𝒚] >= 𝟐𝟓𝟑 𝒐𝒓 [𝑴𝒊𝒏 𝒐𝒇 𝑹𝒆𝒄𝒆𝒏𝒄𝒚] > 𝟏𝟒𝟓 𝑻𝑯𝑬𝑵 𝟐 
𝑬𝑳𝑺𝑬𝒊𝒇 [𝑴𝒊𝒏 𝒐𝒇 𝑹𝒆𝒄𝒆𝒏𝒄𝒚] >= 𝟏𝟒𝟓 𝒐𝒓 [𝑴𝒊𝒏 𝒐𝒇 𝑹𝒆𝒄𝒆𝒏𝒄𝒚] > 𝟔𝟓 𝑻𝑯𝑬𝑵 𝟑 𝑬𝑳𝑺𝑬 𝟒 𝑬𝑵𝑫𝑰𝑭 

### 𝘄𝗵𝗮𝘁 𝗶𝘀 𝗙 𝗦𝗰𝗼𝗿𝗲? 𝗛𝗼𝘄 𝘁𝗼 𝗰𝗮𝗹𝗰𝘂𝗹𝗮𝘁𝗲? 

- “F" stands for Frequency and refers to How often do they purchase?
- Customer with most frequent orders are given F_SCORE AS 4
- Formula used - 𝑰𝑭 [𝑺𝒖𝒎 𝒐𝒇 𝑸𝒖𝒂𝒏𝒕𝒊𝒕𝒚] = 𝟓𝟕 𝒐𝒓 [𝑺𝒖𝒎 𝒐𝒇 𝑸𝒖𝒂𝒏𝒕𝒊𝒕𝒚] > 𝟑𝟓 𝑻𝑯𝑬𝑵 𝟒 𝑬𝑳𝑺𝑬𝑰𝑭 [𝑺𝒖𝒎 𝒐𝒇 𝑸𝒖𝒂𝒏𝒕𝒊𝒕𝒚]>= 𝟑𝟓 𝒐𝒓 [𝑺𝒖𝒎 𝒐𝒇 𝑸𝒖𝒂𝒏𝒕𝒊𝒕𝒚] > 𝟏𝟓 𝑻𝑯𝑬𝑵 𝟑 
  𝑬𝑳𝑺𝑬𝒊𝒇 [𝑺𝒖𝒎 𝒐𝒇 𝑸𝒖𝒂𝒏𝒕𝒊𝒕𝒚] >= 𝟏𝟓 𝒐𝒓 [𝑺𝒖𝒎 𝒐𝒇 𝑸𝒖𝒂𝒏𝒕𝒊𝒕𝒚] > 𝟓 𝑻𝑯𝑬𝑵 𝟐 𝑬𝑳𝑺𝑬 𝟏 𝑬𝑵𝑫𝑰𝑭 
  
### 𝘄𝗵𝗮𝘁 𝗶𝘀 𝗠 𝗦𝗰𝗼𝗿𝗲? 𝗛𝗼𝘄 𝘁𝗼 𝗰𝗮𝗹𝗰𝘂𝗹𝗮𝘁𝗲?

- "M" stands for Monetary Value and refers to how much do they spend?
- Customer with Max SUM_PROFIT are given M_SCORE AS 4
- Formula Used - 𝑰𝑭 [𝑺𝒖𝒎 𝒐𝒇 𝑷𝒓𝒐𝒇𝒊𝒕] = 𝟏𝟗𝟕𝟎 𝒐𝒓 [𝑺𝒖𝒎 𝒐𝒇 𝑷𝒓𝒐𝒇𝒊𝒕] > 𝟓𝟎𝟎 𝑻𝑯𝑬𝑵 𝟒 𝑬𝑳𝑺𝑬𝑰𝑭 [𝑺𝒖𝒎 𝒐𝒇 𝑷𝒓𝒐𝒇𝒊𝒕] >= 𝟓𝟎𝟎 𝒐𝒓 [𝑺𝒖𝒎 𝒐𝒇 𝑷𝒓𝒐𝒇𝒊𝒕] > 𝟐𝟐 𝑻𝑯𝑬𝑵 𝟑 
  𝑬𝑳𝑺𝑬𝒊𝒇 [𝑺𝒖𝒎 𝒐𝒇 𝑷𝒓𝒐𝒇𝒊𝒕] >= 𝟐𝟐 𝒐𝒓 [𝑺𝒖𝒎 𝒐𝒇 𝑷𝒓𝒐𝒇𝒊𝒕] > -𝟐𝟐 𝑻𝑯𝑬𝑵 𝟐 𝑬𝑳𝑺𝑬 𝟏 𝑬𝑵𝑫𝑰𝑭

###  𝗖𝗮𝗹𝗰𝘂𝗹𝗮𝘁𝗶𝗻𝗴 𝗖𝗼𝗺𝗯𝗶𝗻𝗲𝗱 𝗥𝗙𝗠 𝗦𝗰𝗼𝗿𝗲 -  

- Combined RFM Score can be calculated using this formula - ([𝑹_𝑺𝒄𝒐𝒓𝒆] * 𝟏𝟎𝟎) + ([𝑭_𝑺𝒄𝒐𝒓𝒆] * 𝟏𝟎) + [𝑴_𝑺𝒄𝒐𝒓𝒆] 
- Based on the RFM Scores Customers are divided into various segments such as Platimum, Gold, Silver, and Bronze. 
- Refer to the alteryx workflow below 

  <img width="533" alt="image" src="https://user-images.githubusercontent.com/63411758/213882400-327fbf81-41d0-49e9-9348-818fb0143743.png">


## 𝑲𝒆𝒚 𝑰𝒏𝒔𝒊𝒈𝒉𝒕𝒔: <br>

🎯𝗖𝘂𝘀𝘁𝗼𝗺𝗲𝗿 𝗗𝗲𝘁𝗮𝗶𝗹𝘀:

• 63% of total orders is from Clothing category. <br>
• 68% orders are Profitable, 30% orders are giving Loss & 2% are None. <br>
• Most Profitable months are March and November. <br>
• All the categories have achieved more than 70% of target revenue.<br>
• Electronics making the most revenue i.e., 37% <br>
• Electronic games & Tables sub-categories orders are not profitable to the business. <br>

🎯𝗢𝗿𝗱𝗲𝗿 𝗗𝗲𝘁𝗮𝗶𝗹𝘀:

• There are total 331 customers with 440 unique orders. <br>
• Madhya Pradesh is the most profitable state i.e., Rs.7K <br>
• Tamil Nadu, Andhra Pradesh & Punjab are the states which are making loss. <br>
• Most orders are from the customer age bucket of 41-50 i.e., 389 and Clothing is the popular category. <br>
• Indore, Delhi, Allahabad and Mumbai are cities with most profits. <br>
• Average Cost price & Selling price is approximately Rs. 1 Lakh per state. <br>

🎯𝗥𝗙𝗠 𝗔𝗻𝗮𝗹𝘆𝘀𝗶𝘀:

• There are 2 customers with 444 RFM Score. <br>
• RFM Analysis shows that the company has more count of Gold customers and less count of Platinum customers. <br>
• Average Recency Score is 2.50, Average Frequency Score is 1.90 & Average Monetary Score is 2.31. <br>
• In Clothing Category, we have more monetary score. <br>
• Due to loss making orders we have more Bronze customers. <br>
• Age bucket of 41-50 are more likely to be Platinum customers. <be>








