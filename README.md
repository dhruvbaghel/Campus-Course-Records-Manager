# 📘 Campus Course & Records Manager (CCRM)

## 📌 Project Overview
The **Campus Course & Records Manager (CCRM)** is a **console-based Java SE application** that manages student and course data for an institute.  

It supports:
- **Student Management** → Add, update, deactivate, print profiles/transcripts  
- **Course Management** → Add, update, search/filter, assign instructors  
- **Enrollment & Grading** → Enroll/unenroll students, record marks, compute GPA  
- **File Utilities** → Import/export from CSV files, recursive backup, timestamped folders  
- **CLI Workflow** → Interactive menu-driven system using switch-case  

This project also demonstrates **Java concepts** such as OOP principles, exception handling, design patterns, enums, lambdas, and Java NIO.2.

---

## 🏗️ Features
- Manage Students, Courses, and Instructors  
- GPA calculation and transcript generation  
- Enum-based `Semester` and `Grade`  
- Filtering/searching using Java Streams  
- File I/O with NIO.2 APIs (`Path`, `Files`, recursion)  
- Backup with recursive size calculator  
- Design Patterns:
  - **Singleton** → AppConfig  
  - **Builder** → Course.Builder  
- Custom Exceptions:
  - `DuplicateEnrollmentException`  
  - `MaxCreditLimitExceededException`  

---

## 🛠️ How to Run
### Prerequisites
- Install **JDK 17 or above**  
- Verify installation:
  ```bash
  java -version
  javac -version
