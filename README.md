**Online Bookstore E-commerce SQL Project**
This is a simulation-based database project designed for practicing SQL queries using the MS SQL Sever on sqliteonline.com. It simulates a simplified e-commerce platform for an online bookstore.
⚠️ Note: All data structures and queries are fictional and created for learning purposes only. This is not a real application.

**Platform & Tools**
SQL Dialect: MS SQL
Platform: sqliteonline.com
No external libraries or front-end code included

**Project Components**
Schema design with key business entities
Sample data insertion
Query practice for business insights and logic validation

**Main Tables & Relationships**
(Brands) 
BrandID (PK) 
BrandName 
 
(Products)
ProductID (PK) 
BrandID (FK) 
SellerID (FK) 
ProductName  
QuantityInStock 
UnitPrice 
Origin  
Description 
Image 

(Categories) 
CategoryID (PK) 
CategoryName 

(ProductsCategories) 
ProductID (PK) 
CategoryID (PK) 

(Accounts) 
AccountID (PK) 
Username 
FullName 
Password 
Email 
Phone 
Address 
AccountType (Consumer/Seller)

(Consumers) 
ConsumerID (PK) 
AccountID (FK)

(Sellers) 
SellerID (PK) 
AccountID (FK)

(Orders) 
OrderID (PK) 
ConsumerID (FK) 
FullName 
OrderDate 
ShippedDate 
Status (Processing/Shipping/Delivered/Cancelled)

(OrderDetails) 
OrderID (PK) 
ProductID (PK) 
Quantity 
Discount

(Ratings) 
RatingID (PK) 
ConsumerID (FK) 
ProductID (FK) 
Rating 
Review 
