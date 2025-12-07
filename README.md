# student-record-management
Student Record Management
The Student Information Management System is a console-based application designed to manage student academic and personal information in an efficient, structured, and secure manner. The system supports multiple user roles and provides core functionalities required for institutional data handling.
The project implements a role-based access model with three distinct user categories: Admin, Staff, and Guest. Each role has predefined privileges. The Admin has full access to all system features, including user account management and student data operations. Staff users can add, view, update, and delete student records. Guest users have limited access and are allowed only to view general information. This layered access approach ensures system security and prevents unauthorized modifications.
The system includes a Signup Module that allows new users to register by providing a username, password, and role. All registered credentials are stored in a secure file and verified during login. The Login Module validates user identity before granting access to role-specific menus, ensuring authenticated system usage.
The core functionality revolves around the Student Management Module, where details such as roll number, name, course, degree, semester, and marks are stored in structured files. The system provides options to:
Add Student: Insert a new student record into the database file.
View Students: Display all stored records in a readable format.
Update Student: Modify the details of an existing record based on roll number.
Delete Student: Remove a selected student record from the file permanently.
All file operations are handled using standard C file handling functions, ensuring data persistence and consistent storage across program executions. Input validation routines prevent invalid or incomplete data from being processed.
Overall, the project demonstrates practical use of C programming concepts such as structures, file handling, pointer operations, conditional logic, and modular design. It serves as a simplified model of real-world information systems used in educational institutions and highlights the importance of secure authentication, structured data management, and role-based system design
