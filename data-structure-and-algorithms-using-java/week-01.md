# NPTEL Data Structure and Algorithms Using Java Week 01 Assignment Answers

Are you looking for NPTEL Data Structure and Algorithms Using Java Week 01 Assignment Answers? This repository will help you find your answers and solutions for Week 01 of the Data Structure and Algorithms Using Java course. We provide detailed solutions to help you complete your assignments efficiently.

## Data Structure and Algorithms using Java Week 1 Nptel Answers (July-Dec 2025)

***

**Que.1 Which of the following statements is not true for non-linear data structures?**\
A) They can represent hierarchical relationships.\
B) They are always more complex than linear data structures\
C) They can have multiple paths to access data.\
D) They do not store data sequentially.

**[**View Answer**](https://my.progiez.com/courses/data-structure-and-algorithms-using-java-nptel-answers/)**

***

**Que.2 Which of the following operations can be performed on a stack?**\
A) Push\
B) Enqueue\
C) Dequeue\
D) Union

****[**View Answer**](https://my.progiez.com/courses/data-structure-and-algorithms-using-java-nptel-answers/)****

***

**Que.3 Which of the following applications necessitate the use of generic methods in Java?**\
A) Performing arithmetic on primitive data types\
B) Designing type-safe data structures\
C) Writing utility libraries that work with any data type\
D) Implementing reusable sorting algorithms

****[**View Answer**](https://my.progiez.com/courses/data-structure-and-algorithms-using-java-nptel-answers/)****

***

**Que.4 What will be the output of the following code snippet?**

    public class Printer {
        public static <T> void printElement(T element) {
            System.out.println(element);
        }
        public static void main(String[] args) {
            int x = 5;
            printElement(x);
        }
    }

A) Generic methods can’t be used with single arguments\
B) Compilation error due to the use of primitive type\
C) 5\
D) Runtime error due to type mismatch

****[**View Answer**](https://my.progiez.com/courses/data-structure-and-algorithms-using-java-nptel-answers/)****

***

**Que.5 Which symbol is used to denote a generic type in Java?**\
A) &\
B) $\
C) +\
D) #

****[**View Answer**](https://my.progiez.com/courses/data-structure-and-algorithms-using-java-nptel-answers/)****

**_**These are Data Structure and Algorithms using Java Week 1 Nptel **_**Assignment**_** Answers**_**

***

**Que.6 What will be the output of the following code snippet?**

    public class Box<T> {
        private T value;
        public void set(T val) { value = val; }
        public T get() { return value; }
        public static void main(String[] args) {
            Box<String> box = new Box<>();
            box.set("NPTEL");
            System.out.println(box.get());
        }
    }

A) null\
B) Compilation error due to generic instantiation\
C) Runtime error due to an uninitialized value\
D) NPTEL

****[**View Answer**](https://my.progiez.com/courses/data-structure-and-algorithms-using-java-nptel-answers/)****

***

**Que.7 Consider the following class:**

    class Pair<K, V> {
        K key;
        V value;
        public Pair(K k, V v) {
            key = k;
            value = v;
        }
    }

Which of the following instantiations are valid?\
A) new Pair<>(true, new Double(98.6))\
B) new Pair<>(new LinkedList(), “Location”)\
C) new Pair<>(123)\
D) new Pair<>(“Grade”, new int\[]{85, 92, 78})

[****See also**  **AI in Marketing Nptel Week 1 Assignment Answers****](https://progiez.com/ai-in-marketing-nptel-week-1-assignment-answers)

****[**View Answer**](https://my.progiez.com/courses/data-structure-and-algorithms-using-java-nptel-answers/)****

***

**Que.8 Can a parameterized class with a minimum number of distinct type parameters be used to store the grades of students in a course?**\
_(Assume the following data is needed: name, roll, list of scores, and final letter grade)_\
A) No, at least 4 parameters are necessary\
B) No, parameterized classes can’t handle multiple data types\
C) Yes, 2 parameters are sufficient\
D) Yes, 3 parameters are sufficient

****[**View Answer**](https://my.progiez.com/courses/data-structure-and-algorithms-using-java-nptel-answers/)****

***

**Que.9 What is the primary advantage of using a bounded argument generic class in Java?**\
A) It ensures type safety within a class hierarchy\
B) It improves the memory usage of generic containers\
C) It allows generics to work with primitive types\
D) It increases runtime flexibility

****[**View Answer**](https://my.progiez.com/courses/data-structure-and-algorithms-using-java-nptel-answers/)****

**_**These are Data Structure and Algorithms using Java Week 1 Nptel **_**Assignment**_** Answers**_**

***

**Que.10 Consider the following class:**

    class DataContainer<T extends Number> {
        private T value;
        public DataContainer(T value) {
            this.value = value;
        }
        public double getDoubleValue() {
            return value.doubleValue();
        }
    }

Which of the following objects can be passed as arguments to `DataContainer`?\
A) new DataContainer<>(“NPTEL”)\
B) new DataContainer<>(new Integer(5))\
C) new DataContainer<>(3.14f)\
D) new DataContainer<>(10)

****[**View Answer**](https://my.progiez.com/courses/data-structure-and-algorithms-using-java-nptel-answers/)****


**Session: JUL-DEC 2024**

**Course name: Data Structure and Algorithms using Java**

**Course Link:** [**Click Here**](https://onlinecourses.nptel.ac.in/noc24_cs96/)

These are Data Structure and Algorithms using Java Week 1 Nptel Assignment Answers


Q1. Which of the following statements is true about linear and non-linear data structures in java?\
a. Array and LinkedList are non-linear data structures, while Graph and Tree are linear data structures.\
b. Array and LinkedList are linear data structures, while Graph and Tree are non-linear data structures.\
c. Array and Graph are linear data structures, while LinkedList and Tree are non-linear data structures.\
d. Array and Tree are linear data structures, while LinkedList and Graph are non-linear data structures.<a id="dd57"></a>
-------------------------------------------------------------------------------------------------------------------------

[_ANSWER: Click here to view answer_](https://progiez.com/data-structure-and-algorithms-using-java-week-1-nptel)

**Q2. Which symbol is used to denote a generic type in Java? Which of the following statements is true about this method?**\
a. \*\
b. &\
c. #\
d. <>

[_ANSWER: Click here to view answer_](https://progiez.com/data-structure-and-algorithms-using-java-week-1-nptel)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Data Structure and Algorithms using Java Week 1 Nptel Assignment Answers**

**Q3. Consider the following generic method in Java:\
public static void printArray (T\[] array) {\
for (T element: array) {\
System.out.print(element + “);\
}\
System.out.println();\
}**\
a. This method can only print arrays of Strings.\
b. This method can print arrays of any object type, but not primitive types.\
c. This method can print arrays of any type, including primitive types.\
d. This method will cause a compile-time error.

[_ANSWER: Click here to view answer_](https://progiez.com/data-structure-and-algorithms-using-java-week-1-nptel)

**Q4. Consider the following Java method:\
public static void printVarargs (String… args) {\
for (String arg: args) {\
System.out.print(arg + “);\
}\
}Which of the following calls to this method are valid?\
A. printVarargs(“Hello”, “World”); B. printVarargs({“Hello”, “World”}); C. printVarargs(new String\[]{“Hello”, “World”}); D. printVarargs(new String\[]{“Hello”}, “World”);**\
a. A and B\
b. B and C\
c. A and C\
d. C and D

[_ANSWER: Click here to view answer_](https://progiez.com/data-structure-and-algorithms-using-java-week-1-nptel)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Data Structure and Algorithms using Java Week 1 Nptel Assignment Answers**

**Q5. Which of the following statements about variable-length arguments (varargs) is true?**\
a. A method can have multiple varargs parameters.\
b. Varargs parameters must be the first parameter in a method’s parameter list.\
c. Varargs parameters can only accept an array of arguments.\
d. A method can have only one varargs parameter, and it must be the last parameter in the method’s parameter list.

[_ANSWER: Click here to view answer_](https://progiez.com/data-structure-and-algorithms-using-java-week-1-nptel)

**Q6. Consider the following Java code snippet:\
Which of the following statements is true about the given code?**\
a. The code will produce a compilation error because generic classes cannot be instantiated with primitive types.\
b. The code will produce a runtime error when calling getContent on integerBox because of type mismatch.\
c. The code will output 123 and Hello.\
d. The code will produce a compilation error because the same generic class cannot be used with different types.

[_ANSWER: Click here to view answer_](https://progiez.com/data-structure-and-algorithms-using-java-week-1-nptel)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Data Structure and Algorithms using Java Week 1 Nptel Assignment Answers**

**Q7. Which of the following is true?**\
a. A generic class may be established with several type parameters.\
b. Primitive data types can be utilized as parameter types.\
c. It is possible to instantiate an array with an element type that is a type parameter.\
d. All of the above

[_ANSWER: Click here to view answer_](https://progiez.com/data-structure-and-algorithms-using-java-week-1-nptel)

**Q8.Which of the following code snippets correctly demonstrates method overloading in Java?**\
A.\
public class Calculator {\
public int add(int a, int b) {\
return a + b;\
}\
public double add(int a, int b) {\
return a b;\
B.\
public class Calculator {\
public int add(int a, int b) {\
return a + b;\
}\
public int add(int a, int b, int c) {\
return a + b + c;\
C.\
public class Calculator {\
public int add(int a, int b) {\
return a + b;\
}\
public String add (String a, String b) {\
return a + b;

D.\
public class Calculator (\
public int add(int a, int b) {\
return a + b;\
}\
public int add(int a, int b) {\
return a + b + 10;\
}

a. A and B\
b. B and C\
c. D and B\
d. All

[_ANSWER: Click here to view answer_](https://progiez.com/data-structure-and-algorithms-using-java-week-1-nptel)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Data Structure and Algorithms using Java Week 1 Nptel Assignment Answers**

**Q9. Which of these is a wildcard symbol?**\
a. ?\
b. !\
c. &\
d. %

[_ANSWER: Click here to view answer_](https://progiez.com/data-structure-and-algorithms-using-java-week-1-nptel)

**Q10. Which of the following keywords is used to declare an upper bounded wildcard?**\
a. bound\
b. extends\
c. implement\
d. super

[_ANSWER: Click here to view answer_](https://progiez.com/data-structure-and-algorithms-using-java-week-1-nptel)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Data Structure and Algorithms using Java Week 1 Nptel Assignment Answers**

More Weeks of Data Structure and Algorithms using Java: [Click here](https://progiez.com/nptel-assignment-answers/data-structure-and-algorithms-using-java)

More Nptel Courses: <https://progiez.com/nptel-assignment-answers>
