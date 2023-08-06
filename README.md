# Excel-Project-on-US-Superstore-Data
My first Project on data analysis using Excel/Spreadsheet tool in Data Analysis 3rd Cohort Class with Promise Chinonso
# Introduction
In the previous week, we rounded up Data Analysis using Excel/Spreadsheet and this came with an assigned project using a given US Superstore dataset. This project another interesting way of exercising the skills and knowledge learnt in the past couple of weeks. In this project, we were required to come up with six business questions relevant to the task, 
The data used in this project comprises of 21 columns and thousands of rows. The columns contained attributes as listed below:
#
Row ID, Order ID, Order date, Ship Date, Ship Mode, Customer ID, Customer Name, Segment, Country, City, State, Postal Code, Region, Product ID, Category, Sub-Category, Product Name, Sales, Quantity, Discount and Profit. See the raw data below.
-----------------
# Data Preparation and Processing
The first crucial step in every data analysis project is to duplicate any raw data given so as to preserve the original data and work with the duplicate. Then the next crucial step was to go through the data to get familiar with it, check the data types of each column, etc. From here, I was able to draft the relevant business questions to be answered in this project. After this, I checked for any blank spaces but found none. I went further to format the date columns as I noticed they were formatted as text and not as dates. I did this by selecting both columns then using the Text-to-Column feature, then unchecked Text and checked Dates. 
Because one of the business questions will require quarterly analysis, I then created two new columns for this purpose. Using the formula ="Q"&ROUNDUP(MONTH(C2)/3,0)&"-"&YEAR(C2) and ="Q"&ROUNDUP(MONTH(E2)/3,0)&"-"&YEAR(E2) I created the two columns "Order year and quarter" and "Ship year and quarter" from their respective dates columns. I also high;ighted the entire dataset to remove duplicates but found none to remove. See a glimpse of the processed data below.
![image](https://github.com/dianeanalyst/Excel-Project-on-US-Superstore-Data/assets/120665115/9b1a41ed-263d-4f1b-b2f0-705fbda9b67b)

The business questions I came up with are listed as follows
1. What is the sales performance across all the states?
2. In what year and quarter was the most and least sales made?
3. Which ship mode is the most frequently used in the last two years?
4. What states and regions processed the highest order?
5. Show the profit summary by category
6. Which segment sold the least quantity in all four yerars?
To answer these questions, I created pivot tables for each of them. These are contained in the figures below.

![image](https://github.com/dianeanalyst/Excel-Project-on-US-Superstore-Data/assets/120665115/54099239-373f-4330-b887-feaa6b778510)
The sales performance was filtered to show the top 10 perfoming states.

![image](https://github.com/dianeanalyst/Excel-Project-on-US-Superstore-Data/assets/120665115/6555f4f9-2ce1-4c78-8f15-95a5f62dde64)

![image](https://github.com/dianeanalyst/Excel-Project-on-US-Superstore-Data/assets/120665115/b28098d9-9807-436b-9187-d1474d3f539e)

![image](https://github.com/dianeanalyst/Excel-Project-on-US-Superstore-Data/assets/120665115/dc22d0a5-9c5a-4e24-8d07-4bbd03099a6a)





