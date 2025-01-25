# NPTEL Database Management System Week 01 Assignment Answers

Are you looking for NPTEL Database Management System Week 01 Assignment Answers? This repository will help you find your answers and solutions for Week 01 of the Database Management System course. We provide detailed solutions to help you complete your assignments efficiently.

## Data Base Management System Nptel Assignment 1 Answers (Jan-Apr 2025)

**Course Link: [**Click Here**](https://onlinecourses.nptel.ac.in/noc24_cs75/preview)**

***

**Que. 1: Which of the following statements is (are) incorrect?**\
a) Logical level abstraction defines the physical storage of data.\
b) View level abstraction provides a user-friendly interface for end users.\
c) Physical level abstraction focuses on the relationships among data.\
d) Logical level abstraction focuses on the relationships among data.

**[**View Answer**](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)**

***

**Que. 2: Consider the following SQL statements:**

    sqlCopyEditINSERT INTO emp_name, dept)  
    VALUES (101, 'Alice', 'HR');  

    ALTER TABLE employees ADD count salary number(8, 2);

Identify the correct statement.\
a) Both S1 and S2 are Data Manipulation (DML) Queries.\
b) S1 is a Data Manipulation (DML) Query, and S2 is a Data Definition (DDL) Query.\
c) Both S1 and S2 are Data Definition (DDL) Queries.\
d) S1 is a Data Control Query, and S2 is a Data Definition (DDL) Query.

****[**View Answer**](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)****

***

**Que. 3: Identify the valid primary key for the relation `event_registration` from the given instance:**

| participant\_id | event\_id | registration\_date | status    |
| --------------- | --------- | ------------------ | --------- |
| 1001            | E001      | 2024-01-10         | Confirmed |
| 1002            | E002      | 2024-01-11         | Pending   |
| 1003            | E001      | 2024-01-10         | Confirmed |
| 1004            | E003      | 2024-01-12         | Confirmed |
| 1001            | E002      | 2024-01-14         | Pending   |

a) `participant_id`.\
b) `event_id`, `registration_date`.\
c) `participant_id`, `event_id`.\
d) `event_id`, `status`.

****[**View Answer**](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)****

***

**Que. 4: Identify the correct statement(s):**\
a) Employee(empID, empName) is an instance of a relation schema.\
b) Employee(empID, empName) is an example of a physical schema.\
c) (101, John) is an instance of a relation schema.\
d) (101, John) is an example of a logical schema.

****[**View Answer**](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)****

***

**Que. 5: Consider a relation `CityDetails(CityName, Population, CountryName)` where the superkeys are as follows:**\
{CityName}, {CityName, Population}, {CityName, CountryName}, {CityName, Population, CountryName}.

[****See also**  **Data Base Management System | Week 7****](https://progiez.com/data-base-management-system-week-7-assignment-answers)

Select the possible candidate key(s).\
a) {CityName, Population, CountryName}.\
b) {CityName, Population}.\
c) {CityName}.\
d) {CityName, CountryName}.

****[**View Answer**](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)****

***

**Que. 6: Consider the following relations:**\
Employee(eid, ename, salary), Department(dept\_id, dept\_name).

Consider the following Relational Algebras:\
RA1: πEmployee.eid, ename(Employee ⨝ Department).\
RA2: πEmployee.eid, ename(Employee × Department).

Which of the following is correct?\
a) RA1 = RA2.\
b) RA1 ⊂ RA2.\
c) RA2 ⊂ RA1.\
d) RA1 ≠ RA2.

****[**View Answer**](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)****

***

**Que. 7: Consider the following instance of the `CourseDetails (CourseID, CourseName)` relation:**

| CourseID | CourseName  |
| -------- | ----------- |
| C101     | Mathematics |
| C102     | Physics     |

If `CourseID` is the foreign key in the relational schema `StudentEnrollments (EnrollmentID, StudentName)`, which of the following is a valid instance of `StudentEnrollments`?

a)

| EnrollmentID | CourseID | StudentName |
| ------------ | -------- | ----------- |
| E001         | C105     | Amit        |
| E002         | C102     | Raj         |

b)

| EnrollmentID | CourseID | StudentName |
| ------------ | -------- | ----------- |
| E001         | C102     | Amit        |
| E001         | C102     | Raj         |

c)

| EnrollmentID | CourseID | StudentName |
| ------------ | -------- | ----------- |
| NULL         | C102     | Amit        |
| E003         | C102     | Raj         |

d)

| EnrollmentID | CourseID | StudentName |
| ------------ | -------- | ----------- |
| E001         | C102     | Amit        |
| E002         | C102     | Raj         |

****[**View Answer**](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)****

***

**Que. 8: Identify the correct operation(s) to produce the following output:**

Given table `CityDetails`:

| CityName  | Population | StateName   |
| --------- | ---------- | ----------- |
| Mumbai    | 20000      | Maharashtra |
| Delhi     | 19000      | Delhi       |
| Bengaluru | 12000      | Karnataka   |

a) σ (CityDetails).\
b) σ (Population > 10000) ∧ (StateName = ‘Maharashtra’) (CityDetails).\
c) σ (StateName = ‘Delhi’) (CityDetails).\
d) π (CityDetails).

****[**View Answer**](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)****

***

**Que. 9)**\
**Consider the following tables:**

| CityName  | Population | StateName   |
| --------- | ---------- | ----------- |
| Delhi     | 20000      | Maharashtra |
| Ahmedabad | 8000       | Gujarat     |
| Pune      | 6000       | Maharashtra |
| Bengaluru | 12000      | Karnataka   |
| Chennai   | 10000      | Tamil Nadu  |

From the above tables, identify the correct operation(s) that produce the following output:

| CityName  | Population | StateName   |
| --------- | ---------- | ----------- |
| Mumbai    | 20000      | Maharashtra |
| Ahmedabad | 8000       | Gujarat     |

**Options:**\
A) `CityDetails1 ∩ CityDetails2`\
B) `CityDetails1 - CityDetails2`\
C) `CityDetails2 - CityDetails1`\
D) `CityDetails1 ∪ CityDetails2`

****[**View Answer**](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)****

***

**Que. 10)**\
**Consider the following table:**

| CityName  | Population | StateName   |
| --------- | ---------- | ----------- |
| Mumbai    | 20000      | Maharashtra |
| Delhi     | 19000      | Delhi       |
| Bengaluru | 12000      | Karnataka   |
| Hyderabad | 10000      | Telangana   |
| Ahmedabad | 8000       | Gujarat     |
| Pune      | 6000       | Maharashtra |

Identify the correct operation(s) that produce the following output from the above relation:

[****See also**  **Data Base Management System | Week 3****](https://progiez.com/data-base-management-system-week-3-assignment-answers)

| CityName  | StateName   |
| --------- | ----------- |
| Mumbai    | Maharashtra |
| Delhi     | Delhi       |
| Bengaluru | Karnataka   |

**Options:**\
A) `π(CityName, StateName)`\
B) `σ(Population > 12000)`\
C) `π(CityName, StateName) ⨝ σ(Population > 12000) (CityDetails)`\
D) `σ(CityName, StateName) (CityDetails)`

****[**View Answer**](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)****


**Session: JUL-DEC 2024**

**Course name: Data Base Management System**

**Course Link:** [**Click Here**](https://onlinecourses.nptel.ac.in/noc24_cs75/preview)

These are Data Base Management System Nptel Assignment 1 Answers

**Q1. Consider the SQL statement(s) below:\
S1:\
CREATE table students( student\_id number(5), student\_name varchar2(20), address varchar2(20), emailid varchar2(20));\
S2:\
DELETE FROM students WHERE student\_id = 10005;\
Identify the correct statement.**\
a) Both S1 and S2 are Data Definition (DDL) Queries\
b) Both S1 and S2 are Data Manipulation (DML) Queries\
c) S1 is a Data Definition (DDL) Query and S2 is a Data Manipulation Query (DML)\
d) S1 is a Data Control Query and S2 is a Data Manipulation (DML) Query

[**_**Answer: Click here to view answer**_**](https://progiez.com/data-base-management-system-nptel-assignment-1-answers)

**Q2. Identify the valid primary key for the relation students.**\
a) student\_id\
b) student\_name\
c) student\_name, address\
d) student\_id, dept\_name

[**_**Answer: Click here to view answer**_**](https://progiez.com/data-base-management-system-nptel-assignment-1-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Data Base Management System Nptel Assignment 1 Answers**

**Q3. Models developed using artificial neural networks are _**\_\_**_ .**\
a representation of past experience\
a representation of future outcome\
made of biological neurons

[**_**Answer: Click here to view answer**_**](https://progiez.com/data-base-management-system-nptel-assignment-1-answers)

**Q4. Planning systems are used to _**\_\_**_ .**\
recall past experience\
compute a sequence of moves for the future

[**_**Answer: Click here to view answer**_**](https://progiez.com/data-base-management-system-nptel-assignment-1-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Data Base Management System Nptel Assignment 1 Answers**

**Q5. Let students (student\_id, student name, address, emailid) and enrolment (student\_id, dept name, enrolment\_date) be two relations in a schema. The primary keys are shown underlined.\
Let student\_id be a foreign key in enrolment relation referring to students relation. Suppose, there is no violation of the above referential integrity constraint in the corresponding relation instances of students and enrolment.\
Which one of the following relational algebra expressions would necessarily produce an empty relation?**\
a) Istudent\_id (enrolment) Istudent\_id (students)\
b) Istudent\_id (students) Istudent\_id (enrolment)\
c) Istudent\_id(enrolment <> students)\
d) Istudent\_id (enrolment students)

[**_**Answer: Click here to view answer**_**](https://progiez.com/data-base-management-system-nptel-assignment-1-answers)

**Q6. Which of the following AI agents first demonstrated that machines can beat the very best humans at chess?**\
Blue Gene\
Chess Machine\
Deep Blue\
Deep Thought

[**_**Answer: Click here to view answer**_**](https://progiez.com/data-base-management-system-nptel-assignment-1-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Data Base Management System Nptel Assignment 1 Answers**

**Q7. Tyson told Buster that he won. The pronoun “he” refers to _**\_\_**_ .**\
Tyson\
Buster\
Cannot say

[**_**Answer: Click here to view answer**_**](https://progiez.com/data-base-management-system-nptel-assignment-1-answers)

**Q8. The judge told Buster that he won. The pronoun “he” refers to _**\_\_**_ .**\
Tyson\
Buster\
Cannot say

[**_**Answer: Click here to view answer**_**](https://progiez.com/data-base-management-system-nptel-assignment-1-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Data Base Management System Nptel Assignment 1 Answers**

**Q9. The dog chased the cat, which ran up a tree. It waited at the top. Who does “It” refer to?**\
The dog\
The cat\
Cannot say

[**_**Answer: Click here to view answer**_**](https://progiez.com/data-base-management-system-nptel-assignment-1-answers)

**Q10. The dog chased the cat, which ran up a tree. It waited at the bottom. Who does “It” refer to?**\
The dog\
The cat\
Cannot say

[**_**Answer: Click here to view answer**_**](https://progiez.com/data-base-management-system-nptel-assignment-1-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Data Base Management System Nptel Assignment 1 Answers**

More Weeks of Data Base Management System: [Click here](https://progiez.com/nptel-assignment-answers/nptel-data-base-management-system-answers)
