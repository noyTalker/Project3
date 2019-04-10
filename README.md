# Project3
Coupon System prat 3 - core &amp; server side (Spring Boot project)

In this part of the project I united the first and second part to one Spring Boot project.

The dependencies in this project are JPA, Web and MySQL.

This project is a coupon management system that allows companies to create coupons, customer to purchase coupons, incomes documentation and admin to manages the companies and customers.

This project defines a database to store and retrieve information about customers, companies ,coupons and incomes.
Above the database there is an insulating layer that allowes convenient work from JAVA to SQL for DB operations.

In addition there are basic infrastructure services such as ConnectionPool and Daily Thread Which maintain the system and clean expired coupons.

There are three entry points in the system for each of its customers (adamin, company or customer) who will login to execute a connect.

Each of the customers (admin, company and customer) is exposed as a service.
There are three network services that will enable integration using REST with the system.

There is a ApplicationUnitTest in which you can see that the system works.
But first you have to pick up the MySQL Server for the DB, and check the username and password of your MySQL in the property file.



