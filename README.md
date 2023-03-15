# Student Management System in JAVA
This is a simple Student Management System project implemented using Java and MySQL. It allows users to perform CRUD (Create, Read, Update, Delete) operations on student data such as ID, first name, last name, major, phone number, GPA, and date of birth.

[Step by Step guide to design and develop this application](https://iq.opengenus.org/student-management-system-in-java/)

# Features
* Add a new student
* View student data
* Update student data
* search for a student
* sort students by major, lastname and firstname.

# Requirements
* Java 8 or higher.
* MySQL Server.

# Installation
1. Clone the repository
```bash
git clone https://github.com/your_username/student-management-system.git
```
2. Create a new MySQL database and import the student_data.sql file to 
3. create the required table and sample data.
4. Update the MySQL database connection details in the dbConnect class.
5. Build and run the project using a Java IDE or command-line tool.
6. To import *student_data.sql* into your mysql database.
    * **Type**: ```mysql -u username -p database_name < file.sql```
    * The **username** refers to your MySQL username.
    * **database_name** refers to the database you want to import.
    * **file.sql** is your file name. (student_data.sql in our case.)
    * If you've assigned a password, type it now and press Enter.

# Usage
* Launch the application
* Select the desired operation from the main menu
* Follow the prompts to enter or update student data

# Database Columns
The database table used in this project has the following columns:

* Student_ID: The unique identifier for each student.  
* first_name: The first name of the student.  
* last_name: The last name of the student.  
* major: The major that the student is studying.  
* Phone: The phone number of the student.  
* GPA: The grade point average of the student.  
* DOB: The date of birth of the student.

# Future Enhancements
* Fee tracking
* Attendance management



