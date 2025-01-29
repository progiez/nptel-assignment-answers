# NPTEL Database Management System Week 02 Assignment Answers

Are you looking for NPTEL Database Management System Week 02 Assignment Answers? This repository will help you find your answers and solutions for Week 02 of the Database Management System course. We provide detailed solutions to help you complete your assignments efficiently.

![Nptel Database Management System Assignment 2 Answers](https://miro.medium.com/v2/resize:fit:875/1*nw-gOvlsQ1d6ph1xPn-prQ.jpeg)
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
