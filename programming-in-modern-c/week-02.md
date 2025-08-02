# NPTEL Programming In Modern C++ Week 02 Assignment Answers

Are you looking for NPTEL Programming In Modern C Week 02 Assignment Answers? This repository will help you find your answers and solutions for Week 02 of the Programming In Modern C course. We provide detailed solutions to help you complete your assignments efficiently.

![Programming in Modern C++ Week 2 Assignment Answers](https://miro.medium.com/v2/resize:fit:875/1*JUAJ-dpuw49liEDXhXE-VA.jpeg)

## _Programming in Modern C++ Week 2 Assignment Answers (July-Dec 2025)_

***

**Question 1.** **Consider the following program.**

    #include <iostream>
    using namespace std;
    int main(){
        const int n = 20; // LINE-1
        n = 30;           // LINE-2
        cout << n;
        return 0;
    }

**What will be the output/error?**\
a) 20\
b) 30\
c) Compilation Error at LINE-1: const must be initialized\
d) Compilation Error at LINE-2: assignment of read-only variable ’n’

[**View Answer**](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**Question 2.** **Consider the following program.**

    #include <iostream>
    using namespace std;
    int main(){
        int n = 10;
        int * const p = &n;
        int m = 20;
        p = &m; // LINE-1
        cout << *p;
        return 0;
    }

**What will be the output/error?**\
a) 10\
b) 20\
c) Compilation Error at LINE-1: assignment of read-only variable ’p’\
d) Segmentation fault

[**View Answer**](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**Question 3.** **Consider the following code segment and find the output.**

    #include <iostream>
    #define SQUARE(x) (x + x)
    using namespace std;
    int main(){
        int a = 4;
        int b = SQUARE(a + 1);
        cout << b;
        return 0;
    }

**What will be the output/error?**\
a) 10\
b) 5\
c) 13\
d) 20

[**View Answer**](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**Question 4.** **Consider the following code segment.**

    #include <iostream>
    using namespace std;
    int main(){
        ____ int z = x + y; // LINE-1
        cout << z;
        return 0;
    }

**Fill in the blank at LINE-1 such that the code compiles.**\
a) const\
b) static\
c) inline\
d) register

[**View Answer**](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**Question 5.** **Consider the following code segment.**

    #include <iostream>
    using namespace std;
    void modify(int x1, _______, _______){ //Line-1
        x2 = x1 * 2;
        *x3 = x1 + 5;
    }
    int main(){
        int a = 2, b, c;
        modify(a, b, &c);
        cout << a <<" "<< b <<" "<< c;
        return 0;
    }

**Choose the correct option for parameter list at LINE-1 such that the output is `2 4 7`.**\
a) int \&x2, int \*x3\
b) int x2, int \*x3\
c) int \&x2, int \&x3\
d) int \*x2, int \&x3

[**View Answer**](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**Question 6.** **Consider the following code segment.**

    #include <iostream>
    using namespace std;
    int max(int a, int b){
        return (a > b) ? a : b;
    }
    float max(float a, float b){
        return (a > b) ? a : b;
    }
    int main(){
        cout << max(3, 4.5); // LINE-1
        return 0;
    }

**What will be the output/error?**\
a) 4.5\
b) 3\
c) Compilation Error at LINE-1: call to ’max’ is ambiguous\
d) 4

[**View Answer**](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**Question 7.** **Consider the following code segment.**

    #include <iostream>
    using namespace std;
    void fun(int a, int b = 0){ cout << a + b << endl; }
    void fun(double a, double b = 1.0){ cout << a * b << endl; }
    int main(){
        fun(2);    // LINE-1
        fun(2.0);  // LINE-2
        return 0;
    }

**Which line/s will give compilation error?**\
a) LINE-1\
b) LINE-2\
c) Both LINE-1 and LINE-2\
d) No error

[**View Answer**](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**Question 8.** **Consider the following code segment.**

    #include <iostream>
    using namespace std;
    enum class Color { Red = 1, Green, Blue };
    int main(){
        Color c = Color::Red;
        cout << static_cast<int>(c + 1); // LINE-1
        return 0;
    }

**What will be the output/error?**\
a) 2\
b) Compilation Error at LINE-1: invalid operands to binary +\
c) 1\
d) 3

[**View Answer**](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**Question 9.** **Consider the following code segment.**

    #include <iostream>
    #include <stdlib.h>
    using namespace std;
    int main(){
        int *p = new int[5]; // LINE-1
        p[0] = 42;
        cout << *p;
        delete[] p;
        return 0;
    }

**What will be the output?**\
a) 0\
b) 42\
c) Compilation Error\
d) Segmentation fault

[**View Answer**](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)


**1) Consider the following function prototypes of function add().**

![image 20](https://progiez.com/wp-content/uploads/2024/08/image-20.png "Programming in Modern C++ Week 2 Assignment Answers 3")

Which of the following sets consists of all valid prototypes of function add()?

![image 21](https://progiez.com/wp-content/uploads/2024/08/image-21.png "Programming in Modern C++ Week 2 Assignment Answers 4")

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**2) Consider the following function prototypes of function add().**

![image 22](https://progiez.com/wp-content/uploads/2024/08/image-22.png "Programming in Modern C++ Week 2 Assignment Answers 5")

Which of the above pairs of the prototypes is ambiguous and illegal as per the rule of function overloading?

![image 23](https://progiez.com/wp-content/uploads/2024/08/image-23.png "Programming in Modern C++ Week 2 Assignment Answers 6")

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**3) Consider the following code segment.**

What will be the output/error?

    #include <iostream>
    using namespace std;

    int add(int n1) { return n1; }
    int add(int n1, int n2) { return n1 + n2; }
    double add(double d1) { return d1; }
    int add(int n1, int n2, double n3) { return n1 + n2 + n3; }

    int main() {
        int r = add(10, 20);
        cout << r << endl;
        return 0;
    }

A) 30\
B) 130\
C) 300\
D) Compilation Error: call of overloaded `add(int, int)` is ambiguous

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**4) Consider the following code segment.**

What will be the output?

    #include <iostream>
    using namespace std;

    #define DOUBLE(x) (2 * x)
    inline int TRIPLE(int x) { return 3 * x; }

    int main() {
        cout << DOUBLE(10 + 10) << endl;
        cout << TRIPLE(10 + 10) << endl;
        return 0;
    }

A) 40 60\
B) 30 60\
C) 30 40\
D) 20 30

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**5) Consider the following code segment.**

Choose the correct option to fill in the blank at LINE—I such that the output is `11 11 20 20`.

    #include <iostream>
    using namespace std;

    int& incr(int i) {
        return ++i;
    }

    int main() {
        int x = 10, y = 20;
        int& z = incr(x);
        cout << x << " " << z;
        incr(x);
        cout << x << " " << z;
        return 0;
    }

A) `int incr(int i)`\
B) `int incr(int& i)`\
C) `int& incr(const int& i)`\
D) `int& incr(int& i)`

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**6) Consider the following code segment.**

What will be the output?

    using namespace std;

    #define CL 10 + 1
    const int C2 = 10;

    int main() {
        int nl, n2;
        nl = CL * 100 * C2;
        n2 = C2 * 100 * CL;
        cout << nl << " " << n2;
        return 0;
    }

A) 1110 11001\
B) 1011 1011\
C) 12100 12100\
D) 11001 1110

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**7) Consider the following code segment.**

What will be the output?

    #include <iostream>
    using namespace std;

    int main() {
        int i = 21;
        int* ptr = &i;
        cout << *ptr << " " << i;
        return 0;
    }

A) 21 32\
B) 32 32\
C) 21 44\
D) 44 44

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**8) Consider the following code segment.**

![image 24](https://progiez.com/wp-content/uploads/2024/08/image-24.png "Programming in Modern C++ Week 2 Assignment Answers 7")

**Identify the correct statement(s) to fill in the blank at LINE—I such that the output is X.**

A) const char\* cp\
B) char\* const cp\
C) char const\* cp\
D) const char\* const cp

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**9) Consider the following statement in C.**

![image 25](https://progiez.com/wp-content/uploads/2024/08/image-25.png "Programming in Modern C++ Week 2 Assignment Answers 8")

Among the given options below, identify the equivalent statement/s (perform the same task).

A) `int* new int(5);`\
B) `int* new int[5];`\
C) `int* new int t operator new(sizeof(int) * 5);`\
D) `int* (int*) operator new(sizeof(int))[5];`

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

Programming in Modern C++ Week 2 Assignment Answers (July-Dec 2024)


# Programming in Modern C++ Week 2 Assignment Answers (July-Dec 2024)<a id="17ca"></a>

Q1.Consider the following code segment.

What will be the output/error?\
a) 5\
b) 10\
c) 0\
d) Compilation Error at LINE-1: assignment of read only variable ‘p’

**Answer: d) Compilation Error at LINE-1: assignment of read only variable ‘p’**

**Q2.**Consider the following code segment.

What will be the output?\
a) 3 4\
b) 89\
c) 84\
d) 3 9

**Answer: b) 89**

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 2 Assignment Answers**

**Q3.** Consider the following code segment.

Which line/s will give you an error?\
a) LINE-1\
b) LINE-2\
c) LINE-3\
d) LINE-4\
e) LINE-5

[**_**Answer: Click here to see answers**_**](https://progiez.com/programming-in-modern-c-week-2-assignment-answers)

**Q4.Consider the following code segment.**

What will be the output/error?\
a) 10 21\
b) 10 20\
c) Compilation Error: attempt to increment a constant reference\
d) Compilation Error: invalid initialization of non-const reference

[**_**Answer: Click here to see answers**_**](https://progiez.com/programming-in-modern-c-week-2-assignment-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 2 Assignment Answers**

**Q5.** Consider the following code segment

What will be the output?\
a) 6 6 4 4\
b) 6 6 8 8\
c) 3 3 4 4\
d) 3 3 8 8

[**_**Answer: Click here to see answers**_**](https://progiez.com/programming-in-modern-c-week-2-assignment-answers)

**Q6.** Consider the following code segment.

Fill in the blank at LINE-1 such that the output is 20.\
a) (int)malloc(20sizeof(int))\
b) new int\
c) new int (20)\
d) new int \[20]

[**_**Answer: Click here to see answers**_**](https://progiez.com/programming-in-modern-c-week-2-assignment-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 2 Assignment Answers**

**Q7.** Consider the following code segment.

What will be the output/error?\
a) 0\
b) 5\
c) 2\
d) Compilation Error: invalid value in enum

[**_**Answer: Click here to see answers**_**](https://progiez.com/programming-in-modern-c-week-2-assignment-answers)

**Q8.** Consider the following code segment.

What will be the output/error?\
a) 9.0\
b) -1.0\
c) -1\
d) Compilation Error at LINE-1: Call of overloaded ‘calculate (int, int)’ is ambiguous

[**_**Answer: Click here to see answers**_**](https://progiez.com/programming-in-modern-c-week-2-assignment-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 2 Assignment Answers**

**Q9.** Consider the following code segment.

Fill in the blank at LINE-1 with the correct function header.\
a) vector operator\* (vector \&v1, vector \&v2)\
b) vector operator_(vector v1, vector v2) c) int operator_ (vector v1, vector v2)\
d) void operator\*(vector v1, vector v2)

[**_**Answer: Click here to see answers**_**](https://progiez.com/programming-in-modern-c-week-2-assignment-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++Nptel Week 2 Assignment Answer**


# Programming Questions<a id="a5cd"></a>

**W1\_Programming-Qs.1\
Consider the program below.\
• Fill in the blank at LINE-1 to declare a stack variable st.\
• Fill in the blank at LINE-2 to push values into the stack.\
• Fill in the blank at LINE-3 with the appropriate statement.\
The program must satisfy the given test cases.**

**Solution:**

    Update Soon

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 2 Assignment Answers**

**W1\_Programming-Qs.2\
Consider the following program.\
• Fill in the blank at LINE-1 with the appropriate if statement,\
• Fill in the blank at LINE-2 and LINE-3 with the appropriate return statements.\
The program must satisfy the sample input and output.**

**Solution:**

    Update Soon

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 2 Assignment Answers**

**W1\_Programming-Qs.3\
Consider the program below.\
• Fill in the blank at LINE-1 to include the appropriate header file to utilize the abs () function.\
• Fill in the blank at LINE-2 to compute the Manhattan distance between two points pt1 and pt2 as pt1.ypt2.y+pt1.x pt2.r\
The program must satisfy the given test cases.**

**Solution:**

    Update Soon

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++Nptel Week 2 Assignment Answer**

All Solutions of Programming in Modern C++: [Click Here](https://progiez.com/nptel-assignment-answers/nptel-programming-in-modern-cpp-answers)

For answers to additional Nptel courses, please refer to this link: [NPTEL Assignment Answers](https://progiez.com/nptel-assignment-answers)


# Programming in Modern C++ Week 2 Assignment Answers (JAN-APR 2024)<a id="9c5e"></a>

**Course Name: Programming in Modern C++**

**Course Link:** [**Click Here**](https://onlinecourses.nptel.ac.in/noc24_cs44/preview)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

These are Nptel Programming in Modern C++ Assignment 2 Answers


# Quiz<a id="5003"></a>

**Q1. Consider the following program.\
What will be the output?**\
a)15\
b)14\
c)62\
d)Compilation error:call of overload “add(int,int)”is ambiguous

**Answer: b)14**

**Q2. Consider the following program.\
What will be the output (Consider right to left execution of the cout statement)?**\
a) 7 4\
b) 8 4\
c) 4 4\
d) 7 6

**Answer: a) 7 4**

**Q3. Consider the following code segment.\
What will be the output?**\
a) 6 6 2 2\
b) 6 8 4 2\
с) 6 6 4 4\
d) 8 6 4 4

**Answer: с) 6 6 4 4**

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Nptel Programming in Modern C++ Assignment 2 Answers**

**Q4. Consider the following code segment.\
Fill in the blank at LINE-1 so that the program will print 1, 300.**\
a) int x3, int x4\
b) int \&x3, int\* x4\
c) int x3, int& x4\
d) int x3, int\* x4

**Answer: d) int x3, int\* x4**

**Q5. Consider the following code segment.\
What will be the output?**\
a) 0\
b) 10\
c) Compilation error at LINE-1: ‘x’ declared as reference but not initialized\
d) Compilation error at LINE-2: assignment of read only reference x

**Answer: c), d)\
c) Compilation error at LINE-1: ‘x’ declared as reference but not initialized\
d) Compilation error at LINE-2: assignment of read only reference x**

**Q6. Consider the following code segment.\
Fill in the blank at LINE-1 with appropriate option/s such that the output is: 11**\
a) const\
b) volatile\
c) static\
d) inline

**Answer: a) const**

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Nptel Programming in Modern C++ Assignment 2 Answers**

**Q7. Consider the following code segment.\
Fill in the blank at LINE-1 so that the program will print a.**\
a) (char\*)malloc (10\*sizeof (char))\
b) new char(‘a’)\
c) new char (97)\
d) new char \[97]

**Answer: b), c)\
b) new char(‘a’)\
c) new char (97)**

**Q8. Consider the following code segment.\
What will be the output(s) /error(s)?**\
a) 97\
b) 120\
c) Error at LINE-1: cannot convert int\* to const char\* in initialization\
d) Error at LINE-2: assignment of read-only location \*p

**Answer: c), d)\
c) Error at LINE-1: cannot convert int\* to const char\* in initialization\
d) Error at LINE-2: assignment of read-only location \*p**

**Q9. Consider the following function prototypes of overloaded function func().\
Which functions will be invoked for the call func (2.1, 3.7f)?**\
а) 2, 3, 5\
b) 2, 3\
c) 2\
d) 1, 2

**Answer: b) 2, 3**

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Nptel Programming in Modern C++ Assignment 2 Answers**


# Programming<a id="8f89"></a>

**Question 1**

**Consider the program below.**\
**• Fill in the blank at LINE-1 with an appropriate statement.**\
**The program must satisfy the given test cases.**

**Solution:**

    #include <iostream>

<!---->

    using namespace std;#define THRICE(X) ((X) * 3)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Nptel Programming in Modern C++ Assignment 2 Answers**

**Question 2**

**Consider the following program.\
• Fill in the blank at LINE-1 with appropriate formal arguments list.\
• Fill in the blank at LINE-2 with the appropriate return statement.\
The program must satisfy the sample input and output.**

**Solution:**

    #include <iostream>

<!---->

    using namespace std;int sqr(int num) {
        return num * num;
    }

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Nptel Programming in Modern C++ Assignment 2 Answers**
