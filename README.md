# Employee Management System

This application is to allow users to dynamically update, and manage their business. It utilizes the power of the mysql node module to use javascript to update our mySQL database and view our insertions using console.table.

# Install
Create a clone of this Github repository.
Once cloned to your local computer, in the terminal, run npm install.
Replace user and password from app.js and lib folder files, and use yours.
Load the seed.sql and the schema.sql into MySQLWorkbench.
Once the packages have been installed and MySQLWorkbench is running, run node server.js in the terminal. Prompts should appear automatically after.
# Functionality
Users are prompted for their desired action which can be:
1.View All Employees
2.Add Employee
3.Update Employee Role


Employee class attributes are handled in the server and, depending on which role is chosen, a salary, manager, and department are assigned
# Screenshots
  connection
<img src="assets/images/node.png">
  view all employees
   <img src="assets/images/node2.png">
   add employee
    <img src="assets/images/node3.png">
    view again
     <img src="assets/images/node4.png">
# Requirments
This application utilizes several node modules. Run the following npm install accordingly

npm install
mysql inquirer console-table
# License
MIT License
