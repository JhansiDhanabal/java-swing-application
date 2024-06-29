# Leave Report Generator

## Project Overview

The Leave Report Generator is a Java Swing application designed to efficiently manage and generate reports on student leave. This tool provides an intuitive graphical interface for class in-charges to report leave details seamlessly.

## Project Purpose

The primary goal of this project is to facilitate communication between the Head of Department (HOD) and parents regarding students who frequently take leave, by generating comprehensive reports.

## Features

- **User Authentication**
  - Secure login for authorized personnel.

- **Leave Management**
  - Add, update, and delete student records.

- **Report Generation**
  - Generate detailed reports on frequent leave.
  - Export reports in PDF format.

## Functional Requirements

1. **User Authentication**
   - Class in-charge users can log in securely.

2. **Leave Management**
   - Add new student records.
   - Edit existing student records.
   - Delete student records as needed.

3. **Leave Report Generation**
   - Generate reports based on selected roll numbers.
   - Export reports for external use.

## Non-Functional Requirements

1. **Usability**
   - User-friendly interface designed with Java Swing.
   - Clear navigation and prompts for ease of use.

2. **Performance**
   - Quick retrieval and management of leave records.
   - Efficient report generation.

## Technologies Used

- **Java**
- **Swing**
- **JDBC (Java Database Connectivity)**
- **MySQL**

## Use Case

### Actors
- **Class In-charge Personnel**: Can log in, manage student leave records, and generate reports.

### Use Cases
- **Login**
- **View Student Record**
- **Add Student Record**
- **Update Student Record**
- **Delete Student Record**
- **Generate Leave Report**
- **Export Report**

## Class Diagram

```plaintext
+--------------+
|   Student    |
+--------------+
| - id         |
| - name       |
| - guardian   |
| - address    |
| - year       |
| - degree     |
| - course     |
| - gender     |
+--------------+

+--------------+
|    Admin     |
+--------------+
| - admin_id   |
| - password   |
+--------------+
```

## Sequence Diagram

1. **Login Flow**:
   - Launch Application → Login Screen → Enter Credentials → Authentication → Main Dashboard

2. **Leave Management Flow**:
   - Main Dashboard → View Student Details → Add/Update/Delete Student Details → Save Changes

3. **Report Generation Flow**:
   - Main Dashboard → Generate Report → Give Rollno → View/Export Report

## Thank You

Thank you for reviewing the Leave Report Generator project. For any inquiries or contributions, please feel free to open an issue or submit a pull request.

---
