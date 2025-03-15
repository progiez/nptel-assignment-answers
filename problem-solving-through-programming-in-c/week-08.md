# NPTEL Problem Solving Through Programming In C Week 08 Assignment Answers

Are you looking for NPTEL Problem Solving Through Programming In C Week 08 Assignment Answers? This repository will help you find your answers and solutions for Week 08 of the Problem Solving Through Programming In C course. We provide detailed solutions to help you complete your assignments efficiently.

## _Problem Solving Through Programming In C Assignment 8_ _(Jan-Apr 2025)_

**Course Link**:[ Click Here](https://onlinecourses.nptel.ac.in/noc25_cs56/course)

***

1\) **A function prototype is used for**\
a) Declaring the function logic\
b) Calling the function from the main body\
c) Telling the compiler, the kind of arguments used in the function\
d) Telling the user for proper use of syntax while calling the function

[View Answer](https://my.progiez.com/courses/problem-solving-through-programming-in-c/)

***

2\) **What is the output of the following C program?**

       #include <stdio.h>
       void foo(), f();
       int main() 
       return 0;
       void foo() 
       printf("2 ");  
       void f() 
       printf("1 ");  
       foo();  

a) Compiler error as foo() is not declared in main\
b) 12\
c) 21\
d)Compile time error due to declaration of functions inside main

[View Answer](https://my.progiez.com/courses/problem-solving-through-programming-in-c/)

***

3\) **How many times ‘Hi’ will be printed in the program given below**

       #include<stdio.h>
       int i;
       int fun();
       int main() 
       while(i)
       main();  
       printf("Hello\n");  
       return 0;  
       int fun()  
       printf("Hi");

a) Only once\
b) Zero times\
c) Infinite times\
d) Compilation error

[View Answer](https://my.progiez.com/courses/problem-solving-through-programming-in-c/)

***

**_**Problem Solving Through Programming In C Assignment 8**_**

***

4\) **What is the output of the C code given below**

       #include <stdio.h>
       float func(float age[]);  
       int main() 
       float result, age[] = {23.4, 55, 22.6, 3, 40.5, 18};  
       result = func(age);  
       printf("%0.2f", result);  
       return 0;  
       float func(float age[])  
       int i;  
       float result, sum = 0.0;  
       for (i = 0; i < 6; i++) {  
           sum += age[i];  
           result = (sum / 6);  
       }  
       return result;

a) 27.08\
b) 27.083334\
c) Compiler error as result is declared twice\
d) Error: Invalid prototype declaration

[****See also**  **Problem Solving Through Programming In C Nptel Week 3 Assignment Answers****](https://progiez.com/problem-solving-through-programming-in-c-week-3-answers)

[View Answer](https://my.progiez.com/courses/problem-solving-through-programming-in-c/)

***

5\) **Which statement is correct about Passing by value parameters?**\
a) It cannot change the actual parameter value\
b) It can change the actual parameter value\
c) Parameter is always in read-write mode\
d) None of them

[View Answer](https://my.progiez.com/courses/problem-solving-through-programming-in-c/)

***

6\) **What will be the output?**

       int main()  
       int a = 70;  
       printf("%d", a);  
       return 0;

a) 70\
b) Garbage value\
c) Compilation error\
d) None

[View Answer](https://my.progiez.com/courses/problem-solving-through-programming-in-c/)

***

7\) **How many times Hello world will be printed?**

       #include<stdio.h>
       int main()  
       printf("Hello world\n");  
       return 0;  

a) Infinite times\
b) 32767\
c) 65535\
d) Till stack overflows

[View Answer](https://my.progiez.com/courses/problem-solving-through-programming-in-c/)

***

**_**Problem Solving Through Programming In C Assignment 8**_**

***

8\) **What will be the output?**

       #include<stdio.h>
       void func(int n, int sum)  
       int k = 0, j = 0;  
       if (n == 0) return;  
       j = n / 10;  
       sum = sum + k;  
       func(j, sum);  
       printf("%d, ", k);  
       int main()  
       int a = 2048, sum = 0;  
       func(a, sum);  
       printf("%d ", sum);  
       return 0;

a) 8, 4, 0, 2, 14\
b) 8, 4, 0, 2, 0\
c)2, 0, 4, 8, 14\
d) 2, 0, 4, 8, 0

[View Answer](https://my.progiez.com/courses/problem-solving-through-programming-in-c/)

***

****_**These are Problem Solving Through Programming In C Assignment**_**** _8_

***

9\) **Consider the function**

       find(int x, int y)  
       return((x < y) ? 0 : (x - y));  

Let a and b be two non-negative integers. The call find(a, find(a, b)) can be used to find the\
a) Maximum of a, b\
b) Positive difference between a and b\
c) Sum of a and b\
d) Minimum of a and b

[View Answer](https://my.progiez.com/courses/problem-solving-through-programming-in-c/)

***

10\) **Consider the function**

       int fun(int x)  
       if (x > 100)  
       then fun(x - 10);  
       else  
       return x;  

For the input x = 95, the function will return\
a) 89\
b) 90\
c) 91\
d) 92

[****See also**  **Problem Solving Through Programming In C Week 8****](https://progiez.com/problem-solving-through-programming-in-c-assignment-8)

[View Answer](https://my.progiez.com/courses/problem-solving-through-programming-in-c/)
