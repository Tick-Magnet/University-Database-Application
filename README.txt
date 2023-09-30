CONTENTS OF THIS FILE
---------------------
* Introduction
* Installation
* STRUCTURE
* TESTING
* CREDITS

INTRODUCTION
------------
The Jacob_Bowers'_Big_Database_Project is a professional, user-friendly, database, designed with the constraints expected of a University database system. 
Great care was taken to make sure this project meets every requirement requested by our employers. Particularly the database was designed to feel and look professional. 
Muted colors paletts, a simple straight forward GUI, and visual responses help to ease the user through the experience.    


INSTALLATION
------------
During development, this program used MYSQL to handle the database contents and Java Eclipse/Swing to design and create the GUI for this program.
To run this program on your machine the following steps must be taken. 
	
A large issue you may face is connection errors as my Java uses a particular localhost and password. This won't be an issue if you're localhost runs on root has an address of 3306, and a 
a password of "*id4_As32b". 

Open up MySQL and create the database on your localhost. First, take the SQL_CREATE_TABLES file copy-paste the contents into the SQL command line, and run it. 
Once completed run each of the INSERTs into MySQL. (Unfortunately, I was unable to consolidate these files into one. Apologies)
You should now have a fully operational database on the back end!

The next step should be easy. Open up the java files and run them accordingly. Take the JDBC.java file and move it to either Eclipse or any other Java workspace.
To run the application simply run the file DatabaseApplication.java in any way that you are accustomed to.

*IMPORTANT NOTE* If these steps fail in any way please contact the author for more input.

STRUCTURE
---------

The Jacob_Bowers'_Big_Database has a user-friendly GUI that makes navigation a breeze. To begin using the project run DatabaseApplication.java and you will be greeted with the homepage.
Here select occupation, (I.E. Student, Staff, or Faculty) and input your corresponding login information. Depending on what occupation you are a part of you will be greeted with three separate homepages. 
The student page allows for a student to see/edit personal information (note: students cannot change ID number), check grades, navigate all courses available, 
and enroll/drop courses. Faculty will be greeted with the powerful search tool that allows them to view any information requested in the database. Lastly, Staff can maintain the database as they see fit. 
They are given the power to add, remove, update, or search through any content from the database as they please. 

TESTING
-------
The following Usernames and Passwords are designed for testing all the functionalities of the Jacob_Bowers'_Big_Database.

Student:	Name: Jacob_Bowers	ID: 100001
Faculty:	Name: Garth_Caiden	ID: 100001
Staff:		Name: Leland_Luther	ID: 1001 <- (Typically less staff then faculty so smaller ID numbers)

If you wish to skip the log-in process you can run student_home.java, faculty_home.java, or staff_home.java without logging in, but you will be restricted to the corresponding testing users.

CREDITS
-------
Constructed by: Jacob Bowers
I can be reached at: jacob.bowers@siu.edu