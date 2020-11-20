# **Investigating Sakila DVD Rental Database Project**
Udacity Programming for Data Science Nanodegree Program - Project I

## 12th Oct'20

## **Overview**
In this project, I used SQL to explore a database related to movie rental the Sakila DVD Rental database. The Sakila Database holds information about a company that rents movie DVDs. For this project, I queryed the database to gain an understanding of the customer base, such as what the patterns in movie watching are across different customer groups, how they compare on payment earnings, and how the stores compare in their performance.

## **DVD Rental ERD**
(Note: One quirk you may notice as you explore this "fake" database is that the rental dates are all from 2005 and 2006, while the payment dates are all from 2007. Don't worry about this.)

![alt text](https://github.com/beroXD/PDSND-P1-Investigate-Sakila-DVD-Rental-Database/blob/main/dvd-rental-erd-2.png)

## **What Software Do I Need?**
To complete this project, the following software requirements apply:
### PostgreSQL:
PostgreSQL is an object-relational database management system. Object-relational databases use a hybrid approach to databases. 
In object databases, information is stored as objects, much like object-oriented programming.
In relational databases, information is stored in tables with relationships between tables defined by primary and foreign keys.
Importantly, PostgreSQL allows the use of advanced functions (such as Window Functions), and even development and use of custom functions written in different programming languages. Here is a [link](https://en.wikipedia.org/wiki/Object-relational_database) to better understand what is meant by an object-relational database, and how it differs from a relational database.

* [PostgreSQL for Windows](http://www.postgresqltutorial.com/install-postgresql/)
* [Sakila Database](http://www.postgresqltutorial.com/postgresql-sample-database/)

## **Question Answered and Visualized**
* Question 1:
   - We want to understand more about the movies that families are watching. The following categories are considered family movies: Animation, Children, Classics, Comedy, Family and Music. Create a query that lists each movie, the film category it is classified in, and the number of times it has been rented out.
   
* Question 2:
    - Now we need to know how the length of rental duration of these family-friendly movies compares to the duration that all movies are rented for. Can you provide a table with the movie titles and divide them into 4 levels (first_quarter, second_quarter, third_quarter, and final_quarter) based on the quartiles (25%, 50%, 75%) of the rental duration for movies across all categories? Make sure to also indicate the category that these family-friendly movies fall into.
    
* Question 3:
    - We want to find out how the two stores compare in their count of rental orders during every month for all the years we have data for. Write a query that returns the store ID for the store, the year and month and the number of rental orders each store has fulfilled for that month. Your table should include a column for each of the following: year, month, store ID and count of rental orders fulfilled during that month.
    
* Question 4:
    - We would like to know who were our top 10 paying customers, how many payments they made on a monthly basis during second quarter of 2007. Can you write a query to capture the customer name, month and year of payment, and total payment amount for each month by these top 10 paying customers?
    
## **Credits**
* Derek steer (Udacity mentor - CEO at Mode)
    - [https://www.linkedin.com/in/dereksteer/](https://www.linkedin.com/in/dereksteer/)

* Two such highly recommended SQL guides :
    - [SQL Style Guide](https://www.sqlstyle.guide/)
    - [SQL Formatter](https://sql-format.com/)
    
