# Sales Analytics
Performing Data Cleaning and Manipulation Techniques Using Pandas. 
Filename – data_dump.xlsx 
Given purchase-date column is in UTC time format, converting it to IST then spliting the column into two named as date_stamp and time_stamp. 
Bucketing the time_stamp into given intervals which are as follows: 
     00:00:00 - 08:00:00 – bucket1
     00:00:00 - 16:00:00 – bucket2
     00:00:00 - 23:59:59 – bucket3
Every bucket will be in separate column. 
Obtaining  top5 sales state wise and ASIN using the above data. 
