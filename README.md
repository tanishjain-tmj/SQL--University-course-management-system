# SQL--University-course-management-system
University Course Management System:

Project Overview:
The University Course Management System is a relational database project developed using MySQL to manage academic information within a university.
It efficiently stores and manages data related to students, courses, instructors, enrollments, and departments.
This project focuses on applying SQL fundamentals and advanced concepts such as CRUD operations, joins, subqueries, aggregate functions, date functions, string functions, and CASE expressions.

Objectives:
Maintain student academic records
Manage courses offered by different departments
Assign instructors to departments
Track student enrollments in courses
Perform meaningful data analysis using SQL queries
🗄️ Database Schema
The database consists of five core tables connected through primary and foreign key relationships:
Students
Courses
Instructors
Enrollments
Departments
These relationships ensure data integrity and accurate academic reporting.

Table Description:
1. Students
Column Name
Description
StudentID
Primary Key
FirstName
Student first name
LastName
Student last name
Email
Email address
BirthDate
Date of birth
EnrollmentDate
Date of admission
2. Courses
Column Name
Description
CourseID
Primary Key
CourseName
Course title
DepartmentID
Foreign Key → Departments
Credits
Number of credits
3. Instructors
Column Name
Description
InstructorID
Primary Key
FirstName
Instructor first name
LastName
Instructor last name
Email
Email address
DepartmentID
Foreign Key → Departments
4. Enrollments
Column Name
Description
EnrollmentID
Primary Key
StudentID
Foreign Key → Students
CourseID
Foreign Key → Courses
EnrollmentDate
Course enrollment date
5. Departments
Column Name
Description
DepartmentID
Primary Key
DepartmentName
Department name

SQL Operations Covered:
CRUD Operations (INSERT, SELECT, UPDATE, DELETE)
SQL Clauses (WHERE, HAVING, LIMIT)
Logical Operators (AND, OR)
Aggregate Functions (COUNT, AVG, MAX)
Joins (INNER JOIN, LEFT JOIN)
Subqueries
Date Functions
String Functions
Window Functions
CASE Expressions
Primary & Foreign Key Constraints

Queries Implemented:
🔹 Basic Queries
Perform CRUD operations on all tables
Retrieve students enrolled after a specific year
Retrieve courses offered by a specific department
🔹 Aggregate & Grouping Queries
Count number of students enrolled in each course
Calculate average number of credits for all courses
Count students enrolled in each department
Find maximum instructor salary (department-wise scenario)
🔹 Joins
INNER JOIN to retrieve students with their enrolled courses
LEFT JOIN to retrieve all students even if not enrolled in any course
🔹 Subqueries
Find students enrolled in courses with more than a given number of students
🔹 Date & String Functions
Extract year from enrollment date
Concatenate instructor first name and last name
🔹 Advanced SQL
Calculate running total of students enrolled
Classify students as Senior or Junior using CASE expression
Senior: Enrollment date more than 4 years old
Junior: Otherwise

Conclusion:
The University Course Management System successfully demonstrates the use of relational database design and SQL querying techniques in an academic environment.
This project is ideal for SQL practical exams, viva preparation, and portfolio projects, as it covers both basic and advanced SQL concepts in a structured and meaningful way.
