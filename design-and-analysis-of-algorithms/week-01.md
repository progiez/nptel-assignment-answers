# NPTEL Design and Analysis of Algorithms Week 01 Assignment Answers

Are you looking for NPTEL Design and Analysis of Algorithms Week 01 Assignment Answers? This repository will help you find your answers and solutions for Week 01 of the Design and Analysis of Algorithms course. We provide detailed solutions to help you complete your assignments efficiently.

![Design and analysis of algorithms Week 1 Quiz Answers](https://progiez.com/wp-content/uploads/2025/01/Design-and-analysis-of-algorithms-Nptel-Week-1-Assignment-Answer-and-solution-Swayam-Platform-image-1024x576.jpg "Design and analysis of algorithms Nptel Week 1 Quiz Answers 1")

__Design and analysis of algorithms Week 1 Quiz Answers__

## Design and analysis of algorithms Week 1 Quiz Answers (July-Dec 2025)

***

**Que.1 What does f(2000, 3) return?**

    f(m, n) {
      ans = 1;
      count = 0;
      while (ans <= m) {
        count = count + 1;
        ans = ans * n;
      }
      return(count)
    }

**[**View Answer**](https://my.progiez.com/courses/design-and-analysis-of-algorithms-answers/)**

***

**Que.2 Suppose someone designs a new airline routing algorithm called MagicPath and claims that its worst-case complexity is O(n² log n). Which of the following statements is inconsistent with this claim?**\
A) For every n, for every input of size n, MagicPath is able to solve the problem in time proportional to n².\
B) For some n, for every input of size n, MagicPath is able to solve the problem in time proportional to n².\
C) For every sufficiently large n, there is an input of size n for which MagicPath requires time proportional to n².\
D) For every sufficiently large n, there is an input of size n for which MagicPath requires time proportional to n³.

**[**View Answer**](https://my.progiez.com/courses/design-and-analysis-of-algorithms-answers/)**

***

**Que.3 You are executing an algorithm with worst-case time complexity O(n⁴) on a CPU that can perform 10⁸ operations per second. Which of the following is the most accurate guarantee for the time required to solve a worst-case input of size 800?**\
A) Under 5 minutes\
B) Under 5 hours\
C) Under 5 days\
D) Under 5 weeks

[****See also**  **Software Engineering Nptel Week 1 Assignment Answers****](https://progiez.com/software-engineering-nptel-week-1-assignment-answers)

**[**View Answer**](https://my.progiez.com/courses/design-and-analysis-of-algorithms-answers/)**

***

**Que.4 Suppose f(n) is n² log n. Consider the following statements:**\
(A) f(n) is O(n √n)\
(B) f(n) is O(n² √n)\
(C) f(n) is O(n³)

Which of the following is true?\
A) (A), (B), and (C) are all not true.\
B) (B) and (C) are true but (A) is not true.\
C) (B) is true but (A) and (C) are not true.\
D) (A) and (B) are true but (C) is not true.

**[**View Answer**](https://my.progiez.com/courses/design-and-analysis-of-algorithms-answers/)**

***

**Que.5 In the code fragment below, `first` and `last` are integer values and `composite(x)` is a function that returns true if x is not a prime number and false otherwise:**

    i = 0; j = 0; k = 0;
    for (m = last; m >= first; m = m - 1){
      k = k + m;
      if (composite(m)){
        i = i + m;
      } else {
        j = j - m;
      }
    }

    if (…) {
      print("True");
    } else {
      print("False");
    }

**Which of the following expressions can we put in place of the missing if condition (…) to ensure that the program prints “True”?**\
A) k == i + j\
B) k == i – j\
C) k == j – i\
D) None of the other options is universally true. The expression depends on the values of first and last.

**[**View Answer**](https://my.progiez.com/courses/design-and-analysis-of-algorithms-answers/)**



## Design and analysis of algorithms Week 1 Quiz Answers (Jan-Apr 2025)

Course link: [Click here](https://onlinecourses.nptel.ac.in/noc25_cs23/course)

***

**Que. 1) An algorithm has two phases. The first phase, initialization, takes time O(n3)O(n^3). The second phase, which is the main computation, takes time O(n2)O(n^2). What is the most accurate description of the complexity of the overall algorithm?**

a) O(n6)O(n^6)\
b) O(n5)O(n^5)\
c) O(n3)O(n^3)\
d) O(n2)O(n^2)

**[**View Answer**](https://my.progiez.com/courses/design-and-analysis-of-algorithms-answers/)**

***

**Que. 2) We are using a computer that performs 10810^8 basic operations per second. We are trying to determine the worst-case time complexity of a library function that is provided to us, whose code we cannot read. We test the function by feeding large numbers of random inputs of different sizes. We find that for inputs of size 50 the function always returns well within one second, for inputs of size 500 it sometimes takes a couple of seconds, and for inputs of size 5,000 it sometimes takes over 15 minutes. What is a reasonable conclusion we can draw about the worst-case time complexity of the library function?**

a) O(n4)O(n^4)\
b) O(n3)O(n^3)\
c) O(n2log⁡n)O(n^2 \log n)\
d) O(n2)O(n^2)

**[**View Answer**](https://my.progiez.com/courses/design-and-analysis-of-algorithms-answers/)**

***

**Que. 3) Suppose f(n)=2n2+4n+5f(n) = 2n^2 + 4n + 5 and g(n)=7n3+5n2+12g(n) = 7n^3 + 5n^2 + 12. Let h(n)h(n) be a third, unknown function. Which of the following is not possible?**

a) h(n)h(n) is O(f(n))O(f(n)) and h(n)h(n) is also O(g(n))O(g(n))\
b) h(n)h(n) is not O(f(n))O(f(n)) and h(n)h(n) is also not O(g(n))O(g(n))\
c) h(n)h(n) is O(f(n))O(f(n)) but h(n)h(n) is not O(g(n))O(g(n))\
d) h(n)h(n) is O(g(n))O(g(n)) but h(n)h(n) is not O(f(n))O(f(n))

[****See also**  **Design and analysis of algorithms Nptel Week 2 Quiz Answers****](https://progiez.com/design-and-analysis-of-algorithms-week-2-quiz-answers)

**[**View Answer**](https://my.progiez.com/courses/design-and-analysis-of-algorithms-answers/)**

***

**Que. 4) How many times is the comparison i≤ni \leq n performed in the following program?**

    int i = 60, n = 300;
    main(){
      while (i <= n){
        i = i + 2;
        n = n - 3; 
      }
    }

a) 48\
b) 49\
c) 50\
d) 51

**[**View Answer**](https://my.progiez.com/courses/design-and-analysis-of-algorithms-answers/)**

***

**Que. 5) If T(n)T(n) is O(n4/3)O(n^{4/3}), which of the following is false?**

a) T(n)T(n) is O(nlog⁡n)O(n \log n)\
b) T(n)T(n) is O(n2)O(n^2)\
c) T(n)T(n) is O(n2log⁡n)O(n^2 \log n)\
d) T(n)T(n) is O(n3)O(n^3)

**[**View Answer**](https://my.progiez.com/courses/design-and-analysis-of-algorithms-answers/)**
