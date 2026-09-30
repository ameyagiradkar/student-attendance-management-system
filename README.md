README

Student Attendance Management System
A beginner-friendly Python project for recording, calculating, and reporting student attendance.
1. Project Overview
The Student Attendance Management System is designed to make basic attendance management
easier. The system allows users to store student information, enter attendance data, calculate
attendance percentages, and generate useful attendance reports.
2. Problem Statement
Managing student attendance manually can take time and may lead to calculation mistakes. This project
provides a simple computerized system for recording attendance and automatically calculating
attendance results.
3. Objectives
• Add and manage student information.
• Record the number of working days and days present.
• Automatically calculate absent days and attendance percentage.
• Identify students with low attendance.
• Generate a simple attendance report.
• Reduce manual calculation errors.
4. Main Features
Module
Main Functions
Student Management
Attendance Management
Add, view, search, and remove students.
Enter working days and present days and calculate attendance.
Attendance Report
Validation
Display attendance details and identify low-attendance students.
Prevent invalid values such as negative days or present days greater than working days.
5. Example Calculation
Attendance Percentage = (Days Present / Working Days) × 100
Student
Working Days
Present
Rahul
60
Absent
52
Attendance
8
Priya
Amit
60
60
6. Non-Functional Requirements
45
58
15
2
86.67%
75.00%
96.67%
• Usability – simple menu and easy-to-understand inputs.
• Reliability – attendance calculations should be accurate.
• Error Handling – invalid attendance values should be rejected.
• Maintainability – the program should be organized into understandable functions/modules.
7. Technologies Used
• Programming Language: Python
• Storage: CSV/text file (depending on final implementation)
• Development Environment: Any Python-compatible IDE
• Version Control: Git and GitHub
8. Suggested Project Structure
Student-Attendance-Management/
nnn main.py
nnn student.py
nnn attendance.py
nnn report.py
nnn validation.py
nnn data.csv
nnn tests.py
nnn README.md
nnn statement.md
9. How to Run
• Install Python on your computer.
• Download or clone the project from GitHub.
• Open the project folder in a Python IDE or terminal.
• Run the main Python file, for example: python main.py
• Follow the instructions displayed by the program.
10. Testing
The project should be tested using valid and invalid inputs. Important test cases include zero or negative
values, present days greater than working days, duplicate student entries, searching for an existing
student, and searching for a student who does not exist.
11. Future Enhancements
• Add a graphical user interface.
• Add login functionality for authorized users.
• Store attendance for individual dates.
• Export attendance reports to PDF or Excel.
• Add monthly and subject-wise attendance reports.
12. Academic Alignment
This README is based on the uploaded VITyarthi project guidelines. The guidelines require a
meaningful problem, at least three major functional modules, clear input/output, a logical workflow,
non-functional requirements, modular implementation, documentation, testing where applicable, a
GitHub README, a statement file, and a project report.
13. Author
Ameya D. Giradka
