![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![NetBeans](https://img.shields.io/badge/Apache%20NetBeans-1B6AC6?style=for-the-badge&logo=apache-netbeans-ide&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white)
# Online Course Management System - Java

A Java desktop application for managing online courses, users, quizzes, certificates, and dashboards using Object-Oriented Programming principles.

## Project Overview
This project simulates an online course platform where users can interact with courses, complete quizzes, track progress, and generate certificates through a Java GUI application.

## Features
- User account handling
- Course management
- Quiz system
- Progress tracking
- Certificate generation
- Dashboard interface
- GUI built with Java Swing
- File-based data storage using JSON files

## Technologies Used
- Java
- Java Swing
- Apache NetBeans
- Object-Oriented Programming (OOP)
- MVC Architecture
- JSON
- File Handling
- Apache PDFBox
- JFreeChart

## Project Structure
```text
src/
lib/
nbproject/
courses.json
users.json
```

## Dependencies
This project uses external Java libraries:
- Apache PDFBox
- JFreeChart
- org.json

The required `.jar` files are included in the `lib/` folder.

## Key Highlights
- Role-based system with Admin, Instructor, and Student dashboards
- Course approval workflow
- Quiz and certificate generation system
- PDF generation using Apache PDFBox
- Analytics visualization using JFreeChart

## Screenshots
### Login & Role Selection
<img width="400" height="300" alt="Screenshot 2026-05-25 163140" src="https://github.com/user-attachments/assets/0785a25c-dcac-47a4-bd11-66607800d2ca" />

User authentication screen with role-based login support for Admins, Students, and Instructors.

### Student Dashboard
<img width="400" height="300" alt="Screenshot 2026-05-25 163527" src="https://github.com/user-attachments/assets/2dbde117-9a7d-409f-9345-2d5274ace142" />

Student dashboard providing access to enrolled courses, certificates, and course browsing features.

### Instructor Dashboard
<img width="400" height="300" alt="Screenshot 2026-05-25 163739" src="https://github.com/user-attachments/assets/1dacb45f-fe12-4fbd-97e8-74ea4a650a76" />

Instructor dashboard for managing courses, lessons, quizzes, and student interactions.

### Admin Dashboard
<img width="400" height="300" alt="Screenshot 2026-05-25 164531" src="https://github.com/user-attachments/assets/5b18e60b-a07f-47c3-a135-65b94279df57" />

Admin dashboard used for reviewing and approving submitted courses.

### Course Creation
<img width="400" height="300" alt="Screenshot 2026-05-25 164825" src="https://github.com/user-attachments/assets/14ed1fa3-ce3a-4c20-80f3-a669a3e5a7b9" />

Interface for instructors to create new courses with custom titles and descriptions.

### Course Management
<img width="400" height="300" alt="Screenshot 2026-05-25 164727" src="https://github.com/user-attachments/assets/2e8816c6-d4bd-43af-8e81-16c8e6241ac3" />

Comprehensive course management interface for editing lessons, tracking students, and managing course content.

### Quiz Creation
<img width="400" height="300" alt="Screenshot 2026-05-25 164954" src="https://github.com/user-attachments/assets/0ed792c4-e628-48b6-a377-44e7214551fc" />

Quiz creation system allowing instructors to add multiple-choice questions and answers.

### Course Approval System
<img width="400" height="300" alt="Screenshot 2026-05-25 165238" src="https://github.com/user-attachments/assets/0f2e4530-077a-4237-8d8b-d467c6dcb3f2" />

Admin approval interface for reviewing and validating newly created courses before publishing.

### Course Enrollment
<img width="400" height="300" alt="Screenshot 2026-05-25 165359" src="https://github.com/user-attachments/assets/d7f665fc-911a-4a1e-8e4d-0c9fbe6163f7" />

Students can browse available courses and enroll directly through the application.

### My Courses
<img width="400" height="300" alt="Screenshot 2026-05-25 165430" src="https://github.com/user-attachments/assets/50e32c1c-f741-4f5f-abfc-41a09d479466" />

Student course tracking interface displaying enrolled courses and completion progress.

### Lesson & Progress Tracking
<img width="400" height="300" alt="Screenshot 2026-05-25 165444" src="https://github.com/user-attachments/assets/8fa5d8ad-1d9a-4ece-9cc0-6f04b8b42ffc" />

Lesson management and completion tracking system for monitoring student progress.

### Quiz System
<img width="400" height="300" alt="Screenshot 2026-05-25 165517" src="https://github.com/user-attachments/assets/84a38f39-0995-456d-b88c-e86c59225e31" />

Interactive quiz system integrated into lessons for evaluating student understanding.

### Course Completion
<img width="400" height="300" alt="Screenshot 2026-05-25 165555" src="https://github.com/user-attachments/assets/2c94ddc3-2052-4117-9fa6-3b0f9585df52" />

The system automatically detects course completion and generates a unique certificate ID.

### Certificates Management
<img width="400" height="300" alt="Screenshot 2026-05-25 165611" src="https://github.com/user-attachments/assets/8774c374-89d6-442c-9a3f-0988f1a0d276" />

Students can access, download, and manage earned course certificates in PDF and JSON formats.

### Generated PDF Certificate
<img width="400" height="300" alt="Screenshot 2026-05-25 165638" src="https://github.com/user-attachments/assets/82c3a4c1-fef5-4759-b526-534f9ff021fe" />

Automatically generated course completion certificate created using Apache PDFBox.

### User Registration
<img width="400" height="300" alt="Screenshot 2026-05-25 171915" src="https://github.com/user-attachments/assets/8cf33d96-94ad-43a0-87f9-5384c2e8537c" />

New users can register as Students or Instructors through the built-in account creation system.

### Enrolled Students Tracking
<img width="400" height="300" alt="Screenshot 2026-05-25 171834" src="https://github.com/user-attachments/assets/037d58d2-fe9b-456d-93da-00034bc4e529" />

Instructors can monitor students enrolled in each course directly from the management interface.

### Course Insights & Analytics
<img width="400" height="300" alt="Screenshot 2026-05-25 172305" src="https://github.com/user-attachments/assets/72519291-863d-4689-a5c2-f121161842cb" />

The system provides quiz averages and completion statistics for monitoring course performance.

### Student Performance Visualization
<img width="400" height="300" alt="Screenshot 2026-05-25 172318" src="https://github.com/user-attachments/assets/809537a8-6538-4843-8eb1-f2a55a887a44" />

Performance analytics visualization generated using JFreeChart for tracking quiz averages across lessons.

## How to Run
1. Clone or download this repository.
2. Open the project in Apache NetBeans.
3. Make sure the `.jar` files inside the `lib/` folder are added to the project libraries.
4. Open `src/lab/pkg7/Lab7.java`.
5. Run the `Lab7` main class.
6. Log in or create a new account as a Student, Instructor, or Admin.
