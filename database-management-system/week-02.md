# NPTEL Database Management System Week 02 Assignment Answers

Are you looking for NPTEL Database Management System Week 02 Assignment Answers? This repository will help you find your answers and solutions for Week 02 of the Database Management System course. We provide detailed solutions to help you complete your assignments efficiently.

![Nptel Database Management System Assignment 2 Answers](https://miro.medium.com/v2/resize:fit:875/1*nw-gOvlsQ1d6ph1xPn-prQ.jpeg)

## _Nptel Database Management System Assignment 2 Answers( Jan-Apr 2026)_

Que1. Consider two relations EmployeeDept and EmployeeProject as follows.\
An operation Θ between EmployeeDept and EmployeeProject will generate the given output. Identify the operation Θ.

a) natural join\
b) natural left outer join\
c) natural right outer join\
d) natural full outer join

[View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

Que2. Consider the following CREATE statements for tables `department` and `employee`.\
Identify the correct statement(s) from the following options.

a) If a dept\_id value is deleted from the department table, the corresponding records in the employee table that use this dept\_id will also be deleted.\
b) If a dept\_id value is deleted from the department table, the foreign key constraint will become invalid.\
c) If a dept\_id value is deleted from the department table, the corresponding records in the employee table that use this dept\_id will be deleted and the foreign key constraint will become invalid.\
d) If a dept\_id value is deleted from the department table, the corresponding records in the employee table that use this dept\_id will not be deleted.

[View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

Que3. Consider the following table Products.\
How many tuples will be returned by the following query?

    SELECT product, cost
    FROM Products
    WHERE cost > (SELECT MIN(cost) FROM Products);

a) 2\
b) 3\
c) 4\
d) 5

[View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

Que4. Consider the following table Library.\
Which of the following options will NOT be present in the output produced by:

    SELECT MAX(book_id) FROM Library GROUP BY category;

a) 3\
b) 8\
c) 15\
d) 21

[View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

Que5. Consider the following table Library.\
What will be the output of the following SQL query?

    SELECT COUNT(book_id)
    FROM Library
    WHERE category LIKE 'S%' OR category LIKE 'F%';

a) 2\
b) 3\
c) 4\
d) 5

[View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

Que6. Consider the following instance of the table Library.\
Identify the correct CREATE statement for this table.

a) CREATE TABLE Library (\
    book\_id INT NOT NULL,\
    category VARCHAR(50),\
    copies INT,\
    PRIMARY KEY (book\_id)\
);

b) CREATE TABLE Library (\
    book\_id INT NOT NULL,\
    category VARCHAR(50) NOT NULL,\
    copies INT,\
    PRIMARY KEY (category)\
);

c) CREATE TABLE Library (\
    book\_id INT,\
    category VARCHAR(50) NOT NULL,\
    copies DATE,\
    PRIMARY KEY (category, copies)\
);

d) CREATE TABLE Library (\
    book\_id INT NOT NULL,\
    category VARCHAR(50),\
    copies INT,\
    PRIMARY KEY (copies)\
);

[View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

Que7. Suppose a library wants to create a view consisting of the book\_id of books in the ‘Science’ category with the number of copies being greater than or equal to 25 but less than or equal to 40.\
Identify the correct query from the following.

a)

    CREATE VIEW v1 AS
    SELECT book_id
    FROM Library
    WHERE category = 'Science'
    AND copies >= 25 AND copies <= 40;

b)

    CREATE VIEW v1 AS
    SELECT book_id
    FROM Library
    WHERE category = 'Science'
    AND copies BETWEEN 25 AND 40;

c)

    CREATE VIEW v1 AS
    SELECT book_id
    FROM Library
    WHERE category = 'Science'
    AND copies > 25 AND copies < 40;

d)

    CREATE VIEW v1 AS
    SELECT book_id
    FROM Library
    WHERE category = 'Science'
    AND copies >= 25, copies <= 40;

[View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

Que8. Consider the following instance of the table Library.\
Identify the correct SQL statement(s) to produce the given output.

a)

    SELECT * FROM Library
    WHERE copies >= 30;

b)

    SELECT * FROM Library
    WHERE category = 'Science';

c)

    SELECT * FROM Library
    WHERE copies >= 30 AND category = 'Science';

d)

    SELECT * FROM Library
    WHERE copies >= 30 OR category = 'Science';

[View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

Que9. Consider the following instance of the table Library.\
Identify the correct SQL command to find the average number of copies of books in the ‘Science’ category.

a)

    SELECT avg(copies) FROM Library;

b)

    SELECT * FROM Library WHERE category='Science' AND avg(copies);

c)

    SELECT * FROM Library WHERE category='Science' OR avg(copies);

d)

    SELECT avg(copies) FROM Library WHERE category='Science';

[View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

Que10. Consider the following instance of the table Library.\
Identify the correct SQL statement(s) to find the book\_id and copies of books whose number of copies is greater than all books in the ‘Fiction’ category.

a)

    SELECT book_id, copies
    FROM Library
    WHERE copies > (SELECT copies FROM Library WHERE category='Fiction');

b)

    SELECT book_id, copies
    FROM Library
    WHERE copies > ALL (SELECT copies FROM Library WHERE category='Fiction');

c)

    SELECT book_id, copies
    FROM Library
    WHERE copies > (SELECT MAX(copies) FROM Library WHERE category='Fiction');

d)

    SELECT book_id, copies
    FROM Library
    WHERE copies > FOR (SELECT copies FROM Library WHERE category='Fiction');

[View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)


## _Nptel Database Management System Assignment 2 Answers( July-Dec 2025)_

***

**Question 1.** **Consider two relations StudentInfo and CourseEnrollment… Identify the operation ©.**\
a) Natural join\
b) Natural left outer join\
c) Natural right outer join\
d) Natural full outer join

[**View Answers**](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

**Question 2.** **How many tuples will be returned by the query on GameInventory?**\
a) 1\
b) 2\
c) 3\
d) 4

[**View Answers**](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

**Question 3.** **Which game\_id will not appear in the output of:\
`SELECT MIN(game_id) FROM GameInventory GROUP BY rarity;`**\
a) G101\
b) G205\
c) G307\
d) G503

[**View Answers**](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

**Question 4.** **Which emp\_id will appear in the output of the first query but not in the second?**\
a) E101\
b) E205\
c) E307\
d) E412

[**View Answers**](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

**Question 5.** **Which course\_code appears in the output of both queries?**\
a) MATH202\
b) PHYS101\
c) ECE209\
d) CS101

[**View Answers**](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

**Question 6.** **Identify the correct `CREATE` statement for StudentRecords.**\
a) `PRIMARY KEY (student_code)`\
b) `PRIMARY KEY (course)`\
c) `PRIMARY KEY (student_code, department)`\
d) `PRIMARY KEY (department, year)`

[**View Answers**](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

**Question 7.** **Given RiverDetails relation, what will be the output of the max-length query?**\
[**View Answers**](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

**Question 8.** **Identify the correct SQL query to get rivers from China or Egypt.**\
a) `WHERE Country = 'China' OR 'Egypt'`\
b) `WHERE Country BETWEEN 'China' AND 'Egypt'`\
c) `WHERE Country IN ('China', 'Egypt')`\
d) `WHERE Country LIKE 'Ch%' OR 'Egh'`

[**View Answers**](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

**Question 9.** **Identify the correct SQL query to find RiverName and Country for rivers with length between 2500 and 3000.**\
a) `WHERE Length IN (2500, 3000)`\
b) `WHERE Length AS (2500, 3000)`\
c) `WHERE Length BETWEEN 2500 AND 3000`\
d) `WHERE Length BETWEEN (2500, 3000)`

[**View Answers**](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)



## _Nptel Database Management System Assignment 2 Answers( Jan-Apr 2025)_

***

1. **What is the correct SQL query to update the Quantity values in the OrderDetails table where the current values are greater than 2?**

- a) MODIFY OrderDetails where Quantity>2;
- b) UPDATE OrderDetails set Quantity=Quantity-1 where Quantity>2;
- c) UPDATE OrderDetails where Quantity>2;
- d) ALTER OrderDetails set Quantity=Quantity-1 where Quantity>2;

[View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

2. **What is the output of the following SQL query for a bookstore system?**

<!---->

    SELECT Category, SUM(Quantity) FROM OrderDetails, BookDetails WHERE OrderDetails.BookID = BookDetails.BookID GROUP BY Category;

- a) Fiction: 5, Science: 7
- b) Fiction: 6, Science: 7
- c) Fiction: 9, Science: 7
- d) Fiction: 5, Science: 6\
  [View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

3. **What is the correct SQL statement to create a VIEW for retrieving Name and Price of all products in the ‘Electronics’ category from the ProductDetails table?**

- a) Create Electronics\_Products AS SELECT Name, Price FROM ProductDetails WHERE Category = ‘Electronics’;
- b) Create view Electronics\_Products AS SELECT Name, Price FROM ProductDetails WHERE Category = ‘Electronics’;
- c) Create view Electronics\_Products ON ProductDetails SELECT Name, Price WHERE Category = ‘Electronics’;
- d) Create view Electronics\_Products TO ProductDetails SELECT Name, Price WHERE Category = ‘Electronics’;\
  \
  [View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

4. **Which of the following options will be present in the output of the SQL query for the DriverDetails table?**

<!---->

    SELECT Location FROM DriverDetails WHERE Location LIKE 'B%' AND Location LIKE 'B%';

- a) Bangalore
- b) Bhopal
- c) Pune
- d) Hyderabad\
  \
  [View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

5. **Which relational algebra operation will generate the given output?**

- a) OrderDetails NATURAL JOIN ProductDetails
- b) OrderDetails LEFT OUTER JOIN ProductDetails
- c) OrderDetails RIGHT OUTER JOIN ProductDetails
- d) OrderDetails EQUI JOIN ProductDetails ON OrderDetails.ProductID = ProductDetails.ProductID\
  \
  [View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

6. **Which of the following statements is incorrect?**

- a) The INSERT command is used to remove/modify rows in a relation.
- b) The UPDATE command is used to modify data (values in rows) of a relation.
- c) The DELETE command is used to remove all data from a relation.
- d) The DELETE command is used to remove a relation entirely.\
  \
  [View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

[****See also**  **Data Base Management System | Week 8****](https://progiez.com/data-base-management-system-week-8-assignment-answers)

***

7. **What will be the output of the following SQL query on the DriverDetails table?**

![image 17](https://progiez.com/wp-content/uploads/2024/08/image-17.png "Nptel Database Management System Assignment 2 Answers 2")

[View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

8. **What will be the output of the following SQL query on the DriverDetails table?**

![image 16](https://progiez.com/wp-content/uploads/2024/08/image-16.png "Nptel Database Management System Assignment 2 Answers 3")

[View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

9. **What will be the output of the following SQL query on the DriverDetails table?**

<!---->

    SELECT * FROM DriverDetails WHERE City IN ('New York', 'Chicago');

- a) DriverID: D001, D003, D004, D006, D007
- b) DriverID: D002, D005
- c) DriverID: D001, D002, D003
- d) DriverID: D005, D008

[View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

10. **What is the correct SQL statement to find the DriverID, Name, and City of drivers with an Age between 25 and 35?**

- a) SELECT DriverID, Name, City FROM DriverDetails WHERE Age AS (26, 35);
- b) SELECT DriverID, Name, City FROM DriverDetails WHERE Age IN (25, 35);
- c) SELECT DriverID, Name, City FROM DriverDetails WHERE Age BETWEEN 25 AND 35;
- d) SELECT DriverID, Name, City FROM DriverDetails WHERE Age BETWEEN (25, 35);

[View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

Nptel Database Management System Assignment 2 Answers


# Nptel Database Management System Assignment 2 Answers<a id="2f5b"></a>

**Session: JUL-DEC 2024**

**Q1. In a particular messenger application, the instance of Chat Details is as follows:**

**For the instance, the Total\_Text values need to be updated to increase by 500 for those entries whose current values are less than 1000. What is the correct SQL Query for updating the current instance?**\
a) MODIFY ChatDetails Total\_Text=Total\_Text+500 where Total\_Text<1000;\
b) UPDATE ChatDetails set Total\_Text=Total\_Text+500 where Total\_Text<1000;\
c) UPDATE ChatDetails Total\_Text=Total\_Text+500 where Total\_Text<1000;\
d) ALTER ChatDetails set Total\_Text=Total\_Text+500 where Total\_Text<1000;

**Answer: b) UPDATE ChatDetails set Total\_Text=Total\_Text+500 where Total\_Text<1000;**

**Q2. In a particular messenger application, the instances of ChatDetails and UserDetails are as follows:**

What is the output of the following SQL Query?\
SELECT COUNT(Address) FROM ChatDetails, UserDetails GROUP BY Address;\
a) 4\
3\
b) 4\
8\
c) 4\
d) 3

**Answer:** b) 4\
8

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Nptel Database Management System Assignment 2 Answers**

**Q3. In a particular messenger application, the instance of UserDetails is as follows:**

Which of the options will not be present in the output generated by the SQL query: SELECT Address FROM UserDetails WHERE Address LIKE ‘%’ OR Address LIKE ‘M%’;\
a) Agartala\
b) Kolkata\
c) Mumbai\
d) Delhi

[**_**Answer: Click here to view answers**_**](https://progiez.com/nptel-database-management-system-assignment-2-answers)

**Q4. Which of the following statements is incorrect?**

a) ALTER command is used to add remove\modify rows to a relation.\
b) ALTER command is used to add remove\modify attributes to a relation.\
c) DROP command is used to delete all data from a relation.\
d) DROP command is used to delete a relation.

[**_**Answer: Click here to view answers**_**](https://progiez.com/nptel-database-management-system-assignment-2-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Nptel Database Management System Assignment 2 Answers**

**Q5. Let students (student\_id, student name, address, emailid) and enrolment (student\_id, dept name, enrolment\_date) be two relations in a schema. The primary keys are shown underlined.\
Let student\_id be a foreign key in enrolment relation referring to students relation. Suppose, there is no violation of the above referential integrity constraint in the corresponding relation instances of students and enrolment.\
Which one of the following relational algebra expressions would necessarily produce an empty relation?**\
a) Istudent\_id (enrolment) Istudent\_id (students)\
b) Istudent\_id (students) Istudent\_id (enrolment)\
c) Istudent\_id(enrolment <> students)\
d) Istudent\_id (enrolment students)

[**_**Answer: Click here to view answers**_**](https://progiez.com/nptel-database-management-system-assignment-2-answers)

**Q6. Consider the following instance of MountainDetails (MountainName, Altitude, StateName) relation.**\
What will be the output of the following query?\
SELECT MountainName, Altitude\
FROM MountainDetails md1\
WHERE Altitude = (\
SELECT MAX(Altitude) FROM MountainDetails md2 WHERE md1.StateName = md2. StateName);

[**_**Answer: Click here to view answers**_**](https://progiez.com/nptel-database-management-system-assignment-2-answers)

![](https://miro.medium.com/v2/resize:fit:375/0*AJbp1z-A6xKrXp5_.png)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Nptel Database Management System Assignment 2 Answers**

**Q7.** Consider the following instance of MountainDetails (MountainName, Altitude, StateName) relation.

What will be the output of the following query?\
SELECT MountainName, Altitude FROM MountainDetails WHERE Altitude > (\
SELECT Altitude FROM MountainDetails WHERE StateName = “Uttarakhand”);

[**_**Answer: Click here to view answers**_**](https://progiez.com/nptel-database-management-system-assignment-2-answers)

![](https://miro.medium.com/v2/resize:fit:413/0*c3R0j0b_JaVh2zF_.png)

**Q8.** Consider the following instance UserDetails of a messenger application

a) SELECT \* FROM UserDetails\
WHERE Address AS (‘Delhi’, ‘Mumbai’);\
b) SELECT \* FROM UserDetails WHERE Address IN (‘Delhi’, ‘Mumbai’);\
c) SELECT \* FROM UserDetails WHERE Address FOR (‘Delhi’, ‘Mumbai’);\
d) SELECT \* FROM UserDetails WHERE Address TO (‘Delhi’, ‘Mumbai’);

[**_**Answer: Click here to view answers**_**](https://progiez.com/nptel-database-management-system-assignment-2-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Nptel Database Management System Assignment 2 Answers**

**Q9.**Consider the following instance UserDetails of a messenger application:

Identify the correct statement to create an index on SenderID and Address of UserDetails relation named as ‘View\_UserDetails’\
a) Create View\_UserDetails AS UserDetails (Sender ID, Address);\
b) Create index View\_UserDetails AS UserDetails (Sender ID, Address);\
c) Create index View\_UserDetails ON UserDetails (Sender ID, Address);\
d) Create index View\_UserDetails TO UserDetails (SenderID, Address);

[**_**Answer: Click here to view answers**_**](https://progiez.com/nptel-database-management-system-assignment-2-answers)

**Q10.** Consider the following instance UserDetails of a messenger application:

Identify the correct statement to find the SenderID, Receiver ID, and Address of UserDetails table whose Total\_Text is in between 700 and 1200.\
a) SELECT SenderID, ReceiverID, Address FROM UserDetails WHERE Total\_Text AS (700, 1200);\
b) SELECT SenderID, ReceiverID, Address FROM UserDetails WHERE Total\_Text IN (700, 1200);\
c) SELECT SenderID, ReceiverID, Address FROM UserDetails WHERE Total\_Text BETWEEN (700, 1200);\
d) SELECT SenderID, ReceiverID, Address FROM UserDetails WHERE Total\_Text BETWEEN 700 AND 1200;

[**_**Answer: Click here to view answers**_**](https://progiez.com/nptel-database-management-system-assignment-2-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Nptel Database Management System Assignment 2 Answers**

All Weeks of Database Management System: [Click here](https://progiez.com/nptel-assignment-answers/nptel-data-base-management-system-answers)

For answers to additional Nptel courses, please refer to this link: [Check here](https://progiez.com/nptel-assignment-answers)
