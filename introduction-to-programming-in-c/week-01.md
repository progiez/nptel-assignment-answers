# NPTEL Introduction to programming in C Week 01 Assignment Answers

Are you looking for NPTEL Introduction to programming in C Week 01 Assignment Answers? This repository will help you find your answers and solutions for Week 01 of the Introduction to programming in C course. We provide detailed solutions to help you complete your assignments efficiently.



## Introduction to programming in C Nptel Week 1 Answers (July-Dec 2025)

***

**Question 1.** **Given three distinct integers a, b, and c, write a C program to find the second largest number among them.**

Input:\
Three distinct integers a b c.

Output:\
The second largest among a, b, and c.

_Note:_ The assignment evaluation is automated. Do not print anything other than the output value.

**Sample Input:**

    2 3 1

**Sample Output:**

    2

[View Answer](https://my.progiez.com/courses/introduction-to-programming-in-c-nptel-answers/)

***

**Question 2.** **Write a C program to convert a length given in centimeters into feet and inches.**

Use the following conversions:\
1 inch = 2.54 cm\
1 foot = 12 inches\
1 foot = 30.48 cm

Input:\
A non-negative integer, the value of the length in cm.

Output:\
Output the length in feet followed by a space followed by the remaining length in inches (truncated to 2 decimal places).

_Note:_ Do not change the given input/output handling in the template.

**Sample Input:**

    170

**Sample Output:**

    5 6.93

[View Answer](https://my.progiez.com/courses/introduction-to-programming-in-c-nptel-answers/)

***

**Question 3.** **Write a C program to compute the area of a rectangle.**

Use the formula:

    Area = Length × Breadth

Input:\
Two non-negative integers, the values of the length and breadth of the rectangle.

Output:\
Output the area of the rectangle as a single integer.

**Sample Input:**

    5 7

**Sample Output:**

    35

[View Answer](https://my.progiez.com/courses/introduction-to-programming-in-c-nptel-answers/)

***


## Introduction to programming in C Nptel Week 1 Answers (Jan-Apr 2024)

**Course Name: Introduction to Programming in C**

**Course Link: [**Click Here**](https://onlinecourses.nptel.ac.in/noc24_cs02/preview)**

**_**For answers or latest updates join our telegram channel: [**Click here to join**](https://telegram.me/nptel_assignments)**_**

**_**These are Introduction to programming in C Nptel Week 1 Answers**_**

***

**Question 1**\
**Problem Statement**

**You have a certain number of 100 rupee notes, 10 rupee notes and 1 rupee notes with you.\
There is an item you want to buy whose price is given to you.\
Write a program to find if the item is affordable, that is the price of the item is _**less than or equal to**_ the current money you have**

[****See also**  **Deep Learning Week 1 Assignment Answers Nptel****](https://progiez.com/nptel-deep-learning-week-1-assignment-answers)

**Input\
Four non negative integers. \
The first input is an integer representing the number of 100 rupee notes.\
The second input is an integer representing the number of 10 rupee notes.\
The third input is an integer representing the number of 1 rupee notes.\
The fourth input is an integer representing the price of the item.\
Output\
You have to output 1 if the item is affordable.\
You have to output 0 if the item is not affordable.** 

**Solution:**

    #include <stdio.h>

    int is_affordable(int hundred_notes, int ten_notes, int one_notes, int item_price) {
        int total_money = (hundred_notes * 100) + (ten_notes * 10) + one_notes;
        return (total_money >= item_price) ? 1 : 0;
    }

    int main() {
        int hundred_notes, ten_notes, one_notes, item_price;

        scanf("%d", &hundred_notes);
        scanf("%d", &ten_notes);
        scanf("%d", &one_notes);
        scanf("%d", &item_price);

        int result = is_affordable(hundred_notes, ten_notes, one_notes, item_price);
        printf("%d", result);

        return 0;
    }

***

**_**For answers or latest updates join our telegram channel: [**Click here to join**](https://telegram.me/nptel_assignments)**_**

**_**These are Introduction to programming in C Nptel Week 1 Answers**_**

***

**Question 2**\
**Problem Statement**

**Given three distinct integers a b and c, write a C program to find the second largest number among them.\
Input\
Three distinct integers a b c.\
The first input is the integer a.\
The second input is the integer b.\
The third input is is the integer c.\
Output\
The second largest among a, b and c**

**Solution:**

    #include <stdio.h>

    int main() {
        int a, b, c;

        scanf("%d", &a);
        scanf("%d", &b);
        scanf("%d", &c);

        int second_largest;
        
        if ((a > b && a < c) || (a < b && a > c)) {
            second_largest = a;
        } else if ((b > a && b < c) || (b < a && b > c)) {
            second_largest = b;
        } else {
            second_largest = c;
        }

        printf("%d", second_largest);

        return 0;
    }

***

**_**For answers or latest updates join our telegram channel: [**Click here to join**](https://telegram.me/nptel_assignments)**_**

[****See also**  **Business Intelligence & Analytics Week 1 Nptel Answers****](https://progiez.com/nptel-business-intelligence-analytics-week-1-answers)

**_**These are Introduction to Programming in C Assignment 1 Answers**_**

***

**Question 3**\
**Problem Statement**

**Given the coefficients of a pair of linear equations,\
a1x+b1y=c1\
a2x+b2y=c2\
Find the solutions to x and y\
Input\
Input consists two lines.\
The first line contains coefficients of first equation, a1 b1 c1 in that order.\
The second line contains coefficients of second equation, a2 b2 c2 in that order.\
Output\
The solutions to x and y.**

**Solution:**

    #include <stdio.h>

    int main() {
        int a1, b1, c1;
        int a2, b2, c2;

        scanf("%d %d %d", &a1, &b1, &c1);
        scanf("%d %d %d", &a2, &b2, &c2);
        int det = a1 * b2 - a2 * b1;

        if (det == 0) {
            printf("The system of equations has no unique solution.\n");
        } else {
            int x = (int)(c1 * b2 - c2 * b1) / det;
            int y = (int)(a1 * c2 - a2 * c1) / det;
            printf("%d %d", x, y);
        }

        return 0;
    }

***

**_**For answers or latest updates join our telegram channel: [**Click here to join**](https://telegram.me/nptel_assignments)**_**

**_**These are Introduction to Programming in C Assignment 1 Answers**_**

More Solutions of Introduction to Programming in C: [Click Here](https://progiez.com/nptel-assignment-answers/nptel-c)

More NPTEL Solutions: <https://progiez.com/nptel-assignment-answers/>

***


## Introduction to programming in C Nptel Week 1 Answers (Jan-Apr 2023)

**Course Name: Introduction to Programming in C**

**Course Link: [**Click Here**](https://onlinecourses.nptel.ac.in/noc23_cs02/course)**

**_**These are Introduction to Programming in C Assignment 1 Answers**_**

***

**Question 1**

You have a certain number of 100 rupee notes, 10 rupee notes and 1 rupee notes with you.\
There is an item you want to buy whose price is given to you.\
Write a program to find if the item is affordable, that is the price of the item is less than or equal to the current money you have.

**Input\
—–\
Four non-negative integers. \
The first input is an integer representing the number of 100 rupee notes.\
The second input is an integer representing the number of 10 rupee notes.\
The third input is an integer representing the number of 1 rupee notes.\
The fourth input is an integer representing the price of the item.\
Output\
——\
You have to output 1 if the item is affordable.\
You have to output 0 if the item is not affordable.** 

[****See also**  **Introduction to Programming in C Week 2****](https://progiez.com/introduction-to-programming-in-c-assignment-2-answers)

**_**These are Introduction to programming in C Nptel Week 1 Answers**_**

**Solution:**

    //Code

***

**_**These are Introduction to programming in C Nptel Week 1 Answers**_**

***

**Question 2**

**You are given two positive integers, say M and N.\
Check whether M is an exact multiple of N, without using loops.\
Input\
—–\
Two positive integers, say M and N.\
Output\
——\
You have to output 0 if M is not a multiple of N.\
You have to output 1 if M is a multiple of N.**

**Solution:**

    //Code

***

**_**These are Introduction to programming in C Nptel Week 1 Answers**_**

***

**Question 3**

**Given three integers a b and c, find if they are strictly increasing/decreasing or not.\
Input\
——-\
Triplet of three integers (a,b,c)\
Output\
———\
You have to output 1 if they are either in strictly increasing (a>b>c) or decreasing (a\<b\<c) order.\
Output 0, otherwise.**

**Solution:**

    //Code
