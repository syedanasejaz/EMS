**Employee Management System**

The Employee Management System is a ASP.Net web-based application. It provides features for adding, editing, and deleting employee records, as well as viewing and searching employee data along with the departments. This system is built using ASP.NET and utilizes Telerik controls for a rich user interface.

**Installation**

To run the Employee Management System locally, follow these steps:

    Clone the repository from GitHub: git clone https://github.com/syedanasejaz/employee-management-system.git
    Open the project in Visual Studio.
    Restore NuGet packages to install the necessary dependencies.
    Build the solution to ensure all dependencies are resolved.
    Update the connection string in the web.config file to point to your database server.
    Run the application using IIS Express or your preferred development server.

**Usage**

Once the application is up and running, you can perform the following tasks:
    View employee details: Employee List with the details shown on the grid.
    Add a new employee: Click on the "New Employee" button on the Employee List page to add a new employee record. Fill in the required information and save the record.
    Edit an existing employee: In the Employee List, click on the "Edit" button for the employee you want to modify. Update the employee details and save the changes.
    Delete an employee: In the Employee List, click on the "Delete" button for the employee you want to remove. 
    View department details: Department List with the details shown on the grid.
    Edit an existing department: In the department List, click on the "Edit" button for the department you want to modify. Update the department name and save the changes.
    Delete a department: In the department List, click on the "Delete" button for the department you want to remove.

**Validation**
  Required Field and custom validator for the input fields for inserting and updating the employees.
  Server-side validation for duplicate email while adding and updating the employee's details
  Server-side validation for checking the department has been to any employees, before deleting it.

**Configuration**

The Employee Management System uses a SQL Server database to store employee information. To configure the database connection, update the connection string in the web.config file. Make sure to specify the correct server, database name, username, and password.

**Testing**

The project includes unit tests to ensure the functionality of the EmployeeRepository class. These tests cover Adding and Getting operations and can be executed using a testing framework such as NUnit. Run the tests from the test runner in your preferred IDE or using the command line.

