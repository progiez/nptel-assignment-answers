# NPTEL Introduction To Operating Systems Week 03 Assignment Answers

Are you looking for NPTEL Introduction To Operating Systems Week 03 Assignment Answers? This repository will help you find your answers and solutions for Week 03 of the Introduction To Operating Systems course. We provide detailed solutions to help you complete your assignments efficiently.


![](https://miro.medium.com/v2/resize:fit:875/1*DRkbdwM0MQ1jK04naaSrBw.jpeg)


## _Introduction to Operating Systems Nptel Week 3 Answers_ (July-Dec 2025)

***

**Question 1. Match the following**\
a. Inode → 3) Stores metadata\
b. New state → 1) The pid is assigned to a process\
c. Trapframe → 4) For restarting a process after a context switch\
d. Init → 2) Never exits\
a) a-4, b-2, c-3, d-1\
b) a-3, b-4, c-2, d-1\
c) a-4, b-1, c-2, d-3\
d) a-3, b-1, c-4, d-2

[View Answers](https://my.progiez.com/courses/introduction-to-operating-systems-nptel-answers/)

***

**Question 2. We have n number of fork system calls, denoted as nXfork(). What is the total number of processes created?**\
a) n\
b) 2ⁿ\
c) 2ⁿ⁻¹\
d) (2ⁿ) − 1

[View Answers](https://my.progiez.com/courses/introduction-to-operating-systems-nptel-answers/)

***

**Question 3. State True/False: The process whose parent exited before the child is an orphan process. Can a process be Zombie and Orphan at the same time.**\
a) True\
b) False

[View Answers](https://my.progiez.com/courses/introduction-to-operating-systems-nptel-answers/)

***

**Question 4. What is the output of the following program for any value of `a`**

    int main() {
        int a, pid;
        pid = fork();
        if(pid == 0) {
            a = a + 5;
            printf("u = %d\n", a);
        } else {
            a = a - 5;
            printf("x = %d\n", a);
        }
    }

a) u = x + 5\
b) x = u + 5\
c) x = u + 10\
d) u = x + 10

[View Answers](https://my.progiez.com/courses/introduction-to-operating-systems-nptel-answers/)

***

**Question 5. Which of the below statements is false?**\
a) Init is the first process created using booting\
b) Init process is a daemon process\
c) Init process has process identifier as 1\
d) None of these

[View Answers](https://my.progiez.com/courses/introduction-to-operating-systems-nptel-answers/)

***

**Question 6. A student has written a program and used `pid = fork()` function call in it. The pid returned by the fork was 5119. Which of the following is true about the process invoking fork?**\
a) Process is a parent process with pid = 5119\
b) Process is a child process. Its Parent’s pid is 5119\
c) The process is a parent process. Its Child’s pid is 5119\
d) Process is a child process with pid = 5119

[View Answers](https://my.progiez.com/courses/introduction-to-operating-systems-nptel-answers/)

***

**Question 7. Which of the following is false?**\
a) Process: Contains code + data + heap + stack + process state\
b) Program: One program can be used to create many processes\
c) Process: Process is not a unique isolated entity\
d) Program: Code + Static and Global data

[View Answers](https://my.progiez.com/courses/introduction-to-operating-systems-nptel-answers/)

***

**Question 8. The state transition that occurs due to the `scanf` system call in the program is \_\_\_\_\_\_.**

    int main() {
        int a;
        scanf("%d \n", &a);
        exit(0);
    }

a) NEW → READY\
b) READY → RUNNING\
c) RUNNING → BLOCKED\
d) BLOCKED → READY

[View Answers](https://my.progiez.com/courses/introduction-to-operating-systems-nptel-answers/)

***

**Question 9. Which one of the following is the property of Operating System that helps to prevent attacks?**\
a) i) Rings\
b) i), ii)\
c) i), ii), iii)\
d) i), ii), iii), iv)

[View Answers](https://my.progiez.com/courses/introduction-to-operating-systems-nptel-answers/)

***

**Question 10. Match the following**

1. If the parent and the child process share the same page table. Does this mean they share the same page frames in the RAM? COW creates a copy of the shared pages if it changes.
2. All further changes are made in this new page.\
   a) True, False\
   b) False, True\
   c) False, False\
   d) True, True

[View Answers](https://my.progiez.com/courses/introduction-to-operating-systems-nptel-answers/)

***

**Question 11. Match the following**\
a. Init.d → 3) Created by kernel while booting\
b. Zombie → 4) Allows a parent process to read the status of child\
c. Child process → 2) The %eax register is cleared when this is created\
d. Trapframe → 1) Created when system call occurs\
a) a-1, b-2, c-3, d-4\
b) a-3, b-4, c-2, d-1\
c) a-2, b-1, c-4, d-3\
d) a-4, b-3, c-1, d-2

[View Answers](https://my.progiez.com/courses/introduction-to-operating-systems-nptel-answers/)

***

**Question 12. State True/False: In memory mapping, the entire kernel is mapped into the process’ address space, which helps the user process to easily access the kernel data.**\
a) True\
b) False

[View Answers](https://my.progiez.com/courses/introduction-to-operating-systems-nptel-answers/)

***

**Question 13. Arrange the following in order**\
a. Change state to runnable\
b. Copy page directory contents from parent to child process\
c. Copy the trapframe from the parent process\
d. Change state to embryo\
a) a, c, b, d\
b) c, d, a, b\
c) d, b, c, a\
d) a, c, b, d

[****See also**  **Introduction to Operating Systems Nptel Week 6 Answers****](https://progiez.com/introduction-to-operating-systems-nptel-week-6-answers)

[View Answers](https://my.progiez.com/courses/introduction-to-operating-systems-nptel-answers/)

***

**Question 14. `wait()` system call inside the parent process returns the status of the child. What does it return when it is called inside the child?**\
a) Returns -1 , when it is not the parent of any other process\
b) Returns its own process id\
c) Returns the exit status of the parent currently exited\
d) None of these

[View Answers](https://my.progiez.com/courses/introduction-to-operating-systems-nptel-answers/)

***

**Question 15. State True/False: `execlp()` system call replaces the child process with a new program file, but the process ID will not change.**\
a) True\
b) False

[View Answers](https://my.progiez.com/courses/introduction-to-operating-systems-nptel-answers/)


Introduction to Operating Systems Nptel Week 3 Answers (July-Dec 2024)


# Introduction to Operating Systems Nptel Week 3 Answers (July-Dec 2024)<a id="de44"></a>

**Q1**.If the MAX\_SIZE is 0x20000000, the virtual address of a kernel variable is 0x2fffffff, and the Physical memory starts from 0x00000000, then the Physical address of the kernel variable will be **_**\_**_**.\
0xffffffff\
0x00ffffff\
0x0fffffff\
0xffffff

[**Answer: Click here to see answer**](https://progiez.com/introduction-to-operating-systems-nptel-week-3-answers)

**Q2.**The kernel pages in Physical and Virtual Address space are mapped randomly.\
True\
False

[**Answer: Click here to see answer**](https://progiez.com/introduction-to-operating-systems-nptel-week-3-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Introduction to Operating Systems Nptel Week 3 Answers**

**Q3.**There are multiple copies of kernel in the Physical Address space but there is only one copy of kernel in Virtual Address space from where all the processes share it.\
True\
False

[**Answer: Click here to see answer**](https://progiez.com/introduction-to-operating-systems-nptel-week-3-answers)

**Q4.**There are two processes currently in a system. Process A has no I/O operations, process B has an I/O operation that reads the input from the keyboard. When Process A pre-empts process B (not executing I/O) process B goes from _to_ **_**\_**_**.\
Ready, Running\
Ready, Runnable\
Running, Ready\
Blocked, Runnable

[**Answer: Click here to see answer**](https://progiez.com/introduction-to-operating-systems-nptel-week-3-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Introduction to Operating Systems Nptel Week 3 Answers**

**Q5**There are two processes currently in a system. Process A has no I/O operations, process B has an I/O operation that reads input from the keyboard. When Process B executes the I/O, and Process A goes from _to_ **_**\_**_**.\
Running, Ready\
Ready, Runnable\
Ready. Running\
Blocked, Runnable

[**Answer: Click here to see answer**](https://progiez.com/introduction-to-operating-systems-nptel-week-3-answers)

**Q6**.When a child is being created from a parent using the fork() system call initially the state of the process is set to READY state and before the fork() system call returns the state is changed to RUNNING.\
True\
False

[**Answer: Click here to see answer**](https://progiez.com/introduction-to-operating-systems-nptel-week-3-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Introduction to Operating Systems Nptel Week 3 Answers**

**Q7.**When a child process is created using the fork() system call, its state is set to running.\
True\
False

[**Answer: Click here to see answer**](https://progiez.com/introduction-to-operating-systems-nptel-week-3-answers)

**Q8.A zombie process is used to remove the reaper processes created on termination, which if not controlled, might lead to infinite resource leakage.**\
True\
False

[**Answer: Click here to see answer**](https://progiez.com/introduction-to-operating-systems-nptel-week-3-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Introduction to Operating Systems Nptel Week 3 Answers**

**Q9.I. The value of all the registers are same for parent and child process except for the registers %eip and %ebp**II. forkret changes only the %eip of child\
I- False, II- True\
I- False, II- False\
I- True, II — True\
I- True, II — False

**Answer:**

**Q10. -s flag of the readelf utility shows details about _**\_\_\_**_.**\
Syntax errors\
Symbol table\
Semantics\
Headers

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Introduction to Operating Systems Nptel Week 3 Answers**

All weeks of Introduction to Operating Systems: [Click Here](https://progiez.com/nptel-assignment-answers/introduction-to-operating-systems)

For answers to additional Nptel courses, please refer to this link: [NPTEL Assignment Answers](https://progiez.com/nptel-assignment-answers)


# Introduction to Operating Systems Nptel Week 3 Answers (July-Dec 2023)<a id="b4ac"></a>

**Course Name: Introduction to Operating Systems**

**Course Link:** [**Click Here**](https://onlinecourses.nptel.ac.in/noc23_cs101/course)

**These are Introduction to Operating Systems NPTEL Week 3 Assignment Answers**

**Q1. Match the following\
a. Inode 1) The pid is assigned to a process\
b. New state 2)Never exits\
c. Trapframe 3)Stores metadata\
d. init 4) For restarting a process after a context switch**\
a-4, b-2, c-3, d-1\
a-3, b-4, c-2, d-1\
a-4, b-1, c-2, d-3\
a-3, b-1, c-4, d-2

**Answer: a-3, b-1, c-4, d-2**

**Q2. We have n number of fork system calls, denoted as nXfork(). What is the total number of process created?**\
n\
2^n\
2^(n-1)\
(2^n) — 1

**Answer: 2^n**

**Q3. State True/ False\
The process whose parent exited before the child is an orphan process. Can a process can be Zombie and Orphan at the same time.**\
True\
False

**Answer: False**

**These are Introduction to Operating Systems NPTEL Week 3Assignment Answers**

**Q4. What is the output of the following program for any value of a**\
u =x+5\
x=u+5\
x=u+10\
u=x+10

**Answer: u =x+5**

**Q5. Which of the below statement is false.**\
Init is the first process created using booting\
Init process is a daemon process.\
Init process have process identifier as 1\
None of these

**Answer: None of these**

**Q6. A student have written a program and used pid = fork() function call in it. The pid returned by the fork was 5119. Which of the following is true about the process invoking fork?**\
Process is a parent process with pid = 5119\
Process is a child process. Its Parent’s pid is 5119\
The process is a parent process. Its Child’s pid is 5119\
Process is a child process with pid = 5119

**Answer: The process is a parent process. Its Child’s pid is 5119**

**These are Introduction to Operating Systems NPTEL Week 3 Assignment Answers**

**Q7. Which of the following is false?**\
Process : Contains code+data+heap+stack+process state\
Program : One program can be used to create many processes\
Process : Process is not a unique isolated entity\
Program : Code + Static and Global data

**Answer: Process : Process is not a unique isolated entity**

**Q8. The state transition that occurs due to the scanf system call in the program is \_\_\_\_\_\_.**\
NEW -> READY\
READY -> RUNNING\
RUNNING -> BLOCKED\
BLOCKED -> READY

**Answer: RUNNING -> BLOCKED**

**Q9. Which one of the following is the property of Operating system that helps to prevent attacks?\
i)Rings\
ii) a separate stack for the kernel\
iii)Virtual memory\
iv) Shared Libraries**\
i\
i, ii\
i, ii, iii\
i, ii, iii, iv

**Answer: i, ii**

**These are Introduction to Operating Systems NPTEL Week 3 Assignment Answers**

**Q10. State True or False.\
1\. If the parent and the child process share the same page table. Does this mean they share the same page frames in the RAM?\
2\. COW creates a copy of the shared pages if it changes. All further changes are made in this new page.**\
True, False\
False, True\
False, False\
True, True

**Answer: True, True**

**Q11. Match the following\
a. Init.d 1) Created when system call occurs\
b. Zombie 2) The %eax register is cleared when this is created\
c. Child process 3) Created by kernel while booting\
d. Trapframe 4) Allows a parent process to read the status of child**\
a-1, b-2, c-3, d-4\
a-3, b-4, c-2, d-1\
a-2, b-1, c-4, d-3\
a-4, b-3, c-1, d-2

**Answer: a-3, b-4, c-2, d-1**

**Q12. State True/False\
In memory mapping, the entire kernel is mapped into process’ address space, which helps the user process to easily access the kernel data.**\
True\
False

**Answer: False**

**These are Introduction to Operating Systems NPTEL Week 3 Assignment Answers**

**Q13. Arrange the following in order\
a. Change state to runnable\
b. Copy page directory contents from parent to child process\
c. Copy the trapframe from the parent process\
d. Change state to embryo**\
a, c, b, d\
c, d, a, b\
d, b, c, a\
a, c, b, d

**Answer: d, b, c, a**

**Q14. wait() system call inside the parent process returns the status of the child. What does it returns when it is called inside the child?**\
Returns -1 , when it is not the parent of any other process\
Returns its own process id\
Returns the exit status of the parent currently exited.\
None of these.

**Answer: Returns -1 , when it is not the parent of any other process**

**Q15. State True/False\
execlp() system call replaces the child process with a new program file, but the process ID will not change.**\
True\
False

**Answer: True**

**These are Introduction to Operating Systems NPTEL Week 3 Assignment Answers**

More Weeks of Introduction to Operating Systems: [Click here](https://progiez.com/nptel-assignment-answers/introduction-to-operating-systems)

More Nptel Courses: [Click here](https://progiez.com/nptel-assignment-answers)
