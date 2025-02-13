# NPTEL Programming In Modern C++ Week 04 Assignment Answers

Are you looking for NPTEL Programming In Modern C++ Week 04 Assignment Answers? This repository will help you find your answers and solutions for Week 04 of the Programming In Modern C course. We provide detailed solutions to help you complete your assignments efficiently.

![Programming in Modern C++ Week 4 Assignment Answers (July-Dec 2024)](https://miro.medium.com/v2/resize:fit:875/1*izhvViLtYMIE5H6rHVcsTQ.jpeg)

## Programming in Modern C++ Week 4 Assignment Answers (Jan-Apr 2025)

***

Q1. Consider the following code segment.

    #include<iostream>
    using namespace std;
    class myClass{
        static int s;
    public:
        myClass(int _s) : s(_s) { }
        void incr(){ s = s+10; }
        void print(){ cout << s; }
    };

    int myClass::s = 10;
    int main(){
        myClass o1(5), o2(10);
        o2.incr();
        o2.print();
        return 0;
    }

What will be the output/error?

a) 15\
b) 20\
c) 30\
d) Compilation Error: myClass::s is a static data member; it can only be initialized at its definition

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Q2. Consider the following code segment.

    #include<iostream>
    using namespace std;
    class Point{
        int x, y;
    public:
        Point(int r=0, int i=0) : x(r), y(i) {}
        Point& operator<< (const Point& c){ //Line-1
            cout << x + c.x << "," << y + c.y << endl;
            return *this;
        }
        
        friend Point& operator<<(ostream& os, Point c);
    };

    Point& operator<<(ostream& os, Point c){ //Line-2
        cout << c.x << "," << c.y << endl;
        return c;
    }

    int main(){
        Point c1(2,5), c2(4,6);
        cout << c1 << c2;
        return 0;
    }

What will be the output?

a) 2,5 4,6\
b) 6,5 2,11\
c) 6,11 2,5\
d) 2,5 6,11

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Q3. Consider the following code segment.

    #include <iostream>
    using namespace std;
    int var = 0;
    namespace name {
        int var = 25;
    }
    int main() {
        int var = 1;
        using namespace name;
        cout << ::var <<" " << var <<" " << name::var; // LINE-1
        return 0;
    }

What will be the output/error?

a) 0 1 2\
b) 0 2 2\
c) 2 0 1\
d) Compilation Error: reference to ‘var’ is ambiguous

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Q4. Consider the following code segment.

    #include <iostream>
    using namespace std;
    class myClass {
        static int X;
        static int Y;
    public:
        ____ void print() { // LINE-1
            cout << X << " " << Y;
        }
        void setX(int a){ X = a; }
        void setY(int a){ Y = a; }
    };

    int myClass::X = 10;
    int myClass::Y = 10;
    int main() {
        myClass t1, t2;
        t1.setX(4);
        t2.setY(5);
        myClass::print();
        return 0;
    }

Fill in the blank at LINE-1 such that the output will be `4 5`.

a) mutable\
b) static\
c) const\
d) friend

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Q5. Consider the following code segment.

    #include<iostream>
    using namespace std;
    int x = 10;
    namespace e {
        namespace e1 {
            int x = 15;
        }
    }
    int main(){
        ____ // LINE-1
        cout << x;
        return 0;
    }

Fill in the blank at LINE-1 such that the program will print `15`.

a) `using e::e1::x`\
b) `using e::e1`\
c) `using namespace e::e1`\
d) `using namespace e`

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Q6. Consider the following code segment.

    #include<iostream>
    using namespace std;
    class constTest{
        ____ int x; // LINE-1
    public:
        constTest(int _x) : x(_x) {}
        void set(int a) const {
            x = a;
        }
        void print() const {
            cout << x << endl;
        }
    };

    int main(){
        const constTest m(5);
        m.set(10);
        m.print();
        return 0;
    }

Fill in the blank at LINE-1 such that the output is `10`.

a) `int mutable`\
b) `mutable int`\
c) `volatile int`\
d) `const int`

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Q7. Consider the following code segment.

    #include<iostream>
    using namespace std;
    namespace name{
        class Student{
            int roll;
        public:
            Student(int x) : roll(x) {}
            void print(){ cout << roll; }
        };
    }
    int main(){
        ____ // LINE-1
        s.print();
        return 0;
    }

Fill in the blank at LINE-1 such that the output is `5`.

a) `name::Student s(5);`\
b) `Student s(5);`\
c) `name.Student s(5);`\
d) `using name::Student(5);`

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Q8. Consider the following code segment.

    #include<iostream>
    using namespace std;
    class Point{
        int x, y;
    public:
        Point(int _x, int _y) : x(_x), y(_y) {}
        ____ // LINE-1
        Point& operator<< (ostream& os, Point p){
            cout << "(" << p.x << "," << p.y << ")" << endl;
            return p;
        }
    };
    int main(){
        Point pt(2,5);
        cout << pt;
        return 0;
    }

Fill in the blank at LINE-1 such that the program will print `(2,5)`.

a) `Point& operator<< (ostream&, Point&)`\
b) `friend Point& operator<< (ostream&, Point&)`\
c) `Point& friend operator<< (ostream&, Point&)`\
d) `const Point& operator<< (ostream&, Point&)`

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Q9. Consider the following code segment.

    #include<iostream>
    using namespace std;
    class A{
        static int a;
    public:
        int get(){ return a; }
        ____ // LINE-1
    };
    int A::a = 0;
    class B{
        int b;
    public:
        B(int y) : b(y) {}
        void print(){
            A::a = 10;
            cout << A::a << " " << A::a + b;
        }
    };
    int main(){
        B t(5);
        t.print();
        return 0;
    }

Fill in the blank at LINE-1 such that the program will print `10 15`.

a) `static class B`\
b) `friend class B`\
c) `class friend B`\
d) `using class B`

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***


## Programming in Modern C++ Week 4 Assignment Answers (July-Dec 2024)

***

Q1.Consider the following code segment.

include

using namespace std;\
class Counter {\
static int count;\
public:\
void increment() {\
count = count + 5;\
}\
void display() {\
cout << count;\
}\
};\
int Counter::count = 15;\
int main() {\
Counter c1, c2;\
c1.increment();\
c2.increment();\
c2.display();\
return 0;\
}

What will be the output?\
a) 15\
b) 20\
c) 25\
d) 30

**Answer: c) 25**

***

**Q2**Consider the following code segment.

[****See also**  **Programming in Modern C++ | Week 6****](https://progiez.com/nptel-programming-in-modern-c-assignment-6-answers)

include

using namespace std;\
class Example {\
static int count;\
public:\
void increment() {\
count = count + 5;\
show();\
}\
void show() { // LINE-1\
cout << count;\
}\
};\
int Example::count = 0;\
int main() {\
Example e;\
e.increment();\
return 0;\
}

Fill in the blank at LINE-1 such that the program will print 5.\
a) mutable\
b) static\
c) class\
d) friend

**Answer: b) static**

***

**_**For answers or latest updates join our telegram channel: [**Click here to join**](https://telegram.me/nptel_assignments)**_**

***

**Q3.**Consider the following code segment.

include

using namespace std;\
class Number {\
int value;\
public:\
Number(int\_value = 0) value(\_value) {}\
// LINE-1\
};\
void show (Number \&n) {\
cout << n.value;\
}\
int main() {\
Number n(10);\
show(n);\
return 0;\
}\
Fill in the blank at LINE-1 such that the program will print 10.\
a) void friend show (Number&);\
b) static void show (Number&);\
c) friend void show (Number&);\
d) void const show (Number&);

**Answer:a) void friend show (Number&);** , **c) friend void show (Number&);**

***

**Q4.**Consider the following code segment.

include

using namespace std;\
int num = 5;\
namespace space {\
int num = 15;\
}\
int main() { using namespace space;\
int num = 10;\
{\
cout << : : num << << num << << space::num;\
}\
return 0;\
}\
What will be the output/error?\
a) 5 10 15\
b) 10 5 15\
c) 15 5 10\
d) Compilation Error: reference to ‘num’ is ambiguous

**Answer: a) 5 10 15**

***

**_**For answers or latest updates join our telegram channel: [**Click here to join**](https://telegram.me/nptel_assignments)**_**

***

**Q5.**Consider the following code segment.

include

int main() { char message\[] = “Welcome”; cout << message; // LINE-1 return 0;\
}

The cout statement at LINE-1 gives an error. Change the cout statement such that it prints Welcome.\
a) std::cout << message;\
b) using cout << message;\
c) using std::cout << message;\
d) std.cout << message;

**Answer:a) std::cout << message;**

***

**Q6.** Consider the following code segment.

include

using namespace std;\
int y = 2;\
namespace name2 {\
int y = 4;\
}\
int main() {\
int y = 3;\
cout << <<< endl; // LINE-1\
return 0;\
}\
Fill in the blank at LINE-1 so that the program will print 6.\
a) name2::y+ :: y\
b) name2::y+ y\
c) y+::y\
d) name2.y+:: y

**Answer: a) name2::y+ :: y**

***

**_**For answers or latest updates join our telegram channel: [**Click here to join**](https://telegram.me/nptel_assignments)**_**

***

**Q7.** Consider the following code segment.

include

using namespace std;\
class X {\
int x;\
public: X(int x) x(x) {}\
int getValue() {\
return x;\
}\
};\
class Y {\
static X obj;\
public:\
static int getValue() {\
return obj.getValue();\
}\
};\
int main(void) {\
cout << Y::getValue();\
return 0;\
}

What will be the output/error?\
a) 0\
b) 10\
c) Compilation error: cannot access static object obj\
d) Compilation error: undefined reference Y::obj

**Answer: d) Compilation error: undefined reference Y::obj**

***

**Q8.** Consider the following code segment.

include

using namespace std;\
class Counter {\
static int count;\
public:\
Counter() { count++;\
}\
static int getCount() { return count;\
}\
};\
int Counter::count = 5;\
int main() {\
cout << Counter::getCount() << “;\
Counter c \[3];\
cout << Counter::getCount();\
return 0;\
}\
What will be the output?\
a) 58\
b) 5 9\
c) 68\
d) 69

**Answer: a) 58**

***

**_**For answers or latest updates join our telegram channel: [**Click here to join**](https://telegram.me/nptel_assignments)**_**

***

**Q9.**Consider the following code segment.

include

using namespace std;\
class Alpha {\
int x = 15;\
**_**\_**_**; // LINE-1: };\
class Beta {\
public:\
int increase (Alpha \&a) {\
return (a.x + 5);\
}\
};\
int main() {\
Alpha a1;\
Beta b1;\
cout << bi.increase (a1);\
return 0;\
}\
Fill in the blank at LINE-1 such that the program will print 20.\
a) friend class Beta\
b) class friend Beta\
c) friend int increase (Alpha&)\
d) friend int Beta:: increase (Alpha&)

**Answer: a) friend class Beta**

***

**_**For answers or latest updates join our telegram channel: [**Click here to join**](https://telegram.me/nptel_assignments)**_**

For answers to additional Nptel courses, please refer to this link: [NPTEL Assignment](https://progiez.com/nptel-assignment-answers)

***


## Programming in Modern C++ Week 4 Assignment Answers (JAN-APR 2024)

**Course Name: Programming in Modern C++**

**Course Link: [**Click Here**](https://onlinecourses.nptel.ac.in/noc24_cs44/preview)**

**_**For answers or latest updates join our telegram channel: [**Click here to join**](https://telegram.me/nptel_assignments)**_**

**_****These are Programming in Modern C++ Week 4 Assignment Answers****_**

***

Quiz

Q1. Consider the following program.\
Fill in the blank at LINE-1 so that the program will print 30.\
a) friend class ReTest\
b) class friend ReTest\
c) static class ReTest\
d) const class ReTest

**Answer: a) friend class ReTest**


Programming in Modern C++ Week 4 Assignment Answers (July-Dec 2024)


# Programming in Modern C++ Week 4 Assignment Answers (July-Dec 2024)

Q1.Consider the following code segment.

include

using namespace std;\
class Counter {\
static int count;\
public:\
void increment() {\
count = count + 5;\
}\
void display() {\
cout << count;\
}\
};\
int Counter::count = 15;\
int main() {\
Counter c1, c2;\
c1.increment();\
c2.increment();\
c2.display();\
return 0;\
}

What will be the output?\
a) 15\
b) 20\
c) 25\
d) 30

**Answer:** [**Click Here to view Answer**](https://progiez.com/programming-in-modern-c-week-4-assignment-answers)

**Q2**Consider the following code segment.

include

using namespace std;\
class Example {\
static int count;\
public:\
void increment() {\
count = count + 5;\
show();\
}\
void show() { // LINE-1\
cout << count;\
}\
};\
int Example::count = 0;\
int main() {\
Example e;\
e.increment();\
return 0;\
}

Fill in the blank at LINE-1 such that the program will print 5.\
a) mutable\
b) static\
c) class\
d) friend

**Answer:** [**Click Here to view Answer**](https://progiez.com/programming-in-modern-c-week-4-assignment-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**Q3.**Consider the following code segment.

include

using namespace std;\
class Number {\
int value;\
public:\
Number(int\_value = 0) value(\_value) {}\
// LINE-1\
};\
void show (Number \&n) {\
cout << n.value;\
}\
int main() {\
Number n(10);\
show(n);\
return 0;\
}\
Fill in the blank at LINE-1 such that the program will print 10.\
a) void friend show (Number&);\
b) static void show (Number&);\
c) friend void show (Number&);\
d) void const show (Number&);

**Answer:** [**Click Here to view Answer**](https://progiez.com/programming-in-modern-c-week-4-assignment-answers)

**Q4.**Consider the following code segment.

include

using namespace std;\
int num = 5;\
namespace space {\
int num = 15;\
}\
int main() { using namespace space;\
int num = 10;\
{\
cout << : : num << << num << << space::num;\
}\
return 0;\
}\
What will be the output/error?\
a) 5 10 15\
b) 10 5 15\
c) 15 5 10\
d) Compilation Error: reference to ‘num’ is ambiguous

**Answer:** [**Click Here to view Answer**](https://progiez.com/programming-in-modern-c-week-4-assignment-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**Q5.**Consider the following code segment.

include

int main() { char message\[] = “Welcome”; cout << message; // LINE-1 return 0;\
}

The cout statement at LINE-1 gives an error. Change the cout statement such that it prints Welcome.\
a) std::cout << message;\
b) using cout << message;\
c) using std::cout << message;\
d) std.cout << message;

**Answer:** [**Click Here to view Answer**](https://progiez.com/programming-in-modern-c-week-4-assignment-answers)

**Q6.** Consider the following code segment.

include

using namespace std;\
int y = 2;\
namespace name2 {\
int y = 4;\
}\
int main() {\
int y = 3;\
cout << <<< endl; // LINE-1\
return 0;\
}\
Fill in the blank at LINE-1 so that the program will print 6.\
a) name2::y+ :: y\
b) name2::y+ y\
c) y+::y\
d) name2.y+:: y

**Answer:** [**Click Here to view Answer**](https://progiez.com/programming-in-modern-c-week-4-assignment-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**Q7.** Consider the following code segment.

include

using namespace std;\
class X {\
int x;\
public: X(int x) x(x) {}\
int getValue() {\
return x;\
}\
};\
class Y {\
static X obj;\
public:\
static int getValue() {\
return obj.getValue();\
}\
};\
int main(void) {\
cout << Y::getValue();\
return 0;\
}

What will be the output/error?\
a) 0\
b) 10\
c) Compilation error: cannot access static object obj\
d) Compilation error: undefined reference Y::obj

**Answer:** [**Click Here to view Answer**](https://progiez.com/programming-in-modern-c-week-4-assignment-answers)

**Q8.** Consider the following code segment.

include

using namespace std;\
class Counter {\
static int count;\
public:\
Counter() { count++;\
}\
static int getCount() { return count;\
}\
};\
int Counter::count = 5;\
int main() {\
cout << Counter::getCount() << “;\
Counter c \[3];\
cout << Counter::getCount();\
return 0;\
}\
What will be the output?\
a) 58\
b) 5 9\
c) 68\
d) 69

**Answer:** [**Click Here to view Answer**](https://progiez.com/programming-in-modern-c-week-4-assignment-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**Q9.**Consider the following code segment.

include

using namespace std;\
class Alpha {\
int x = 15;\
**_**\_**_**; // LINE-1: };\
class Beta {\
public:\
int increase (Alpha \&a) {\
return (a.x + 5);\
}\
};\
int main() {\
Alpha a1;\
Beta b1;\
cout << bi.increase (a1);\
return 0;\
}\
Fill in the blank at LINE-1 such that the program will print 20.\
a) friend class Beta\
b) class friend Beta\
c) friend int increase (Alpha&)\
d) friend int Beta:: increase (Alpha&)

**Answer:** [**Click Here to view Answer**](https://progiez.com/programming-in-modern-c-week-4-assignment-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

For answers to additional Nptel courses, please refer to this link: [NPTEL Assignment](https://progiez.com/nptel-assignment-answers)


# Programming in Modern C++ Week 4 Assignment Answers (JAN-APR 2024)

**Course Name: Programming in Modern C++**

**Course Link:** [**Click Here**](https://onlinecourses.nptel.ac.in/noc24_cs44/preview)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 4 Assignment Answers**


# Quiz

Q1. Consider the following program.\
Fill in the blank at LINE-1 so that the program will print 30.\
a) friend class ReTest\
b) class friend ReTest\
c) static class ReTest\
d) const class ReTest

**Answer: a) friend class ReTest**

**Q2. Consider the following program.\
Fill in the blank at LINE-1 so that the program will print 012.**\
a) using Test\
b) namespace Test\
c) using namespace Test\
d) using namespace Test: :var

**Answer: c) using namespace Test**

**Q3. Consider the following code segment.\
Fill in the blank at LINE-1 so that the program will print 9.81.**\
a) mutable double\
b) const double\
c) static double\
d) double mutable

**Answer: a), d)**

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 4 Assignment Answers**

**Q4. Consider the following code segment.\
What will be the output?**\
a) 10\
b) 15\
c) 20\
d) 25

**Answer: d) 25**

**Q5. Consider the following code segment.\
Fill in the blank at LINE-1 so that the program will print 5.**\
a) display()\
b) myClass: :display()\
c) myClass.display()\
d) myClass->display()

**Answer: b) myClass: :display()**

**Q6. Consider the following code segment.\
Change the LINE-1 with the appropriate option so that the program will run successfully.**\
a) using cout < greet;\
b) using std:: cout « greet;\
c) std:: cout < greet;\
d) std.cout < greet;

**Answer: c) std:: cout < greet;**

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 4 Assignment Answers**

**Q7. Consider the following code segment.\
Which line/s will generate a compilation error?**\
a) LINE-1\
b) LINE-2\
c) LINE-3\
d) LINE-4

**Answer: a) LINE-1**

**Q8. Consider the following code segment.\
What will be the output /error?**\
a) 0\
b) 5\
c) Compilation error: inaccessible object c1\
d) Compilation error: undefined reference classB:: c1

**Answer: d) Compilation error: undefined reference classB:: c1**

**Q9. Consider the following code segment.\
What will be the output?**\
а) 0 3\
b) 0 4\
c) 1 3\
d) 1 4

**Answer: b) 0 4**

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 4 Assignment Answers**


# Programming

**Question 1**

**Consider the program below.\
• Fill in the blank at LINE-1 with appropriate keyword,\
• Fill in the blank at LINE-2 with appropriate return type of the function,\
• Fill in the blank at LINE-3 with the appropriate initialization statement of the static variable obj.\
The program must satisfy the given test cases.**

**Solution:**

    #include<iostream>
    using namespace std;

<!---->

    class myClass {
        char c;
        static myClass* obj;
        myClass(char x) : c(x) { }
    public:
        static myClass* create(char x) {
            if(!obj)
                obj = new myClass(x);
            return obj;
        }
        void show();
    };myClass* myClass::obj = nullptr;

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 4 Assignment Answers**

**Question 2**

**Consider the following program.\
• Fill in the blank at LINE-1 with the appropriate statement such that the global function can access private class members,\
• Fill in the blank at LINE-2 with the appropriate statement such that the global function can access private class members\
The program must satisfy the sample input and output.**

**Solution:**

    #include<iostream>
    using namespace std;

<!---->

    class B;class A {
        int x;
    public:
        A(int _x) : x(_x) { cout << "Class A: "; }
        friend void print(int a, int b);
    };class B {
        int x;
    public:
        B(int _x) : x(_x) { cout << "Class B: "; }
        friend void print(int a, int b);
    };

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 4 Assignment Answers**

**Question 3**

**Consider the following program.\
• Fill in the blanks at LINE-1, LINE-2, LINE-3 and LINE-4 with appropriate keywords\
The program must satisfy the sample input and output.**

**Solution:**

    #include<iostream>
    using namespace std;
    class Emp{
        int id;
        mutable double basic;                    //LINE-1
        mutable double salary;                   //LINE-2
        public:
            Emp(int i, double b, double s=0) : id(i), basic(b), salary(s){ }
            void setBasic(double b) const{        //LINE-3
                basic = b;
            }
            friend double calculate(const Emp&); //LINE-4
    };

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 4 Assignment Answers**

More Weeks of Programming in Modern C++: [Click here](https://progiez.com/nptel-assignment-answers/nptel-programming-in-modern-cpp-answers)

More Nptel Courses: [Click here](https://progiez.com/nptel-assignment-answers/)

**Session: JULY-DEC 2023**

**Course Name: Programming in Modern C++**

**Course Link:** [**Click Here**](https://onlinecourses.nptel.ac.in/noc23_cs50/course)


## These are Programming in Modern C++ Week 4 Assignment Answers

# Programming

**Question 1\
Consider the following program. Fill in the blanks as per the instructions given below:\
• Complete the variable declaration at LINE-1,\
• Complete the function prototype at LINE-2 and LINE-3 with appropriate keywords\
such that it will satisfy the given test cases.**

**Solution:**

    #include<iostream>
    using namespace std;
    class Employee
    {
        const int id;
        string name;
        mutable int salary;

<!---->

        public:
            Employee(int a, string b, int c) : id(a), name(b), salary(c) {}        void updateSal(int x) const
            {
              salary += x;
            }        void print() const
            { 
              cout << id << " : " << name << " : " << salary;
            }
    };

**These are Programming in Modern C++ Week 4 Assignment Answers**

**Question 2\
Consider the following program. Fill in the blanks as per the instructions given below.\
• at LINE-1 with appropriate forward declaration,\
• at LINE-2 with appropriate statement\
such that it will satisfy the given test cases**

**Solution:**

    #include<iostream>
    using namespace std;

<!---->

    class B;
    class A
    {
        int a_ = 0;
        public:
            A(int x) : a_(x) {}
            int mulB (B&);
            int subtractB (B&);
    };
    class B
    {
        int b_;
        public:
            B(int y) : b_(y) {	}        friend int A::mulB(B&), A::subtractB(B&);
    };

**These are Programming in Modern C++ Week 4 Assignment Answers**

**Question 3\
Consider the following program. Fill in the blanks at LINE-1, LINE-2 and LINE-3 with appropriate statements such that it will satisfy the given test cases.**

**Solution:**

    #include<iostream>
    using namespace std;
    class Singleton{
        int data;
        static Singleton *ins;
        Singleton(int i) : data(i) {}
        public:
            int get(){ return data; }
            static Singleton* createIns(int i)
            {
                if(!ins)
                    ins = new Singleton(i);
                return ins;
            }
            ~Singleton(){ cout << data; }
    };

**These are Programming in Modern C++ Week 4 Assignment Answers**

More Weeks of Programming in Modern C++: [Click here](https://progiez.com/nptel-assignment-answers/nptel-programming-in-modern-cpp-answers)

More Nptel Courses: [Click here](https://progiez.com/nptel-assignment-answers)


# Programming in Modern C++ Week 4 Assignment Answers (JULY-DEC 2022)

**Course Name: Programming in Modern C++**

**Course Link:** [**Click Here**](https://onlinecourses.nptel.ac.in/noc23_cs50/course)

**These are Programming in Modern C++ Week 4 Assignment Answers**


# Quiz

**Q1. Consider the following code segment.**What will be the output/error?\
a) 15\
b) 20\
c) 30\
d) Compilation Error : myClass::s is a static data member; it can only be initialized at its definition

**Answer: d) Compilation Error : myClass::s is a static data member; it can only be initialized at its definition**

**Q2. Consider the following code segment.\
What will be the output?**\
a) 2,5 4,6\
b) 6,5 2,11\
c) 6,11 2,5\
d) 2,5 6,11

**Answer: d) 2,5 6,11**

**These are Programming in Modern C++ Week 4 Assignment Answers**

**Q3. Consider the following code segment.**What will be the output/error?\
a) 0 1 2\
b) 0 2 2\
c) 2 0 1\
d) Compilation Error: reference to ‘var’ is ambiguous

**Answer: a) 0 1 2**

**Q4. Consider the following code segment.\
Fill in the blank at LINE-1 such that the output will be 4 5.**\
a) mutable\
b) static\
c) const\
d) friend

**Answer: b) static**

**These are Programming in Modern C++ Week 4 Assignment Answers**

**Q5. Consider the following code segment.\
Fill in the blank at LINE-1 such that the program will print 15.**\
a) using e::e1 : : x\
b) using e::e1\
c) using namespace e::e1\
d) using namespace e

**Answer: a) using e::e1 : : x**

**These are Programming in Modern C++ Week 4 Assignment Answers**

**Q6. Consider the following code segment.\
Fill in the blank at LINE-1 such that the output is 10.**\
a) int mutable\
b) mutable int\
c) volatile int\
d) const int

**Answer: a, b**

**These are Programming in Modern C++ Week 4 Assignment Answers**

**Q7. Consider the following code segment.\
Fill in the blank at LINE-1 such that the output is 5.**\
a) name::Student s(5)\
b) Students (5)\
c) name. Student s(5)\
d) using name::Student s(5)

**Answer: a) name::Student s(5)**

**These are Programming in Modern C++ Week 4 Assignment Answers**

**Q8. Consider the following code segment.\
Fill in the blank at LINE-1 such that the program will print (2,5).**\
a) Point& operator<<(ostream&, Point&)\
b) friend Point& operator<<(ostream&, Point&)\
c) Point& friend operator<<(ostream&, Point&)\
d) const Point& operator<<(ostream&, Point&)

**Answer: b) friend Point& operator<<(ostream&, Point&)**

**These are Programming in Modern C++ Week 4 Assignment Answers**

**Q9. Consider the following code segment.\
Fill in the blank at LINE-1 such that the program will print 5 15.**\
a) static class B\
b) friend class B\
c) class friend B\
d) using class B

**Answer: b) friend class B**

**These are Programming in Modern C++ Week 4 Assignment Answers**


# Assignment Questions

**Question 1**

**Consider the program below which defines a class Database. Complete the program with the following instructions.\
• Fill in the blank at LINE-1 to complete the declaration of member variable ins.\
• Fill in the blank at LINE-2 to specify the return type of createIns() function.\
• Fill in the blank at LINE-3 to call the createIns() function with parameter i.\
The program must satisfy the given test cases.**

**Solution:**

    #include<iostream>
    using namespace std;
    class Database{
        int id;
        static Database *ins;
        Database(int i) : id(i) {}
        public:
            int getIns(){ return id; }
            static Database *createIns(int i){
                if(!ins)
                    ins = new Database(i);
                return ins;
            }
            ~Database();
    };
    Database *Database::ins = 0;
    void fun(int i){
        Database *s = Database::createIns(i);

**These are Programming in Modern C++ Week 4 Assignment Answers**

**Question 2**

**Consider the following program.\
• Fill in the blanks at LINE-1 to complete forward declaration.\
• Fill in the blank at LINE-2 with appropriate function declaration so that function\
calculate can access private data member of TotalAmount class.\
The program must satisfy the sample input and output.**

**Solution:**

    #include<iostream>
    using namespace std;

<!---->

    class Interest; //LINE-1
    class TotalAmount{
        double prinAmt;
        double amt = 0;
    public:
        TotalAmount(double p) : prinAmt(p){}
        double calculate(Interest&);
    };
    class Interest{
        double in;
    public:
        Interest(double i) : in(i){ }    friend class TotalAmount; //LINE-2
    };

**These are Programming in Modern C++ Week 4 Assignment Answers**

**Question 3**

**Consider the following program. Fill in the blanks as per the instructions given below:\
• at LINE-1 to complete operator overload function,\
• at LINE-2 and LINE-3 to calculate subtraction of two position class.\
such that it will satisfy the given test cases.**

**Solution:**

    #include<iostream>
    using namespace std;
    class position{
        int x, y;
        public:
            position(int a, int b) : x(a), y(b) {}

<!---->

            position operator-(const position& p1){            position p(0,0);            p.x = x-p1.x;            p.y = y-p1.y;            return p;
            }

**These are Programming in Modern C++ Week 4 Assignment Answers**

More Solutions of Programming in Modern C++: [Click Here](https://progiez.com/nptel-assignment-answers/nptel-programming-in-modern-cpp-answers)

More NPTEL Solutions: <https://progiez.com/nptel-assignment-answers/>
