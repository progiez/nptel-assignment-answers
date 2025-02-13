# NPTEL Programming DSA Using Python Week 04 Assignment Answers

Are you looking for NPTEL Programming DSA Using Python Week 04 Assignment Answers? This repository will help you find your answers and solutions for Week 04 of the Programming DSA Using Python course. We provide detailed solutions to help you complete your assignments efficiently.


![Programming DSA using Python Week 4 Assignment Answers (July-Dec 2024)](https://miro.medium.com/v2/resize:fit:875/1*tP4NyxEZKtH0uzyo9w0B2Q.jpeg)

## _Programming DSA using Python Week 4 Assignment Answers (Jan-Apr 2025)_

Q1. Consider the following Python function:

    def mystery(l):
        if (l == []):
            return(l)
        else:
            mid = len(l)//2
            if (len(l) % 2 == 0):
                return l[mid-1:mid+1] + mystery(l[:mid-1] + l[mid+1:])
            else:
                return l[mid:mid+1] + mystery(l[:mid] + l[mid+1:])

What does `mystery([22,14,19,65,82,55])` return?

👉 **[**View Answer**](https://my.progiez.com/courses/programming-data-structures-and-algorithms-using-python-nptel-answers/)**

***

Q2. What is the value of `triples` after the following assignment?

    triples = [ (x,y,z) for x in range(1,4) for y in range(2,5) for z in range(5,8) if x+y > z ]

👉 **[**View Answer**](https://my.progiez.com/courses/programming-data-structures-and-algorithms-using-python-nptel-answers/)**

***

Q3. Consider the following dictionary:

    marks = {
        "Quizzes": {"Mahesh": [3,5,7,8], "Suresh": [9,4,8,8], "Uma": [9,9,7,6]},
        "Exams": {"Mahesh": [37], "Uma": [36]}
    }

Which of the following statements does **not** generate an error?

    marks["Exams"]["Suresh"].extend([44])
    marks["Exams"]["Suresh"] = [44]
    marks["Exams"]["Suresh"].append(44)
    marks["Exams"]["Suresh"][0:] = [44]

👉 **[**View Answer**](https://my.progiez.com/courses/programming-data-structures-and-algorithms-using-python-nptel-answers/)**

***

Q4. Assume that `inventory` has been initialized as an empty dictionary:

    inventory = {}

Which of the following generates an error?

    inventory["Amul"] = ["Mystic Mocha", 55]
    inventory["Amul, Mystic Mocha"] = 55
    inventory[["Amul", "Mystic Mocha"]] = 55  # (Possible Error)
    inventory[("Amul", "Mystic Mocha")] = 55

👉 **[**View Answer**](https://my.progiez.com/courses/programming-data-structures-and-algorithms-using-python-nptel-answers/)**

***


## _Programming DSA using Python Week 4 Assignment Answers (July-Dec 2024)_

***

Q1Consider the following Python function.

def mystery(l):\
if l == \[]:\
return(l)\
else:\
return(mystery(l\[1:])+l\[:1])

What does mystery(\[22,14,19,65,82,55]) return?

**Answer: \[55,82,65,19,14,22]**

***

**Q2.**What is the value of pairs after the following assignment?\
pairs = \[ (x,y) for x in range(4,1,-1) for y in range(5,1,-1) if (x+y)%3 == 0 ]

**Answer: \[(4,5),(4,2),(3,3),(2,4)]**

***

**_**For answers or latest updates join our telegram channel: [**Click here to join**](https://telegram.me/nptel_assignments)**_**

**_**These are Programming DSA using Python Week 4 Assignment Answers**_**

***

**Q3.** Consider the following dictionary.\
wickets = {“Tests”:{“Bumrah”:\[3,5,2,3],”Shami”:\[4,4,1,0],”Ashwin”:\[2,1,7,4]},”ODI”:{“Bumrah”:\[2,0],”Shami”:\[1,2]}}\
Which of the following statements does not generate an error?\
wickets\[“ODI”]\[“Ashwin”]\[0:] = \[4,4]\
wickets\[“ODI”]\[“Ashwin”].extend(\[4,4])\
wickets\[“ODI”]\[“Ashwin”] = \[4,4]\
wickets\[“ODI”]\[“Ashwin”] = wickets\[“ODI”]\[“Ashwin”] + \[4,4]

**Answer: wickets\[“ODI”]\[“Ashwin”] = \[4,4]**

***

**Q4.** Assume that hundreds has been initialized as an empty dictionary:\
hundreds = {}\
Which of the following generates an error?\
hundreds\[“Tendulkar, international”] = 100\
hundreds\[“Tendulkar”] = {“international”:100}\
hundreds\[(“Tendulkar”,”international”)] = 100\
hundreds\[\[“Tendulkar”,”international”]] = 100

**Answer: hundreds\[\[“Tendulkar”,”international”]] = 100**

***

**_**For answers or latest updates join our telegram channel: [**Click here to join**](https://telegram.me/nptel_assignments)**_**

**_**These are Programming DSA using Python Week 4 Assignment Answers**_**

Programming, Data Structures and Algorithms using Python NPTEL All weeks: [Click Here](https://progiez.com/nptel-assignment-answers/programming-data-structure-and-algorithms-using-python)


Programming DSA using Python Week 4 Assignment Answers (July-Dec 2024)


# Programming DSA using Python Week 4 Assignment Answers (July-Dec 2024)

Q1Consider the following Python function.

def mystery(l):\
if l == \[]:\
return(l)\
else:\
return(mystery(l\[1:])+l\[:1])

What does mystery(\[22,14,19,65,82,55]) return?

**Answer:** [**Click Here to view Answer**](https://progiez.com/programming-dsa-using-python-week-4-assignment-answers)

**Q2.**What is the value of pairs after the following assignment?\
pairs = \[ (x,y) for x in range(4,1,-1) for y in range(5,1,-1) if (x+y)%3 == 0 ]

**Answer:** [**Click Here to view Answer**](https://progiez.com/programming-dsa-using-python-week-4-assignment-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming DSA using Python Week 4 Assignment Answers**

**Q3.** Consider the following dictionary.\
wickets = {“Tests”:{“Bumrah”:\[3,5,2,3],”Shami”:\[4,4,1,0],”Ashwin”:\[2,1,7,4]},”ODI”:{“Bumrah”:\[2,0],”Shami”:\[1,2]}}\
Which of the following statements does not generate an error?\
wickets\[“ODI”]\[“Ashwin”]\[0:] = \[4,4]\
wickets\[“ODI”]\[“Ashwin”].extend(\[4,4])\
wickets\[“ODI”]\[“Ashwin”] = \[4,4]\
wickets\[“ODI”]\[“Ashwin”] = wickets\[“ODI”]\[“Ashwin”] + \[4,4]

**Answer:** [**Click Here to view Answer**](https://progiez.com/programming-dsa-using-python-week-4-assignment-answers)

**Q4.** Assume that hundreds has been initialized as an empty dictionary:\
hundreds = {}\
Which of the following generates an error?\
hundreds\[“Tendulkar, international”] = 100\
hundreds\[“Tendulkar”] = {“international”:100}\
hundreds\[(“Tendulkar”,”international”)] = 100\
hundreds\[\[“Tendulkar”,”international”]] = 100

**Answer:** [**Click Here to view Answer**](https://progiez.com/programming-dsa-using-python-week-4-assignment-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming DSA using Python Week 4 Assignment Answers**

Programming, Data Structures and Algorithms using Python NPTEL All weeks: [Click Here](https://progiez.com/nptel-assignment-answers/programming-data-structure-and-algorithms-using-python)

More Nptel Courses: <https://progiez.com/nptel-assignment-answers>


# Programming DSA using Python Week 4 Assignment Answers (JULY-DEC 2023)

**Course Name: Programming Data Structure And Algorithms Using Python**

**Course Link:** [**Click Here**](https://onlinecourses.nptel.ac.in/noc23_cs95/announcements?force=true)

**These are Programming DSA using Python Week 4 Assignment Answers**


# Quiz

**Q1) Consider the following Python function.\
def mystery(l):\
if l == \[]:\
return(l)\
else:\
return(l\[-1:]+mystery(l\[:-1]))\
What does mystery(\[23,35,19,58,93,46]) return?**

Answer: \[46, 93, 58, 19, 35, 23]

**Q2) What is the value of pairs after the following assignment?\
pairs = \[ (x,y) for x in range(6,1,-1) for y in range(3,1,-1) if (x+y)%2 == 0 ]**

Answer: \[(6,2), (5,3), (4,2), (3,3), (2,2)]

**Q3) Consider the following dictionary.\
goals = {“Country”:{“Ronaldo”:123,”Messi”:103,”Pele”:83},”Club”:{“Ronaldo”:\[512,51,158],”Pele”:\[604,49,26]}}\
Which of the following statements does not generate an error?**\
goals\[“Club”]\[“Messi”]\[0:] = \[496,71,145]\
goals\[“Club”]\[“Messi”].extend(\[496,71,145])\
goals\[“Club”]\[“Messi”] = \[496,71,145]\
goals\[“Club”]\[“Messi”] = goals\[“Club”]\[“Messi”] + \[496,71,145]

**Answer: goals\[“Club”]\[“Messi”] = \[496,71,145]**

**Q4) Assume that wickets has been initialized as an empty dictionary:\
wickets = {}\
Which of the following generates an error?**\
wickets\[“Muralitharan, tests”] = 800\
wickets\[“Muralitharan”] = {“tests”:800}\
wickets\[(“Muralitharan”,”tests”)] = 800\
wickets\[\[“Muralitharan”,”tests”]] = 800

**Answer: wickets\[\[“Muralitharan”,”tests”]] = 800**


# Assignment

**Question 1\
Write a Python function histogram(l) that takes as input a list of integers with repetitions and returns a list of pairs as follows:\
for each number n that appears in l, there should be exactly one pair (n,r) in the list returned by the function, where r is the number of repetitions of n in l.\
the final list should be sorted in ascending order by r, the number of repetitions. For numbers that occur with the same number of repetitions, arrange the pairs in ascending order of the value of the number.**

Answer:

    def histogram(l):
        count,ans,k = 0,list(),[]
        for i in range(len(l)):
            index,count=i,0
            for j in range(index,len(l)):
                if l[index] == l[j] and l[index] not in k :
                    count =count + 1
            k = k + [l[index]] 
            if (count != 0): 
                ans = ans + [(l[index], count)]
        ans.sort()
        ans=sorted(ans,key=lambda ans:ans[1])
        return(ans)
      
      
    def transcript(coursedetails, studentdetails, grades):
        ans = list()
        studentdetails.sort()
        coursedetails.sort()
        grades.sort()
        for studentdet in studentdetails:
            tuple,inlist = studentdet,list()
            for grade in grades:
                if studentdet[0] == grade[0]:
                    for cdetail in coursedetails:
                        if grade[1] == cdetail[0]:
                            intuple = cdetail
                            intuple = intuple + (grade[2],)
                            inlist.append(intuple)
            tuple = tuple + (inlist,)
            ans.append(tuple)
        return(ans)

**These are Programming DSA using Python Week 4 Assignment Answers**

More Weeks of Programming Data Structure And Algorithms Using Python: [Click here](https://progiez.com/nptel-assignment-answers/programming-data-structure-and-algorithms-using-python)

More Nptel Courses: [Click here](https://progiez.com/nptel-assignment-answers)
