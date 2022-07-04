# Task manager #
## Overview ##
This is a Python program named Task Manager and is used for assisting companies keep track of their tasks by assigning tasks to specific people, registering new
users, checking if tasks as overdue and if tasks are complete or not. This program can only be used by registered user at the company the program is being used at
and these users are listed in the user.txt file. The program will read this file to see if the user is authorised to use the program and this is done in the logging in 
section of the program. 

If the user successfully logs in, a menu option will be displayed to the user. Admin user is displayed a separate menu to the other registered users. It is deifferent
such that admin users have the option to register a new user and generate statistics whereas other user do not have that option, they only have the option to
view all tasks, add a task, view their tasks. 

If the user selects to register a new user, the user is asked to enter the username and password and confirm the password, the username and password is then written to
the user.txt file. If the user selects to had a task, the user is asked to enter: username, title, description, due date. This is then appended to the tasks.txt file.
If the user selects to view all the tasks the program reads the tasks.txt file and displays all the tasks to the user. If the user selects view my tasks, the 
tasks for the user who is logged in will only be displayed. If the admin user selects to generate statistics the program will read the user.txt and tasks.txt files and
display how many users and how manu tasks there are. If the user selects to exit the program the program is exited. 

## Motivation ##
This program was developed as a project for my software engineering course.

## Build status ##
The program does not have any bugs or errors.

## How to use? ##
In order to run this program, Python as to be installed to the computer or laptop. Once installed, download this file, right-click on the file and select "Edit with
IDLE", thereafter to run the program press F5 on the keyboard. When the user is asked to enter input, enter the data required and press "Enter". 
