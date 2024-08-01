# Employee Management System

## Overview

The Employee Management System is a Java-based desktop application that allows administrators to manage employee information efficiently. The application provides functionalities to add, view, update, and remove employee records. The system is built using Java Swing for the user interface, JDBC for database connectivity, and MySQL as the database management system.

## Features

- **Add Employee**: Add new employee records to the database.
- **View Employee**: View details of all employees in the system.
- **Update Employee**: Update existing employee records.
- **Remove Employee**: Remove employee records from the database.
- **Login**: Secure login for administrators.
- **Splash Screen**: Attractive splash screen displayed on startup.

## Technologies Used

- **Java**: Core programming language.
- **Swing**: Used for building the graphical user interface (GUI).
- **JDBC**: Java Database Connectivity for connecting to the database.
- **MySQL**: Database management system.
- **IntelliJ IDEA**: Integrated development environment (IDE).

## Prerequisites

- **Java JDK**: Version 8 or above.
- **MySQL**: Version 5.7 or above.
- **IntelliJ IDEA** (or any preferred Java IDE).

## Setup and Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/employee-management-system.git
    cd employee-management-system
    ```

2. **Set up the MySQL database**:
    - Create a database named `employeeRegister`.
    - Use the following SQL script to create the required table:
    ```sql
    CREATE DATABASE employeeRegister;
    USE employeeRegister;

    CREATE TABLE employees (
        id INT AUTO_INCREMENT PRIMARY KEY,
        name VARCHAR(100),
        age INT,
        department VARCHAR(100),
        email VARCHAR(100),
        phone VARCHAR(15)
    );
    ```

3. **Configure the database connection**:
    - Open `conn.java` file located in `src/employee/management/system/`.
    - Update the database URL, username, and password with your MySQL configuration.
    ```java
    String url = "jdbc:mysql://localhost:3306/employeeRegister";
    String username = "your_mysql_username";
    String password = "your_mysql_password";
    ```

4. **Compile and run the application**:
    - Open the project in IntelliJ IDEA.
    - Navigate to `src/employee/management/system/Main_class.java`.
    - Run the `Main_class.java` file.


## Screenshots

Check for Screenshots file.

## Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Icons used from [source].
- Special thanks to the Java community for continuous support and inspiration.

