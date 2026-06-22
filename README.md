# Employee Management System

## Overview

Employee Management System is a console-based Java application developed using Core Java concepts. The project allows users to manage employee records through a menu-driven interface and perform CRUD (Create, Read, Update, Delete) operations.

## Features

* Add Employee
* View Employees
* Search Employee by ID
* Update Employee Details
* Delete Employee
* Duplicate Employee ID Validation
* Exception Handling using InputMismatchException
* Menu-Driven Console Application

## Technologies Used

* Java
* OOP (Object-Oriented Programming)
* Collections Framework (ArrayList)
* Exception Handling
* Scanner Class

## Project Structure

### Employee.java

* Employee model class
* Encapsulation using private variables
* Constructors
* Getters and Setters
* toString() method

### EmployeeService.java

Contains business logic for:

* Add Employee
* View Employee
* Search Employee
* Update Employee
* Delete Employee

### EmployeeManagementSystem.java

* Menu-driven application
* User interaction
* Exception handling
* Calls service methods

## Concepts Implemented

* Classes and Objects
* Encapsulation
* Constructors
* Collections (ArrayList)
* CRUD Operations
* Exception Handling
* Method Overriding (toString)

## Sample Menu

```text
===== Employee Management System =====

1. Add Employee
2. View Employees
3. Search Employee
4. Update Employee
5. Delete Employee
6. Exit
```

## Exception Handling

The application handles invalid user inputs using InputMismatchException.

Example:

* Entering a name instead of salary
* Entering characters instead of employee ID
* Entering invalid menu choices

The program displays an error message and continues execution without crashing.

## Learning Outcomes

This project helped in understanding:

* Core Java Programming
* Object-Oriented Programming
* Collections Framework
* Exception Handling
* Menu-Driven Application Development

## Future Enhancements

* JDBC Integration
* MySQL Database Connectivity
* Spring Boot Integration
* REST API Development
* Spring Data JPA
* Hibernate
* Web-Based User Interface

## Author

Nitisha 

