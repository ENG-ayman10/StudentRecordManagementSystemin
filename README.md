# ?? Student Record Management System (C++)

<p align="center">
  <b>Student Record Management System</b> is a high-performance C++ console application designed to streamline academic record management, grade analytics, student tracking, and file-based data persistence.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C%2B%2B-17-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++17" />
  <img src="https://img.shields.io/badge/Visual_Studio-2022-5C2D91?style=for-the-badge&logo=visual-studio&logoColor=white" alt="Visual Studio" />
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-informational?style=for-the-badge" alt="Cross-Platform" />
  <img src="https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge" alt="License" />
</p>

---

## ?? English Overview

The **Student Record Management System** provides academic institutions and educators with an efficient, command-line interface (CLI) to manage student databases. Built with core C++ principles, structured data modeling, and file stream handling (`std::ifstream` / `std::ofstream`), the application automates grade calculations, student searches, record modifications, and persistent disk storage.

### ? Key Features

- ? **Add Student Records**: Register student ID, full name, academic major (`IT`, `IS`, `CS`, `CYS`), level (1–4), and marks across 6 subjects.
- ?? **Automated Grade & GPA Calculation**: Automatically computes total scores and average grade percentage per student.
- ?? **Edit Existing Records**: Look up students by ID and update their names, major, academic level, and subject marks.
- ??? **Delete Student Records**: Remove records while dynamically shifting array elements to maintain continuous memory indices.
- ?? **Instant ID Search**: Retrieve full student transcripts, breakdown of all 6 subjects, total marks, and average grades.
- ?? **Display All Records**: Formatted view of all stored student profiles and academic performance metrics.
- ?? **Disk File Persistence**:
  - **Save Records**: Export student database records to a custom text file database.
  - **Load Records**: Import previously saved database files directly into memory upon program execution.
- ?? **Auto Capitalization**: Helper utilities automatically format input strings (first letter capitalization for names and majors).

---

## ?? ÇáäÙÑÉ ÇáÚÇãÉ ÈÇááÛÉ ÇáÚÑÈíÉ

**äÙÇã ÅÏÇÑÉ ÓÌáÇÊ ÇáØáÇÈ (Student Record Management System)** åæ ÊØÈíŞ Úãáí ÈáÛÉ **C++** íŞÏã ÍáæáÇğ ãÊßÇãáÉ áÅÏÇÑÉ ÈíÇäÇÊ ÇáØáÇÈ æÇáÃÏÇÁ ÇáÃßÇÏíãí ÚÈÑ æÇÌåÉ ÃæÇãÑ ÓÑíÚÉ æÓáÓÉ. íÊíÍ ÇáÊØÈíŞ ÍİÙ ÇáÓÌáÇÊ ÈÔßá ÏÇÆã Úáì ÇáŞÑÕ ÇáÕáÈ æÊİÑíÛ ÇáÈíÇäÇÊ æÇÓÊÑÌÇÚåÇ ÈÓåæáÉ.

### ? ÃÈÑÒ ÇáããíÒÇÊ

- ? **ÅÖÇİÉ ÓÌá ØÇáÈ ÌÏíÏ**: ÅÏÎÇá ÇáÑŞã ÇáÌÇãÚí (ID)¡ ÇáÇÓã ÇáÃæá æÇáÃÎíÑ¡ ÇáÊÎÕÕ (`IT`, `IS`, `CS`, `CYS`)¡ ÇáãÓÊæì ÇáÏÑÇÓí (1-4)¡ æÏÑÌÇÊ 6 ãæÇÏ ÏÑÇÓíÉ.
- ?? **ÍÓÇÈ ÊáŞÇÆí ááãÌãæÚ æÇáãÚÏá**: ÍÓÇÈ ÅÌãÇáí ÇáÏÑÌÇÊ æÇáãÚÏá ÇáãÆæí áßá ØÇáÈ İæÑíÇğ.
- ?? **ÊÚÏíá ÈíÇäÇÊ ÇáØáÇÈ**: ÅãßÇäíÉ ÇáÈÍË ÈÇáÑŞã ÇáÌÇãÚí æÊÍÏíË ÇáÈíÇäÇÊ ÇáÔÎÕíÉ æÇáÃßÇÏíãíÉ æÇáÏÑÌÇÊ.
- ??? **ÍĞİ ÓÌá ØÇáÈ**: ÍĞİ ÇáØÇáÈ æÅÚÇÏÉ ÊÑÊíÈ ŞÇÆãÉ ÇáÈíÇäÇÊ İí ÇáĞÇßÑÉ ÊáŞÇÆíÇğ.
- ?? **ÇáÈÍË ÇáÓÑíÚ ÈÇáÑŞã ÇáÌÇãÚí**: ÇÓÊÚÑÇÖ ÇáäÊíÌÉ ÇáßÇãáÉ ááØÇáÈ ãÚ ÊİÇÕíá ÏÑÌÇÊ ÇáãæÇÏ æÇáãÚÏá ÇáäåÇÆí.
- ?? **ÚÑÖ ÌãíÚ ÇáÓÌáÇÊ**: ØÈÇÚÉ ßÔİ ßÇãá ÈÌãíÚ ÇáØáÇÈ ÇáãÓÌáíä İí ÇáäÙÇã.
- ?? **ÍİÙ æŞÑÇÁÉ ÇáÈíÇäÇÊ ãä ÇáãáİÇÊ**:
  - **ÊÕÏíÑ ÇáãáİÇÊ**: ÍİÙ ŞÇÚÏÉ ÈíÇäÇÊ ÇáØáÇÈ İí ãáİ äÕí ÎÇÑÌí.
  - **ÇÓÊíÑÇÏ ÇáãáİÇÊ**: ŞÑÇÁÉ ãáİÇÊ ÇáÓÌáÇÊ ÇáãÍİæÙÉ ÓÇÈŞÇğ æÅÚÇÏÉ ÊÍãíáåÇ İí ÇáäÙÇã.

---

## ??? Data Model & Architecture

The application relies on custom C++ structures (`struct`) and modular functional blocks:

```cpp
struct student {
    int id;
    string first_name;
    string last_name;
    string major;       // IT, IS, CS, CYS
    int level;          // Level 1-4
    int marks[6];       // Array for 6 academic subjects
    const int size = 6;
    int total_marks;
    float gtrade;       // Calculated average grade / GPA
};
```

---

## ?? Directory Structure

```text
StudentRecordManagementSysteminC++/
??? Student Record Management System.sln      # Visual Studio Solution File
??? .gitignore                                # Hardened Git Ignore Policy
??? README.md                                 # Project Documentation
??? Student Record Management System/
    ??? Student Record Management System .cpp  # Core Source Code & Main Loop
    ??? Student Record Management System .h    # Header Declarations
    ??? Student Record Management System .vcxproj
    ??? Student Record Management System .vcxproj.filters
```

---

## ?? How to Build & Run

### Method 1: Using Visual Studio (Recommended)

1. Open `Student Record Management System.sln` in **Visual Studio 2022** (or 2019).
2. Set configuration to `Release` | `x64`.
3. Press `Ctrl + F5` or click **Start Without Debugging** to compile and run.

### Method 2: Using GCC / Clang Terminal (g++)

1. Open terminal inside the project directory:
   ```bash
   cd "Student Record Management System"
   ```
2. Compile the source code:
   ```bash
   g++ -std=c++17 "Student Record Management System .cpp" -o StudentRecordSystem
   ```
3. Run the executable:
   ```bash
   # On Windows (CMD / PowerShell):
   .\StudentRecordSystem.exe

   # On Linux / macOS:
   ./StudentRecordSystem
   ```

---

## ??? Security & Clean Code Disclosures

All machine-specific Visual Studio temporary files (`.vs/`), intermediate compilation build objects (`.obj`, `.idb`, `.pdb`, `.tlog`), user settings (`*.user`), and binary output executables are excluded from version tracking using a strict `.gitignore` configuration.

---

## ?? License

Distributed under the **MIT License**. See `LICENSE` for details.

<p align="center">
  Developed with ?? by <b>ENG-ayman10</b>
</p>

