# Sales Performance Analysis Using SQL

## Introduction
Northwind Traders is a fictitious company that specializes in importing and exporting specialty foods from around the world. In addition to managing orders, products, customers, and suppliers, the company handles several other aspects of small business operations.


## Scenario
As a method of increasing future sales, the company has decided to give employees bonuses for exemplary performance in sales. As the data analyst on the team I have been tasked with finding which Northwind Traders employees should get bonuses for their sales performance. 

## Goal
Bonuses will be awarded to those employees who are responsible for the five highest order amounts. This analysis aims to examine the Northwind Traders database, determine the tables needed for answering the business task, and analyzing the data in order to provide an answer to the stakeholders. 

## Dataset
The Northwind database is a sample database originally created and used by Microsoft to demonstrate the features of some of its products. The database schema is presented below.

After examining the database I have determined that I will need to query data from the Employees table, Orders table, OrderDetails table, and Products table in order to solve the business task.

<img src="https://docs.yugabyte.com/images/sample-data/northwind/northwind-er-diagram.png"  width="70%" height="20%">

Skills:
A few of the SQL skills that will be utilized during this project are:

* <span style="font-family:Open Sans; font-size:15px;">ORDER BY</span>
* <span style="font-family:Open Sans; font-size:15px;">GROUP BY</span>
* <span style="font-family:Open Sans; font-size:15px;">JOINS</span>
* <span style="font-family:Open Sans; font-size:15px;">ALIASING</span>
* <span style="font-family:Open Sans; font-size:15px;">Common Table Expressions</span>
* <span style="font-family:Open Sans; font-size:15px;">Subquries</span>
* <span style="font-family:Open Sans; font-size:15px;">Window Functions</span>


## Approach
To achieve the project objective of finding which Northwind Traders employees should get bonuses for their sales performance, I followed these steps:

1. Joining the tables
2. Finding the sales amount for each order item
3. Finding the sales amount per order
4. Finding the distinct employees responsible for the highest individual orders
   

## Conclusion
It appears the five employees who will recieve a bonus for their part in handeling the top orders are

1. Andrew Fuller
2. Robert King
3. Nancy Davolio
3. Steven Buchanan
5. Margaret Peacock
