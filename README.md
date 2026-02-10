# RevWorkForce – Console Based HR Management System

RevWorkForce is a Java-based console Human Resource Management System (HRMS) developed using layered architecture. It manages employees, leave requests, performance reviews, and system configurations with role-based access for Employees, Managers, and Admins.

## Features

### Employee
- Login using Employee ID and password
- View and update basic profile details
- View reporting manager information
- Apply for leave and track leave status
- Cancel pending leave requests
- View leave balance and holiday calendar
- Submit performance self-review
- Set yearly goals and update progress
- Receive in-app notifications

### Manager
- View team members and hierarchy
- Approve or reject leave requests
- View team leave calendar
- Review employee performance documents
- Provide feedback and ratings
- Track team goals and performance

### Admin
- Add, update, deactivate, and reactivate employees
- Assign or change reporting managers
- Manage departments and designations
- Configure leave types and policies
- Adjust employee leave balances
- Set company holiday calendar
- View audit logs and system activity
- Search employees by ID, name, or department

## Technologies Used
- Java (Core Java, Java 8)
- JDBC
- MySQL
- Eclipse IDE
- DAO Design Pattern
- Layered Architecture

## Architecture
The project follows a layered architecture:
- Presentation Layer (Controllers)
- Business Logic Layer (Services)
- Data Access Layer (DAOs)
- Data Persistence Layer (MySQL Database)

## Project Structure

com.revworkforce  
├── model  
├── dao  
├── service  
├── util  
└── main  


## How to Run
1. Clone the repository
2. Import the project into Eclipse
3. Configure MySQL database and tables
4. Update database credentials in DBConnection
5. Run Main.java
6. Use the console menu to interact with the application


## Author
Dudekula Babji  
Java Developer
