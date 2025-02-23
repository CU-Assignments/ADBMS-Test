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


# SQL Aggregate Functions Test Questions  

## 1. Total Number of Students  
**Problem Statement:**  
Write an SQL query to count the total number of students in the **Students** table.  

---

## 2. Average Fee Paid  
**Problem Statement:**  
Write a query to calculate the **average fee paid** by students in the **Enrollments** table.  

---

## 3. Highest and Lowest Fee Paid  
**Problem Statement:**  
Write a query to find the **highest** and **lowest** fee paid by students.  

---

## 4. Total Students in Each Course  
**Problem Statement:**  
Write a query to display the **course name** along with the **total number of students** enrolled in each course.  

---

## 5. Count of Students Who Paid Fees  
**Problem Statement:**  
Write a query to count the number of students who have paid their fees (i.e., `fee_paid > 0`).  


# SQL Questions Using IN and BETWEEN  

## 1. Find Students Enrolled in Specific Courses  
**Problem Statement:**  
Write an SQL query to display the names of students who are enrolled in **"MCA", "B.Tech", or "BCA"** courses.  


---

## 2. Find Students Who Paid Fees in a Specific Range  
**Problem Statement:**  
Write a query to retrieve student names and the amount they paid where the **fee_paid is between 30,000 and 80,000**.  


---

## 3. Find Courses Starting Between Two Dates  
**Problem Statement:**  
Write an SQL query to display the course names that started **between '2024-01-01' and '2024-06-30'**.  


---

## 4. Find Students from a Specific Set of Cities  
**Problem Statement:**  
Write a query to display student names who are from the cities **"Delhi", "Mumbai", or "Bangalore"**.  


---

## 5. Find Students Who Enrolled in a Specific Year Range  
**Problem Statement:**  
Write an SQL query to display student names who enrolled **between 2022 and 2024**.  


# SQL Normalization Questions  

## 1. Identify the Normal Form  
**Problem Statement:**  
Consider the following table:  

| OrderID | CustomerName | ProductName | Quantity | Price | TotalAmount |  
|---------|-------------|-------------|----------|-------|-------------|  
| 101     | Rahul       | Laptop      | 1        | 50000 | 50000       |  
| 102     | Sneha       | Mobile      | 2        | 20000 | 40000       |  

- Identify which **normal form** (1NF, 2NF, 3NF, BCNF) this table is in.  
- Justify your answer and suggest how it can be further normalized.  

---

## 2. Convert to First Normal Form (1NF)  
**Problem Statement:**  
A university stores student and their enrolled courses in a single table:  

| StudentID | StudentName | Courses |  
|-----------|------------|---------|  
| 1         | Amit       | Math, Science, English |  
| 2         | Priya      | Physics, Chemistry |  

- Identify the issue in this design.  
- Convert this table into **1NF**.  

---

## 3. Convert to Second Normal Form (2NF)  
**Problem Statement:**  
A hospital maintains the following table:  

| PatientID | PatientName | DoctorID | DoctorName | Department | Disease |  
|-----------|------------|----------|------------|------------|---------|  
| 1         | Rahul      | D101     | Dr. Sharma | Cardiology | Heart Issue |  
| 2         | Anjali     | D102     | Dr. Verma  | Neurology  | Migraine    |  

- Identify if this table is in **1NF** or **2NF**.  
- If not in 2NF, **normalize it to 2NF** by splitting into separate tables.  

---

## 4. Convert to Third Normal Form (3NF)  
**Problem Statement:**  
A company stores employee data as follows:  

| EmpID | EmpName | Department | DeptLocation | ManagerID | ManagerName |  
|-------|--------|------------|-------------|-----------|-------------|  
| 101   | Raj    | IT         | Mumbai      | 201       | Mr. Sharma  |  
| 102   | Meera  | HR         | Delhi       | 202       | Ms. Gupta   |  

- Identify if this table violates **3NF**.  
- If so, **normalize it into 3NF**.  

---







