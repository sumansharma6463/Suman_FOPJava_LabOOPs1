#Summary:
This e-commerce database is designed to manage suppliers, customers, products, orders, and ratings.
The provided queries offer insights into customer behavior, supplier performance, and product categories. The sample data allows for testing and analysis.
Additionally, a stored procedure is included to calculate average ratings for suppliers.

#Database Schema:
##ECOM Database:
• A container for the entire e-commerce database.

Supplier Table:
• Stores information about suppliers, including ID, name, city, and phone number.
Customer Table:
• Contains details about customers, such as ID, name, phone number, city, and gender.
Category Table:
• Holds information about product categories, including ID and name.
Product Table:
• Stores product details like ID, name, description, and the category it belongs to.
Supplier Pricing Table:
• Manages pricing information from suppliers for various products.
Order Table:
• Records order details, such as order ID, amount, date, customer ID, and pricing ID.
Rating Table:
• Captures ratings given by customers for their orders.

##Inserted Data:
• Suppliers, Customers, Categories, Products:
Populated with sample data to simulate a diverse set of entities.
• Supplier Pricings:
Reflects the pricing agreements between suppliers and products.
• Orders:
Includes order information with associated customers and products.
• Ratings:
Represents ratings given by customers for specific orders.

##Queries:
Query 4:
• Identifies the gender distribution of customers who made orders exceeding $3000.

Query 5:
• Retrieves details of orders made by a specific customer (Customer ID = 2), including product names.

Query 6:
• Lists suppliers with multiple pricings for different products.

Query 7:
• Presents the lowest-priced product for each category.

Query 8:
• Fetches order details for products ordered after a specific date (2021-10-05).

Query 9:
• Lists customers whose names start with 'A' or contain 'A'.

Query 10:
• Defines a stored procedure (SP) to calculate average ratings for suppliers and categorize their service.
