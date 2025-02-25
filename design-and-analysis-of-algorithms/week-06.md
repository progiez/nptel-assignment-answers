# NPTEL Design and Analysis of Algorithms Week 06 Assignment Answers

Are you looking for NPTEL Design and Analysis of Algorithms Week 06 Assignment Answers? This repository will help you find your answers and solutions for Week 06 of the Design and Analysis of Algorithms course. We provide detailed solutions to help you complete your assignments efficiently.

## Design and analysis of algorithms Week 6 Quiz Answers (Jan-Apr 2025)

Course link: [**Click here**](https://onlinecourses.nptel.ac.in/noc25_cs23/course)

***

1. **Suppose we implement a binary search tree without a parent pointer in each node. So each node has a value and pointers to the left and right children. What would be the complexity of computing the successor for a node in such an implementation for a balanced search tree on n nodes?**\
   a. O(n) for all nodes\
   b. O(log n) for all nodes\
   c. O(log n) for a node with a right child, O(n) otherwise\
   d. O(log n) for a node with a right child, O(n log n) otherwise

[View Answer](https://my.progiez.com/courses/design-and-analysis-of-algorithms-answers/)

***

2. **We have n distinct values stored in a height-balanced (AVL) binary search tree. Which of the following statements is always true?**\
   a. The value at each node is the median of the values in the subtree rooted at that node.\
   b. The shortest path between any pair of nodes is at most O(log n).\
   c. For any node, the difference between the size of the left subtree and the right subtree is at most 3.\
   d. The number of leaf nodes is greater than or equal to the number of internal nodes.

[View Answer](https://my.progiez.com/courses/design-and-analysis-of-algorithms-answers/)

***

3. **The postorder traversal of a binary search tree with integer values produces the following sequence: 17, 28, 25, 51, 98, 55, 42, 37. What is the value of the left child of the root of the tree?**\
   a. 37\
   b. 28\
   c. 25\
   d. 17

[****See also**  **Cloud Computing Nptel Week 6 Assignment Answers****](https://progiez.com/cloud-computing-nptel-week-6-assignment-answers)

[View Answer](https://my.progiez.com/courses/design-and-analysis-of-algorithms-answers/)

***

4. **Consider the following function to traverse a search tree t with integer values, where prime(m) returns True if m is an even number and False otherwise.**

<!---->

    function strangeOrder(t) {
      if (t != NIL) {    
        if (prime(t.value)){
          strangeOrder(t.left);
          print(t.value);
          strangeOrder(t.right);
        }else{
          strangeOrder(t.right);
          print(t.value);
          strangeOrder(t.left);
        }
      }
    }

**What is the complexity of this traversal for a binary search tree with n nodes?**\
a. O(n) whether the tree is balanced or unbalanced.\
b. O(n log n) whether the tree is balanced or unbalanced.\
c. O(log n) if the tree is balanced, O(n) otherwise.\
d. O(n) if the tree is balanced, O(n log n) otherwise.

[View Answer](https://my.progiez.com/courses/design-and-analysis-of-algorithms-answers/)

***

_Design and analysis of algorithms Week 6 Quiz Answers_

***

5. **Suppose we build a Huffman code over the four-letter alphabet {a, b, c, d}, where f(a), f(b), f(c), and f(d) denote the frequencies (probabilities) of the letters and f(a) > f(b) > f(c) > f(d). Which of the following conditions will result in a Huffman code assigning a 2-bit code for each letter?**\
   a. f(a) > f(c) + f(d)\
   b. f(b) > f(c) + f(d)\
   c. f(a) > f(b) + f(c) + f(d)\
   d. It is not possible to have a Huffman code that assigns two bits to each letter.

[View Answer](https://my.progiez.com/courses/design-and-analysis-of-algorithms-answers/)
