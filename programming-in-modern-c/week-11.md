# NPTEL Programming In Modern C Week 11 Assignment Answers

Are you looking for NPTEL Programming In Modern C Week 11 Assignment Answers? This repository will help you find your answers and solutions for Week 11 of the Programming In Modern C course. We provide detailed solutions to help you complete your assignments efficiently.

## _Programming in Modern C++ Week 11 Assignment Answers (Jan-Apr 2025)_

**Course Link: [**Click Here**](https://onlinecourses.nptel.ac.in/noc25_cs58/course)**

***

**1) Consider the code segment (in C++11) given below.**

Identify the line/s where indicates a universal reference.

a) LINE-I\
b) LINE-2\
c) LINE-3\
d) LINE-4

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**2) Consider the code segment (in C++11) given below.**

    #include<iostream>
    void fun(const int& i){ std::cout << "Lvalue " << i << std::endl; }
    void fun(int&& i){ std::cout << "Rvalue " << i << std::endl; }

    template<typename T, typename U>
    void wrapper(T&& n1, U&& n2){
        fun(n1);
        fun(n2);
        fun(std::move(n1));
        fun(std::move(n2));
        fun(std::forward<T>(n1));
        fun(std::forward<U>(n2));
    }

    int main(){
        int i = 10;
        wrapper(i, std::move(i));
        return 0;
    }

What will be the output?

a)\
b)\
c)\
d)

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**3) Consider the following class (in C++11).**

    #include <iostream>
    enum class Color { RED, GREEN, YELLOW } color;
    enum class Signal { RED, GREEN, YELLOW } signal;
    enum Tint { RED, GREEN, YELLOW } tint;

    bool testRed(Color col){
        if (col == Color::RED)
            return true;
        return false;
    }

    bool testGreen(Color col){
        if (col == Signal::GREEN)
            return true;
        return false;
    }

    bool testYellow(Color col){
        if (col == Color::YELLOW)
            return true;
        return false;
    }

    int main() {
        if (testRed(Color::RED)) // LINE-I
        if (testGreen(Color::GREEN)) // LINE-2
        if (testYellow(Color::YELLOW)) // LINE-3
            std::cout << "success";
        return 0;
    }

Identify the statement/s which are true for the given program.

a) It generates compiler error at LINE-I\
b) It generates compiler error at LINE-2\
c) It generates compiler error at LINE-3\
d) It generates the output success

[****See also**  **Programming in Modern C++ | Week 2****](https://progiez.com/nptel-programming-in-modern-c-assignment-2-answers)

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**4) Consider the following code segment (in C++11).**

    #include <iostream>

    template<typename T>
    T findMax(T t){
        return t;
    }

    template<typename T, typename... Args>
    T findMax(T t, Args... args){
        return 
    }

    // LINE-I
    std::cout << findMax(20, 30, 60, 50) << std::endl;
    return 0;

Identify the appropriate return statement at LINE-I such that the function `findMax` finds out the maximum element from the given argument list (in this case the output is 60).

a)\
b)\
c)\
d)

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**5) Consider the following code segment (in C++11).**

    #include <iostream>
    #include <algorithm>
    #include <vector>

    template<typename T>
    void process(std::vector<T>& tVec){
        struct compare{
            bool operator()(T a, T b){ return a > b; }
        };

        std::sort(tVec.begin(), tVec.end(), compare()); // LINE-I
    }

    int main() {
        std::vector<int> iVec {20, 40, 60, 10, 50};
        process(iVec);
        for (int i : iVec)
            std::cout << i << " ";
        return 0;
    }

What will be the output/error?

a) 10 20 40 50 60\
b) 60 50 40 20 10\
c) 20 40 60 10 50\
d) Compiler error at LINE-I: compare is local

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**6) Consider the following code segment (in C++11).**

    #include <iostream>
    #include <vector>
    #include <functional>

    int main(){
        int sum = 0, multi = 0;
        
        auto process = [](int x, int y){
            multi = x * y;
            return x + y;
        };

        auto result = process(10, 20); // LINE-I
        std::cout << "sum = " << result << ", multiplication = " << multi;
        return 0;
    }

Identify the appropriate option(s) to fill in the blanks at LINE-I such that the output becomes `sum = 30, multiplication = 200`.

a) `auto process = [&multi] (int x, int y)`\
b) `auto process = [sum, multi] (int x, int y)`\
c) `auto process = = (int x, int y)`\
d) `auto process = (int x, int y)`

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

[****See also**  **Programming in Modern C++ | Week 9****](https://progiez.com/nptel-programming-in-modern-c-assignment-9-answers)

***

**7) Consider the lambda function (in C++11) below.**

    auto process = [interval, &result] (int val){
        result = val + interval;
        std::cout << val << " " << interval << " = " << result;
    };

Identify the correct option that defines the equivalent Closure object for the above lambda function.

a)\
b)\
c)\
d)

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**8) Consider the following code segment (in C++11).**

    #include <iostream>
    #include <string>

    class Data {
    public:
        explicit Data(int _d1) : d1(_d1) { std::cout << "ctor-1 "; }
    private:
        int d1 {10};
    };

    class DataPair : public Data {
    public:
        DataPair() = default;
        explicit DataPair(int _d1) : DataPair(_d1, 0.0f) { std::cout << "ctor-2 "; }
        explicit DataPair(int _d1, double _d2) : Data(_d1), d2(_d2) { std::cout << "ctor-3 "; }
    private:
        double d2 {0.0};
    };

    int main() {
        DataPair data(100);
        return 0;
    }

What will be the output?

a)\
b)\
c)\
d)

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**9) Consider the following code segment (in C++11).**

    #include <iostream>
    #include <string>

    struct StringData {
        explicit StringData(const std::string& _d) : d(_d) {}
        std::string d;
    };

    struct IntData {
        explicit IntData(const int& _d) : d(_d) {}
        operator int() { return d; }
        explicit operator int*() const { return nullptr; }
        explicit operator std::string() const { return "test"; }
        explicit operator StringData() const { return StringData("test"); }
    private:
        int d;
    };

    int main() {
        IntData data(100);
        int i1 = data; // LINE-I
        int i2 = static_cast<int>(data); // LINE-2
        int *i3 = data; // LINE-3
        int *i4 = static_cast<int*>(data); // LINE-4
        std::string s1 = static_cast<std::string>(data); // LINE-5
        StringData s2 = static_cast<std::string>(data); // LINE-6
        StringData s3 = static_cast<StringData>(data); // LINE-7
        return 0;
    }

Identify the line(s) that will generate compiler error.

a) LINE-I\
b) LINE-2\
c) LINE-3\
d) LINE-4\
e) LINE-5\
f) LINE-6\
g) LINE-7

[View Answer](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)
