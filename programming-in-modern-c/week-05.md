# NPTEL Programming In Modern C Week 05 Assignment Answers

Are you looking for NPTEL Programming In Modern C Week 05 Assignment Answers? This repository will help you find your answers and solutions for Week 05 of the Programming In Modern C course. We provide detailed solutions to help you complete your assignments efficiently.


![](https://miro.medium.com/v2/resize:fit:875/1*a15g_5B9iY-bzzKKXbPR1A.jpeg)

## Programming in Modern C++ Week 5 Assignment Answers (Jan-Apr 2025)

**Course Link: [**Click Here**](https://onlinecourses.nptel.ac.in/noc25_cs58/preview)**

***

Q1. Consider the following code segment:

    #include <iostream>
    using namespace std;
    class myClass1 {
        static int x1;
        double x2;
    public:
        void fun() { cout << "fun" << endl; }
    };
    class myClass2 : public myClass1 {
        double dt;
    };
    int myClass1::x1 = 0;
    int main() {
        myClass2 d;
        cout << sizeof(d);
        return 0;
    }

What will be the output? (Assume `sizeof(double) = 8` and `sizeof(int) = 4`)

a) 16\
b) 12\
c) 20\
d) 24

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Q2. Consider the following code segment:

    #include <iostream>
    using namespace std;
    class base {
    protected:
        int m1;
    public:
        base(int x) : m1(x) { }
        void f1() { cout << m1 << endl; }
    };
    class derived : public base {
    public:
        derived(int x) : base(x) { }
        void f1(int a) { cout << a << endl; }
    };
    int main() {
        derived d(10);
        d.f1(); // LINE-1
        return 0;
    }

What will be the output/error?

a) 10\
b) 44\
c) 12\
d) Compilation Error: no matching function for call to `derived::f1()`

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Q3. Consider the following code segment:

    #include <iostream>
    using namespace std;
    class base {
    public:
        void print() { cout << "C" << " "; }
    };
    class derived : public base {
    public:
        void print() { cout << "CH" << " "; }
    };
    int main() {
        base *a1 = new base();
        base *b1 = new derived();
        a1->print();
        b1->print();
        return 0;
    }

What will be the output?

a) C\
b) C CH\
c) CH\
d) CH CH

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Q4. Consider the following code segment:

    #include<iostream>
    using namespace std;
    class A {
    public:
        int a;
        A(int x) : a(x) { }
    };
    class B : protected A {
        int b;
    public:
        B(int x, int y) : A(x), b(y) {}
    };
    int main() {
        B t1(1,2);
        A t2(5);
        cout << t1.a; // LINE-1
        cout << t2.a; // LINE-2
        return 0;
    }

Which line will generate a compilation error in the `main()` function?

a) LINE-1\
b) LINE-2\
c) Both LINE-1 and LINE-2\
d) No compilation error

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Q5. Consider the following code segment:

    #include<iostream>
    using namespace std;
    class A {
    public:
        A() { cout << "A "; }
        ~A() { cout << "~A "; }
    };
    class B : public A {
    public:
        B() { cout << "B "; }
        ~B() { cout << "~B "; }
    };
    class C : public B {
    public:
        C() { cout << "C "; }
        ~C() { cout << "~C "; }
    };
    int main() {
        C obj;
        return 0;
    }

What will be the output?

a) A B C \~C \~B \~A\
b) A A B C \~C \~B \~A\
c) A B A B C \~C \~B \~A \~A\
d) A A B C A \~A \~A

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Q6. Consider the following code segment:

    #include <iostream>
    using namespace std;
    class base {
    public:
        static void func() { cout << "C++" << endl; }
    };
    class derived : private base {
    public:
        derived () {
            // LINE-1
        }
    };
    int main() {
        derived d;
        return 0;
    }

Fill in the blank at LINE-1 such that the output is `"C++"`

a) `(new base)->func()`\
b) `base::func()`\
c) `base.func()`\
d) `base::func`

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Q7. Consider the following code segment:

    #include <iostream>
    using namespace std;
    class A1 {
    public:
        int t1;
    };
    class A2 : private A1 {
    public:
        int t2;
        int sum() { return t1 + t2; }
    };
    int main() {
        A1 b;
        A2 d;
        b.t1 = 10; // LINE-1
        d.t1 = 20; // LINE-2
        d.t2 = 30; // LINE-3
        cout << d.sum(); // LINE-4
        return 0;
    }

Which line/s in the `main()` function will generate a compilation error?

a) LINE-1\
b) LINE-2\
c) LINE-3\
d) LINE-4

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Q8. Consider the following code segment:

    #include<iostream>
    using namespace std;
    class B {
        int x;
    public:
        B(int _x) : x(_x) {}
        int fun() { return x; }
    };
    class D : public B {
        int y;
    public:
        D(int _x, int _y) : B(_x), y(_y) {} // LINE-1
        void fun() { cout << B::fun() << y; }
    };
    int main() {
        D *b2 = new D(1,0);
        b2->fun();
        return 0;
    }

Fill in the blank at LINE-1 such that the program will print `10`.

a) `B(x), y(y)`\
b) `B(y), y(y)`\
c) `y(y), B(y)`\
d) `y(x), B(y)`

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Q9. Consider the following code segment:

    #include<iostream>
    using namespace std;
    class myClass1 {
        int x;
    public:
        myClass1(int a) : x(a) {}
        void fun() {
            cout << x;
        }
    };
    class myClass2 : public myClass1 {
        int y;
    public:
        myClass2(int a, int b) : myClass1(a), y(b) {}
        void fun() {
            cout << y;
        }
    };
    int main() {
        myClass2 m(1,2);
        // LINE-1
        return 0;
    }

Fill in the blank at LINE-1 such that the program will print `4`.

a) `myClass1.m::fun()`\
b) `m.myClass1::fun()`\
c) `m.myClass1.fun()`\
d) `myClass1.m.fun()`

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)


Programming in Modern C++ Week 5 Assignment Answers (July-Dec 2024)


# Programming in Modern C++ Week 5 Assignment Answers (July-Dec 2024)

Q1.Consider the following code segment.

What will be the output?\
a)1, 2,3

b) 1, 2, 3–3, 1, 2, 3–3,\
c) 1,2, 3–3, 4, 5, 6–6,\
d) 1–1, 2, 3, 4–4, 5, 6,

[**Answer: Click here to see answers**](https://progiez.com/programming-in-modern-c-week-5-assignment-answers)

**Q2** Consider the following code segment.

What will be the output?\
a) AB C- C -B -A\
b)A A B C -C A -A\
c) A C -C -A

d) A A B C -C -B- A- A

[**Answer: Click here to see answers**](https://progiez.com/programming-in-modern-c-week-5-assignment-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**Q3.**Consider the following code segment.

What will be the output?

a) Vehicle created, Car created, Vehicle created, Bike created, SportsCar created, SportsCar destroyed, Bike destroyed, Vehicle destroyed, Car destroyed, Vehicle\
destroyed,

b) Vehicle created, Car created, SportsCar created, Vehicle created, Bike created, Bike destroyed, Vehicle destroyed, SportsCar destroyed, Car destroyed, Vehicle\
destroyed,

c) Vehicle created, Car created, SportsCar created, Bike created, Bike destroyed, SportsCar destroyed, Car destroyed, Vehicle destroyed,

d) Vehicle created, Car created, Sports Car created, Bike created, Vehicle destroyed, Car destroyed, Sports Car destroyed, Bike destroyed,

[**Answer: Click here to see answers**](https://progiez.com/programming-in-modern-c-week-5-assignment-answers)

**Q4.**Consider the following code segment.

Choose the appropriate option to fill in the blank at LINE-1 such that the output of the code becomes Instrument: :play().

a) g.play()

b) Instrument: :play()

¢) g.Instrument: :play()

d) Instrument::g.play()

[**Answer: Click here to see answers**](https://progiez.com/programming-in-modern-c-week-5-assignment-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**Q5.**Consider the following code segment.

Choose the appropriate option(s) to fill in the blank at LINE-1 such that the output becomes |\
25 15 5\
a) this->value << ” ” << Parent::value << ” ” << value |\
b) Child::value << ” ” << Parent::value << ” ” << value |\
c) value << ” ” << Parent::value << ” ” << ::value |\
d) Child: :value << ” ” << Parent::value << ” ” << ::value |

[**Answer: Click here to see answers**](https://progiez.com/programming-in-modern-c-week-5-assignment-answers)

**Q6.** Consider the following code segment.

a) memberVar = 6, globalVar = 7\
memberVar = 1, globalVar = 8

b) memberVar = 6, globalVar = 8\
memberVar = 1, globalVar = 0

c) memberVar = 1, globalVar = 7\
memberVar = 2, globalVar = 8

d) memberVar = 1, globalVar = 7\
memberVar = 1, globalVar = 0

[**Answer: Click here to see answers**](https://progiez.com/programming-in-modern-c-week-5-assignment-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**Q7.** Consider the following code segment.

‘What will be the output /error?

a) 12345:Sedan:

b) 12346:Sedan:101

c) compiler error at LINE-1: Vehicle is an inaccessible base of Car

d) compiler error at LINE-2: ‘display’ was not declared in this scope

[**Answer: Click here to see answers**](https://progiez.com/programming-in-modern-c-week-5-assignment-answers)

**Q8.** Consider the following code segment.

‘What will be the output /error?

a) 40 30

b) 40 40

c) Compiler error: ’Basek operator=(const Basek)’ is private\
d) Compiler error: ’Base(const Basek obj)’ is private

[**Answer: Click here to see answers**](https://progiez.com/programming-in-modern-c-week-5-assignment-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**Q9.**Consider the following code segment.

What will be the output /error(s)?

a) 10 20 30

b) compiler error at LINE-1: X::x is not accessible\
c) compiler error at LINE-2: X::x is not accessible\
d) compiler error at LINE-3: Y::y is not accessible

[**Answer: Click here to see answers**](https://progiez.com/programming-in-modern-c-week-5-assignment-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

For answers to additional Nptel courses, please refer to this link: [NPTEL Assignment](https://progiez.com/nptel-assignment-answers)


# Programming in Modern C++ Week 5 Assignment Answers (JAN-APR 2024)

**Course Name: Programming in Modern C++**

**Course Link:** [**Click Here**](https://onlinecourses.nptel.ac.in/noc24_cs44/preview)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)


# Quiz

Q1. Consider the following code segment.\
What will be the output/error?\
a) 6.75\
b) 0\
c) 675\
d) Compilation error: no matching function for call to ‘Derived::calculate()’

**Answer: d) Compilation error: no matching function for call to ‘Derived::calculate()’**

**Q2. Consider the following code segment.\
What will be the output?**\
a) C Programming\
C++ Programming\
b) C++ Programming\
C Programming\
c) C Programming\
C Programming\
d) C++ Programming\
C++ Programming

**Answer: c) C Programming\
C Programming**

**Q3. Consider the following code segment.\
What will be the output?**\
a) 1 2 3 -3 -2 -1\
b) 1 2 1 2 3 -3 -2 -1 -2 -1\
c) 1 3 -3 -1\
d) 1 1 2 3 -3 -2 -1 -1

**Answer: b) 1 2 1 2 3 -3 -2 -1 -2 -1**

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 5 Answers**

**Q4. Consider the following code segment.\
Fill in the blank at LINE-1 so that the program will print Father.**\
a) Father::print();\
b) Father.print();\
c) (new Father)->print();\
d) Father->print();

**Answer: a), c)**

**Q5. Consider the following code segment.\
Fill in the blank at LINE-1 so that the output is 1.**\
a) obj.Base->f ()\
b) obj. Base::f()\
c) obj.Base.f()\
d) Base : : f()

**Answer: b) obj. Base::f()**

**Q6. Consider the following code segment.\
Fill in the blank at LINE-1 so that the program will print 30 20 10.**\
a) Class2::x << ” ” << Class1 : : x << ” ” << x\
b) Class2::x << ” ” << Class1 : : x << ” ” << : : x\
c) x << ” ” << Class1 : : x << ” ” << : : x\
d) : : x << ” ” << Class1 : : x << ” ” << : : x

**Answer: b), c)**

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 5 Answers**

**Q7. Consider the following code segment.\
Fill in the blank at LINE-1 so that the program will print 23.**\
a) Print (\_x), y(\_y)\
b) Print (\_y), y(\_x)\
c) y(\_y), Print (\_x)\
d) y(\_x), Print (\_y)

**Answer: a), c)**

**Q8. Consider the following code segment.\
What will be the output /error?**\
a) 1 2\
b) 1 3\
c) 1 1\
d) Compilation error: int A::x is inaccessible

**Answer: d) Compilation error: int A::x is inaccessible**

**Q9. Consider the following code segment.\
Fill in the blank at LINE-1 such that the program will run successfully without any error.**\
a) private\
b) protected\
c) public\
d) friend

**Answer: c) public**

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 5 Answers**
