# doublenines

This repository contains a mini coop booking app, designed as a test for the Doublenine company. It features a user-friendly interface, allowing users to easily book coops and manage their bookings.

## Conceptual Questions

1. Why will you choose to design an API with REST or GraphQL, and why?

2. When will you choose relational storage vs. non-relational storage? How many types of non-relational storage do you know?

3. When and why will you use Redux?

4. What steps would you follow to improve the performance of a slow endpoint?

5. What steps would you follow to improve the performance of a SQL query? (or a non-sql query)

## Coding Exercise

Mini COOP Booking

This exercise aims to show us your code style and experience. We will focus on how you resolve the problem, how you name things, how you define the API, how you test, how you document, etc.

Create a ReactJS+BE application from scratch with a simple form + a REST or GraphQL backend to CRUD vehicle reservations.

You can assume a reservation has: User Id, Vehicle Id, From, To, etc. (feel free to add more if you want)

No need to store the data; just in-memory storage will be fine.

You need to deliver a working project (e.g. “npm install && npm start” to run it)

You need to deliver both UTs and ITs (e.g. “npm test” to run the unit tests and “npm run it” to run the ITs).

Feel free to use any libraries that you want (we love libraries vs. doing the code ourselves)

Linting or similar is also appreciated (feel free to start from a template if you want)

Deliver the exercise as a GitHub public repo (easier to share).

## Database Exercise

1. Assuming the vehicle data that you proposed for the coding exercise. Write a SQL to get the total number of daily reservations for a specific date range.

2. Assuming the vehicle data that you proposed for the coding exercise. Write a MongoDB query to get the total number of daily reservations for a specific date range?

## Conceptual Questions - Answers

1. I would choose to design an API with REST or GraphQL depending on the needs of the application. REST is a well-established and widely-used approach for designing web APIs, and is often the go-to choice for many developers. It is well-suited for creating APIs that have a lot of resources and endpoints, and is great for creating simple, intuitive APIs that are easy to understand and use.

GraphQL, on the other hand, is a newer approach to designing APIs that is becoming increasingly popular. GraphQL is great for creating APIs that are more flexible and powerful than those designed with REST, and is especially useful when creating APIs that need to handle complex queries and operations.

2. Relational storage is best suited for data that is structured and requires complex queries, transactions, and joins. Non-relational storage is better suited for data that is unstructured, has no complex relationships, and requires fast read/write access.

Below I will list the databases from the one I know best to the one I know least:

Relationals: MySQL, MariaDB, PostgreSQL, Oracle Database
Non-relationals: MongoDB, Firebase

3. Redux is especially helpful for applications with complex states that require frequent updates, such as e-commerce or real-time applications. Redux can also help improve the performance of an application by reducing the amount of code required to manage the state.

4. Stepts to improve an endpoint
   4.1. Identify the source of the slowness: Start by identifying the source of the slowness. Is it due to an issue with the application code, or is it a network or server issue?
   4.2. Analyze the application code: Once you know the source of the problem, you can analyze the application code to see if there are any bottlenecks or inefficient queries that could be causing the slow performance.
   4.3. Monitor the system: Use a performance monitoring tool to track the performance of the endpoint over time4. and identify any trends or changes that could be impacting performance.
   4.4. Optimize the code and database: Optimize the code and database to improve performance. This could include making changes to the code, such as reducing the number of database queries, or making changes to the database, such as adding indexes or partitions.
   4.5. Test the changes: Test the changes to ensure that the performance has improved.
   4.6. Monitor the system again: Monitor the system again to ensure that the changes have had the desired effect.

5. Improving Databases
   5.1 Relational Databases
   5.1.1 Analyze the query to identify potential areas of improvement. This can include examining the query structure, the data types used, and the number of joins and subqueries.
   5.1.2 Optimize the query by simplifying the query structure and ensuring that all necessary indexes are in place.
   5.1.3 Consider using query hints to improve performance.
   5.1.4 Test the query to ensure that it is performing as desired.
   5.1.5 Monitor the query performance over time to ensure that it remains optimized.
   5.1.6 Consider using stored procedures or other methods to further improve performance.

   5.2 Non-Relational Databases
   5.2.1. Check the query structure and syntax to ensure it is optimized for the No-SQL database.
   5.2.2. Ensure that the query is using the appropriate indexing and data structures for the No-SQL database.
   5.2.3. Check the query for any unnecessary complexity that can be simplified.
   5.2.4. Consider using caching to store query results and reduce the amount of data being queried.
   5.2.5. Profile the query to identify any bottlenecks and optimize the query accordingly.
   5.2.6. Use query optimization techniques such as query plan analysis and query optimization hints.
   5.2.7. Consider using No-SQL specific features such as sharding and replication to improve performance.
   5.2.8. Monitor query performance regularly to identify any changes in query performance.
