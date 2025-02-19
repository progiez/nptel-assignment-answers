# NPTEL Introduction to Database Systems Week 05 Assignment Answers

Are you looking for NPTEL Introduction to Database Systems Week 05 Assignment Answers? This repository will help you find your answers and solutions for Week 05 of the **Introduction to Database Systems** course. We provide detailed solutions to help you complete your assignments efficiently.

## Introduction to Database Systems Week 5 Quiz Answers (Jan-Apr 2025)

**Course Link: [**Click Here**](https://onlinecourses.nptel.ac.in/noc25_cs40/course)**

***

Q1. Which of the following SQL sub-language constructs are used to insert rows into tables?

a) DDL\
b) DML\
c) Transaction control language\
d) None of the above

[View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

Q2. Which of the following relational calculus operators does not have an equivalent keyword in SQL?

a) exists (∃)\
b) for all (∀)\
c) and (∧)\
d) None of the above

[View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

Q3. Suppose that in the given schema, we want to change the teaching table and add an extra column called ‘teachingAssistant’. A teaching assistant is a student who assists the professor of a course in clarifying student doubts, setting up quizzes, and evaluating students, etc. Assume that each course is allotted at most one teaching assistant. Which of the following commands is suitable to enforce the above requirement?

a) ALTER TABLE teaching ADD teachingAssistant VARCHAR(10);\
b) ALTER TABLE teaching ADD teachingAssistant VARCHAR(10) NOT NULL;\
c) ALTER TABLE teaching ADD teachingAssistant VARCHAR(10) REFERENCES professor(empId);\
d) ALTER TABLE teaching ADD teachingAssistant VARCHAR(10) REFERENCES student(rollNo);

[View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

Q4. Which of the following are unique keys in the teaching table definition?

(i) empId, courseId, year\
(ii) empId, courseId, sem, year\
(iii) empId, courseId, sem, year, classRoom

a) Only (i)\
b) Only (ii)\
c) Only (ii) and (iii)\
d) All (i), (ii), and (iii)

[****See also**  **Artificial Intelligence: Knowledge Representation And Reasoning Week 5 Answer****](https://progiez.com/ai-knowledge-representation-and-reasoning-week-5-answer)

[View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

Q5. Suppose that in the given schema, the PRIMARY KEY of the preRequisite table is only “courseId.” Then, which of the following statements is TRUE in all data instances of the database?

a) Every course in the course table (specified in the courseId column) has at least one prerequisite\
b) Every course in the course table (specified in the courseId column) has exactly one prerequisite\
c) Every course in the preRequisite table (specified in the courseId column) has exactly one prerequisite\
d) All of the above

[View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

These are Introduction to Database Systems Week 5 Quiz Answers

***

Q6. Suppose we need to find the roll numbers of students whose grades are neither ‘U’ nor ‘W’ in the course having id ‘CS123’. What is the correct SQL query?

a) SELECT rollNo FROM enrollment WHERE courseId = ‘CS123’ and grade != ‘U’ or grade != ‘W’\
b) SELECT rollNo FROM enrollment WHERE courseId = ‘CS123’ and NOT (grade != ‘U’ and grade != ‘W’)\
c) SELECT rollNo FROM enrollment WHERE courseId = ‘CS123’ and grade NOT EXISTS (‘U’, ‘W’);\
d) SELECT rollNo FROM enrollment WHERE courseId = ‘CS123’ and grade NOT IN (‘U’, ‘W’);

[View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

Q7. Which of the following queries would find the students who enrolled in a course twice (Note that a course is usually offered once in a year but some popular courses are offered in both semesters of the same year)?

a) SELECT e1.rollNo FROM enrollment e1 WHERE EXISTS (SELECT \* FROM enrollment e2 WHERE e1.rollNo = e2.rollNo and e1.courseId = e2.courseId)\
b) SELECT e1.rollNo FROM enrollment e1 WHERE EXISTS (SELECT \* FROM enrollment e2 WHERE e1.rollNo = e2.rollNo and e1.courseId = e2.courseId and e1.year = e2.year and e1.sem = e2.sem)\
c) SELECT e1.rollNo FROM enrollment e1 WHERE EXISTS (SELECT \* FROM enrollment e2 WHERE e1.rollNo = e2.rollNo and e1.courseId = e2.courseId and e1.year != e2.year and e1.sem != e2.sem)\
d) SELECT e1.rollNo FROM enrollment e1 WHERE EXISTS (SELECT \* FROM enrollment e2 WHERE e1.rollNo = e2.rollNo and e1.courseId = e2.courseId and (e1.year != e2.year or e1.sem != e2.sem))

[****See also**  **Data Analytics with Python Nptel Week 5 Assignment Answers****](https://progiez.com/data-analytics-with-python-nptel-week-5-quiz-answers)

[View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

Q8. Consider the following query to retrieve the most senior professor (determined based on startYear):

    SELECT p1.name
    FROM professor p1
    WHERE p1.startYear ---------- (SELECT p2.startYear FROM professor p2)

Which of the following options is the correct filler for the blank?

a) < ALL\
b) <= ALL\
c) <= ANY\
d) IN

[View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

Q9. Which of the following queries would find the courses with at least two prerequisites?

a)

    SELECT *
    FROM course c1
    WHERE EXISTS (SELECT * FROM prerequisite p1 WHERE p1.courseId = c1.courseId)
    AND EXISTS (SELECT * FROM prerequisite p2 WHERE p2.courseId = c1.courseId)

b)

    SELECT *
    FROM course c1
    WHERE EXISTS (SELECT * FROM prerequisite p1 WHERE p1.courseId = c1.courseId)
    AND EXISTS (SELECT * FROM prerequisite p2 WHERE p2.courseId = c1.courseId
    AND p1.preCourseId <> p2.preCourseId)

c)

    SELECT *
    FROM course c1
    WHERE EXISTS (SELECT * FROM prerequisite p1, prerequisite p2
    WHERE p1.courseId = c1.courseId AND p2.courseId = c1.courseId)

d)

    SELECT *
    FROM course c1
    WHERE EXISTS (SELECT * FROM prerequisite p1, prerequisite p2
    WHERE p1.courseId = c1.courseId AND p2.courseId = c1.courseId
    AND p1.preCourseId <> p2.preCourseId)

[View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

Q10. Consider the following query:

    SELECT rollNo as identifier FROM student
    UNION
    SELECT empId as identifier FROM professor

Which of the following statements is correct regarding the above query?

a) The query executes only if rollNo of student and empId of professor have the same data types\
b) The query executes in all cases (irrespective of the data types of rollNo and empId)\
c) The query does not execute at all\
d) None of the above

[View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

Introduction to Database Systems Week 5 Quiz Answers

For answers to others Nptel courses, please refer to this link: [NPTEL Assignment](https://progiez.com/nptel-assignment-answers)
