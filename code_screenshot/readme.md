# Here, the Sales dataset is analyzed using SQL. Below are the steps followed to analyze insights from the data: 

- A new database named "online_sales" has been created and then all records from the "online_retail" table are retreived.

- Then missing values and duplicates are handled from the dataset.Checks for missing values in critical columns
(e.g InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country) and
Identification of the duplicate rows is done.

- Customer Analysis is done by calculating metrics such as the number of invoices per customer, number of unique
customers in each country, average quantity of items purchased per invoice by each customer, and identifies the 
top 10 customers by total spending.

- Product Analysis identifies top-selling products by quantity and revenue. Calculations for the average unit price
of items sold is done here.


- Invoice Analysis examines the distribution of invoice quantities. It analyzes trends in the number of invoices over
time and calculates the average invoice value change over time.

- Geographical Analysis identifies the country with the highest total revenue. It examines the distribution of customers
across different countries. From here we can investigate the correlation between the number of invoices and country.

- Time Analysis is done to identify the busiest days or months in terms of sales. Additionally, it analyzes trends in
sales over different years.

- With the help of Customer Behavior Analysis, we can explore patterns in types of products purchased by customers 
from different countries. We can analyze the variation of quantity purchased with the customer's country and identify
seasonal trends in customer purchasing behavior.

- Price Analysis checks the distribution of unit prices for items.

  
#### Each query in the SQL code performs specific analyses to gain insights into different aspects of the online retail dataset. This comprehensive approach enables stakeholders to understand customer behavior, product performance, sales trends, geographical patterns, and pricing dynamics, among other factors, and make informed business decisions based on the findings.







