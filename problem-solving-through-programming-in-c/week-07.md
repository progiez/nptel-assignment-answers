# NPTEL Problem Solving Through Programming In C Week 07 Assignment Answers

Are you looking for NPTEL Problem Solving Through Programming In C Week 07 Assignment Answers? This repository will help you find your answers and solutions for Week 07 of the Problem Solving Through Programming In C course. We provide detailed solutions to help you complete your assignments efficiently.

## Problem Solving Through Programming In C Week 7 Answers (Jan-Apr 2025)

***

**Que. 1**\
Which of the following statements are correct?

1. A string is a collection of characters terminated by ‘\0’.
2. The format specifier `%s` is used to print a string.
3. The length of the string can be obtained by using the function `strlen()`.
4. The pointer cannot work on string.

a) 1,2\
b) 1,2,3\
c) 2,4\
d) 1,3

[View Answer](https://my.progiez.com/courses/problem-solving-through-programming-in-c/)

***

**Que. 2**\
The correct method of initializing a 2D array is:

    int abc[2][2] = {1, 2, 3, 4};
    int abc[][] = {1, 2, 3, 4};
    int abc[2][] = {1, 2, 3, 4};

a) All of the above

[View Answer](https://my.progiez.com/courses/problem-solving-through-programming-in-c/)

***

**Que. 3**\
Array passed as an argument to a function is interpreted as:

a) Address of all the elements in an array\
b) Value of the first element of the array\
c) Address of the first element of the array\
d) Number of elements of the array

[View Answer](https://my.progiez.com/courses/problem-solving-through-programming-in-c/)

***

**Que. 4**\
What will be the output of the following C program?

    #include <stdio.h>

    int main() {
        int disp[3][4] = {{5, 6, 8, 2}, {4, 5, 3, 7}, {1, 10, 13, 15}};
        printf("%d\n", disp[2][1]);

        return 0;
    }

[View Answer](https://my.progiez.com/courses/problem-solving-through-programming-in-c/)

***

**Que. 5**\
Find the output of the following C program.

    #include <stdio.h>

    int main() {
        char a[10][8] = {"hi", "hello", "fellows"};
        printf("%s", a[2]);

        return 0;
    }

a) fellows\
b) h\
c) fello\
d) Compiler error

[View Answer](https://my.progiez.com/courses/problem-solving-through-programming-in-c/)

***

**Que. 6**\
What will be the output of the following C program?

    #include <stdio.h>

    int main() {
        char str1[] = "Week-7-Assignment";
        char str2[] = {'W', 'e', 'e', 'k', '-', '7', '-', 'A', 's', 's', 'i', 'g', 'n', 'm', 'e', 'n', 't'};
        int n1 = sizeof(str1) / sizeof(str1[0]);
        int n2 = sizeof(str2) / sizeof(str2[0]);
        printf("n1 = %d, n2 = %d", n1, n2);
        return 0;
    }

a) n1 = 18, n2 = 17\
b) n1 = 18, n2 = 18\
c) n1 = 17, n2 = 17\
d) n1 = 17, n2 = 18

[View Answer](https://my.progiez.com/courses/problem-solving-through-programming-in-c/)

***

**Que. 7**\
Consider the following C program segment:

    #include <stdio.h>
    #include <string.h>

    int main() {
        char p[20];
        char s[] = "string";
        int length = strlen(s);
        int i;

        for (i = 0; i < length; i++)
            p[i] = s[length - i - 1];

        p[length] = '\0'; // Adding null terminator

        printf("%s", p);

        return 0;
    }

The output would be:

a) gnirts\
b) gnirt\
c) string\
d) Nothing is printed

[View Answer](https://my.progiez.com/courses/problem-solving-through-programming-in-c/)

***

**Que. 8**\
If the starting address of a floating-point array `Arr[10][10]` is 2000,\
what would be the memory address of the element `Arr[5][6]`?\
(Considering `float` takes 4 bytes of memory)

a) 2268\
b) 2120\
c) 2224\
d) 2144

[View Answer](https://my.progiez.com/courses/problem-solving-through-programming-in-c/)

***

**Que. 9**\
In C, the placement of elements of a two-dimensional array is:

a) Row-wise\
b) Column-wise\
c) Diagonal-wise\
d) Bottom-to-top wise

[View Answer](https://my.progiez.com/courses/problem-solving-through-programming-in-c/)

***

**Que. 10**\
What will be the value of `i` after the execution of the C code fragment given below?

    #include <stdio.h>
    #include <string.h>

    int main() {
        static char str1[] = "dills";
        static char str2[20];
        static char str3[] = "daffo";
        int i;
        i = strcmp(strcat(str3, strcpy(str2, str1)), "daffodills");
        printf("%d", i);
        return 0;
    }

[View Answer](https://my.progiez.com/courses/problem-solving-through-programming-in-c/)
