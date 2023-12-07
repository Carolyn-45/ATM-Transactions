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

#### _Data Modelling_
After this I made use of the import storage mode to bring the dataset into Power BI. I proceeded to establish relationships between the tables. I created a snowflake schema as shown below;


#### _Key Findings_
I took a deep dive into the data and uncovered the following interesting insights;
1. The total number of transactions for all the 5 states is 6.52M with Lagos leading with 2.59M and the least being from Federal City 
   Territory with 537,950 transactions.
2. 71.4% of the transactions are performed on weekdays while 28.6% are performed on weekends.
3. In addition, most of the transaction’s activities usually occur between 4 to 6pm with the peak hour being 5pm
4. Over the years, the transactions depict very interesting trends. In 2019, March reports the highest number of years with the numbers 
   decreasing gradually in the last quarter of the year.
5. In 2021 and 2022, there is a drastic decrease in transactions in February followed by a drastic increase in March, reporting an 
   increase of 300M in transaction revenue.
6. Withdrawal transaction types are usually performed on the ATMs, contributing 35% of the transactions followed by Transfers with 24% 
   and 20% each for Deposits and Balance Inquiry.
7. 8828 customers have transacted with the Datakliq Bank. Of these, 50.3% are male and 49.7% are female. On average, the transaction 
   frequency is 739.
8. Majority of the customers are in the ages between 21 and 30 years old. These customers report a transaction frequency of 801 and they 
   contribute 2M of the total transactions. Customers who are over 60 years old form the least transacting age group.
9. Although the Skilled professional category are leading in the number of transactions, students on their own have over 820,000 
   transactions.
10. In overall, the average transaction success rate for the 131 ATMs is 50.8% while the average error is 1.1%.
11. Although ATMs in Lagos state have generated the highest transaction revenue of 43.9B customers from that state report the lowest 
    transaction frequency of 588. Federal City Territory has generated the lowest transaction revenue of 8.6B yet it reports a 
    transaction frequency of 2126.

#### _Recommendations_
1. Given that Lagos has the highest transaction revenue, the bank can optimize the placement of ATMs in locations with high foot traffic 
   or areas with a dense population to maximize ATM utilization.
   
2. Since withdrawals are the most common transaction type, the bank should ensure that cash replenishment cycles are done regularly so 
   that ATMs are well-stocked with cash to meet customer demands. 
3. It is very clear that the peak transaction hours are between 4pm and 6pm. Therefore, DataKliq Bank should ensure high ATM availability 
   during these busy periods to meet customer demand. This can be possible through the utilization of real-time monitoring systems to 
   track the status of the ATMs continuously. This would then allow the Bank to respond to any malfunctions or issues that may arise 
   during the peak hours.
4. Kano and Lagos states report the lowest transaction frequencies. Hence, the Bank should conduct targeted marketing or promotional 
   campaigns to increase awareness and encourage more frequent usage. Some of the campaigns include cashback rewards, fee waivers on ATM 
   transactions for a period and social media campaign to share engaging content on the benefits of ATM usage.
5. The average transaction success rate for ATMs is 50.8%, which is an area for improvement. To enhance customer experience should focus 
   on understanding the causes of transaction errors and optimize transaction success rates. This can be done by investigating and 
   identifying the root causes of transaction errors such as error patterns, error messages, and transaction logs to understand the 
   specific issues that lead to failures. Also, the Bank should gather and analyze customer feedback related to transaction experiences, 
   paying attention to common complaints or concerns mentioned by customers and use this information to prioritize areas for improvement.


#### _Conclusion_
In the pursuit of optimizing ATM services, this project exemplifies the transformative power of data analysis. By decoding customer transactions, we pave the way for strategic enhancements that promise a more streamlined, cost-effective, and user-friendly ATM experience. The insights gained mark not just a conclusion but a stepping stone towards a data-informed evolution in banking services.





