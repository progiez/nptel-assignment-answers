# NPTEL Programming In Modern C Week 01 Assignment Answers

Are you looking for NPTEL Programming In Modern C Week 01 Assignment Answers? This repository will help you find your answers and solutions for Week 01 of the Programming In Modern C course. We provide detailed solutions to help you complete your assignments efficiently.

![](https://miro.medium.com/v2/resize:fit:875/1*BWdKgwW5z0uF7VsYO4jcwQ.jpeg)

Programming in Modern C++ Week 1 Assignment Nptel Answers

## _Programming in Modern C++ Week 1 Assignment Answers_ _(July-Dec 2025)_

***

**Question 1.** Consider the following code segment.

    #include<iostream>
    #include<string>
    using namespace std;
    int main() {
        string greet = "Welcome Back";
        // LINE-1
        cout << greet;
        return 0;
    }

Choose the correct option to fill in the blank at LINE-1 so that the output is Welcome.\
a) greet.resize(7)\
b) greet.shrink\_to\_fit()\
c) greet.copy(“Welcome”, 7, 0)\
d) strncpy(greet, “Welcome”, 7)

[View Answers](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**Question 2.** Consider the following code segment.

    #include<iostream>
    #include<algorithm>
    using namespace std;
    bool descending(int i, int j) {
        return (i > j);
    }
    int main() {
        int arr[] = {8, 3, 5, 9, 6, 7};
        sort(______________); // LINE-1
        for(int i=0; i<6; i++)
            cout << arr[i] <<" ";
        return 0;
    }

Choose the correct option to fill in the blank at LINE-1 so that the output is 8 5 3 9 6 7.\
a) arr, arr+3, descending\
b) \&arr\[0], \&arr\[0]+4, descending\
c) arr+1, arr+4, descending\
d) \&arr, \&arr+3, descending

[View Answers](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**Question 3.** Consider the following code and find the correct output.

    #include<iostream>
    #include<vector>
    #include<algorithm>
    using namespace std;
    int main() {
        vector<int> nums = {10, 20, 30, 40, 50, 60, 70};
        rotate(nums.begin(), nums.begin()+2, nums.begin()+4);
        for(auto i : nums)
            cout << i <<" ";
        return 0;
    }

a) 30 10 20 40 50 60 70\
b) 30 40 10 20 50 60 70\
c) 40 10 20 30 50 60 70\
d) 10 30 20 40 50 60 70

[View Answers](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**Question 4.** Consider the following code and find the correct output or error.

    #include<iostream>
    #include<stack>
    using namespace std;
    int main() {
        int arr[5] = {6, 2, 5, 4, 1};
        stack<int> s;
        for(int i=0; i<5; i++) {
            while(!s.empty() && s.top() >= arr[i])
                s.pop();
            if (s.empty())
                cout << -1 <<" ";
            else
                cout << s.top() << " ";
            s.push(arr[i]);
        }
        return 0;
    }

a) -1 6 2 2 1\
b) -1 -1 6 2 2\
c) -1 -1 2 2 -1\
d) Compilation Error

[View Answers](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**Question 5.** Consider the following code segment.

    #include<iostream>
    using namespace std;
    int sumRows(_________) {
        // returns the sum of first row
    }
    int main() {
        int mat[3][3] = {{1,2,3}, {4,5,6}, {7,8,9}};
        cout << sumRows(mat);
        return 0;
    }

Choose the correct option to fill in the blank at LINE-1 so that the program does not generate any compilation error.\
a) int mat\[10]\
b) int mat\[]\[3]\
c) int mat\[3]\[]\
d) int mat\[3]\[3]

[View Answers](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**Question 6.** Consider the following code and choose the correct output.

    #include<iostream>
    using namespace std;
    int main() {
        bool x = false, y = true, z = true;
        cout << (x && y | 2);
        return 0;
    }

a) 0\
b) 1\
c) false\
d) true

[View Answers](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**Question 7.** Consider the following code segment.

    #include <iostream>
    #include <string>
    using namespace std;
    int main() {
        string word1 = "Good ";
        string word2 = "Morning";
        // LINE-1
        cout << message;
        return 0;
    }

Fill in the blank at LINE-1 so that the program generates output as Good Morning.\
a) string message = word1 + word2;\
b) string message = strcat(word1, word2);\
c) string message = word1.insert(word2);\
d) string message = word1.append(word2);

[****See also**  **Programming in Modern C++ | Week 7****](https://progiez.com/nptel-programming-in-modern-c-assignment-7-answers)

[View Answers](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**Question 8.** Consider the following code segment.

    #include <iostream>
    #include <algorithm>
    int main() {
        int data[] = {5, 10, 15, 20, 25};
        int key = 20;
        if (__________) // LINE-1
            std::cout << "Found";
        else
            std::cout << "Not Found";
        return 0;
    }

Fill in the blank at LINE-1 so that the program generates output as Found.\
a) binary\_search(data, data+3, key)\
b) std::binary\_search(data, data+5, key)\
c) std::binary\_search(data, data+3, key)\
d) binary\_search(data, data+5, key)

[View Answers](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**Question 9.** Consider the following code and choose the correct output.

    #include <iostream>
    #include <algorithm>
    using namespace std;
    int main() {
        int data[] = {2, 3, 3, 4, 5, 5, 6};
        replace(data, data+7, 3, 5);
        for (int i = 0; i < 4; ++i)
            cout << data[i] << " ";
        return 0;
    }

a) 2 4 6 5\
b) 2 4 6 3\
c) 2 5 5 4\
d) 2 5 6 6

[View Answers](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)


## _Programming in Modern C++ Week 1 Assignment Answers_ _(Jan-Apr 2025)_

**Course Link: [**Click Here**](https://examform.nptel.ac.in/2025_01/exam_form/dashboard)**

***

**Que. 1) Consider the following program:**

    #include <iostream>
    #include <stack>
    using namespace std;
    char str[] = "COMPUTER";
    stack<char> s1, s2;
    int i;
    for (i = 0; i < strlen(str); i++)
        s1.push(str[i]);
    while (!s1.empty()) {
        s2.push(s1.top());
        s1.pop();
    }
    while (!s2.empty()) {
        cout << s2.top();
        s2.pop();
    }
    return 0;

a) COMPUTER\
b) REIUPHDC\
c) UTERCOHP\
d) CINPRETU

[**View Answer**](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)

***

**Que. 2) Which of the following is a container adapter?**\
a) stack\
b) queue\
c) deque\
d) priority-queue

**[****View Answer****](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)**

***

**Que. 3) Consider the following code segment:**

    #include <iostream>
    using namespace std;
    int main() {
        char data[] = "2453";
        char key = '5';
        if (binary_search(data, data+5, key)) {
            cout << "found";
        } else {
            cout << "not found";
        }
        return 0;
    }

Identify the appropriate option to fill in the blank such that the output is “found.”\
a) key\
b) data, data+5, key\
c) data, key, data+5\
d) \&key, \&data\[5]

**[****View Answer****](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)**

***

**Que. 4) Consider the following code:**

    #include <iostream>
    #include <algorithm>
    using namespace std;
    void modify(int* arr) {
        rotate(arr, arr+3, arr+2);
        rotate(arr+4, arr+3, arr+5);
    }
    int main() {
        int arr[5];
        for (int i = 0; i < 5; ++i) {
            cin >> arr[i];
        }
        modify(arr);
        for (int i = 0; i < 5; ++i) {
            cout << arr[i];
        }
        return 0;
    }

What will be the output?\
a) 1 2 3 4 5\
b) 5 4 3 2 1\
c) 4 5 1 2 3\
d) 1 5 4 3 2

**[****View Answer****](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)**

***

**Que. 5) Consider the following code segment:**

    #include <iostream>
    #include <vector>
    using namespace std;
    int main() {
        vector<int> cVec(3, -1);
        for (int i = 0; i < 3; i++) {
            cVec[i] = (i + 1) * 10;
        }
        cVec.resize(3);
        cVec.resize(3, 110);
        for (int i = 0; i < cVec.size(); i++) {
            cout << cVec[i] << " ";
        }
        return 0;
    }

What will be the output?\
a) 10 20 30 20 40 60\
b) -1 -1 -1 10 20 30 20 40 60\
c) -1 -1 -1 10 20 30 0 0 0 20 40 60\
d) 10 20 30

**[****View Answer****](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)**

***

**Que. 6) Consider the following code segment:**

    #include <iostream>
    #include <algorithm>
    using namespace std;
    int main() {
        int iarr[] = {10, 50, 40, 10, 50};
        rotate(iarr, iarr+6, 50);
        for (int i = 0; i < 4; ++i)
            cout << iarr[i] << " ";
        return 0;
    }

Fill in the blank such that the output is 40 10 10 50.\
a) rotate(iarr, iarr+6, 50)\
b) rotate(iarr, iarr+6, iarr\[5])\
c) rotate(iarr, iarr+6, iarr\[4])\
d) rotate(iarr, iarr+5, 50)

[****See also**  **Programming in Modern C++ | Week 1****](https://progiez.com/nptel-programming-in-modern-c-assignment-1-answers)

**[****View Answer****](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)**

***

**Que. 7) Consider the following code segment:**

    #include <iostream>
    #include <algorithm>
    using namespace std;
    int main() {
        int idata[] = {1, 2, 3, 4, 5};
        int n = sizeof(idata) / sizeof(idata[0]);
        for (int i = 0; i < n / 2; i++) {
            int temp = idata[i];
            replace(idata, idata + 5, temp, *(idata + n - i - 1));
            replace(idata + i + 1, idata + 5, idata[n - i - 1], temp);
        }
        for (int i = 0; i < 5; ++i) {
            cout << idata[i] << " ";
        }
        return 0;
    }

What will be the output?\
a) 3 2 1 2 3\
b) 1 2 3 4 5\
c) 5 4 3 2 1\
d) 5 4 3 4 5

**[****View Answer****](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)**

***

**Que. 8) Consider the following code segment:**

    #include <iostream>
    #include <string>
    using namespace std;
    int main(void) {
        string str1 = "Modern ";
        string str2 = "C++";
        str1.append(str2);
        cout << str1;
        return 0;
    }

What is the appropriate option to fill in the blank at LINE-I, such that the output of the code would be “Modern C++”?\
a) str1 + str2\
b) strcat(str1, str2)\
c) str1.append(str2)\
d) str1.insert(str2)

**[****View Answer****](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)**

***

**Que. 9) Consider the following code segment:**

    #include <iostream>
    #include <algorithm>
    using namespace std;
    int main() {
        int iArr[] = {40, 50, 10, 30, 20};
        rotate(iArr, iArr+4, iArr+6);
        for (int i = 0; i < 5; i++) {
            cout << iArr[i] << " ";
        }
        return 0;
    }

What will be the output?\
a) 10 30 40 50 20\
b) 50 40 30 20 10\
c) 10 20 30 40 50\
d) 30 20 10 40 50

**[****View Answer****](https://my.progiez.com/courses/programming-in-modern-cpp-nptel-answers/)**

***

**Session: JULY-DEC 2024**

**Course Name: Programming in Modern C++**

**Course Link:** [**Click Here**](https://onlinecourses.nptel.ac.in/noc24_cs125/)

These are Programming in Modern C++ Week 1 Assignment 1 Nptel Answers


Q1.Consider the following program\
Fill in the blank at LINE-1 such that the output is Good Morning.\
a) message.resize(12)\
b) message.clear()\
c) message.replace(0, 12, “Good Morning”)\
d) strcpy(message, “Good Morning”)<a id="d316"></a>
---------------------------------------------------

[**_**ANSWER: Click here to see answer**_**](https://progiez.com/programming-in-modern-cpp-week-1-assignment-1-nptel)

**Q2.Consider the following code segment.\
Identify the appropriate option(s) to fill in the blank at LINE-1, such that the output is:\
2 4 9 8 6 3 1**\
a) \&arr\[0], \&arr\[0] + 3, compare\
b) arr, arr + 3, compare\
c) \&arr\[0], \&arr\[0] + 2, compare\
d) arr, arr+ 2, compare

[**_**ANSWER: Click here to see answer**_**](https://progiez.com/programming-in-modern-cpp-week-1-assignment-1-nptel)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 1 Assignment 1 Nptel Answers**

**Q3. Consider the following code segment.\
What will be the output?**\
a) 60 15 25 35 45\
b) 60 25 15 35 45\
c) 60 25 35 45 15\
d) 60 25 35 15 45

[**_**ANSWER: Click here to see answer**_**](https://progiez.com/programming-in-modern-cpp-week-1-assignment-1-nptel)

**Q4.Consider the following code segment.\
What will be the output?**\
a) 10 20 30 40 50 60\
b) 10 20 60 30 40 50\
c) 60 30 40 50 10 20\
d) 20 30 40 60 10 50

[**_**ANSWER: Click here to see answer**_**](https://progiez.com/programming-in-modern-cpp-week-1-assignment-1-nptel)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 1 Assignment 1 Nptel Answers**

**Q5. Consider the following code segment .\
What will be the output?**\
a) 5 5 5 5 101 102 103 99 99 99\
b) 5 5 5 5 100 101 102 103 99 99\
c) 5 5 5 5 101 102 103 99 99\
d) 5 5 5 5 100 101 102 103 99 99 99 99

[**_**ANSWER: Click here to see answer**_**](https://progiez.com/programming-in-modern-cpp-week-1-assignment-1-nptel)

**Q6. Consider the following code segment .\
What will be the output?**\
a) ProABXYZing\
b) ProABgXYZramming\
c) ProABXYZmming\
d) ProXYZABgramming

[**_**ANSWER: Click here to see answer**_**](https://progiez.com/programming-in-modern-cpp-week-1-assignment-1-nptel)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 1 Assignment 1 Nptel Answers**

**Q7. Consider the following code segment .\
Fill in the blank at LINE-1 such that the output is 50 20 30 40 50**\
a) array + 4 i\
b) array + 5 i\
c) arrayi-4\
d) array + i 5

[**_**ANSWER: Click here to see answer**_**](https://progiez.com/programming-in-modern-cpp-week-1-assignment-1-nptel)

**Q8. Consider the following code segment.\
What will be the output?**\
a) ABCDEKJIHGFE\
b) ABCDEKJIHG\
c) ABCDEJIHGF\
d) ABCDEFGHIJK

[**_**ANSWER: Click here to see answer**_**](https://progiez.com/programming-in-modern-cpp-week-1-assignment-1-nptel)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 1 Assignment 1 Nptel Answers**

**Q9. Consider the following code segment\
Identify the appropriate option/s to fill in the blank at LINE-1 such that output becomes lval 20 rval 20.\
Which statement/statements is/are correct?**\
a) STMT-1\
b) STMT-2\
c) STMT-3\
d) STMT-4

[**_**ANSWER: Click here to see answer**_**](https://progiez.com/programming-in-modern-cpp-week-1-assignment-1-nptel)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 1 Assignment 1 Nptel Answers**


# Programming Questions<a id="0dbf"></a>

**W1\_Programming-Qs.1\
Consider the program below.\
• Fill in the blank at LINE-1 to declare a stack variable st.\
• Fill in the blank at LINE-2 to push values into the stack.\
• Fill in the blank at LINE-3 with the appropriate statement.\
The program must satisfy the given test cases.**

**Solution:**

    ANSWER: Click here to see answer

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 1 Assignment 1 Nptel Answers**

**W1\_Programming-Qs.2\
Consider the following program.\
• Fill in the blank at LINE-1 with the appropriate if statement,\
• Fill in the blank at LINE-2 and LINE-3 with the appropriate return statements.\
The program must satisfy the sample input and output.**

**Solution:**

    ANSWER: Click here to see answer

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 1 Assignment 1 Nptel Answers**

**W1\_Programming-Qs.3\
Consider the program below.\
• Fill in the blank at LINE-1 to include the appropriate header file to utilize the abs () function.\
• Fill in the blank at LINE-2 to compute the Manhattan distance between two points pt1 and pt2 as pt1.ypt2.y+pt1.x pt2.r\
The program must satisfy the given test cases.**

**Solution:**

    ANSWER: Click here to see answer

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Modern C++ Week 1 Assignment 1 Nptel Answers**

More Solutions of Programming in Modern C++: [Click Here](https://progiez.com/nptel-assignment-answers/nptel-programming-in-modern-cpp-answers)

More Nptel Courses: <https://progiez.com/nptel-assignment-answers>
