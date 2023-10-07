# Stock-Exchange-Data-Analysis-Using-HIVE

I will be analysing seven years of New York Stock Exchange data from 2010-16 of 500 + companies using MYSQL,HIVE, and SCQOP from Hadoop and Spark. I will create a data pipleine using sqoop to pull data into HIVE from MYSQL server, and then create a hive table for data analysis.


### Problem Statement:
NewYork stock exchange data of seven years, between 2010 to 2016, is captured for 500+ listed companies. The data set comprises of intra-day prices and volume traded for each listed company. The data serves both for machine learning and exploratory analysis projects, to automate the trading process and to predict the next trading-day winners or losers.. The scope of this project is limited to exploratory data analysis.

### Analysis to be done: 
Exploratory analysis to understand how MoM or YoY companies from different sectors or industries and states have progressed in a period of 7 years


## Datasets:
 
Column Name	Datatype
Trading_date	Date
Symbol	String
Open	double
Close	double
Low	double
High	double
Volume	int

TABLE: STOCK_COMPANIES

Column Name	Datatype
Symbol	String
Company_name	String
Sector	String
Sub_industry	String
Headquarter	String
