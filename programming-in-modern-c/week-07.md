# NPTEL Programming In Modern C++ Week 07 Assignment Answers

Are you looking for NPTEL Programming In Modern C Week 07 Assignment Answers? This repository will help you find your answers and solutions for Week 07 of the Programming In Modern C course. We provide detailed solutions to help you complete your assignments efficiently.


<figure class="aligncenter size-large is-resized"><img decoding="async" width="1024" height="576" src="https://progiez.com/wp-content/uploads/2024/09/Programming-in-Modern-C-Nptel-Week-7-Assignment-Answer-and-solution-Swayam-Platform-image-1024x576.webp" alt="Programming in Modern C++ Week 7 Assignment Answers" class="wp-image-13616" title="Programming in Modern C++ Week 7 Assignment Answers 1" srcset="https://progiez.com/wp-content/uploads/2024/09/Programming-in-Modern-C-Nptel-Week-7-Assignment-Answer-and-solution-Swayam-Platform-image-1024x576.webp 1024w, https://progiez.com/wp-content/uploads/2024/09/Programming-in-Modern-C-Nptel-Week-7-Assignment-Answer-and-solution-Swayam-Platform-image-300x169.webp 300w, https://progiez.com/wp-content/uploads/2024/09/Programming-in-Modern-C-Nptel-Week-7-Assignment-Answer-and-solution-Swayam-Platform-image-768x432.webp 768w, https://progiez.com/wp-content/uploads/2024/09/Programming-in-Modern-C-Nptel-Week-7-Assignment-Answer-and-solution-Swayam-Platform-image.webp 1280w" sizes="(max-width: 1024px) 100vw, 1024px"><figcaption class="wp-element-caption">Programming in Modern C++ Week 7 Assignment Answers</figcaption></figure>

## Programming in Modern C++ Week 7 Assignment Answers (Jan-Apr 2025)

***

Que. 1 Consider the following code segment.

    #include <iostream>
    using namespace std;
    class Employee {
        string name;
    public:
        Employee(string _name = "unknown") : name(_name) {}
        void update(string na) const {
            // LINE-1
        }
        void showInfo() const {
            cout << "Name: " << name;
        }
    };
    int main(void) {
        const Employee e("Sam");
        e.update("Sameer");
        e.showInfo();
        return 0;
    }

Fill in the blank at LINE-1 such that the program will print Name: Sameer.

a) `const_cast<Employee*>(this)`\
b) `static_cast<Employee*>(this)`\
c) `dynamic_cast<Employee*>(this)`\
d) `(Employee*)(this)`

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Que. 2 Consider the following code segment.

    #include <iostream>
    using namespace std;
    int incr(int* ptr){
        return ++(*ptr);
    }
    int main(void) {
        int x = 5;
        const int *ptr = &x;
        // LINE-1
        cout << x;
        return 0;
    }

Fill in the blank at LINE-1 such that the program will print 6.

a) `const_cast<int*>(ptr)`\
b) `static_cast<int*>(ptr)`\
c) `dynamic_cast<int*>(ptr)`\
d) `reinterpret_cast<int*>(ptr)`

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Que. 3 What will be the virtual function table for the class A3?

a) `A1::f(A1* const)`, `A3::g(A3* const)`, `A3::h(A3* const)`, `A2::i(A2* const)`\
b) `A1::f(A1* const)`, `A2::g(A2* const)`, `A3::h(A3* const)`, `A2::i(A2* const)`\
c) `A1::f(A1* const)`, `A2::g(A2* const)`, `A2::h(A2* const)`, `A3::i(A3* const)`\
d) `A1::f(A1* const)`, `A2::g(A2* const)`, `A3::h(A3* const)`, `A3::i(A3* const)`

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Que. 4 How many virtual tables will be created for the following classes?

    class A { public: void f() {} };
    class B : public A { public: virtual void f() { } };
    class C : public A { public: void g() {} };
    class D : public B, public C { public: void g() {} };

a) 1\
b) 2\
c) 3\
d) 4

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Que. 5 Which of the following type-casting is permissible?

    class st1 { };
    class st2 { };
    st1* s1 = new st1;
    st2* s2 = new st2;

a) `s2 = static_cast<st2*>(s1);`\
b) `s2 = dynamic_cast<st2*>(s1);`\
c) `s2 = reinterpret_cast<st2*>(s1);`\
d) `s2 = const_cast<st2*>(s1);`

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Que. 6 What will be the output of the following program?

    #include <iostream>
    #include <typeinfo>
    using namespace std;

    class Base { public: virtual ~Base(){} };
    class Derived: public Base {};

    int main() {
        Base b; Derived d;
        Derived *dp = &d;
        Base *bp = dp;
        Derived *dpp = (Derived*)bp;
        cout << (typeid(dp).name() == typeid(bp).name());
        cout << (typeid(*dp).name() == typeid(*bp).name());
        cout << (typeid(bp).name() == typeid(dpp).name());
        cout << (typeid(*bp).name() == typeid(*dpp).name());
        return 0;
    }

a) 0101\
b) 1010\
c) 0111\
d) 1011

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Que. 7 What will be the output of the following code segment?

    #include <iostream>
    using namespace std;
    class Base{
    public:
        virtual void f() {
            cout << "Base ";
        }
    };
    class Derived : public Base{
    public:
        virtual void f() {
            cout << "Derived ";
        }
    };
    int main() {
        Base objb;
        Derived objd;
        try {
            Base& ra1 = static_cast<Base&>(objd); // LINE-1
            ra1.f();
            Base& ra2 = dynamic_cast<Base&>(objd); // LINE-2
            ra2.f();
            Derived& rb1 = static_cast<Derived&>(objb); // LINE-3
            rb1.f();
            Derived& rb2 = dynamic_cast<Derived&>(objb); // LINE-4
            rb2.f();
        }
        catch (exception& e) {
            cout << e.what();
        }
        return 0;
    }

a) `Derived Derived Base`\
b) `Derived Derived Base Base`\
c) `Derived Derived Base std::bad_cast`\
d) `Derived Base Derived Base`

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Que. 8 What will be the output of the following code segment?

    #include <iostream>
    using namespace std;
    class A { public: virtual ~A() {} };
    class B : public A {};
    class C : public A {};
    int main(){
        A objA;
        B objB;
        A* pA = static_cast<A*>(&objB); // LINE-1
        pA == NULL ? cout << "cast-1 invalid:" : cout << "cast-1 valid:";
        B* pB = static_cast<B*>(pA); // LINE-2
        pB == NULL ? cout << "cast-2 invalid:" : cout << "cast-2 valid:";
        C* pC = dynamic_cast<C*>(new A); // LINE-3
        pC == NULL ? cout << "cast-3 invalid:" : cout << "cast-3 valid:";
        pC = dynamic_cast<C*>(&objB); // LINE-4
        pC == NULL ? cout << "cast-4 invalid" : cout << "cast-4 valid";
        return 0;
    }

a) `cast-1 valid:cast-2 valid:cast-3 invalid:cast-4 invalid`\
b) `cast-1 valid:cast-2 invalid:cast-3 invalid:cast-4 invalid`\
c) `cast-1 valid:cast-2 valid:cast-3 valid:cast-4 invalid`\
d) `cast-1 valid:cast-2 invalid:cast-3 valid:cast-4 invalid`

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

Que. 9 What will be the output of the following code?

a) `108`\
b) `107`\
c) `721`\
d) `720`

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)


## **Programming in Modern C++ Week 7 Assignment Answers (July-Dec 2024**)

* * *

Q1.Fill in the blank at LINE-1 and LINE-2 with the same statement such that the program will  
print Ram : 30000.

a) const\_cast (this)

b) static\_cast (this)

c) dynamic\_cast (this)

d) (employees) (this)

**Answer:** [Click here to view Answers](https://progiez.com/programming-in-modern-c-week-7-assignment-answers)

* * *

**Q2** ‘What will be virtual function table (VFT) for the class A3?  
a) A3::f(A3\*const)  
 A2::g(A2 \* const)  
 A3::h(A3 *const) A2::1(A2* const)  
b) A1::f(A1\* const)  
A2::g(A2* const)*

*A3::h(A3* const)  
A2::i(A2* const)*

*c) A1::f(A1* const)  
A2::g(A2* const)*

*A2::h(A2* const)  
A3::i(A3* const)*

*d) A1::f(A1* const)  
A2::g(A2* const)*

*A3::h(A3* const)  
A3::i(A3\* const)

**Answer: **a)

* * *

**<mark class="has-inline-color has-vivid-red-color">For answers or latest updates join our telegram channel:<span> </span><a href="https://telegram.me/nptel_assignments" target="_blank" rel="noreferrer noopener">Click here to join</a></mark>**

* * *

**Q3.**‘Which line/s will give compilation error?  
a) LINE-1  
b) LINE-2  
c) LINE-3  
d) LINE-4

**Answer:** [Click here to view Answers](https://progiez.com/programming-in-modern-c-week-7-assignment-answers)

* * *

**Q4.**Which of the following type-casting is permissible?  
a) tst2 = static\_cast(tsti);

b) tst2 = dynamic\_cast(tsti);

c) tst2 = reinterpret\_cast(tsti);  
d) tst2 = const\_cast(tstl);

**Answer:** [Click here to view Answers](https://progiez.com/programming-in-modern-c-week-7-assignment-answers)
* * *

**<mark class="has-inline-color has-vivid-red-color">For answers or latest updates join our telegram channel:<span> </span><a href="https://telegram.me/nptel_assignments" target="_blank" rel="noreferrer noopener">Click here to join</a></mark>**

* * *

**Q5.**What will be the output? 

a) 0101   
b) 0111   
c) 0110   
d) 0010 

**Answer:** [Click here to view Answers](https://progiez.com/programming-in-modern-c-week-7-assignment-answers)
* * *

**Q6. **‘What will be the output?  
a) 0101  
b) 1010  
c) 1100  
d) 1011

**Answer:** [Click here to view Answers](https://progiez.com/programming-in-modern-c-week-7-assignment-answers)
* * *

**<mark class="has-inline-color has-vivid-red-color">For answers or latest updates join our telegram channel:<span> </span><a href="https://telegram.me/nptel_assignments" target="_blank" rel="noreferrer noopener">Click here to join</a></mark>**

* * *

**Q7. **Fill in the blank at LINE-1 so that the program will print 10.  
a) const\_cast&lt;double\*&gt;

b) static\_cast &lt;double\*&gt;  
c) dynamic\_cast &lt;doubles&gt;  
d) (const double\*)

**Answer:** [Click here to view Answers](https://progiez.com/programming-in-modern-c-week-7-assignment-answers)

* * *

**Q8. **Consider the following code segment.

Fill in the blank at LINE-1 so that the program will print “C++”.   
a) reinterpret\_cast   
b) static\_cast   
c) dynamic\_cast   
d) (Bs)

**Answer:** [Click here to view Answers](https://progiez.com/programming-in-modern-c-week-7-assignment-answers)

* * *

**<mark class="has-inline-color has-vivid-red-color">For answers or latest updates join our telegram channel:<span> </span><a href="https://telegram.me/nptel_assignments" target="_blank" rel="noreferrer noopener">Click here to join</a></mark>**

* * *

**Q9.**How many virtual function table (VFT) will be created?  
a) 1  
b) 2  
c) 3  
d) 4

**Answer:** [Click here to view Answers](https://progiez.com/programming-in-modern-c-week-7-assignment-answers)

* * *

**<mark class="has-inline-color has-vivid-red-color">For answers or latest updates join our telegram channel:<span> </span><a href="https://telegram.me/nptel_assignments" target="_blank" rel="noreferrer noopener">Click here to join</a></mark>**

For answers to additional Nptel courses, please refer to this link: [NPTEL Assignment](https://progiez.com/nptel-assignment-answers)
