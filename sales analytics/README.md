Performing Data Cleaning and Manipulation Techniques Using Pandas. 
- Filename – data_dump.xlsx 
- Step1: Given purchase-date column is in UTC time format, converting it to IST then spliting the column into two named as date_stamp and time_stamp. 
- Step2: Bucket the time_stamp into given intervals which are as follows: <br />
  00:00:00 - 08:00:00 – bucket1 <br />
   00:00:00 - 16:00:00 – bucket2 <br />
   00:00:00 - 23:59:59 – bucket3 <br />
- Every bucket will be in separate column. 
- Step3: Obtaining total sales state wise and ASIN using the above data. 
