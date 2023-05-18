# EduTrack - Efficient ERP Solution for Academic Operations

EduTrack is an efficient ERP (Enterprise Resource Planning) solution designed and developed for academic institutions. It serves as a comprehensive college management system, leveraging the Java Swing framework for the user interface and MySQL as the database backend. The system provides a wide range of features to streamline various aspects of academic operations.

## Features

### Common Features

- Cources Management: Manage different courses offered by the college.
- Subjects Management: Manage subjects taught in each course.
- Students Management: Maintain student records.
- Faculties Management: Manage faculty members.
- Students Attendance Management: Track and record student attendance.
- Student Marks Management: Enter and manage student marks.

### Advanced Features 🔥

- Rollnumber Generator: Automatically generate unique roll numbers for students.
- Chatting: Communicate via built-in chat functionality.
- Photo view of Students and Faculties: View student and faculty photos.
- Student or Faculty login history: Track login activities.
- Download Marksheet: Enable students to download mark sheets.
- Notification: Broadcast important announcements and updates.
- Declare result: Automate result generation and announcement.

## Installation

1. Import the project into your preferred Java IDE.
2. Create a new MySQL database named 'collegedata'.
3. Import the 'collegedata.sql' file into the 'collegedata' database.

## Database Connection

By default, the system uses the following database connection details:

- URL: jdbc:mysql://localhost:3306/collegedata
- Username: root
- Password: 

To modify these settings, open '.\src\collegeapplication\common\DataBaseConnection.java'.

## How to Run

1. Start your MySQL database server.
2. Run 'src/collegeapplication/chat/Server.java' to start the chat server.
3. Run 'src/collegeapplication/login/LoginPageFrame.java' to start the application.
4. Use the following credentials for login:
   - Admin User ID: admin
   - Admin Password: admin
   - Faculty User ID: Faculty ID
   - Student User ID: Course-Semester-RollNumber (e.g., IT-1-1001)

## Demo

A demonstration of the EduTrack college management system is available in the [Demo Video](https://user-images.githubusercontent.com/63580687/236466989-dc4c93f7-7f11-4bd6-9737-dbe43cbdfffd.mp4). Please note that the demo showcases the system's features and functionality.

## Acknowledgements

This College Management System project was independently developed and does not contain any copied content.

