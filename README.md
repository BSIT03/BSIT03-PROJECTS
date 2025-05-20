# QR CODE-BASED Campus Event Management System 
The QR Code-Based Campus Event Management System is a digital platform designed to streamline the planning, registration, attendance tracking, and management of school or campus events using QR codes. Here's a detailed overview of what such a system typically includes, especially tailored for deployment in schools like Cansilayan Farm School:
🎯 Objective:
To automate and simplify event organization and attendance tracking in a campus environment using QR codes, minimizing manual effort and improving accuracy, security, and efficiency.

🛠️ Key Features:
🔐 User Login System
Admin/Teacher Login using ID and Name (from teacher_adviser.php)

Secure login and logout functionality

📅 Event Management
Add, edit, delete events (Only teachers)

Input event name, date, time

Auto-generate QR code for each event

Print QR codes for physical posting

🧑‍🎓 Student Participation
Students scan QR codes with their phones

Enter LRN (Learner Reference Number) as a unique identifier

System verifies LRN and logs attendance

📝 Attendance Tracking
Record attendance in real-time upon QR scan

Display list of students who attended (filtered by Grade & Section/Strand)

Notification system to confirm attendance

Attendance records saved per event

📋 Dashboards
Admin Dashboard for managing teachers, events, and student records

Student Dashboard to view event details and attendance

Teacher Dashboard to view/manage attendance for their section/strand

📁 Import Functionality
Upload Excel files for bulk student or teacher data

Auto-fill missing fields as "N/A"

Auto-group students by Grade 7-12, and for Grades 11-12: TVL or Academic strands

🔔 Notification System
Students notified when an event is added/updated

Includes information on which teacher made the change

After attendance is logged, a confirmation is shown

🧩 Technologies Used:
Frontend: HTML, CSS, JavaScript, Bootstrap, AJAX

Backend: PHP

Database: MySQL

QR Code Generation: PHP QR Code Library or Google Chart API

File Handling: PHPExcel or PhpSpreadsheet for Excel import

🧠 Use Case Workflow:
Teacher logs in ➜ Creates an event ➜ QR code is generated.

QR Code is printed/postered on campus.

Student scans QR code ➜ Enters LRN ➜ Attendance is logged.

System sends confirmation message ➜ Displays event info and who else attended (based on section/strand).
