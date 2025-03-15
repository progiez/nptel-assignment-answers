# NPTEL Database Management System Week 08 Assignment Answers

Are you looking for NPTEL Database Management System Week 08 Assignment Answers? This repository will help you find your answers and solutions for Week 08 of the Database Management System course. We provide detailed solutions to help you complete your assignments efficiently.

## Nptel Database Management System Assignment 8 Answers (Jan-Apr 2025)

**course link:** [click here](https://onlinecourses.nptel.ac.in/noc25_cs18/course)

***

**1) Identify the cost estimation of a query evaluation plan, if 9000 blocks are required to be transferred from the disk and the required number of disk seeks are 25.**

a) 40 Seconds\
b) 45 Seconds\
c) 50 Seconds\
d) 55 Seconds

[View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

**2) Assume an immediate database modification scheme. Consider the following log records for transactions T0, T1, T2, T3, and T4:**

Steps:

1. (T0, start)
2. (T1, start)
3. (T1, commit)
4. (T2, start)
5. (checkpoint {T0, T2})
6. (T3, start)
7. (T2, commit)
8. (T3, commit)
9. (T4, start)

If there is a crash just after step 14 and the recovery of the system is successfully completed, identify the correct action for the above scenario.

a) After recovery completion, value of A will be 600.\
b) After recovery completion, value of C will be 200.\
c) After recovery completion, value of D will be 900.\
d) After recovery completion, value of E will be 300.

[View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

**3) Let us consider the following statistics for two relations Instructor and Job-Assignments:**

- Number of records of Instructor: nInstructor = 5050
- Number of blocks of Instructor: bInstructor = 30
- Number of records of Job-Assignments: nJob-Assignments = 1050
- Number of blocks of Job-Assignments: bJob-Assignments = 10

[****See also**  **Nptel Database Management System Assignment 4 Answers****](https://progiez.com/nptel-database-management-system-assignment-4-answers)

Let us consider a natural join of Instructor and Job-Assignments relations (Instructor ⨝ Job-Assignments). Identify the required number of block transfers in the worst case (enough memory only to hold one block of each relation) using Nested-loop join and assume Instructor as the outer relation.

a) 40000 block transfers\
b) 40030 block transfers\
c) 50030 block transfers\
d) 50530 block transfers

[View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

**4) Consider the following relational schema:**

INSTRUCTOR(InstructorID, Name, HireDate)\
COURSE(CourseID, CourseName, Credits)\
JOB-ASSIGNMENTS(InstructorID, CourseID, JobTitle, StartDate, EndDate)

Two query trees are given.

Identify the correct statement for the above two query trees.

a) Two query trees are equivalent, and the query tree of Figure 2 will lead to more efficient query processing.\
b) Two query trees are equivalent, and the query tree of Figure 1 will lead to more efficient query processing.\
c) Two query trees are equivalent, as identical operations (irrespective of their positions) are used in both trees.\
d) Two query trees are not equivalent as selection or projection operation cannot be carried out before or after the natural join operation.

[View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

**5) Assume deferred database modification scheme. Consider the following log records for transactions T1, T2, T3, and T4:**

If there is a crash just after step 10 and the recovery of the system is successfully completed, identify the correct action(s) for the above scenario.

a) After recovery completion, the value of B is 400.\
b) After recovery completion, the value of C is 300.\
c) Redo list contains transactions {T1, T2} and undo list contains {T3, T4}.\
d) Redo list contains transactions {T1, T2} and undo list contains {T3}.

[****See also**  **Data Base Management System | Week 1****](https://progiez.com/data-base-management-system-week-1-assignment-answers)

[View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

**6) Consider the following state of transactions and the statements below.**

T4, Checkpoint 1, Checkpoint 2, System Failure.

1. T1, T2, and T3 can be ignored.
2. T5 and T6 need to be undone.
3. T1 and T2 can be ignored.
4. T3, T4, and T5 need to be redone.
5. T3 and T4 need to be redone.

Identify the correct group of statements.

a)\
b)\
c)\
d)

[View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

**7) Consider the following relational schema:**

INSTRUCTOR(InstructorID, Name)\
COURSE(CourseID, CourseName, Credits)\
JOB-ASSIGNMENTS(InstructorID, CourseID, JobTitle, StartDate, EndDate)

Four relational algebra queries are given below:

Q1: σ(INSTRUCTOR × JOB-ASSIGNMENTS)\
Q2: πStartDate, Name(INSTRUCTOR × JOB-ASSIGNMENTS)\
Q3: πName(INSTRUCTOR × JOB-ASSIGNMENTS)\
Q4: σ(INSTRUCTOR.InstructorID = JOB-ASSIGNMENTS.InstructorID) (INSTRUCTOR × JOB-ASSIGNMENTS)

Identify the correct options.

a) Q1 is equivalent to Q2.\
b) Q1 is not equivalent to Q2.\
c) Q3 is equivalent to Q4.\
d) Q3 is not equivalent to Q4.

[View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

**8) Consider the following relational algebra expression:**

πName(σInstructorID, Name(INSTRUCTOR × JOB-ASSIGNMENTS × COURSE))

Identify the most optimized relational algebra expression equivalent to the above.

a)\
b)\
c)\
d)

[View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

**9) Consider the following two relational algebra expressions (RA) given below:**

RA I: ((P × Q) × R) ≡ (P × (Q × R))\
where P, Q, and R are relational algebra expressions.

Identify the correct statement(s).

a) Both RA I and RA II are true.\
b) Both RA I and RA II are false.\
c) RA I is true but RA II is false.\
d) RA I is false but RA II is true.

[View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)

***

**10) Consider the log record of Transaction T1 with two operation instances O1 and O2 used in a recovery system with early lock release and B+ tree-based concurrency control.**

[****See also**  **Nptel Database Management System Assignment 6 Answers****](https://progiez.com/nptel-database-management-system-assignment-6-answers)

Steps:

1. (T1, start)
2. (T1, x, 200, 400)
3. (O1, operation begin)
4. (T1, Y, 100, 500)
5. (O1, operation-end, (Y, -400))
6. (O2, operation begin)
7. (T1, Z, 500, 800)
8. Crash or abort here

Choose the correct set of log entries for the recovery of transactions.

a) (T1, Y, 100) (T1, O1, operation-abort) (T1, abort)\
b) (T1, Y, 500, 100) (T1, O1, operation-abort) (T1, abort)\
c) (T1, Y, 500) (T1, O1, operation-abort) (T1, abort)\
d) (T1, Y, 500, 100) (T1, O1, operation-abort) (T1, abort)

[View Answer](https://my.progiez.com/courses/data-base-management-system-nptel-answers/)
