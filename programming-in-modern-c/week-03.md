# NPTEL Programming In Modern C++ Week 03 Assignment Answers

Are you looking for NPTEL Programming In Modern C++ Week 03 Assignment Answers? This repository will help you find your answers and solutions for Week 03 of the Programming In Modern C course. We provide detailed solutions to help you complete your assignments efficiently.


![Programming in Modern C++ Week 3 Assignment Answers (July-Dec 2025)](https://miro.medium.com/v2/resize:fit:875/1*gwxfui9an54R5hLJGT5B-A.jpeg)

## Programming in Modern C++ Week 3 Assignment Answers (Jan-Apr 2025)

***

Q1. Consider the following code segment:

    class Complex {
    private:
        int re, im;
    public:
        void setRE(int r_) { re = r_; }
        void setIM(int i_) { im = i_; }
        void print() { cout << re << ", i" << im; }
        void incr() { re++, im++; }
        int incrRE() { return re + 1; }
        int incrIM() { return ++im; }
    };

Identify the set of all methods that change the state of `Complex` class objects.

a) `setRE()`, `setIM()`, `print()`\
b) `setRE()`, `setIM()`, `incrRE()`, `incrIM()`\
c) `incr()`, `incrRE()`, `incrIM()`\
d) `setRE()`, `setIM()`, `incr()`, `incrIM()`

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Q2. Consider the following code segment:

    #include <iostream>
    using namespace std;

    class Number {
        int n;
    public:
        Number() { cout << "0"; }
        Number(int i): n(i) { cout << n; }
    };

    int main() {
        int i = 4;
        Number n1();  // LINE-1
        Number *n2 = new Number(i++);
        Number *n3;
        new Number(i++);
        return 0;
    }

What will be the output?

a) `0102`\
b) `012`\
c) `023`\
d) `12`

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Q3. Consider the following code segment:

    #include <iostream>
    #include <cstring>
    using namespace std;

    class MyClass {
        const char *s1, *s2, *s3; // LINE-1: declare the data members
    public:
        MyClass(const char* _s1, const char* _s2, const char* _s3) :
            s1(setS1(_s1)), s2(setS2(_s2)), s3(setS3(_s3)) {}

        const char* setS1(const char* s) {
            cout << "a";
            return strdup(s);
        }
        const char* setS2(const char* s) {
            cout << "b";
            return strdup(s);
        }
        const char* setS3(const char* s) {
            cout << "c";
            return strdup(s);
        }
    };

    int main() {
        MyClass obj("programming", "in", "C++");
        return 0;
    }

Fill in the blank at `LINE-1` such that the program will print **“in G++ programming”**.

a) `char* s2, char* s3, char* s1`\
b) `char* s1, char* s2, char* s3`\
c) `char* s1, char* s3, char* s2`\
d) `char* s2, char* s1, char* s3`

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Q4. Consider the following code segment:

    #include <iostream>
    #include <string>
    using namespace std;

    class Test {
        int _t;
    public:
        int set_t(int t) const {
            _t = t;
        }
        int get_t() const {
            return _t;
        }
    };

    int main() {
        Test obj;
        obj.set_t(5);
        cout << obj.get_t();
        return 0;
    }

What will be the output/error?

a) `0`\
b) `5`\
c) Compiler error: assignment of data-member `Test::_t` is read-only object\
d) Compiler error: cannot have const function for non-const object

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Q5. Consider the following code segment:

    #include <iostream>
    using namespace std;

    class Complex {
        int re, im;
    public:
        Complex(int _re, int _im) : re(_re), im(_im) { }
        void change(Complex *new_C) { this = new_C; }
        void show() { cout << re << " + i" << im << endl; }
    };

    int main() {
        Complex c1(10, 20);
        Complex c2(20, 50);
        c1.change(&c2);
        c1.show();
        return 0;
    }

What will be the output/error?

a) `10 + i20`\
b) `20 + i50`\
c) Compiler Error: value required as left operand of assignment\
d) Compiler Error: private variables `re, im` are inaccessible

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Q6. Consider the following code segment:

    class myClass {
        // code...
    };

    int main() {
        const myClass m; // LINE-1
        return 0;
    }

What is the type of `this` pointer associated with the object `m`?

a) `const myClass* this;`\
b) `myClass* const this;`\
c) `myClass const* const this;`\
d) `const myClass* const this;`

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Q7. Consider the following code segment:

    #include <iostream>
    using namespace std;

    class Data {
    public:
        Data() { cout << "O"; }  // LINE-1
        Data(Data* t) { cout << "K"; }  // LINE-2
        Data(const Data& t) { cout << "Z"; }  // LINE-3
    };

    int main() {
        Data *t1, *t2;
        t1 = new Data();
        t2 = new Data(t1);
        Data t3 = *t1;
        Data t4 = t3;
        return 0;
    }

What will be the output?

a) `OKKK`\
b) `OKZZ`\
c) `OKKZ`\
d) `OZZZ`

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Q8. Consider the following code segment:

    #include <iostream>
    using namespace std;

    class String {
        char x;
    public:
        String(char _x): x(_x) {}
        void display() { cout << ________ << "D"; } // LINE-1
    };

    int main() {
        String c('C');
        c.display();
        return 0;
    }

Fill in the blank at `LINE-1` such that the program will print **“CD”**.

a) ++`this->x`\
b) ++`this.x`\
c) ++`x`\
d) `x`++

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Q9. Consider the following code segment:

    #include <iostream>
    using namespace std;

    static int i = 5;

    class myClass {
    public:
        myClass() { cout << i++; }
        ~myClass() { cout << i--; }
        
        void check(myClass c) {
            // Some Code
        }
    };

    int main() {
        myClass c1;
        c1.check(c1);
        return 0;
    }

What will be the output?

a) `5665`\
b) `555`\
c) `665`\
d) `6565`

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***


Programming in Modern C++ Week 3 Assignment Answers (July-Dec 2024)


# Programming in Modern C++ Week 3 Assignment Answers (July-Dec 2024)<a id="a170"></a>

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

**These are Programming in Modern C++ Week 3 Assignment Answers**

**Q3.** Consider the following code segment.

Which line/s will give you an error?\
a) LINE-1\
b) LINE-2\
c) LINE-3\
d) LINE-4\
e) LINE-5

[**Answer: Click here to answer**](https://progiez.com/programming-in-modern-c-week-3-assignment-answers)

**Q4.Consider the following code segment.**

What will be the output/error?\
a) 10 21\
b) 10 20\
c) Compilation Error: attempt to increment a constant reference\
d) Compilation Error: invalid initialization of non-const reference

[**Answer: Click here to answer**](https://progiez.com/programming-in-modern-c-week-3-assignment-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 3 Assignment Answers**

**Q5.** Consider the following code segment

What will be the output?\
a) 6 6 4 4\
b) 6 6 8 8\
c) 3 3 4 4\
d) 3 3 8 8

[**Answer: Click here to answer**](https://progiez.com/programming-in-modern-c-week-3-assignment-answers)

**Q6.** Consider the following code segment.

Fill in the blank at LINE-1 such that the output is 20.\
a) (int)malloc(20sizeof(int))\
b) new int\
c) new int (20)\
d) new int \[20]

[**Answer: Click here to answer**](https://progiez.com/programming-in-modern-c-week-3-assignment-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 3 Assignment Answers**

**Q7.** Consider the following code segment.

What will be the output/error?\
a) 0\
b) 5\
c) 2\
d) Compilation Error: invalid value in enum

[**Answer: Click here to answer**](https://progiez.com/programming-in-modern-c-week-3-assignment-answers)

**Q8.** Consider the following code segment.

What will be the output/error?\
a) 9.0\
b) -1.0\
c) -1\
d) Compilation Error at LINE-1: Call of overloaded ‘calculate (int, int)’ is ambiguous

[**Answer: Click here to answer**](https://progiez.com/programming-in-modern-c-week-3-assignment-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 3 Assignment Answers**

**Q9.** Consider the following code segment.

Fill in the blank at LINE-1 with the correct function header.\
a) vector operator\* (vector \&v1, vector \&v2)\
b) vector operator_(vector v1, vector v2) c) int operator_ (vector v1, vector v2)\
d) void operator\*(vector v1, vector v2)

[**Answer: Click here to answer**](https://progiez.com/programming-in-modern-c-week-3-assignment-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

For answers to additional Nptel courses, please refer to this link: [NPTEL Assignment Answers](https://progiez.com/nptel-assignment-answers)


# Programming in Modern C++ Week 3 Assignment Answers (Jan-Apr 2024)<a id="8a77"></a>

**Course Name: Programming in Modern C++**

**Course Link:** [**Click Here**](https://onlinecourses.nptel.ac.in/noc24_cs44/preview)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 3 Assignment Answers**


# Quiz<a id="f366"></a>

Q1. Consider the following program.\
Which function call/s will generate error/s?\
a) LINE-1\
b) LINE-2\
c) LINE-3\
d) LINE-4

**Answer: a) LINE-1**

**Q2. Consider the following program.\
What will be the output /error?**\
a) Default\
b) Parameterized\
c) Default\
Parameterized\
d) Compilation error: call of overload ‘Check()’ is ambiguous

**Answer: d) Compilation error: call of overload ‘Check()’ is ambiguous**

**Q3. Consider the following code segment.\
What will be the output /error?**\
a) 1 9\
b) 9 1\
c) Compilation error: constructor is private\
d) Compilation error: no default constructor

**Answer: c) Compilation error: constructor is private**

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 3 Assignment Answers**

**Q4. Consider the following code segment.\
What will be the output/error?**\
a) a, c\
b) o, k\
c) Compilation Error: private data members are inaccessible\
d) Compilation Error: lvalue required as left operand of assignment

**Answer: d) Compilation Error: lvalue required as left operand of assignment**

**Q5. Consider the following code segment.\
What will be the output?**\
a) 2 13 4 1 4 3 2\
b) 2 1 3 4 4 3 1 2\
с) 1 2 3 4 1 4 3 2\
d) 1 2 3 4 4 3 2 1

**Answer: a) 2 13 4 1 4 3 2**
