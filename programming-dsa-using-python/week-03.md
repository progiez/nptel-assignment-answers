# NPTEL Programming DSA Using Python Week 03 Assignment Answers

Are you looking for NPTEL Programming DSA Using Python Week 03 Assignment Answers? This repository will help you find your answers and solutions for Week 03 of the Programming DSA Using Python course. We provide detailed solutions to help you complete your assignments efficiently.

## Programming Data Structures and Algorithms using Python (Jan-Apr 2025)

***

**Q1. Removing Duplicates (Keeping Last Occurrence)**

Define a Python function **remdup(l)** that removes all duplicates in `l`, keeping only the last occurrence of each number.

**Example:**

    >>> remdup([3,1,3,5])
    [1, 3, 5]

    >>> remdup([7,3,-1,-5])
    [7, 3, -1, -5]

    >>> remdup([3,5,7,5,3,7,10])
    [5, 3, 7, 10]

[**View Answer**](https://my.progiez.com/courses/programming-data-structures-and-algorithms-using-python-nptel-answers/)

***

**Q2. Splitting Sum of Squares and Cubes**

Write a Python function **splitsum(l)** that returns `[pos, neg]`, where `pos` is the sum of squares of all positive numbers in `l`, and `neg` is the sum of cubes of all negative numbers in `l`.

**Example:**

    >>> splitsum([1,3,-5])
    [10, -125]

    >>> splitsum([2,4,6])
    [56, 0]

    >>> splitsum([-19,-7,-6,0])
    [0, -7418]

    >>> splitsum([-1,2,3,-7])
    [13, -344]

[**View Answer**](https://my.progiez.com/courses/programming-data-structures-and-algorithms-using-python-nptel-answers/)

***

**Q3. Matrix Flip (Horizontal & Vertical)**

Write a Python function **matrixflip(m, d)** that flips a given **2D matrix** horizontally (`'h'`) or vertically (`'v'`). If `d` is invalid, return the matrix unchanged.

**Example:**

    >>> myl = [[1,2],[3,4]]

    >>> myl
    [[1, 2], [3, 4]]  

    >>> matrixflip(myl,'h')
    [[2, 1], [4, 3]]

    >>> myl
    [[1, 2], [3, 4]]  

    >>> matrixflip(myl,'v')
    [[3, 4], [1, 2]]  

    >>> myl
    [[1, 2], [3, 4]]  

    >>> matrixflip(matrixflip(myl,'h'),'v')
    [[4, 3], [2, 1]]

    >>> myl
    [[1, 2], [3, 4]]  

    >>> matrixflip(matrixflip(myl,'h'),'v')
    [[4, 3], [2, 1]]

    >>> myl
    [[1, 2], [3, 4]]  

[**View Answer**](https://my.progiez.com/courses/programming-data-structures-and-algorithms-using-python-nptel-answers/)

***

****Session: JAN-APR 2023****

**Course Name: Programming Data Structure And Algorithms Using Python**

**Course Link: [**Click Here**](https://onlinecourses.nptel.ac.in/noc23_cs15/course)**

****_**These are Programming Data Structure And Algorithms Assignment 3 Answers**_****

**Question 1**

Write three Python functions as specified below. Paste the text for all three functions together into the submission window. Your function will be called automatically with various inputs and should return values as specified. Do not write commands to read any input or print any output.\
You may define additional auxiliary functions as needed.

****_**These are Programming Data Structure And Algorithms Assignment 3 Answers**_****

In all cases you may assume that the value passed to the function is of the expected type, so your function does not have to check for malformed inputs.\
For each function, there are normally some public test cases and some (hidden) private test cases.\
“Compile and run” will evaluate your submission against the public test cases.

“Submit” will evaluate your submission against the hidden private test cases. There are 12 private test cases, with equal weightage. You will get feedback about which private test cases pass or fail, though you cannot see the actual test cases.\
Ignore warnings about “Presentation errors”.

[****See also**  **All About NPTEL****](https://progiez.com/nptel)

****_**These are Programming Data Structure And Algorithms Assignment 3 Answers**_****

1\. Define a Python function remdup(l) that takes a nonempty list of integers l and removes all duplicates in l, keeping only the **last** occurrence of each number. For instance:\
2\. Write a Python function splitsum(l) that takes a nonempty list of integers and returns a list \[pos,neg], where pos is the sum of squares all the positive numbers in l and neg is the sum of cubes of all the negative numbers in l.\
Here are some examples to show how your function should work.\
3\. A two dimensional matrix can be represented in Python row-wise, as a list of lists: each inner list represents one row of the matrix. For instance, the matrix would be represented as \[\[1, 2, 3], \[4, 5, 6], \[7, 8, 9]].

****_**These are Programming Data Structure And Algorithms Assignment 3 Answers**_****

A horizonatal flip reflects each row. For instance, if we flip the previous matrix horizontally, we get which would be represented as \[\[3, 2, 1], \[6, 5, 4], \[9, 8, 7]].\
A vertical flip reflects each column. For instance, if we flip the previous matrix that has already been flipped horizontally, we get which would be represented as \[\[9, 8, 7], \[6, 5, 4], \[3, 2, 1]].

Write a Python function matrixflip(m,d) that takes as input a two dimensional matrix m and a direction d, where d is either ‘h’ or ‘v’. If d == ‘h’, the function should return the matrix flipped horizontally. If d == ‘v’, the function should retun the matrix flipped vertically. For any other value of d, the function should return m unchanged. In all cases, the argument m should remain undisturbed by the function.\
Here are some examples to show how your function should work. You may assume that the input to the function is always a non-empty matrix.

**Solution:**

    ####

    def remdup(l):
        if len(l) <= 1:
            return(l)

        if l[0] in l[1:]:
            return(remdup(l[1:]))
        else:
            return([l[0]] + remdup(l[1:]))

    ####

    def splitsum(l):
        pos = 0
        neg = 0
        for x in l:
            if x > 0:
                pos = pos + x**2
            if x < 0:
                neg = neg + x**3
        return([pos,neg])

    ####

    def matrixflip(l,d):
      outl = []
      for row in l:
        outl.append(row[:])
      if d == 'h':
        for row in outl:
          row.reverse()
      elif d == 'v':
        outl.reverse()
      return(outl)

    ####

    import ast

    def tolist(inp):
      inp = "["+inp+"]"
      inp = ast.literal_eval(inp)
      return (inp[0],inp[1])

    def parse(inp):
      inp = ast.literal_eval(inp)
      return (inp)

    fncall = input()
    lparen = fncall.find("(")
    rparen = fncall.rfind(")")
    fname = fncall[:lparen]
    farg = fncall[lparen+1:rparen]

    if fname == "remdup":
       arg = parse(farg)
       print(remdup(arg))
    elif fname == "splitsum":
       arg = parse(farg)
       print(splitsum(arg))
    elif fname == "matrixflip":
      (arg1,arg2) = parse(farg)
      savearg1 = []
      for row in arg1:
        savearg1.append(row[:])
      myans = matrixflip(arg1,arg2)
      if savearg1 == arg1:
        print(myans)
      else:
        print("Illegal side effect")
    else:
       print("Function", fname, "unknown")

***
