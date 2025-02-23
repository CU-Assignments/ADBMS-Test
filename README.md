# ADBMS-Test



## 📌 Features
- Stores student details
- Maintains course information
- Tracks enrollments of students in courses

---

## 📂 Database Schema

### **📘 Students Table**
| student_id | student_name   | age | course  |
|------------|---------------|-----|--------|
| 1          | Amit Sharma   | 21  | B.Tech |
| 2          | Neha Verma    | 22  | MCA    |
| 3          | Rajesh Kumar  | 23  | BCA    |
| 4          | Pooja Singh   | 21  | B.Tech |
| 5          | Vikram Rathore | 22  | MCA    |

---

### **📗 Courses Table**
| course_id | course_name | fee   |
|-----------|------------|--------|
| 101       | B.Tech     | 50000  |
| 102       | MCA        | 60000  |
| 103       | BCA        | 40000  |

---

### **📙 Enrollments Table**
| enrollment_id | student_id | course_id | enrollment_date |
|--------------|------------|-----------|----------------|
| 1            | 1          | 101       | 2024-01-10    |
| 2            | 2          | 102       | 2024-02-15    |
| 3            | 3          | 103       | 2024-03-20    |
| 4            | 4          | 101       | 2024-04-05    |
| 5            | 5          | 102       | 2024-05-10    |

---






# SQL Joins Test Questions  

## 1. List MCA Students  
**Problem Statement:**  
Write an SQL query to display the names of all students enrolled in the "MCA" course.  

---

## 2. Total Fee Collected per Course  
**Problem Statement:**  
Write a query to calculate the total fee collected for each course.  

---

## 3. Students with Course Details  
**Problem Statement:**  
Display student names along with the courses they are enrolled in.  

---

## 4. Courses Without Enrollments  
**Problem Statement:**  
Write a query to display the names of courses that have no students enrolled.  

---

## 5. Find Students Who Haven’t Paid Fees  
**Problem Statement:**  
Retrieve the names of students who are enrolled in a course but haven’t paid the fee.  

---

## 6. Count of Students in Each Course  
**Problem Statement:**  
Write a query to display each course and the number of students enrolled in it.  

---

## 7. Highest Fee Paid by a Student  
**Problem Statement:**  
Retrieve the student name and course name where the highest fee has been paid.  

---

## 8. Students Enrolled After a Certain Date  
**Problem Statement:**  
Write a query to display the names of students who enrolled after '2024-01-01'.  

---

## 9. Find Common Students in Two Courses  
**Problem Statement:**  
Write a query to find students enrolled in both "B.Tech" and "MCA" courses.  

---

## 10. Instructor Assigned to Each Course  
**Problem Statement:**  
Display course names along with their assigned instructor names.  



