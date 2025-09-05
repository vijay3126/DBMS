A university library needed a robust system to manage its growing collection of books, student records, and borrowing transactions using normal file system. The existing file system could not handle the increasing demand. Convert this file system to database and use appropriate entities and attributes.  
Differentiate an Entity set and Relationship set. List and explain the symbols used to draw ER Diagram
Design the conceptual ER diagram for the University Course Registration System based. on the following requirements:
i)Manage student details, course information, instructors, departments, and enrolment data.
ii)Define entities, attributes, and relationships between them.
iii)Include relationships such as student enrolment in courses, course-instructor associations, and department-course affiliations.
A retail company, "Retail-Mart," initially used file-based storage to manage its customer, product, and transaction data. Over a period, as the business expanded, they encountered issues with the scalability, data redundancy, and leads to inconsistency. Identify the solution to improve scalability and consistency.
Differentiate between strong Entity set and weak Entity set with examples?
The Hospital Management System (HMS) helps streamline hospital operations by managing patients, doctors, appointments, medical records, and hospital resources.
Design the conceptual ER diagram for the HMS.
E-commerce platforms have revolutionized the way people shop. To enhance customer experience and streamline operations, an Online Shopping System is required to manage users, products, orders, and reviews efficiently. Design ER data model for Online Shopping System. 
Explain about different types of database users? What are the responsibilities of a DBA?
Define data model? Explain the different types of data models with examples?


Design a database schema for the course registration system based on the following requirements. Clearly define the tables, fields, and integrity constraints like Primary Key, Not Null, Unique, Foreign Key, and Check constraints.
i)Student(StudentID,Name,Email,EnrollmentYear)
ii)Course(CourseID, CourseName, Credits)
iii)Registration(RegistrationID,StudentID,CourseID,RegistrationDate)
Solve the following queries using relational algebra, tuple relational calculus, domain relational calculus, consider the following tables.
Products(ProductID (PK), ProductName (Not Null), Price(Check constraint values>0), category).
Customers(CustomerID: (PK),Name(Not Null), Email(Unique constraint to avoid duplication), Address).
Orders(OrderID (PK), CustomerID (FK), ProductID (FK), Quantity (Check constraint to ensure values > 0), OrderDate: (Not Null)).
i.Find customers who purchased products costing more than Rs. 1000.
ii.Retrieve product names and quantities ordered by a specific customer named "Alice."  
iii.Retrieve all orders placed for products in the "Clothing" category.
iv.List the names of customers who ordered at least 5 units of any product. 
Implement the following database schema and refine with the appropriate integrity constraints. How these constraints contribute in maintaining data consistency and avoid anomalies in the organization’s database. 
i)Employee(EmployeeID,Name,Email, DepartmentID, Salary)
ii)Department(DepartmentID,DeptName, ManagerID).
Design a relational database schema for an Online Shopping System based on the following entities: Users, Products, Orders, OrderDetails, and Reviews. Identify primary keys and foreign keys, and enforce integrity constraints.
Explain the operations in relational algebra with examples.
Design the ER data model for Hospital Management System (HMS) and convert into relational database schema based on the following entities: Patients, Doctors, Appointments, Medical Records, and Resources. 
Define an integrity constraint? Discuss the different types of integrity constraints over relations?
Explain about outer join operation in relational algebra.
Differentiate between Tuple Relational Calculus and Domain Relational calculus.



The following database is refined upto second normal form. Upgrade this schema without any transitive dependency. 
Book (BookID, BookTitle, AuthorID, PublisherID, PublishDate, AuthorCountry).
Author (AuthorID, AuthorName, AuthorCountry)
Publisher (PublisherID, PublisherName, PublisherLocation).
Transaction (TransactionID, BookID, BorrowerID, BorrowDate, ReturnDate).
The below order table contains information about customers, restaurants, and dishes ordered, all in one table only. This leads to potential redundancy and dependency issues.  Please refine this schema every non key attribute depends on key attribute
Ordertable (OrderID (Primary Key), CustomerName, CustomerPhone, RestaurantName, DishName;DishPrice,Quantity;OrderDate,DeliveryDate).
The following database schema is a Library Management System (LMS) that stores information about books, authors, and their borrowings: this schema not following any normalization process. Refine this schema upto 2nd normal form.
Schema:
Book ( BookID (Primary Key),BookTitle, AuthorName, AuthorCountry, BorrowerID, BorrowerName, BorrowDate)
Consider the following relations 
Sailors (sid, sname, rating, age) 
Boats (bid, bname, color) 
Reserves (sid, bid, day) 
Write the statements in SQL for the following questions. 
i) Find the names of sailors who have reserved a Red boat. 
ii) Find the names of sailors who have reserved at least one boat. 
iii) Find the names of sailors who have reserved a Red and a Green boat. iv) Find the names of sailors who have reserved a Red or a White boat. 
v) Find the names of sailors who have reserved all boats.
Create an user interface to store and retrieve the data using JDBC/ODBC to insert two records into the employee database and retrieve the details and display them on the console.
Explain the aggregate operators in SQL with examples.
What is normalization? Explain 1NF ,2NF, 3NF and BCNF Normal forms with example
Define decomposition? Explain the properties of decomposition? 
Create a trigger that calculates the total marks, percentage, grade, and result of a student after inserting data into the Student table. The trigger should be fired AFTER INSERT and should populate the Result table.
 Tables:
 Student(rollno, sname, marks1, marks2, marks3)
 Result(rollno, total_marks, average, grade, result)


A bank operates a transaction system where multiple customers perform operations like deposits, withdrawals, and balance checks concurrently. To ensure data consistency and prevent anomalies, the system uses a Timestamp-Based Concurrency Control Protocol. Analyze the given scenario, identify concurrency issues, and propose solutions based on timestamp ordering.
Lock-based protocols are critical in Database Management Systems (DBMS) to handle concurrency issues when multiple transactions execute simultaneously. In what ways do lock-based concurrency control protocols contribute to enforcing the ACID properties and preserving database consistency and integrity?
A hotel booking system handles reservations, cancellations, and room availability enquiries. Guests and hotel staff perform multiple concurrent transactions daily. System crashes or failures occasionally disrupt operations. Recover the data using log based protocols without affecting the data integrity. 
An e-commerce platform handles customer orders, inventory updates, and payment processing. A single transaction involves several interconnected steps that must be executed atomically, evaluate the database without any data inconsistency.
Explain the ACID Properties of transaction.
A university library system allows students to borrow, return, and search for books. Multiple users interact with the system simultaneously, leading to concurrency challenges. Analyze and solve the concurrency-related issues.
Explain about Validation-Based Protocol
What is log file? Explain the log based recovery schemes. 



Develop a B+ Tree-based Student Record Management System to efficiently store, manage, and query student data in a database. The system should be optimized to handle large datasets and support advanced queries, such as retrieving students within a specified range of marks. Your solution should leverage B+ tree principles to enhance database performance.
Construct a B+ tree to insert the following key elements (order of the tree is 4) 1,4,7,10,17,21,31,25,19,20,28,42 
Design and develop Inventory Management System that uses B+ tree indexing to efficiently store, search, and manage product information. The system should allow users to perform various inventory operations, including adding, updating, and deleting products, with a focus on optimizing searches for attributes like product ID, price, and stock quantity.
Design and develop a Hotel Room Booking System that utilizes indexed data structures in the database to efficiently manage and retrieve room and booking information. The system should allow users to perform operations such as adding and managing room details, booking rooms, checking room availability, and searching for rooms based on attributes like type, availability, and price. Indexing should be applied appropriately on key fields such as Room ID, Room Type, and Price to optimize search performance and ensure faster access during booking and reporting operations.
Design a database to manage flight bookings and passenger records using file organization, with Flight Number as the primary key index and a secondary index on the Destination and Departure Date attributes
List and explain various file organization methods 
Develop a database for an Online Examination Result System using hash-based indexing to add and manage student details, search results by studentID or rollnumber, and generate performance reports by subject or semester.
Explain Indexed Sequential Access Method.
Explain about Extendable Hashing and linear hashing with examples 
