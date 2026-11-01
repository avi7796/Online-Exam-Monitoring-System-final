# 🎓 Online Exam Monitoring System

## 📌 Project Overview

The **Online Exam Monitoring System** is a database-driven project designed to manage and monitor online examinations efficiently. The system tracks student details, exam schedules, login activities, question attempts, and suspicious activities during exams.

This project uses **SQL and relational database concepts** to organize and analyze exam-related data while maintaining data integrity using primary and foreign keys.

---

## 🎯 Aim of the Project

* Develop a system to conduct and monitor online exams
* Ensure secure and fair examinations
* Manage student and exam data efficiently
* Track student performance during exams
* Detect suspicious or cheating activities

---

## 🛠 Technologies Used

* SQL
* MySQL / DBMS
* Relational Database Concepts

---

## 🗄 Database Structure

The system consists of the following tables:

1. **Students**

   * student_id
   * fullname
   * email
   * college

2. **Exams**

   * exam_id
   * subjects
   * exam_date
   * exam_duration

3. **Login Logs**

   * log_id
   * student_id
   * exam_id
   * login_time
   * logout_time
   * ip_address
   * device_id

4. **Question Attempts**

   * attempt_id
   * student_id
   * exam_id
   * question_id
   * attempt_time
   * answer_time_seconds
   * is_correct

5. **Cheating Alerts**

   * alert_id
   * student_id
   * exam_id
   * alert_type
   * alert_time

---

## 🔗 ER Diagram

The ER diagram shows the relationship between students, exams, login logs, question attempts, and cheating alerts to maintain database integrity.

---

## ⚙️ Features

* Manage student records
* Store exam schedules
* Track login and logout activities
* Record question attempts and answer time
* Detect cheating activities
* Generate performance insights using SQL queries

---

## 📊 SQL Concepts Used

The project demonstrates the following SQL concepts:

* **DDL (Data Definition Language)**

  * CREATE DATABASE
  * CREATE TABLE

* **DML (Data Manipulation Language)**

  * INSERT INTO

* **Joins**

* **Subqueries**

* **Window Functions**

* **Aggregate Functions**

  * COUNT()
  * AVG()
  * MIN()

* **Filtering and Sorting**

  * WHERE
  * LIKE
  * BETWEEN
  * ORDER BY

---

## 📈 Example SQL Queries

Examples implemented in the project:

* Display student name, subject, and login time
* Identify students with cheating alerts
* Calculate login duration of students
* Find students who attempted more questions than average
* Rank students using window functions

---

## 📁 Project Files

Online-Exam-Monitoring-System/

* Online Exam Monitoring System.pdf
* README.md

---

## 🔍 Key Learning Outcomes

* Understanding relational database design
* Implementing primary and foreign keys
* Writing complex SQL queries
* Using joins, subqueries, and window functions
* Monitoring and analyzing exam-related data

---

## 👨‍💻 Author

**Avinash Kad**

SQL Database Management Project
