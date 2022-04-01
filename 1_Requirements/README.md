Employee-Record-System

## Title : Employee Record System

The mini-project “Employee Record System Project in C” is a console application using the C programming language. This project compiled in Code Blocks with the GCC compiler. In this console application, you can do basic Employee Record tasks like adding the employee info, view the added employee, search the employees.
This application based on file handling in C, where I have used a file-related function like fopen, fread, fwrite, ..etc. 
Also to increase the readability, I have broken the application in different functions. Each function of the project extensively use in the file handing function, so it is also a great project to understand file handling in C.

## Research

__Objectives:__

•	This project aims to simplify the task of maintaining records of the employees of Company.

•	To develop an well-designed database to store employee information. 

•	Provides full functional reports to management of Company. 

•	The objective of this project is to provide a comprehensive approach towards the management of employee information.

__Features__

•	Previously the records management was done manually.

•	Encrypted File (Binary).

•	Easily Add, Delete, Modify Records.

## 4W's and 1'H

__Who:__

•	All the organisation who has lot’s of employee in their different units and their different services.

__What:__

•	Earlier Many Companies were inefficient due to prolonged time for entering N numbers of employee records manually.

•	This project gives the opportunity to enter all the required information and deploy into the system easily

__When:__

•	As the business of the organisation increases number of employees increases .

•	With the increases of employee their data management require.

__Where:__

•	This problem is surfaced in all the organisation in the world.

__How:__

•	This project takes in all the input values and yields out the management parameters.


## Challenges Faced and How Was It Overcome

1.I have faced issues in file handling. so, I used strings.

2.Updating and Deleting a file was overcame by using a temporary file to store data for some time.


## Learning Resources

1.tutorials point

2.geeksforgeeks

 __High level and and Low level Requirements__


__HIGH LEVEL REQUIREMENTS__


| ID    |                    DESCRPTION                                       |CATEGORY|   STATUS  |
|-------|---------------------------------------------------------------------|--------|-----------|
| HR01  |  The Application should allow user to make a choice between 1 to 5. |Textual |IMPLEMENTED|   
| HR02  |  The Application should allow user to  enter info.                  |Textual |IMPLEMENTED|
| HR03  |  The Application should allow user to list all the employee records.|Textual |IMPLEMENTED| 
| HR04  |  The Application should allow user to modify the employee records.  |Textual |IMPLEMENTED|
| HR05  |  The Application should allow user to delete employee records       |Textual |IMPLEMENTED|     
| HR06  |  The Application should allow user to exit from application.        |Textual |IMPLEMENTED| 



__LOW LEVEL REQUIREMENTS__



| ID    |                    DESCRPTION                                                            | HLR ID |   STATUS  |
|-------|------------------------------------------------------------------------------------------|-------|-----------|
| HR01  |  The application will ask user tochoose between 1 to 5                                   |  HR01 |IMPLEMENTED| 
|       |   Choices:
|       |     1.Add Record
|       |     2. List Record
|       |     3. Modify Record
|       |     4. Delete Record
|       |     5. Exit                                                              
| HR02  |  The application will ask user to enter info such as Enter name, Enter Salary, Enter Age.| HR02  |IMPLEMENTED|
| HR03  |  The application will show all details of employees.                                     | HR03  |IMPLEMENTED| 
| HR04  |  The application will ask user enter name (for modifying).                               | HR04  |IMPLEMENTED|
| HR05  |  The application will ask user to enter name (for deleting).                             | HR05  |IMPLEMENTED|     
| HR06  |  The user can exit from application by choosing 5.                                       | HR06  |IMPLEMENTED| 

