# NPTEL Design and Analysis of Algorithms Week 07 Assignment Answers

Are you looking for NPTEL Design and Analysis of Algorithms Week 07 Assignment Answers? This repository will help you find your answers and solutions for Week 07 of the Design and Analysis of Algorithms course. We provide detailed solutions to help you complete your assignments efficiently.

## Design and analysis of algorithms Week 7 Quiz Answers (Jan-Apr 2025)

Course link: [**Click here**](https://onlinecourses.nptel.ac.in/noc25_cs23/course)

***

**Que.1** Let Watch\[i] denote the maximum number of complete matches that can be watched among {Mi, Mi+1, …, Mn}. Which of the following is a correct recursive formulation of Watch\[i]?\
a) Watch\[1] = 1, Watch\[i] = max(Watch\[i − 1] + 1, Watch\[Next\[i − 1]]), i ∈ {2, 3, …, n}\
b) Watch\[n] = 1, Watch\[i] = max(1 + Watch\[Next\[i]], Watch\[i + 1]), i ∈ {1, 2, …, n−1}\
c) Watch\[1] = 1, Watch\[i] = max(Watch\[i − 1], 1 + Watch\[Next\[i − 1]]), i ∈ {2, 3, …, n}\
d) Watch\[n] = 1, Watch\[i] = max(Watch\[Next\[i]], 1 + Watch\[i + 1]), i ∈ {1, 2, …, n−1}\
[View Answer](https://my.progiez.com/courses/design-and-analysis-of-algorithms-answers/)

***

**Que.2** What is the size of the memo table for this problem?\
a) N+1\
b) N\
c) N-1\
d) N²\
[View Answer](https://my.progiez.com/courses/design-and-analysis-of-algorithms-answers/)

***

**Que.3** What is a good order to compute Watch\[i] using dynamic programming?\
a) From Watch\[n] to Watch\[1]\
b) From Watch\[1] to Watch\[n]\
c) Either from Watch\[1] to Watch\[n] or from Watch\[n] to Watch\[1]\
d) None of these\
[View Answer](https://my.progiez.com/courses/design-and-analysis-of-algorithms-answers/)

***

**Que.4** How much time will it take to compute Watch\[1] using dynamic programming?\
a) O(n³)\
b) O(n²)\
c) O(n log n)\
d) O(n)\
[View Answer](https://my.progiez.com/courses/design-and-analysis-of-algorithms-answers/)

***

**Que.5** Suppose the list of matches to be watched is presented in the form:\
\[(7,45), (15,31), (35,47), (46,61), (48,60), (57,58), (59,63), (64,70), (71,80), (75,90), (81,83), (91,100)]

where each match Mi is represented by a pair (Si,Ti) indicating its starting time and ending time.\
To be able to watch both Mi and Mj, for j > i, it must be the case that Sj > Ti.

[****See also**  **Design and analysis of algorithms Nptel Week 6 Quiz Answers****](https://progiez.com/design-and-analysis-of-algorithms-week-6-quiz-answers)

What is the maximum number of matches you can watch in this case?\
[View Answer](https://my.progiez.com/courses/design-and-analysis-of-algorithms-answers/)
