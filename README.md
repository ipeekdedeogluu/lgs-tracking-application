# LGS Results Tracking Application

A **desktop-based exam tracking system** developed using C# and Windows Forms.
The application allows administrators and students to manage and analyze
LGS trial exam results in a structured, secure, and user-friendly environment.

---

## 🎯 Project Purpose
The goal of this project is to:
- Track students’ LGS trial exam performance
- Store exam results securely in a database
- Provide role-based access for admins and students
- Visualize academic performance using charts
- Export exam results as PDF reports

---

## 👥 User Roles

### Admin
- Login with admin credentials
- Add, update, and delete students
- Assign trial exams to students
- View all students’ exam histories
- Analyze performance using charts
- Export exam results as PDF

### Student
- Login with personal credentials
- Add own exam results
- View personal exam history
- Analyze performance via charts
- Export own exam results as PDF

---

## 🧪 Exam Structure
Each trial exam includes the following subjects:
- Mathematics
- Turkish
- Science
- English
- History of Turkish Revolution
- Religion and Ethics

Scores are recorded as **correct and wrong answers** and net scores are calculated automatically.

---

## 🛠 Technologies Used
- **C#**
- **Windows Forms (WinForms)**
- **Microsoft SQL Server**
- **ADO.NET**
- **Visual Studio**

---

## 🗄 Database Design
The backend database consists of:
- **Users** (authentication & roles)
- **Students** (student profiles)
- **Exams** (exam records and scores)

Relational structure ensures data consistency and role-based access.

---

## 🖥 Application Screenshots

### Login Page
![Login Page](images/login_page.png)

---

### Admin Panel
![Admin Panel](images/admin_panel.png)

### Admin – Exam History
![Admin Exam History](images/admin_exam_history.png)

### Admin – Add Exam
![Admin Add Exam](images/admin_add_exam.png)

### Admin – Performance Tracking
![Admin Performance Chart](images/admin_performance_chart.png)

### Admin – PDF Export
![Admin PDF Export](images/admin_pdf_export.png)

---

### Student Panel
![Student Panel](images/student_panel.png)

### Student – Exam Results
![Student Exam Results](images/student_exam_results.png)

### Student – Performance Chart
![Student Performance Chart](images/student_performance_chart.png)

### Student – PDF Export
![Student PDF Export](images/student_pdf_export.png)

---

## 🚀 Implemented Features
- Role-based authentication (Admin / Student)
- Secure login system
- Full CRUD operations for students (Admin)
- Exam result entry and history tracking
- Performance visualization with charts
- PDF export functionality
- Clean and intuitive GUI design

---

## 🔮 Future Improvements
- OCR integration for automatic exam result entry
- Advanced performance analytics
- Automated PDF report generation with graphs
- Centralized server deployment

---

## 📄 Project Report
Detailed documentation is available in:
`report/VP MIDTERM PROJECT REPORT.pdf`
