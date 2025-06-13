# 🎓 University Examination System Database

This project models a university's examination system using SQL. It handles students, courses, departments, faculty, exams, and attendance records.

---

## 📘 Key Features

- Students enrolled in departments and courses
- Faculty manage, teach, and create exams
- Departments offer multiple courses
- Exams created per course with type, date, duration
- Attendance tracked per student per course

---

## 🧱 Tables

- **Student**: `Std_id`, `Std_Name`, `Roll_number`, `D_id`, `Course_id`
- **Department**: `D_id`, `D_Name`
- **Course**: `Course_id`, `Course_Name`, `D_id`
- **Faculty**: `F_ID`, `Faculty_Name`
- **Exam**: `Exam_name`, `Date`, `Time`, `Type`, `Std_id`, `Course_id`, `F_id`
- **Attendance**: `Std_id`, `Course_id`, `Attendance_Percentage`

---

## 📌 Notes

- Compatible with MySQL / PostgreSQL (minor edits may be needed)
- Extendable for exam results, grading, user roles, etc.

