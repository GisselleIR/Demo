# Employee-Management-System
This program was built using Java Swing to build the GUI and sqlite as the database.
After forking/downloading this project. It should be able to be run in a Java IDE such as Eclipse. 
We built the GUI with Eclipse Window Builder.

## Logging In

## Main Functionality on the Manager Side
On the Employee Database Management System window.

On the right is the database which updates based on what is in the employee.db file. 

On the top left is the input form for using the add and edit buttons. 

On the bottom left is the delete, print, tasks, requests, documents, and performances button. 

## Add button
The user must fill out all input fields and after valid input, the program sends the input data to the database file to be recorded.
Then the table is updated based on the updated database. 

Input Validation:
- All fields must be filled out 
- First Name, Last Name, Department, and Positon must be all letters
- Email must be in email format (must have @ and .)
- End Date input must be filled OR Current button must be selected
- Salary must be numerical
- Employee ID must be 3 numbers 
- Phone Number must be 10 numbers no dashes

Ex Input:
- First Name: matthew
- Last Name: Pham
- Email: username@domain.com
- Start Date: 02/15/2020
- End Date: 7/12/2021 (or CURR)
- Salary: 70000
- Employee ID: 333
- Phone Number: 1112223333
- Department: Engineering
- Position: Software Developer
- Date of Birth: 05/15/2002

## Edit Button
Edit button also uses the same input form as the Add button. 
Employee ID MUST match an existing record, and all other fields will be editted depending on what is currently in the input fields.
Input Validation is done the same as for the Add button. However, if the ID doesnt not exist in the database, a "Employee Record not Found" message will pop up. 

## Delete Button 
Delete button opens up a pop up that asks the user to input an employee ID in order to delete the corresponding record.
Performs input validation on the ID and deletes it if it exists. 

## Print Button
Print button opens up a window with a printing GUI that can print the database shown in the table on the right.

## Tasks Button

## Requests Button

## Documents Button
The document button opens up to another window which allows the user the management of text documents that may be important to the operation of a company (memos, letters, reports, etc.)

#Create/Edit Document
This button allows for the creation or editing of a text file.  Text in the text field labeled "File Name" will be used to determine what file we are working with.  If the file does not exist, it is created automatically and if it does, it will be edited without difficulty.

Input validation requires that the file name not be empty.

#Open Document
The open button is used to open any text file that resides within the working directory.  From there, you may be able to edit the file using the aforementioned create/edit button

Input validation requires that the file name not be empty.

#Delete Document
The delete document button is simple.  If you would like to get rid of a document that you no longer need, you may press this button.

Input validation requires that the file name not be empty.

#Show Files
If you would like to see what files contained in your working directory, simply press this button.

As there is no input needed to work this function, there is no input validation.


## Performances Button



## Employee Side (Non Manager)


