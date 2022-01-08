# Sales Demand Forecasting - WalMart Company
Every Departmental store chain like Walmart wants to predict the store sales in the nearby future so that inventory planning can be done. Along with that, sales prediction helps to increase/decrease store staff based on the rush (More sales can mean more customers are coming to the stores). Also, it is always a good idea to do sales and revenue forecasting to better understand the company's cash-flows and overall growth. For inventory planning, you also need to know what products (or category of products aka department) will be utilised more. Under-stock some products and your sales are hit. Over-stock items like perishables and you run into losses if the product expires. That's why the sales prediction is done at a combination of store and department level (and sometimes even at product level for high-selling products).
Walmart tries to find the impact of holidays on the sales of stores. For which it has included four holidays weeks into the dataset which are Christmas, Thanksgiving, Super bowl, Labor day. Walmart is one of the largest retailers in the world and it is very important for them to have accurate forecasts for their sales in various departments. Since there can be many factors that can affect the sales for every department, it becomes imperative that we identify the key factors that play a part in driving the sales and use them to develop a model that can help in forecasting the sales with some accuracy.
Most Importantly how inclusion of holidays in a week soar the sales in store?  Why does this problem needs To be Solved? Holidays can create a huge impact on sales. So, if there is a good prediction on Sales then Walmart can Calculate how much product to order during Holiday time. It will help in predicting which products need to be purchased during the holiday time. As customers planning to buy something expect the products to be available immediately. And through prediction they can figure out which product will be required at what time . Thus soar the trust of Customers on Walmart. This problem can also solve the issue of Marketing Campaigns. Forecasting is often used to adjust ads and marketing campaigns and can influence the number of sales. Walmart runs several markdown events throughout the year. And these markdown events precede the prominent holidays. So, to solve the issue Walmart can organize such events more efficiently.
## Objective 
In this project, you aim to forecast the sales for Walmart using various Machine Learning Algorithms to analyze if sales are impacted by time based factors and space based factors  and analytical insights.
## Within this file you will find the following fields:
●	Store - the store number
●	Dept - the department number
●	Date - the week
●	Weekly_Sales -  sales for the given department in the given store
●	IsHoliday - whether the week is a special holiday week
●	Store - the store number
●	Date - the week
●	Temperature - average temperature in the region
●	Fuel_Price - cost of fuel in the region
●	MarkDown1-5 - anonymized data related to promotional markdowns that Walmart is running. MarkDown data is only available after Nov 2011, and is not available for all stores all the time. Any missing value is marked with an NA.
●	CPI - the consumer price index
●	Unemployment - the unemployment rate
●	IsHoliday - whether the week is a special holiday week
## For convenience, the four holidays fall within the following weeks in the dataset (not all holidays are in the data):
●	Super Bowl: 12-Feb-10, 11-Feb-11, 10-Feb-12, 8-Feb-13
●	Labor Day: 10-Sep-10, 9-Sep-11, 7-Sep-12, 6-Sep-13
●	Thanksgiving: 26-Nov-10, 25-Nov-11, 23-Nov-12, 29-Nov-13
●	Christmas: 31-Dec-10, 30-Dec-11, 28-Dec-12, 27-Dec-13
