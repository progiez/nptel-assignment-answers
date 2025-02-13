# NPTEL Programming In Java Week 04 Assignment Answers

Are you looking for NPTEL Programming In Java Week 04 Assignment Answers? This repository will help you find your answers and solutions for Week 04 of the Programming In Java course. We provide detailed solutions to help you complete your assignments efficiently.


![Programming in Java Nptel Week 4 Assignment Answers (July-Dec 2024)](https://miro.medium.com/v2/resize:fit:875/1*Z9Ckq7Lfhu8WVNrNIzQCOg.jpeg)

## Programming in Java Nptel Week 4 Assignment Answers (Jan-Apr 2025)

**Course Link: [**Click Here**](https://onlinecourses.nptel.ac.in/noc25_cs57/preview)**

***

Q1. Which access modifier allows a method to be accessible within the same package but not from outside the package?

a) default\
b) private\
c) public\
d) protected

[View Answer](https://my.progiez.com/courses/programming-in-java-nptel-answers/)

***

Q2. What will happen if you attempt to access a private method from another class in Java?

a) The method will be accessible.\
b) The method will throw an exception.\
c) The method will be inaccessible.\
d) The method will be converted to protected.

[View Answer](https://my.progiez.com/courses/programming-in-java-nptel-answers/)

***

Q3. What will be the output of the following code?

    class Person {
        public Person() {
            System.out.println(a + b + " Java");
        }
    }
    class Employee extends Person {
        public Employee() {
            System.out.println(a * b + " Java");
        }
    }
    public class Question {
        public static void main(String args[]) {
            Person p = new Employee();
        }
    }

a) 1Java 10Java\
b) 1Java 0Java\
c) 10Java 0Java\
d) 1Java1 0Java0

[View Answer](https://my.progiez.com/courses/programming-in-java-nptel-answers/)

***

Q4. Which of the following is a built-in Java package?

a) java.util\
b) my.package.util\
c) default.package\
d) system.java

[View Answer](https://my.progiez.com/courses/programming-in-java-nptel-answers/)

***

Q5. What keyword is used to define a package in Java?

a) define\
b) package\
c) import\
d) namespace

[View Answer](https://my.progiez.com/courses/programming-in-java-nptel-answers/)

***

Q6. How do you import a specific class from a package in Java?

a) import package.\*;\
b) import package.ClassName;\
c) include package.ClassName;\
d) use package.ClassName;

[View Answer](https://my.progiez.com/courses/programming-in-java-nptel-answers/)

***

Q7. Consider the following program:

    class Base {
        public void print() {
            System.out.println("Base class...");
        }
    }
    class Derived extends Base {
        public void print() {
            System.out.println("Derived class...");
        }
    }
    public class Main {
        private static void main(String[] args) {
            Base b = new Base();
            b.print();
            Derived d = new Derived();
            d.print();
        }
    }

How many errors does this program contain?

a) None\
b) 1\
c) 2\
d) 3

[View Answer](https://my.progiez.com/courses/programming-in-java-nptel-answers/)

***

Q8. Which of the following is true about Java interfaces?

a) They cannot contain method implementations.\
b) An interface can extend multiple classes.\
c) An interface can only contain abstract methods.\
d) They allow a class to achieve multiple inheritance.

[View Answer](https://my.progiez.com/courses/programming-in-java-nptel-answers/)

***

Q9. What will happen if you do not specify an access modifier for a class in a package?

a) The class will be ‘private’ by default.\
b) The class will be ‘protected’ by default.\
c) The class will be accessible only within the same package.\
d) The class will be ‘public’ by default.

[View Answer](https://my.progiez.com/courses/programming-in-java-nptel-answers/)

***

Q10. Which access modifier provides the most restrictive access in Java?

a) default\
b) protected\
c) private\
d) public

[View Answer](https://my.progiez.com/courses/programming-in-java-nptel-answers/)

***


## Programming in Java Nptel Week 4 Assignment Answers (July-Dec 2024)

**1. Which of these access specifiers must be used for `main()` method?**\
a) private\
b) public\
c) protected\
d) default

**Answer:b) public**

***

**2. What is the output of the below Java Code Snippet with protected access modifier?**

    // Teacher.java ------------------

    package nptel1;

    public class Teacher {

      protected void showMarks() {
        System.out.println("100 Marks");
      }

    }

    // Student.java ------------------

    package nptel2;

    import nptel1.*;

    public class Student extends Teacher {

      void show() {
        showMarks();
      }

      public static void main(String[] args) {
        Student st1 = new Student();
        st1.show();
      }
    }

a) 100 marks\
b) No output\
c) Compiler error\
d) None of the above

**Answer:a) 100 marks**

***

**3. What is the process by which we can control what parts of a program can access the members of a class?**\
a) Polymorphism\
b) Augmentation\
c) Encapsulation\
d) Recursion

**Answer : c) Encapsulation**

***

**4. Consider the 2 programs:**

    // Main1.java ------------------

    public class Main1{
        public static void main(String args[]){  
            int number = 10;
            System.out.println(number++ + ++number);
        }
    }

<!---->

    // Main2.java ------------------

    public class Main2{
        public static void main(String args[]){  
            int number = 10;
            System.out.println(++number + number++);
        }
    }

a) Both pre-increment and post-increment operators become pre-increment during print.\
b) Both pre-increment and post-increment operators become post-increment during print.\
c) Both Main1 and Main2 classes give the same output.\
d) Pre-increment and post-increment operators don’t work during print.

**Answer:** **c) Both Main1 and Main2 classes give the same output.**

***

**5. Which is the least restrictive access modifier in Java?**\
a) public\
b) private\
c) protected\
d) default

**Answer: a) public**

***

**6. Choose the correct syntax of a Java Package below.**\
a) package PACKAGE\_NAME;\
b) package PACKAGE\_NAME._;_

_c) pkg PACKAGE\_NAME;_

_d) pkg PACKAGE\_NAME._;

**Answer:** **a) package PACKAGE\_NAME;**

***

**7. What is the default package in Java?**\
a) It is a package that contains all built-in classes.\
b) It is a package that needs to be defined as default.\
c) It is a package that does not have a name.\
d) It is a package used for importing external libraries.

[****See also**  **Programming In Java | Week 1****](https://progiez.com/nptel-programming-in-java-week-1-assignment-1-answers)

**Answer:** **c) It is a package that does not have a name.**

***

**8. A package is a collection of:**\
a) classes\
b) interfaces\
c) editing tools\
d) classes and interfaces

**Answer: d) classes and interfaces**

***

**9. In Java, can a subclass in a different package access a superclass’s protected method?**\
a) Yes, without any restrictions.\
b) Yes, but only if they are in the same package.\
c) No, protected methods are not accessible by subclasses.\
d) No, protected methods are only accessible within the same class.

**Answer:** **a) Yes, without any restrictions.**

***

**10. Consider the program given below. What will be the output if the program is executed?**

    // Main1.java ------------------

    public class Main1{
        public static void main(String args[]){  
            int number = 10;
            System.out.println(number++ + ++number);
        }
    }

<!---->

    // Main2.java ------------------

    public class Main2{
        public static void main(String args[]){  
            int number = 10;
            System.out.println(++number + number++);
        }
    }

a) It will give compile-time error\
b) It will give run-time error\
c) 1.0\
d) 3.14

**Answer: c) 1.0**

***

All Weeks of Programming In Java: [Click Here](https://progiez.com/nptel-assignment-answers/nptel-programming-in-java-assignment-answers)

For answers to additional Nptel courses, please refer to this link: [NPTEL Assignment Answers](https://progiez.com/nptel-assignment-answers)

***


## Programming in Java Nptel Week 4 Assignment Answers (Jan-Apr 2024)

**Course name: Programming In Java**

**Course Link: [**Click Here**](https://onlinecourses.nptel.ac.in/noc24_cs43/preview)**

**_**For answers or latest updates join our telegram channel: [**Click here to join**](https://telegram.me/nptel_assignments)**_**

***

Q1. Which is the keyword used to specify the default access modifier in java?\
a. default\
b. DEFAULT\
c. package\
d. “There is no keyword”

**Answer: d. “There is no keyword”**

***

**Q2. What is the output of the Java program with access modifiers?**\
a. FOUR\
b. Runtime Error\
c. null\
d. Compiler Error

**Answer: d. Compiler Error**

***

**Q3. What is the output of the below Java Code Snippet with access modifiers?**\
a. Weeks = 0\
b. Weeks = 12\
c. No Error, blank output\
d. Compiler error

**Answer: b. Weeks = 12**

***

**_**For answers or latest updates join our telegram channel: [**Click here to join**](https://telegram.me/nptel_assignments)**_**

**_**_****These are Programming in Java Nptel Week 4 Assignment Answers****_**_**

***

**Q4. Which of the following is the correct representation of access modifiers in order of increasing visibility?**\
a. private < default < protected < public\
b. private < protected < default < public\
c. public < protected < default < private\
d. protected < default < private < public

**Answer: a. private < default < protected < public**

***

**Q5. Which of the following package stores all the standard java classes?**\
a. java.util\
b. java.lang\
c. java.java\
d. java.packages

**Answer: b. java.lang**

***

**Q6. Which of the following is/are true about packages in Java?\
1\. Every class is part of some package.\
2\. All classes in a file are part of the same package.\
3\. If no package is specified, the classes in the file go into a special unnamed package.\
4\. If no package is specified, a new package is created with folder name of class and the class is put in this package.**\
a. Only 1, 2 and 3\
b. Only 1, 2 and 4\
c. Only 4\
d. Only 1 and 3

**Answer: a. Only 1, 2 and 3**


Programming in Java Nptel Week 4 Assignment Answers (July-Dec 2024)


# Programming in Java Nptel Week 4 Assignment Answers (July-Dec 2024)

**1. Which of these access specifiers must be used for** `main()` **method?**\
a) private\
b) public\
c) protected\
d) default

**Answer:** [Click here to view Answers](https://progiez.com/programming-in-java-nptel-week-4-assignment-answers)

**2. What is the output of the below Java Code Snippet with protected access modifier?**

    // Teacher.java ------------------

<!---->

    package nptel1;public class Teacher {  protected void showMarks() {
        System.out.println("100 Marks");
      }}// Student.java ------------------package nptel2;import nptel1.*;public class Student extends Teacher {  void show() {
        showMarks();
      }  public static void main(String[] args) {
        Student st1 = new Student();
        st1.show();
      }
    }

a) 100 marks\
b) No output\
c) Compiler error\
d) None of the above

**Answer:** [Click here to view Answers](https://progiez.com/programming-in-java-nptel-week-4-assignment-answers)

**3. What is the process by which we can control what parts of a program can access the members of a class?**\
a) Polymorphism\
b) Augmentation\
c) Encapsulation\
d) Recursion

**Answer:** [Click here to view Answers](https://progiez.com/programming-in-java-nptel-week-4-assignment-answers)

**4. Consider the 2 programs:**

    // Main1.java ------------------

<!---->

    public class Main1{
        public static void main(String args[]){  
            int number = 10;
            System.out.println(number++ + ++number);
        }
    }

<!---->

    // Main2.java ------------------

<!---->

    public class Main2{
        public static void main(String args[]){  
            int number = 10;
            System.out.println(++number + number++);
        }
    }

a) Both pre-increment and post-increment operators become pre-increment during print.\
b) Both pre-increment and post-increment operators become post-increment during print.\
c) Both Main1 and Main2 classes give the same output.\
d) Pre-increment and post-increment operators don’t work during print.

**Answer:** [Click here to view Answers](https://progiez.com/programming-in-java-nptel-week-4-assignment-answers)

**5. Which is the least restrictive access modifier in Java?**\
a) public\
b) private\
c) protected\
d) default

**Answer:** [Click here to view Answers](https://progiez.com/programming-in-java-nptel-week-4-assignment-answers)

**6. Choose the correct syntax of a Java Package below.**\
a) package PACKAGE\_NAME;\
b) package PACKAGE\_NAME._; c) pkg PACKAGE\_NAME; d) pkg PACKAGE\_NAME._;

**Answer:** [Click here to view Answers](https://progiez.com/programming-in-java-nptel-week-4-assignment-answers)

**7. What is the default package in Java?**\
a) It is a package that contains all built-in classes.\
b) It is a package that needs to be defined as default.\
c) It is a package that does not have a name.\
d) It is a package used for importing external libraries.

**Answer:** [Click here to view Answers](https://progiez.com/programming-in-java-nptel-week-4-assignment-answers)

**8. A package is a collection of:**\
a) classes\
b) interfaces\
c) editing tools\
d) classes and interfaces

**Answer:** [Click here to view Answers](https://progiez.com/programming-in-java-nptel-week-4-assignment-answers)

**9. In Java, can a subclass in a different package access a superclass’s protected method?**\
a) Yes, without any restrictions.\
b) Yes, but only if they are in the same package.\
c) No, protected methods are not accessible by subclasses.\
d) No, protected methods are only accessible within the same class.

**Answer:** [Click here to view Answers](https://progiez.com/programming-in-java-nptel-week-4-assignment-answers)

**10. Consider the program given below. What will be the output if the program is executed?**

    // Main1.java ------------------

<!---->

    public class Main1{
        public static void main(String args[]){  
            int number = 10;
            System.out.println(number++ + ++number);
        }
    }

<!---->

    // Main2.java ------------------

<!---->

    public class Main2{
        public static void main(String args[]){  
            int number = 10;
            System.out.println(++number + number++);
        }
    }

a) It will give compile-time error\
b) It will give run-time error\
c) 1.0\
d) 3.14

**Answer:** [Click here to view Answers](https://progiez.com/programming-in-java-nptel-week-4-assignment-answers)

All Weeks of Programming In Java: [Click Here](https://progiez.com/nptel-assignment-answers/nptel-programming-in-java-assignment-answers)

For answers to additional Nptel courses, please refer to this link: [NPTEL Assignment Answers](https://progiez.com/nptel-assignment-answers)


# Programming in Java Nptel Week 4 Assignment Answers (Jan-Apr 2024)

**Course name: Programming In Java**

**Course Link:** [**Click Here**](https://onlinecourses.nptel.ac.in/noc24_cs43/preview)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

Q1. Which is the keyword used to specify the default access modifier in java?\
a. default\
b. DEFAULT\
c. package\
d. “There is no keyword”

**Answer: d. “There is no keyword”**

**Q2. What is the output of the Java program with access modifiers?**\
a. FOUR\
b. Runtime Error\
c. null\
d. Compiler Error

**Answer: d. Compiler Error**

**Q3. What is the output of the below Java Code Snippet with access modifiers?**\
a. Weeks = 0\
b. Weeks = 12\
c. No Error, blank output\
d. Compiler error

**Answer: b. Weeks = 12**

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Java Nptel Week 4 Assignment Answers**

**Q4. Which of the following is the correct representation of access modifiers in order of increasing visibility?**\
a. private < default < protected < public\
b. private < protected < default < public\
c. public < protected < default < private\
d. protected < default < private < public

**Answer: a. private < default < protected < public**

**Q5. Which of the following package stores all the standard java classes?**\
a. java.util\
b. java.lang\
c. java.java\
d. java.packages

**Answer: b. java.lang**

**Q6. Which of the following is/are true about packages in Java?\
1\. Every class is part of some package.\
2\. All classes in a file are part of the same package.\
3\. If no package is specified, the classes in the file go into a special unnamed package.\
4\. If no package is specified, a new package is created with folder name of class and the class is put in this package.**\
a. Only 1, 2 and 3\
b. Only 1, 2 and 4\
c. Only 4\
d. Only 1 and 3

**Answer: a. Only 1, 2 and 3**

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Java Nptel Week 4 Assignment Answers**

**Q7. What is the output of following Java program?**\
a. Compiler Error\
b. Runtime Error\
c. Welcome!\
d. None of the above

**Answer: c. Welcome!**

**Q8. Which of these access specifiers can be used for an interface?**\
a. Public\
b. Protected\
c. private\
d. All of the mentioned

**Answer: a. Public**

**Q9. Which of the following is the correct way of implementing an interface salary by class manager?**\
a. class Java extends NPTEL {}\
b. class Java implements NPTEL {}\
c. class Java imports NPTEL {}\
d. none of the mentioned

**Answer: b. class Java implements NPTEL {}**

**Q10. What will be the output of the following Java program?**\
a. 0\
b. 2\
c. 4\
d. Compiler Error

**Answer: c. 4**

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Programming in Java Nptel Week 4 Assignment Answers**

More Weeks of Programming In Java: [Click here](https://progiez.com/nptel-leadership-and-team-effectiveness-assignment-1)

More Nptel Courses: <https://progiez.com/nptel-assignment-answers>


# Programming in Java Nptel Week 4 Assignment Answers (July-Dec 2023)

**Course Name: Programming In Java**

**Course Link:** [**Click Here**](https://onlinecourses.nptel.ac.in/noc23_cs74/course)

**These are Programming in Java Nptel Week 4 Assignment Answers**


# Programming Assignment

**Question 1\
Complete the code segment to execute the following program successfully. You should import the correct package(s) and/or class(s) to complete the code.**

**Solution:**

    import java.util.Scanner;
    import static java.lang.System.*;

**Question 2\
Complete the code segment to print the current year. Your code should compile successfully.**

**Solution:**

    java.util.Calendar current;

<!---->

            current = java.util.Calendar.getInstance();		year = current.get(current.YEAR);

**These are Programming in Java Nptel Week 4 Assignment Answers**

**Question 3\
The program in this assignment is attempted to print the following output:\
— — — — — –_**OUTPUT**_ — — — — — — -\
This is large\
This is medium\
This is small\
This is extra-large\
— — — — — — — — — — — — — — — — -\
However, the code is intentionally injected with some bugs. Debug the code to execute the program successfully.**

**Solution:**

    interface ExtraLarge{
    	static String extra = "This is extra-large";
    	void display();
    }

<!---->

    class Large {
        public void Print() {
            System.out.println("This is large");
        }
    }class Medium extends Large {
        public void Print() {
        	super.Print();
            System.out.println("This is medium");
        }
    }
    class Small extends Medium {
        public void Print() {
            super.Print();
            System.out.println("This is small");
        }
    }class Question43 implements ExtraLarge{
        public static void main(String[] args) {
            Small s = new Small();
            s.Print();
    		Question43 q = new Question43();
    		q.display();
        }
    	public void display(){
    		System.out.print(extra);
    	}
    }

**Question 4\
Complete the code segment to call the default method in the interface First and Second.**

**Solution:**

    First.super.show();

<!---->

            Second.super.show();

**These are Programming in Java Nptel Week 4 Assignment Answers**

**Question 5\
Modify the code segment to print the following output.\
— — — — — –OUTPUT — — — — — — -\
Circle: This is Shape1\
Circle: This is Shape2\
— — — — — — — — — — — — — — — — -**

**Solution:**

    interface ShapeX {
     public String base = "This is Shape1";
     public void display1();
    }

<!---->

    interface ShapeY extends ShapeX {
     public String base = "This is Shape2";
     public void display2();
    }class ShapeG implements ShapeY {
     public String base = "This is Shape3";
     public void display1() {
      System.out.println("Circle: " + ShapeX.base);
     }
     public void display2() {
      System.out.print("Circle: " + ShapeY.base);
     }
    }

**These are Programming in Java Nptel Week 4 Assignment Answers**

More Weeks of Programming In Java: [Click here](https://progiez.com/nptel-assignment-answers/nptel-programming-in-java-assignment-answers)

More Nptel Courses: [Click here](https://progiez.com/nptel-assignment-answers)
