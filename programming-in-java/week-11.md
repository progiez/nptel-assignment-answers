# NPTEL Programming In Java Week 11 Assignment Answers

Are you looking for NPTEL Programming In Java Week 11 Assignment Answers? This repository will help you find your answers and solutions for Week 11 of the Programming In Java course. We provide detailed solutions to help you complete your assignments efficiently.

## Programming in Java Nptel Week 11 Assignment Answers (Jan-Apr 2025)

**Course Link: [**Click Here**](https://onlinecourses.nptel.ac.in/noc25_cs57/course)**

***

**1) What is the full form of JDBC?**

a. Java Database Connectivity\
b. Java Data Code\
c. Java Data Communication\
d. Java Development Connectivity

[View Answer](https://my.progiez.com/courses/programming-in-java-nptel-answers/)

***

**2) Fill in the missing code to establish a connection to a MySQL database.**

    import java.sql.*;
    public class JDBCExample {
        public static void main(String[] args) {
            try {
                Class.forName("com.mysql.cj.jdbc.Driver");
                // Establish Connection
                Connection connection = 
                // INSERT CODE HERE;
                System.out.println("Connected to the database.");
                connection.close();
            } catch (Exception e) {
                e.printStackTrace();
            }
        }
    }

What should replace `// INSERT CODE HERE`?

a. `DriverManager.connect("mysql:localhost:mydb", "user", "password");`\
b. `DriverManager.getConnection("jdbc:mysql://localhost:3306/mydb", "user", "password");`\
c. `Connection.get("jdbc:mysql://localhost:3306/mydb", "user", "password");`\
d. `Driver.connect("jdbc:mysql://localhost:mydb", "user", "password");`

[View Answer](https://my.progiez.com/courses/programming-in-java-nptel-answers/)

***

**3) Identify the error in the following code and select the corrected statement:**

    import java.sql.*;
    public class ResultSetExample {
        public static void main(String[] args) throws SQLException {
            Connection connection = 
            DriverManager.getConnection("jdbc:mysql://localhost:3306/mydb", "user", "password");
            Statement stmt = connection.createStatement();
            ResultSet rs = stmt.execute("SELECT FROM users"); // Error
            while (rs.next()) {
                System.out.println(rs.getString("username"));
            }
            connection.close();
        }
    }

What is the correct statement to replace the line with an error?

a. `ResultSet rs = stmt.executeQuery("SELECT * FROM users");`\
b. `ResultSet rs = stmt.execute("SELECT * FROM users");`\
c. `ResultSet rs = stmt.execute('users SELECT * FROM');`\
d. `ResultSet rs = stmt.fetch("SELECT * FROM users");`

[View Answer](https://my.progiez.com/courses/programming-in-java-nptel-answers/)

***

**4) What will the following Java program output if the database contains a table `products` with a column `name` and three rows: Laptop, Phone, and Tablet?**

    import java.sql.*;
    public class DisplayProducts {
        public static void main(String[] args) {
            try {
                Connection conn = DriverManager.getConnection("jdbc:mysql://localhost:3306/store", "root", "pass");
                Statement stmt = conn.createStatement();
                ResultSet rs = stmt.executeQuery("SELECT name FROM products");
                while (rs.next()) {
                    System.out.println(rs.getString("name"));
                }
                conn.close();
            } catch (SQLException e) {
                e.printStackTrace();
            }
        }
    }

a. Compilation Error\
b. Runtime Error\
c. Laptop, Phone, Tablet\
d. No Output

[****See also**  **Programming in Java Nptel Week 2 Assignment Answers****](https://progiez.com/programming-in-java-nptel-week-2-assignment-answers)

[View Answer](https://my.progiez.com/courses/programming-in-java-nptel-answers/)

***

**5) Complete the following code to insert a new user into a `users` table.**

    import java.sql.*;
    public class InsertUser {
        public static void main(String[] args) {
            try {
                Connection conn = DriverManager.getConnection("jdbc:mysql://localhost:3306/mydb", "root", "password");
                String query = "INSERT INTO users (username, email) VALUES (?, ?)";
                // INSERT CODE HERE
                PreparedStatement pstmt = conn.prepareStatement(query);
                pstmt.setString(1, "john_doe");
                pstmt.setString(2, "john@example.com");
                pstmt.executeUpdate();
                conn.close();
            } catch (SQLException e) {
                e.printStackTrace();
            }
        }
    }

What should replace `// INSERT CODE HERE`?

a. `conn.createStatement(query);`\
b. `conn.prepareStatement(query);`\
c. `conn.execute(query);`\
d. `conn.runStatement(query);`

[View Answer](https://my.progiez.com/courses/programming-in-java-nptel-answers/)

***

Programming in Java Nptel Week 11 Assignment Answers

***

**6) Which of the following SQL operations can be executed using the `executeUpdate` method in JDBC?**

    INSERT INTO users (id, name) VALUES (1, 'Alice');UPDATE users SET name='Bob' WHERE id=1;DELETE FROM users WHERE id=1;SELECT * FROM users;

a. 1, 2, and 3\
b. Only 1 and 2\
c. Only 1\
d. 1, 2, 3, and 4

[View Answer](https://my.progiez.com/courses/programming-in-java-nptel-answers/)

***

**7) What is the purpose of the `DriverManager` class in JDBC?**

a. To manage database connections.\
b. To execute SQL queries.\
c. To fetch data from a database.\
d. To represent a database record.

[View Answer](https://my.progiez.com/courses/programming-in-java-nptel-answers/)

***

**8) How do you establish a connection to a database using JDBC?**

a. By creating an instance of the `Connection` interface\
b. By using the `DriverManager.getConnection()` method\
c. By implementing the `Connection` interface\
d. By extending the `Connection` class

[View Answer](https://my.progiez.com/courses/programming-in-java-nptel-answers/)

***

**9) Which method executes a simple query and returns a single `ResultSet` object?**

a. `executeQuery()`\
b. `executeUpdate()`\
c. `execute()`\
d. `run()`

[View Answer](https://my.progiez.com/courses/programming-in-java-nptel-answers/)

***

**10) Which package in Java contains the classes and interfaces for JDBC?**

a. `java.sql`\
b. `java.io`\
c. `java.db`\
d. `java.net`

[View Answer](https://my.progiez.com/courses/programming-in-java-nptel-answers/)

[****See also**  **Programming in Java | Week 9********](https://progiez.com/nptel-programming-in-java-week-9-assignment-9-answers)
