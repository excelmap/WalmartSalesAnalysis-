# WalmartSalesAnalysis
**ABOUT THE PROJECT **
The main aim of the project is to analyze the sales of Walmart  and behavior of customer. The aim of the project is also to study how sales strategies can be improved and optimized. The dataset was obtained from the Kaggle Walmart Sales Forecasting Competition.
PURPOSE OF THE PROJECT
The main aim of the project is to gain insight sales of Walmart  as well as to understand the different factors that affect the sales of Walmart’s.

**ABOUT DATA** 
The data was obtained from the Kaggle Walmart Sales Forecasting Competition. This dataset contains sales transaction from three different branches of Walmart, respectively located in Mandalay, Yangon and Naypyitaw. The data contains 17 columns and 1000 rows. The data is  run through a SQL database for further analysis by creating data, manipulating and cleaning the data. 
**ANALYSIS**
1.	PRODUCT ANALYSIS
2.	SALES ANALYSIS
3.	CUSTOMER ANALYSIS 
TO UNDERSTAND THE SCENARIO FOLLOWING QUESTIONS WERE ANSWER BY RUNING IN SQL DATABASE: 
Generic Question
1.	How many unique cities does the data have?
2.	In which city is each branch?

Product
1.	How many unique product lines does the data have?
2.	What is the most common payment method?
3.	What is the most selling product line?
4.	What is the total revenue by month?
5.	What month had the largest COGS?
6.	What product line had the largest revenue?
7.	What is the city with the largest revenue?
8.	What product line had the largest VAT?
9.	Fetch each product line and add a column to those product line showing "Good", "Bad". Good if its greater than average sales
10.	Which branch sold more products than average product sold?
11.	What is the most common product line by gender?
12.	What is the average rating of each product line?
SALES 
1.	Number of Sales made in each time of the day.
2.	Which customers brings the most revenue?
3.	Which city has the largest tax %?
4.	Which customers type pays the most in VAT?
CUSTOMER
1.	How many unique customer types does the data have?
2.	How many unique payment methods does the data have?
3.	What is the most common customer type?
4.	Which customer type buys the most?
5.	What is the gender of most of the customers?
6.	What is the gender distribution per branch?
7.	Which time of the day do customers give most ratings?
8.	Which time of the day do customers give most ratings per branch?
9.	Which day fo the week has the best avg ratings?
10.	Which day of the week has the best average ratings per branch?
Revenue And Profit Calculations
$ COGS = unitsPrice * quantity $
$ VAT = 5% * COGS $
$ total(gross_sales) = VAT + COGS $
$ grossProfit(grossIncome) = total(gross_sales) - COGS $
Gross Margin is gross profit expressed in percentage of the total(gross profit/revenue)
$ \text{Gross Margin} = \frac{\text{gross income}}{\text{total revenue}} $
Example with the first row in our DB:
Data given:
•	$ \text{Unite Price} = 45.79 $
•	$ \text{Quantity} = 7 $
$ COGS = 45.79 * 7 = 320.53 $
$ \text{VAT} = 5% * COGS\= 5% 320.53 = 16.0265 $
$ total = VAT + COGS\= 16.0265 + 320.53 = 336.5565
$ \text{Gross Margin Percentage} = \frac{\text{gross income}}{\text{total revenue}}\=\frac{16.0265}{336.5565} = 0.047619\\approx 4.7619% $
