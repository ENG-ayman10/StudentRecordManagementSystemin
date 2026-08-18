# 🎓 Student Record Management System (C++)

<p align="center">
  <b>Student Record Management System</b> is a clean, modular C++ console application designed to manage student academic records, calculate GPAs, track subject performance, and handle file-based data storage.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C%2B%2B-17-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++17" />
  <img src="https://img.shields.io/badge/Visual_Studio-2022-5C2D91?style=for-the-badge&logo=visual-studio&logoColor=white" alt="Visual Studio" />
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-informational?style=for-the-badge" alt="Cross-Platform" />
  <img src="https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge" alt="License" />
</p>

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [Data Structure & Architecture](#-data-structure--architecture)
- [Directory Structure](#-directory-structure)
- [Getting Started & Build Instructions](#-getting-started--build-instructions)
- [License](#-license)

---

## 🌟 Overview

The **Student Record Management System** is a command-line interface (CLI) application written in C++ that enables educational administrators and students to manage academic records efficiently. Built using structured data models and standard file streams (std::ifstream / std::ofstream), the program automates grade calculation, record searching, data updating, and persistent disk storage.

---

## ✨ Key Features

- **Add Student Records**: Register student ID, first name, last name, major (IT, IS, CS, CYS), academic level (1 to 4), and marks for 6 subjects.
- **Automated GPA & Grade Calculation**: Computes total marks and average grade percentage automatically.
- **Edit Records**: Search for existing students by ID to modify details or update grades.
- **Delete Records**: Remove student records safely with automatic array index re-alignment.
- **Search by ID**: Instant lookup of student transcripts, grade breakdown, and overall average.
- **Display All Records**: Formatted list showing all stored student profiles.
- **File Persistence**:
  - **Save to File**: Export student records to a text database file.
  - **Load from File**: Import saved student records back into memory.
- **Input Formatting**: Built-in helper functions to auto-capitalize student names and majors.

---

## 🌐 النظرة العامة باللغة العربية

**نظام إدارة سجلات الطلاب** هو برنامج سطر أوامر مكتوب بلغة **C++** لترتيب وإدارة البيانات الأكاديمية للطلاب. يتيح البرنامج إدخال وتعديل البيانات، حساب المعدل التلقائي، البحث السريع، وحفظ واسترجاع البيانات من وإلى الملفات النصية بشكل دائم.

### المميزات الرئيسية:
- **إضافة طالب جديد**: تسجيل رقم الطالب، الاسم، التخصص، المستوى الدراسي، ودرجات 6 مواد.
- **حساب المعدل المئوي**: حساب مجموع الدرجات والمعدل التلقائي لكل طالب.
- **تعديل البيانات**: البحث بالرقم الجامعي وتحديث درجات الطالب أو بياناته.
- **حذف طالب**: حذف السجل مع ترتيب قائمة الطلاب في الذاكرة تلقائياً.
- **البحث السريع**: استعراض تفاصيل درجات الطالب ونتيجته النهائية فورياً.
- **عرض كافة السجلات**: طباعة جميع بيانات الطلاب المسجلين بكشف كامل.
- **حفظ واسترجاع الملفات**: إمكانية تصدير البيانات إلى ملف نصي وقراءتها منه في أي وقت.

---

## 🛠️ Data Structure & Architecture

The application utilizes a custom C++ structure (struct) and functional programming principles:

`cpp
struct student {
    int id;
    string first_name;
    string last_name;
    string major;       // IT, IS, CS, CYS
    int level;          // Level 1 to 4
    int marks[6];       // Marks for 6 subjects
    const int size = 6;
    int total_marks;
    float gtrade;       // Average grade / GPA
};
`

---

## 📁 Directory Structure

`	ext
StudentRecordManagementSysteminC++/
├── Student Record Management System.sln
├── .gitignore
├── README.md
└── Student Record Management System/
    ├── Student Record Management System .cpp
    ├── Student Record Management System .h
    ├── Student Record Management System .vcxproj
    └── Student Record Management System .vcxproj.filters
`

---

## 🚀 Getting Started & Build Instructions

### Option 1: Visual Studio (Recommended)

1. Open Student Record Management System.sln in **Visual Studio**.
2. Select Release or Debug configuration (x64).
3. Press Ctrl + F5 to compile and run.

### Option 2: Command Line (g++)

1. Open your terminal and navigate to the project directory:
   `ash
   cd "Student Record Management System"
   `
2. Compile using g++:
   `ash
   g++ -std=c++17 "Student Record Management System .cpp" -o StudentRecordSystem
   `
3. Run the executable:
   `ash
   # Windows:
   .\StudentRecordSystem.exe

   # Linux / macOS:
   ./StudentRecordSystem
   `

---

## 📄 License

This project is licensed under the **MIT License**.

<p align="center">
  Developed by <b>ENG-ayman10</b>
</p>