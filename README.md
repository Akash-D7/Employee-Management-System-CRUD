# SKYMUSIC Employee Management System

## Overview
The **SKYMUSIC Employee Management System** is a simple web application designed to manage employee records. This system allows administrators to perform CRUD (Create, Read, Update, Delete) operations on employee data, such as names, roles, departments, and contact information. It is built using ASP.NET Core MVC for the backend and HTML/CSS for the frontend, providing a user-friendly interface for easy employee management.

### Key Features:
- **Create**: Add new employee details to the system.
- **Read**: View and search employee records.
- **Update**: Edit existing employee information.
- **Delete**: Remove employee records from the system.
- User-friendly interface for smooth interaction.
- Manage employee details including roles, departments, and contact information.

## Technologies Used:
- **Backend**: ASP.NET Core MVC
- **Frontend**: HTML, CSS
- **Database**: SQL Server
- **Authentication**: ASP.NET Identity (optional)
- **Version Control**: Git

## Installation

### Prerequisites:
- .NET SDK (version 6 or later)
- Visual Studio or Visual Studio Code
- SQL Server (or any relational database)

### Steps to Run the Application:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Akash-D7/Employee-Management-System-CRUD.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd Employee-Management-System-CRUD
    ```

3. **Restore dependencies**:
    Run the following command in the terminal:
    ```bash
    dotnet restore
    ```

4. **Build the project**:
    ```bash
    dotnet build
    ```

5. **Set up the database**:
    - Ensure SQL Server is installed and running.
    - Update the `appsettings.json` file with the correct connection string for your SQL Server database.

6. **Run the application**:
    ```bash
    dotnet run
    ```

7. Open a web browser and go to `http://localhost:5000` to access the **SKYMUSIC Employee Management System**.

## Features

### Employee Dashboard:
- View all employee records with details such as ID, Name, Department, and Role.
- Edit or update employee information.
- Delete an employee record.
- Search employee records by name or other parameters.

### CRUD Operations:
- **Create**: Add new employee details with essential information.
- **Read**: View a list of all employees or individual employee details.
- **Update**: Edit employee information and update records.
- **Delete**: Remove employee records from the system.

### Responsive Design:
The system is optimized for both desktop and mobile views.

## Contribution:
Feel free to fork and contribute to this project. If you find any bugs or have suggestions, feel free to open an issue or submit a pull request.

## License:
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Developed By:
**Akash D**  
- [LinkedIn](https://www.linkedin.com/in/akashd02/)
