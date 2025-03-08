# NPTEL Programming DSA Using Python Week 07 Assignment Answers

Are you looking for NPTEL Programming DSA Using Python Week 07 Assignment Answers? This repository will help you find your answers and solutions for Week 07 of the Programming DSA Using Python course. We provide detailed solutions to help you complete your assignments efficiently.

## _Programming Data Structure And Algorithms Assignment 7 Answers (Jan -Apr 2025)_

**Course Link: [**Click Here**](https://onlinecourses.nptel.ac.in/noc25_cs59/course)**

***

**1) Given the following permutation of a, b, c, d, e, f, g, h, i, j, what is the previous permutation in lexicographic (dictionary) order? Write your answer without any blank spaces between letters.**

ghadbicefj

[View Answer](https://my.progiez.com/courses/programming-data-structures-and-algorithms-using-python-nptel-answers/)

***

\*\*2) We want to add a function listmin() to the class Node that implements user-defined lists such that listmin() computes the minimum value in a list of values of type int.

An incomplete implementation of listmin() is given below. You have to provide expressions to put in place of AAA, BBB, and CCC.\*\*

    def listmin(self):
        if self.value == None:
            return(AAA)
        elif self.next == None:
            return(BBB)
        else:
            return(CCC)

a) AAA: 0, BBB: self.value, CCC: min(self.value, self.next.listmin())\
b) AAA: 0, BBB: self.value, CCC: min(self.value, self.next.value)\
c) AAA: None, BBB: self.value, CCC: min(self.value, self.next.listmin())\
d) AAA: None, BBB: self.value, CCC: min(self.value, self.next.value)

[View Answer](https://my.progiez.com/courses/programming-data-structures-and-algorithms-using-python-nptel-answers/)

***

**3) Suppose we add this function foo() to the class Tree that implements search trees. For a name mytree with a value of type Tree, what would mytree.foo() compute?**

    def foo(self):
        if self.isempty():
            return(0)
        elif self.isleaf():
            return(1)
        else:
            return(self.left.foo() + self.right.foo())

a) The sum of the elements in the tree\
b) The maximum sum across all root to leaf paths in the tree\
c) The length of the longest root to leaf path in the tree\
d) The number of root to leaf paths in the tree

[View Answer](https://my.progiez.com/courses/programming-data-structures-and-algorithms-using-python-nptel-answers/)

***

**4) The postorder traversal of a binary search tree with integer values produces the following sequence: 22, 38, 28, 49, 48, 58, 61, 52, 45. What is the value of the left child of the root of the tree?**

a) 22\
b) 28\
c) 38\
d) 52

[View Answer](https://my.progiez.com/courses/programming-data-structures-and-algorithms-using-python-nptel-answers/)

***

**Course Name: Programming Data Structure And Algorithms Using Python**

**Course Link: [**Click Here**](https://onlinecourses.nptel.ac.in/noc23_cs95/announcements?force=true)**


## _Programming Data Structure And Algorithms Assignment 7 Answers (JULY-DEC 2023)_

***

**Q1. Given the following permutation of a,b,c,d,e,f,g,h,i,j, what is the next permutation in lexicographic (dictionary) order? Write your answer as a sequence of letters without quotes and without any blank spaces between letters.\
eibjdhgfca**

[****See also**  **Programming DSA using Python Nptel Week 3 Assignment Answers****](https://progiez.com/programming-data-structure-and-algorithms-assignment-3)

Answer:\
(Type: Regex Match): eibjfacdgh\
(Type: Regex Match): ‘eibjfacdgh’\
(Type: Regex Match): “eibjfacdgh”

***

**Q2. We want to add a function listmax() to the class Node that implements user defined lists such that listmax() computes the maximum value in a list where values are of type int.\
An incomplete implementation of listmax() given below. You have to provide expressions to put in place of AAA, BBB and CCC.\
def listmax(self):\
if self.value == None:\
return(AAA)\
elif self.next == None:\
return(BBB)\
else:\
return(CCC)**\
AAA: 0, BBB: self.value, CCC: max(self.value, self.next.listmax())\
AAA: 0, BBB: self.value, CCC: max(self.value, self.next.value)\
AAA: None, BBB: self.value, CCC: max(self.value, self.next.listmax())\
AAA: None, BBB: self.value, CCC: max(self.value, self.next.value)

**Answer: AAA: None, BBB: self.value, CCC: max(self.value, self.next.listmax())**

***

****_**These are Programming Data Structure And Algorithms Assignment 7 Answers**_****

***

**Q3. Suppose we add this function foo() to the class Tree that implements search trees. For a name mytree with a value of type Tree, what would mytree.foo() compute?\
def foo(self):\
if self.isempty():\
return(0)\
elif self.isleaf():\
return(1)\
else:\
return(self.left.foo() + self.right.foo())**\
The number of nodes in mytree\
The largest value in mytree.\
The length of the longest path from root to leaf in mytree.\
The number of leaves in mytree.

**Answer: The number of leaves in mytree.**

***

**Q4. Inorder traversal of a binary tree has been defined in the lectures. A postorder traversal lists the vertices of a binary tree (not necessarily a search tree) as follows:\
Print the left subtree in postorder.\
Print the right subtree in postorder.\
Print the root.\
Suppose we have a binary tree with 10 nodes labelled a, b, c, d, e, f, g, h, i, j, with postorder traversal ehicbjfadg and inorder traversal ehbicgjafd. What is the left child of the root node? (Write your answer as a single letter, without quotes.)**

Answer:\
(Type: Regex Match): b\
(Type: Regex Match): ‘b’\
(Type: Regex Match): “b”

***

****_**These are Programming Data Structure And Algorithms Assignment 7 Answers**_****

****_****_****
