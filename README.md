# E-Commerce_Sales_Analysis_Project

## Dataset
The dataset contains a transaction table from an E-commerce from January 2023 to May 2023. Before processing the data in Jupyter Notebook
using Python, I cleared some rows and columns above the table in excel. The dataset contains a shape of 477 rows and 8 columns and has no missing values in it.

## Tasks
- Find the Average Transaction Per User Value and Median Transaction Per User Value,
- Analyzing Peak Shopping Hours,
- Product Performance Analysis,
- User Behavior Analysis,
- Sales Analysis.

## Analysis

### Finding the Average Transaction Per User Value and Median Transaction Per User Value
- Average Transaction Per User Value means the mean value of transactions per user. This is done by summing all the transaction values for each user. And dividing by the total number of transactions made by the user.
- Median Transaction Per User Value means the the median value of all transactions per user. This is done by sorting all the transaction values for a user. And finding the middle value. If there's an even number of transactions, the median is the average of the two middle numbers.

![image](https://github.com/CountingCrows/E-Commerce_Sales_Analysis_Project/assets/85608120/afb9794e-7837-44ee-ada5-4634cfccc6e8)

### Analyszing Peak Shopping Hours
- We need to make a new 'date' and 'time' column,
- Making a Transactions by Hour plot,
- Making a Sales by Hour plot.

![image](https://github.com/CountingCrows/E-Commerce_Sales_Analysis_Project/assets/85608120/66d3a955-bd29-4d37-8d0d-29f77e8b61f2)

We then split the ‘time’ column to seperate ‘hours’ and ‘minute’. This will help us analyze the Peak Shopping Hours more detailed.

![image](https://github.com/CountingCrows/E-Commerce_Sales_Analysis_Project/assets/85608120/1d7db5cc-2d59-427b-87b2-d082cdd2f76d)

![image](https://github.com/CountingCrows/E-Commerce_Sales_Analysis_Project/assets/85608120/97aeae74-fd17-40c9-bd34-7ef8a7baeb84)

From the Peak Hour Analysis, we found that there were 4 peak hours of number of transactions over 20, and 4 times were number of transactions were under 16 transactions. We can suggest to the management to find why number of transactions around 06.00 to 12.00 are very fluctuate and why the number of transactions from 13.00 to midnight are decreasing.

### Sales by Hour

![image](https://github.com/CountingCrows/E-Commerce_Sales_Analysis_Project/assets/85608120/f142f3b8-e421-43ed-8e5a-cf1d8ecff9ce)

From the Sales by Hour bar chart, we can find the peak hours that generated the most profit is at 13.00 and from 21.00 to 23.00 combined. We can suggest to run ads from 11.00 and above 18.00.

### Product Performance Analysis 
We do a product performance analysis based on the name of the product from column 'SKU' and its total price from 'total harga'.

![image](https://github.com/CountingCrows/E-Commerce_Sales_Analysis_Project/assets/85608120/7ec9dc30-cf82-4cf2-9769-83f7fd596dc0)

![image](https://github.com/CountingCrows/E-Commerce_Sales_Analysis_Project/assets/85608120/e200a5c9-2401-4f99-8e66-9b8733fcd010)

From the top 5 products by total sales value, we can suggest to the management to push ads for those products, and make sure that the stores inventory is always stocked for these products.

### User Behavior Analysis
For the User Behavior Analysis, we try to find:
  - Active Users by Hour,
  - New vs Repeat Customers by Hour.

![image](https://github.com/CountingCrows/E-Commerce_Sales_Analysis_Project/assets/85608120/f8e352eb-495a-4d5c-8836-4c4e4fb3568c)

#### User Behavior Analysis - Active Users by Hour

![image](https://github.com/CountingCrows/E-Commerce_Sales_Analysis_Project/assets/85608120/ee0e7a97-4708-47b3-89e2-26d29f338532)

We can say that with the most Active Users by Hour at 00.00 to 01.00, and at certain hours such as 07.00, 09.00 and 11.00, we can suggest the management to make marketing ads for active users during the time.

#### User Behavior Analysis - New vs Repeat Customers by Hour

![image](https://github.com/CountingCrows/E-Commerce_Sales_Analysis_Project/assets/85608120/9d771c0d-5589-4a77-ab0c-90d7282c5549)

![image](https://github.com/CountingCrows/E-Commerce_Sales_Analysis_Project/assets/85608120/03b7cffd-69b5-437c-8839-ff403699b98b)

From this plot, we can conclude that more than 15 new customers are coming from 07.00 and 11.00 and there's a good pattern of repeating customers from 00.00 to 06.00, 11.00 to 17.00 and 21.00 to 23.00. We suggest the management to continue obtaining new customers by giving them marketing ads and maybe also CRM.

### Sales Analysis
Tasks:
  - Sales Distribution,
  - Sales by Category,
  - Total Sales Over Time.

#### Sales Analysis - Sales Distribution

![image](https://github.com/CountingCrows/E-Commerce_Sales_Analysis_Project/assets/85608120/1f515e2e-40d2-4556-9a85-5d3e5773a001)

From the sales distribution plot, we can see that around 100 transactions generated sales to around 20 million. Where under 5 number of transactions generated sales around 100 million.

#### Sales Analysis - Sales by Category

![image](https://github.com/CountingCrows/E-Commerce_Sales_Analysis_Project/assets/85608120/c30e929f-b3f7-4706-a23b-7a56e18d973b)

![image](https://github.com/CountingCrows/E-Commerce_Sales_Analysis_Project/assets/85608120/5755f37d-4062-4f1d-9930-f86144456af5)

![image](https://github.com/CountingCrows/E-Commerce_Sales_Analysis_Project/assets/85608120/4b7c0734-7e7e-4fbd-8ed0-904ee3321ebb)

Gadget & Aksesoris is the number 1 product category that generated the most total sales value for around 950 million, followed by Olahraga and Dekorasi Rumah. While the bottom three categories are Bahan Makanan, Kesehatan, and Aksesoris Rumah.

#### Sales Analysis - Monthly Sales

![image](https://github.com/CountingCrows/E-Commerce_Sales_Analysis_Project/assets/85608120/b45eff76-76f8-463d-8ead-03926df3af47)

![image](https://github.com/CountingCrows/E-Commerce_Sales_Analysis_Project/assets/85608120/500989c1-cd09-4fb2-867c-e62b0d21cb49)

From the monthly sales over time plot, we gain insights that March and May generated the biggest total sales among the other months. This is maybe due to the some several events during the year.

### Conclusion
- March & May generated the most total sales among the other months. We  can suggest the management to spend more money on ads or marketing events to gain bigger revenue in these months.
- Gadget & Aksesoris is the top category with the most sales. We can suggest the management to push ads in this category and make sure the inventory is always on stock.
- With patterns of customer retention and new customers, we can run the ads or marketing events based on it’s peak hours.
