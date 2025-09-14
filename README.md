# 🏥 Hospital Management Database Project

This project is a **SQL-based database system** designed to handle and manage hospital operations. It includes entities such as **patients, doctors, departments, rooms, admissions, appointments, prescriptions, and billing**.  

The goal of this project is to demonstrate how relational databases can be used to model real-world hospital workflows in a structured and efficient way.

---

## 🚀 Features
- **Departments & Doctors** → Organize doctors by their respective departments  
- **Patients & Rooms** → Manage patient admissions, discharges, and room allocations  
- **Appointments & Prescriptions** → Schedule appointments and record prescriptions  
- **Billing System** → Generate bills for admissions and track payment status  
- **Queries & Reports** → Predefined SQL queries for staff and administrators  

---

## 🛠️ Technologies Used
- **SQL** (compatible with MySQL / SQL Server / PostgreSQL)  
- **Relational Database Concepts** → Primary keys, foreign keys, joins, group by, having  
- Includes **sample data** for quick testing  

---

## 📂 Database Schema
The database contains the following tables:
- `Department` → Stores hospital departments  
- `Doctor` → Stores doctor details (linked to Department)  
- `Patient` → Stores patient details  
- `Room` → Room details with charges per day  
- `Patient_Room` → Assigns patients to rooms  
- `Medication` → Medications prescribed to patients  
- `Appointment` → Doctor-patient appointments with date/time/status  
- `Prescription` → Prescriptions linked to appointments  
- `Admission` → Admission and discharge records  
- `Bill` → Billing information with payment status  

---

## 📊 Example Queries
Here are some queries included in the project:

- Retrieve all patients  
```sql
SELECT * FROM Patient;
