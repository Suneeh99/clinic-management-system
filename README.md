# Clinic Management System

**Created by Suneth Hettiarachchi (SE02 - UGC0223025)**

A simple console-based Clinic Management System built in C++ using CodeBlocks. This system enables basic clinic functionalities such as patient and doctor management, appointment scheduling, and record keeping using text files.

---

## 📘 What Is This?

This project provides a basic management system for clinics. It allows:

- Patients to sign up, book/cancel appointments, and update personal information.
- Doctors to manage appointments, view patient records, and update medical history.
- Secure (hashed) password management for login.
- Data persistence through local text files (e.g., `patient.txt`, `doctor data.txt`).

---

## 💻 Technologies Used

- **C++**: Core programming language used to build the system. It demonstrates:
  - Object-Oriented Programming (OOP)
  - File Handling (text-based storage)
  - Basic authentication and password hashing
  - Menu-driven console interface

- **CodeBlocks**: An open-source IDE used to write, build, and run the C++ code.

- **Text Files**: For lightweight local data storage (no external databases used).

---

## 🖥 Requirements

- A computer with **Windows OS**
- **CodeBlocks IDE** installed

---

## ⚙️ Getting Started

### 1. Open CodeBlocks
Launch CodeBlocks on your machine.

### 2. Load the Project
Click on `File` > `Open` and select the main `.cpp` file of the Clinic Management System.

### 3. Compile the Code
Use `Build` > `Build and run` to compile and execute the program.

### 4. Run the Program
If the compilation is successful, the console application will start.

---

## 🧑‍⚕️ Program Workflow

When the application starts, you will be prompted to identify yourself as a **patient**, **doctor**, or choose to **exit**.

---

### 👨‍💼 For Patients

- **Sign Up / Log In**: 
  - New users can create an account.
  - Existing users can log in with credentials.

- **Features**:
  - **View Info**: See appointments and personal details.
  - **Make Appointment**: Choose a doctor and time slot.
  - **Cancel Appointment**: Remove existing appointments.
  - **Update Info**: Change email or phone number.

---

### 🩺 For Doctors

- **Sign Up / Log In**: 
  - New doctors can register.
  - Existing doctors can log in securely.

- **Features**:
  - **Check Schedule**: View upcoming patient appointments.
  - **View Patient Records**: Access patient histories.
  - **Update Records**: Add notes after consultations.
  - **Complete Appointment**: Mark an appointment as completed.

---

## 📁 File Storage

The program uses simple text files to store and retrieve data:

- `patient.txt` – Patient information and credentials
- `doctor data.txt` – Doctor data and schedules

---

## 🔒 Security Notes

- Passwords are hashed for safety.
- For production use, consider using more robust encryption and secure data storage practices.

---

## ✅ Conclusion

This guide and project aim to simplify clinic operations with a basic and functional C++ console application. Ideal for beginners learning file handling and object-oriented programming in C++.

---


## 🔗 Repository

[👉 Visit the GitHub Repo](https://github.com/Suneeh99/clinic-management-system)
