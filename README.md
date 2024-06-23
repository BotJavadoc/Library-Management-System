# Library Management System

Welcome to the Library Management System project! This project is a comprehensive web application designed to manage a library's operations efficiently. It is developed using Java full stack technologies, including JSP (JavaServer Pages), Servlets, and JDBC (Java Database Connectivity).

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

The Library Management System is a web-based application that facilitates the management of library operations such as adding and managing books, users, and transactions. The system provides an easy-to-use interface for librarians and library users to interact with the system effectively.

## Features

- **User Management:** Register and manage user accounts with different roles (e.g., librarian, member).
- **Book Management:** Add, update, delete, and search for books in the library catalog.
- **Transaction Management:** Manage book borrowings, returns, and overdue transactions.
- **Authentication and Authorization:** Secure login and access control for different user roles.
- **Search Functionality:** Advanced search options for finding books and users quickly.
- **Responsive Design:** User-friendly interface that works on various devices.

## Technologies Used

- **Frontend:**
  - HTML
  - CSS
  - JavaScript
  - JSP (JavaServer Pages)

- **Backend:**
  - Java
  - Servlets

- **Database:**
  - MySQL
  - JDBC (Java Database Connectivity)

## Installation

### Prerequisites

- JDK (Java Development Kit) 8 or higher
- Apache Tomcat 8 or higher
- MySQL Server
- Maven (for dependency management)

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/library-management-system.git
   ```
2. **Import the project into your IDE:**
   Open your IDE (e.g., Eclipse, IntelliJ IDEA), and import the project as a Maven project.

3. **Configure the database:**
   - Create a database in MySQL.
   - Update the `db.properties` file with your database credentials.

4. **Build the project:**
   ```bash
   mvn clean install
   ```

5. **Deploy on Tomcat:**
   - Copy the WAR file from the `target` directory to the Tomcat `webapps` directory.
   - Start the Tomcat server.

6. **Access the application:**
   Open your browser and navigate to `http://localhost:8080/library-management-system`.

## Usage

### Admin

- **Login:** Admin can log in using their credentials.
- **Manage Books:** Add, edit, or delete book records.
- **Manage Users:** Register new users, edit user details, and assign roles.
- **View Transactions:** Monitor all borrowing and returning transactions.

### Member

- **Register/Login:** Members can register for an account and log in.
- **Search Books:** Find books using various search criteria.
- **Borrow/Return Books:** Request to borrow or return books.


## Contact

If you have any questions or suggestions, feel free to reach out:

- **Email:** abhishekabu0155@gmail.com


Thank you for using the Library Management System! We hope it helps in efficiently managing your library's operations.
