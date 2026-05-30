# Attendance-Management-System

## Overview

The Student Attendance Management System is a web-based application developed using HTML, CSS, and JavaScript. It helps manage student attendance records efficiently by allowing users to add students, mark attendance as Present or Absent, and store records locally in the browser.

The application uses Local Storage to ensure that attendance data remains available even after refreshing or reopening the browser.

---

## Features

* Add new students with unique roll numbers
* Select attendance date
* Mark students as Present or Absent
* View attendance status for a selected date
* Automatic roll number generation
* Attendance records stored in Local Storage
* Responsive and user-friendly interface
* Dynamic table generation using JavaScript

---

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* Local Storage API

---

## Project Structure

```text
Student-Attendance-System/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## How It Works

### Adding Students

Users can enter a student's name and click the "Add Student" button. The system automatically assigns a roll number and stores the student information.

### Attendance Tracking

For each selected date, attendance can be marked as:

* Present
* Absent

Attendance records are stored separately for each date.

### Data Persistence

The application uses Local Storage to save attendance records permanently in the browser.

```javascript
localStorage.setItem("students", JSON.stringify(students));
```

Saved data is loaded automatically when the application starts.

---

## Key JavaScript Concepts Used

* DOM Manipulation
* Event Handling
* Arrays and Objects
* Local Storage
* JSON.stringify()
* JSON.parse()
* Array.find()
* Dynamic HTML Generation

---

## Screenshots
<img width="1853" height="844" alt="image" src="https://github.com/user-attachments/assets/797bfaf2-101a-461f-b299-0fd5fe6bff94" />

---

## Future Enhancements

* Edit Student Details
* Delete Student Records
* Search Student Functionality
* Attendance Percentage Calculation
* Dashboard Statistics
* Export Attendance Report to CSV
* Backend Database Integration
* User Authentication

---

## Learning Outcomes

Through this project, the following concepts were learned and implemented:

* Building responsive web interfaces
* Managing application state using JavaScript
* Working with browser storage
* Implementing attendance management logic
* Creating dynamic tables and user interactions

---


