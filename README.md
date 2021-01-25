# Swiggy_Case_Study_MySQL
Analysis of pre-Diwali and post-Diwali data of Swiggy stores using MySQL Workbench

Database contents:
There are two tables in the database which are as follows:
1.	Prediwalisales - Contains Pre-Diwali sales data
2.	Postdiwalisales - Contains Post-Diwali sales data 

About the dataset:
The dataset has 187678 records and 11 fields. The description about each of the fields is given below:

DT: Date of transaction.

ID: Store ID of the Swiggy store.

City: ID of the city the store belongs to.

NAME: Name of the store.

ITEM_ID: Individual Item IDs of the items sold by a particular store.

ITEM_NAME: Name of the item sold.	

HR of the day: The hour of the day a particualr transaction happened.

ORDERS: Number of orders of an item.	

QTY: The quantity of an item sold.

ITEM_GMV: The gross merchandise value of an item.

CATEGORY: The category of food the item belongs to.


Insights:
After running queries in MySQL Workbench on the given post Diwali sales and pre Diwali sales dataset by Swiggy, we can drive the following insights:
1.	The shop wise average sales post Diwali is greater than Pre Diwali sales, though the number of shops considered in the pre and post Diwali datasets are different. So, no accurate comparison can be done.

2.	Peak hours of the day in terms of sales in both Pre Diwali and Post Diwali cases were from afternoon till evening.

3.	The hours of the day when maximum sales occurred in Pre Diwali and Post Diwali cases were 7 PM and 1 PM respectively. In terms of minimum sales, the hours of the day Pre Diwali and Post Diwali were 2 AM and 5 AM respectively.

4.	Pre Diwali, Masala Dosa was the most popular item under South Indian Delight category among all the shops while Post Diwali, Kaju Katli was the most popular item under Sweets category. 

5.	A new category called Diwali Special was introduced among shops Post Diwali. Sweets, Snacks, South Indian, Quick Bites are categories which always give more than average sales across shops in both the Pre and Post Diwali cases.

6.	On 17th October 2019 Pre Diwali, maximum sales happened. The date for the same Post Diwali was 26th October 2019.

7.	City ID 7 had the maximum sales in both Pre Diwali and Post Diwali scenarios.

8.	City IDs 7, 18, 19, 37 are always in the top 10 list in both Pre and Post Diwali cases. As such, they are performing much better than other cities. 

9.	City ID 10487 is always present as before in both the scenarios, but in the bottom 10 list. Thus it is one of the consistently worse performing cities both Pre and Post Diwali.

10.	Haldiram’s and SS Dairy(Tripolis) held the 1st and 2nd positions in terms of sales pre Diwali. Their positions interchanged post Diwali.

11.	Aryas sweets and Bakery and Shree Sweets held the lowest position in terms of sales Pre Diwali and post Diwali respectively.
