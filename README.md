# task1

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: LATIKA SATISH KARKERA

**INTERN ID**: CT08DS9741

**DOMAIN**: SQL

**BATCH DURATION**: DECEMBER 10TH 2024 TO JANUARY 10TH 2025

#OVERVIEW:
In this project, the goal was to create a relational database that efficiently manages student records, including personal details, courses, and grades. The project aims to practice designing and managing databases using SQL, with an emphasis on creating relationships between multiple tables (students, courses, and enrollments) and writing SQL queries to interact with this data. The database structure allows users to add, update, and retrieve relevant information, providing a complete management system for student records in an educational environment.

Project Overview
The database, named StudentManagement, consists of three main tables: Student, Course, and Enrollment. Each table stores different types of information related to students, courses, and the courses they are enrolled in.

Student Table: This table contains personal information about each student, such as their ID, first and last name, date of birth, gender, and email address. It serves as the foundation for tracking student details.

Course Table: This table stores details about the various courses offered by the institution. Each course has an ID, name, course code, and the number of credits assigned to it.

Enrollment Table: This table tracks which students are enrolled in which courses. It links the Student and Course tables using foreign keys (StudentID and CourseID) and includes additional information like the student's grade for each course.

Instructions Followed
The task required creating a set of SQL tables to manage student records, including personal details, courses, and grades. The key focus was to set up a relational database that can manage and retrieve this data efficiently. The instructions were followed through the creation of tables, insertion of sample data, and the development of several SQL queries to retrieve and manipulate the data.

1. Creating the Database and Tables
The first step was to create a new database, StudentManagement. Once the database was created, three tables were defined: Student, Course, and Enrollment. Each table was given relevant columns, with appropriate data types assigned to each column. For example, the StudentID in the Student table was set to auto-increment to automatically generate unique student IDs.

2. Inserting Sample Data
Once the tables were set up, sample data was inserted into each table to populate them. The Student table was populated with fictional student details, including first and last names, email addresses, and birth dates. The Course table was filled with details about the courses offered, such as course names and credits. Finally, the Enrollment table was populated with data showing which students are enrolled in which courses and their grades. This step allowed the database to be populated with realistic data for querying.

3. Writing SQL Queries
The next step was to write SQL queries to retrieve data from the database, demonstrating how the tables can be queried using joins and other SQL commands:

Retrieving All Students and Courses: Simple SELECT queries were used to display all records from the Student and Course tables, showing the student details and the courses offered.

Enrollment Details: A more complex query was written to retrieve enrollment details, combining data from all three tables: Enrollment, Student, and Course. Using JOIN operations, the query fetched the student names, course names, and the grades they received in each course. This query required multiple joins to pull relevant data from the related tables.

Students in a Specific Course: Another query was written to find all students enrolled in a specific course (e.g., "Computer Science"). This query used a WHERE clause to filter the results by course name and returned a list of students enrolled in that particular course.

Updating Student Grades: An UPDATE query was used to change a student's grade in a specific course. This query demonstrated how to modify existing records in the Enrollment table based on student and course IDs, updating the grade for a student who had previously been assigned a different grade.

Execution of Instructions
The instructions were carried out step by step, following a logical sequence for database creation, data insertion, and query development.

The database was successfully created and populated with sample student, course, and enrollment data.
Queries were then written to combine the data using joins, allowing meaningful relationships to be formed between the tables.
The queries focused on both retrieving and updating data, showcasing the full functionality of a student management system.
The join queries were particularly useful in linking multiple tables together. For example, by joining the Student and Course tables with the Enrollment table, it became possible to show which students were enrolled in which courses and their corresponding grades. Similarly, the ability to filter by specific courses or update grades was enabled through SQL commands.

Conclusion
This project demonstrates the practical application of relational database design and SQL. By creating a database to manage student records, including personal details, courses, and grades, the project illustrates the importance of table relationships and how to manipulate data efficiently using SQL. The project also emphasizes the use of joins to combine data from multiple tables, retrieve relevant information, and update records. The final system serves as a comprehensive tool for managing student enrollments and their academic performance. This exercise provided valuable experience in creating, populating, and querying relational databases, which is a foundational skill for managing complex datasets in real-world applications.

#OUTPUT:
![Screenshot 2025-01-09 001111](https://github.com/user-attachments/assets/7dfe5646-3ccf-4b70-9b29-9e91021e5aec)
![Screenshot 2025-01-09 001124](https://github.com/user-attachments/assets/ed89e667-1d19-4541-bec7-7304c9c2b652)
![Screenshot 2025-01-09 001148](https://github.com/user-attachments/assets/0d3ab55c-8bda-4d81-8809-fda366d78a93)
![Screenshot 2025-01-09 001238](https://github.com/user-attachments/assets/d332db31-262a-49ee-b2af-156095208db4)
![Screenshot 2025-01-09 001328](https://github.com/user-attachments/assets/7c9adfd9-0f0b-4ed1-b03d-3653230ec60d)
