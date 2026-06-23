# Employee Management System

A console-based CRUD application built with Java 21, demonstrating Object-Oriented Programming principles with in-memory data management.

## Tech Stack

- **Language:** Java 21
- **Build Tool:** Apache Maven
- **IDE:** NetBeans

## Features

- Add, view, update, and delete employee records
- Search employee by ID
- In-memory storage using `ArrayList`
- Input validation with graceful error handling

## Project Structure

```
src/
└── nhlaks/employmanagementsyste/
    ├── Employee.java                  # Model — fields, getters, setters
    └── EmployeeManagementSystem.java  # Entry point — CRUD + menu loop
```

## Running the App

```bash
# Clone / open in NetBeans, then:
mvn compile
mvn exec:java -Dexec.mainClass="nhlaks.employmanagementsyste.EmployeeManagementSystem"
```

Or simply hit **Run** in NetBeans.

## Employee Fields

| Field        | Type     |
|-------------|----------|
| `id`         | `int`    |
| `name`       | `String` |
| `department` | `String` |
| `salary`     | `double` |

## Author

Nhlalala Lubisi (Vaal University of Technology Student - AdvDip IT (NQF7)
