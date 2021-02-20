# Rockbuster Stealth Data Analysis Project

The main purpose of this sample project is to launch a strategy for the new online video rental service. This project will help to better understand the Rockbuster Database and have better insight for future Rockbuster product investments. 
My rule as a data analyst is to help with the launch of the strategy. And I can do that by answering any ad-hoc business questions that other department might have. My first task will be loading all of the Rockbuster's data into a relational database management system (RDBMS). Rockbuster data set contains information about Rockbuster's film, inventory, customers, and payments, among other things. Tools used for this project was SQL and Excel. My task was to answer the following questions:


**Key Questions:**
- Which movies contributed the most/least to revenue gain?
- What was the average rental duration for all videos?
- Which countries are Rockbuster customers based in?
- Where are customers with a high lifetime value-based?
- Do sales figures vary between geographic regions?

Over all, the process of finding solution to the problem was smooth. I started by creating a dictionary for the Rockbuster database schema. I created separate tables for the Fact Tables and Dimension Tables. Then I run some queries to better know what columns are in each table. Then I did some cleaning of the tables such as duplicates, formats, consistency check and more. After the data was cleaned I run more queries and answered the questions above using PostgreSQL. 
The skills/tool/procedures that were used in PostgreSQL were the following: Filtering Data, Summarizing & Cleaning Data, Subqueries, Joining Tables, CTE (common table expression)

Having the skills to analysis data, tell compelling stories. And write moderately complex SQL queries were essential for solving this case study. Writing SQL is very case sensitive. When I started to write complex queries, I mainly had problem with writing additional space, and caps lock. And For each additional function, I had to either update PostgreSQL or install the package in Terminal. But, as I practiced more I was able to solve the problem myself.

This project helped me develop the ability to solve problems for a variety of clients that could be applied to any project and industry. 


**Filtering Data:**
- Basic SQL Query

**Summarizing & Cleaning Data:**
- cleaning dirty Data

**Subqueries:**
- Finding average amount paid by the top 5 customers
- Finding how many of the top 5 customers are based within each country

**Joining Tables:**
- Finding Top 10 countries for Rockbuster
- Finding Top 10 cities within top countries identified
- Finding Top 5 customers in the top cities – paid highest total amounts

**CTE:**  
- Finding the average amount paid by the top 5 customers
- Finding out how many of the top 5 customers are based within each country.


The answers to the main questions that the Rockbuster Stealth Management Board can use for their 2020 company strategy are the following |
--------------------------------------------------------------------------------------------------------------------------------------------|
1.	Movies that contributed the most to revenue gain are Bright Encounters, Ace Goldfinger and the least are Anaconda Confessions, Artist Coldblooded and more.|
2.	The maximum rental duration were 7 days and minimum rental duration were 3 days.|
3.	Rockbuster customer are based on many countries. The Top 10 countries in terms of customer numbers are the following: 1) India = 60, 2) China = 53, 3) US= 36, 4) Japan =31, 5) Mexico = 30, 6) Brazil = 28, 7) Russian Federation = 28, 8) Philippines =20, 9) Turkey= 15, 10) Indonesia = 14 |
4.	Customer with the high lifetime value are in the following cities: 1. Aurora, 2. Acuna, 3. Citrus Heights, 4. Iwaki, 5. Ambattur , 6. Shawnie, 7. So Leopoldo, 8. Tianjin, 9. Hami, 10. Cianjur, And the Top 5 customers paid the highest are the following:  1.Tommy Collazo = 41.96$ from Iran, 2. Eleanor Hunt = 31 $ from Réunion, 3.  Marion Snyder = 20.98$ from Brazil, 4. Karl Seal = 10.99$ from US, 5. Rhonda Kennedy = 9.99$ from Netherlands |
5.	Yes, sales figures vary between geographic regions. For example, the count of sales is 10 in Buenos Aires, 5 in Southern Tagalog, 7 in England, 9 in California, and so on. |

**My recommendations** 
The Rockbuster should invest more in the above customers, cities, and countries for better profit. While doing this project, I learned that SQL is just a language. By writing the right command and queries, we can get SQL to do any kind of analysis with the data. Things that I would do differently to improve is to write advanced queries. It would help save time. 

- Click [here](https://public.tableau.com/profile/morwarid.najafizada#!/vizhome/RockbusterStealthDataAnalysisProject/Rockbuster) to view the full Tableau Dashboard 


