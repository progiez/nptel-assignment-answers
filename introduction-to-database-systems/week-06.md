# NPTEL Introduction to Database Systems Week 06 Assignment Answers

Are you looking for NPTEL Introduction to Database Systems Week 06 Assignment Answers? This repository will help you find your answers and solutions for Week 06 of the **Introduction to Database Systems** course. We provide detailed solutions to help you complete your assignments efficiently.

## Introduction to Database Systems Week 6 Quiz Answers (Jan-Apr 2025)

**Course Link: [**Click Here**](https://onlinecourses.nptel.ac.in/noc25_cs40/course)**

***

1. Under which of the following conditions are update operations on views NOT allowed?

a) Only (ii)\
b) Only (iii)\
c) Only (i) and (ii)\
d) All (i), (ii), and (iii)

[View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

2. HAVING clause can be used in a query only if GROUP BY clause is used

a) True\
b) False

[View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

3. GROUP BY clause can be used in a query only if HAVING clause is used

a) True\
b) False

[View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

4. It is mandatory to use an aggregate function in a query if GROUP BY clause is used

a) True\
b) False

[View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

5. Aggregate functions can be used in GROUP BY clauses

a) True\
b) False

[View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

6. In which of the following SQL clauses of a main query can a sub-query be made use of?

a) Only (ii)\
b) Only (iii)\
c) Only (ii) and (iii)\
d) All (i), (ii), and (iii)

[View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

7. Which of the following queries would select the courses with at least 10 ‘W’ grades in some offering of the course?

a) `SELECT courseId FROM enrollment WHERE grade = ‘W’ GROUP BY courseId HAVING count(rollNo) >= 10`\
b) `SELECT courseId FROM enrollment WHERE grade = ‘W’ GROUP BY courseId, sem, year HAVING count(rollNo) >= 10`\
c) `SELECT courseId FROM enrollment WHERE grade = ‘W’ AND count(rollNo) >= 10 GROUP BY courseId`\
d) `SELECT courseId FROM enrollment WHERE grade = ‘W’ AND count(rollNo) >= 10 GROUP BY courseId, sem, year`

[View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

[****See also**  **Introduction to Database Systems Week 5 Quiz Answers Nptel****](https://progiez.com/introduction-to-database-systems-week-5-quiz-answers)

***

8. Which of the following queries will retrieve students whose name has ‘p’ as the second letter?

a) `SELECT rollNo FROM student WHERE name = ‘_p’;`\
b) `SELECT rollNo FROM student WHERE name LIKE ‘_p’;`\
c) `SELECT rollNo FROM student WHERE name LIKE ‘_p%’;`\
d) `SELECT rollNo FROM student WHERE name IN ‘_p%’;`

[View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

9. Consider two instances of the relations R1(A, B) and R2(C, D) with the number of rows 10 and 8, respectively. What is the least possible number of tuples in the result of the following query?

<!---->

    SELECT * FROM R1 FULL OUTER JOIN R2 ON R1.A = R2.C

a) 0\
b) 18\
c) 8\
d) 10

[View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

10. Which of the following queries is correct to find the courses with no prerequisites?

a) `SELECT courseId FROM preRequisite GROUP BY courseId HAVING count(preCourseId) = 0`\
b) `SELECT courseId FROM preRequisite a WHERE NOT EXISTS (SELECT preCourseId FROM preRequisite b WHERE a.courseId = b.courseId)`\
c) Both (i) and (ii)\
d) Neither (i) nor (ii)

[View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

11. Which of the following queries would find the ID and name of the senior-most HOD(s)?

a) `SELECT p1.empId, p1.name FROM professor p1 WHERE p1.startYear IN (SELECT min(p.startYear) FROM professor p, department d WHERE p.empId = d.hod)`\
b) `SELECT p.empId, p.name FROM professor p, department d WHERE p.empId = d.hod WHERE p.startYear IN (SELECT min(p1.startYear) FROM professor p1)`\
c) `SELECT p1.empId, p1.name FROM professor p1, department d1 WHERE p1.empId = d1.hod AND p1.startYear IN (SELECT min(p.startYear) FROM professor p, department d WHERE p.empId = d.hod)`\
d) None of the above

[View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

12. Which one of the following queries would find the teacher(s) who taught CS1100 the highest number of times?

[****See also**  **Introduction to Database Systems Week 4 Quiz Answers Nptel****](https://progiez.com/introduction-to-database-systems-week-4-quiz-answers)

a)

    CREATE VIEW EmpCount AS
    SELECT empId, count(*) AS cnt
    FROM teaching
    WHERE courseId = ‘CS1100’
    GROUP BY empId;

    SELECT empId FROM EmpCount WHERE cnt = (SELECT MAX(cnt) from EmpCount);

b)

    CREATE VIEW EmpCount AS
    SELECT empId, count(*) AS cnt
    FROM teaching
    WHERE courseId = ‘CS1100’;

    SELECT empId FROM EmpCount WHERE cnt = (SELECT MAX(cnt) from EmpCount);

c)

    SELECT empId, max(count(*)) AS cnt
    FROM teaching
    WHERE courseId = ‘CS1100’
    GROUP BY empId;

d)

    SELECT empId
    FROM teaching
    WHERE courseId = ‘CS1100’
    GROUP BY empId
    HAVING COUNT(*) = (SELECT max(count(*)) FROM teaching WHERE courseId = ‘CS1100’);

[View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

13. Consider the following sets about different approaches to programmatic access of databases and the properties that may apply to these approaches.

<!---->

    {1: Embedded SQL approach; 2: API based approach; 3: Database language approach}
    {p: Only one connection to a DB server can be active at any time q: Open Database Connectivity (ODBC); r: Cursors; s: Programmers need to learn a new language ; t: Multiple connections to DB servers can be active at any time}

Identify the correct matching between the sets:

a) 1–p; 2–t; 3–q\
b) 1–t; 2–q; 3–s\
c) 1–s; 2–r; 3–p\
d) 1–p; 2–t; 3–s

[View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)
