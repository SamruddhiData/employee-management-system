# 🧾 Employee Management System (HRMS) – SQL & PL/SQL Project

## 🔍 Overview
This project is a complete Employee Management System built using **Oracle SQL** and **PL/SQL**. It helps manage employee records, departments, leaves, and monthly payroll processing using procedures, triggers, and packages.

## 📌 Features
- Employee and department record management
- Leave request tracking with validations
- Monthly salary processing via PL/SQL procedures
- Hierarchical queries for department reporting structure
- Triggers for auto-validation and leave policies
- Sample data for easy testing and demonstration

## 🗃️ Database Schema
**Tables:**
- `employees`: Basic employee information
- `departments`: Department details
- `leaves`: Employee leave records
- `payroll`: Monthly salary data

**Procedures:**
- `process_monthly_salary(p_month IN VARCHAR2)`: Adds salary records for each employee

**Triggers:**
- `trg_validate_leave`: Prevents leaves longer than 5 days

## 📂 File Structure
