🎓 Salesforce Student Management System – Mini Project

📌 Project Overview

The Salesforce Student Management System is a mini project designed to manage student records, courses, and enrollments. It demonstrates Salesforce Admin concepts like custom objects, fields, relationships, record types, validation rules, flows, and dashboards.

🎯 Objectives

* Maintain complete student and course records in Salesforce.
* Automate the enrollment process for courses.
* Track academic performance and attendance.
* Provide insights through reports and dashboards.

⚙️ Features Implemented

Custom Objects:

Student (Name, Email, Phone, DOB, Student ID)
Course (Course Name, Instructor, Duration, Credits)
Enrollment (Lookup to Student & Course, Status, Start Date, End Date)

Relationships:Lookup / Master-Detail between Student ↔ Enrollment ↔ Course

Record Types & Page Layouts: Separate layouts for Undergraduate and Postgraduate students

Validation Rules: Ensure valid email formats and mandatory student ID

Flows: Auto-create enrollment record when a student joins a course

Reports & Dashboards: Track active students, popular courses, and performance

🛠️ Tech Stack

Platform: Salesforce

Features Used: Objects, Fields, Relationships, Record Types, Validation Rules, Flows, Reports & Dashboards

📊 Outcomes

* Centralized student and course management
* Automated course enrollment process
* Improved data quality with validation rules
* Insights into student progress and course popularity

🚀 Future Enhancements

* Add Approval Process for course enrollment
* Integrate Email Notifications for enrollment updates
* Build LWC Component for student self-service portal
