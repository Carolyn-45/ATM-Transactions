# ATM-Transactions Project

### Customer Transactions Behaviour for ATM Optimization

#### _Introduction_
In an era where digital transactions are widespread, understanding and optimizing customer behavior at ATMs is paramount.

This project explores customer transactions behavior to optimize ATM operations. Leveraging data analytics techniques, I delve into patterns, peak usage times, and transaction types. The insights gained aim to enhance ATM placement, resource allocation, and overall efficiency by striving to elevate the ATM experience through informed decision-making and data-driven strategies. 

Join me in harnessing the power of data to revolutionize ATM efficiency and convenience.

#### _Problem Statement_
ATM operations lack the strategic utilization of customer transaction data, resulting in sub-optimal resource allocation, extended queues, and inefficient service delivery. 

In this  project I intend to answer the following questions;
+ What is the total number of transactions
+ What is the distribution of transaction types
+ How do transactions vary over different hours, days and months
+ How many are the transacting customers in the 5 states
+ What is the average transaction frequency per customer
+ What is the age distribution of the customers
+ How does Customer Occupation affect the transacting behaviour
+ Which is the most common transaction type for each customer segment
+ How does transaction frequency compare to the transaction revenue generated in the 5 states
+ Which ATMs have the highest and lowest utilization

#### _Tools Used_
1. SQL; Postgres16
2. Microsoft Power BI

#### _Data Collection_
The dataset I used in this project was provided by the DataKliq team. 

This dataset comprises of a Transactions Table that contains transactions for five states of Nigeria. In addition, the dataset also contains Customer, Transaction type, Hour, Calendar, ATM Location and ATM Maintenance tables that provide more information on the Transactions Table.

#### _Data Cleaning and Transformation_
Data cleaning and transformation are an important aspect of Data Analysis as it ensures accuracy and credibility of the insights generated from the data.
For this, I first created a database in Postgres16 to host the various tables. I then examined each table for null values and errors. I noticed that some columns in the ATM Maintenance table had null values and I had to replace them with 'N/A' so as not to affect the integrity  of the data.
I then performed data transformation tasks such as defining the data types for each column, appending the transformation data and creating a calendar table.



