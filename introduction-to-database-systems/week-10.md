# NPTEL Introduction to Database Systems Week 10 Assignment Answers

Are you looking for NPTEL Introduction to Database Systems Week 10 Assignment Answers? This repository will help you find your answers and solutions for Week 10 of the **Introduction to Database Systems** course. We provide detailed solutions to help you complete your assignments efficiently.

## Introduction to Database Systems Week 10 Quiz Answers (Jan-Apr 2025)

**Course Link: [**Click Here**](https://onlinecourses.nptel.ac.in/noc25_cs40/course)**

***

1. **Consider a B+ tree in which the maximum number of keys in an internal node is 5. What is the minimum number of keys in any non-root internal node?** a) 1\
   b) 2\
   c) 3\
   d) 4\
   \
   [View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

2. **For the B+ tree given above, the minimum number of nodes of the tree (including the root node) that must be fetched in order to obtain the result of the following query: “Get all records with a search key greater than or equal to 14 and less than or equal to 20” is** a) 4\
   b) 5\
   c) 6\
   d) 7\
   \
   [View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

3. **Consider the B+ tree given in Question 2 with order = 3 and orderleaf = 2. If we insert the element 15, the number of internal nodes and leaf nodes in the resulting tree, respectively, are** a) 4, 6\
   b) 4, 7\
   c) 5, 6\
   d) 5, 7\
   \
   [View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

Introduction to Database Systems Week 10 Quiz Answers

***

4. **The details of a RAID-4 (Block-level striping; dedicated parity disk) storage system are as follows: Number of data disks = 6; Number of parity disks = 1. Assume that the disks have a lot of empty space. Suppose, RAID-5 (Block-level striping; distributed parity) is used, instead of RAID-4, to implement the above storage system, the number of disks on which data is stored is** a) 7\
   b) 8\
   c) 13\
   d) 14\
   \
   [View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

[****See also**  **AI in Marketing Nptel Week 10 Assignment Answers****](https://progiez.com/ai-in-marketing-nptel-week-10-assignment-answers)

***

5. **To store huge data, the implementation of which of the following RAID levels requires the largest number of disks?** a) RAID-6 (Block-level striping; double distributed parity)\
   b) RAID-4 (Block-level striping; dedicated parity disk)\
   c) RAID-2 (Bit-level striping; Redundancy using Hamming codes)\
   d) RAID-1 (Mirrored disks; No parity; No data striping)\
   \
   [View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

6. **The number of block accesses during the sort phase is** a) 18\
   b) 228\
   c) 2048\
   d) 4096\
   \
   [View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

Introduction to Database Systems Week 10 Quiz Answers

***

7. **The number of block accesses during the merge phase is** a) 228\
   b) 8192\
   c) 12288\
   d) 16384\
   \
   [View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

8. **The following relation is used to store the details of the students studying in an engineering college: Student(rollNo, name, sex). Consider the following predicates.**

- P1: rollNo = ‘CS17B038’
- P2: name = ‘Suresh’ (Assume that there are at least two people in the college with the name ‘Suresh’)
- P3: sex = ‘Male’ **Let c1, c2, and c3 denote the selectivity of P1, P2, and P3, respectively. Under normal conditions, the relation among c1, c2, and c3 is** a) c1 < c2 < c3 b) c1 < c2 > c3\
  c) c1 < c2 = c3\
  d) c3 < c2 < c1\
  \
  [View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

9. **Consider two data files R and S with b1 and b2 blocks stored on two disks with half blocks on each disk to support parallel access. To perform a Nested loop join on the two files using the algorithm given below, m memory buffers are available (assume that m is an odd number). Two buffers are used for the inner file (one block from each disk), one for the result, and the rest of the buffers are equally divided for the outer file from both the disks. Let the time taken to access a block be t.**

<!---->

       for each record x,y in R do // x is from disk 1 and y is from disk 2
           for each record u,v in S do // u is from disk 1 and v is from disk 2
               check if x, u join .. .
               check if x, v join .. .
               check if y, u join .. .
               check if y, v join .. .

**The number of times all the blocks of the inner file are accessed is**

[****See also**  **Entrepreneurship Essentials Nptel Week 10 Quiz Answers****](https://progiez.com/entrepreneurship-essentials-nptel-week-10-quiz-answers)

a) ceil( b1 / (m – 3) )\
b) ceil( b1 / (2 \* (m – 3)) )\
c) ceil( b1 / (4 \* (m – 3)) )\
d) ceil( b1 / (2 \* (m – 2)) )

[View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)

***

Introduction to Database Systems Week 10 Quiz Answers

***

10. **Using the information in Question 9, the total amount of time taken for the nested loop join operation, excluding the time taken to write the result, is** a) ( (b1 / 2) + ceil( b1 / (m-3) ) \* (b2 / 2) ) \* t\
    b) ( (b1 / 2) + ceil( b1 / (2 \* (m-3)) ) \* (b2 / 2) ) \* t\
    c) ( (b1) + ceil( b1 / (m-3) ) \* b2 ) \* t\
    d) ( (b1 / 2) + ceil( b1 / (m-3) ) \* b2 ) \* t\
    \
    [View Answer](https://my.progiez.com/courses/introduction-to-database-systems-answers/)
