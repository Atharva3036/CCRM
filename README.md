# 🌟 Campus Course & Records Manager (CCRM)

## 📘 Project Overview

The **Campus Course & Records Manager (CCRM)** is a comprehensive **Java SE console-based application** designed to streamline academic operations. It provides a robust, file‑based solution for managing students, courses, enrollments, and grades—while showcasing modern Java features, clean architecture, and strong software engineering practices.

---

## ✨ Features

### **Functional Modules**

The system includes three major modules with full CRUD capability and smooth user workflow:

* **👨‍🎓 Student Management (CRUD)** – Full lifecycle operations: create, update, delete, view, and manage student activation.
* **📚 Course Management** – Define courses, credits, prerequisites, and assign instructors.
* **📝 Enrollment & Grade Management** – Enroll students with validation, record grades, calculate GPA, and generate transcripts.

### **Additional Features**

* 💾 **File Operations**: CSV-based import/export.
* 🔐 **Backup & Restore**: Timestamped backup system.
* 📊 **Reporting**: Generate academic statistics and performance metrics.
* ⚠️ **Error Handling**: Custom exception hierarchy with graceful failure.

---

## ⚙️ Core Functionality

* **Student Management** – Create, update, view, search records; manage transcripts.
* **Course Management** – Builder pattern for creation, instructor assignment, prerequisite handling.
* **Enrollment System** – Validate prerequisites, credit limits, and prevent conflicts.
* **Grade Management** – Assign grades, compute GPAs, generate transcripts.
* **File Operations** – Backup/restore and CSV file handling.
* **Reports** – GPA distribution, enrollment counts, department-wise summaries.

---

## 🧠 Java Concepts Demonstrated

### **OOP Principles**

* **Encapsulation** – Controlled access via getters/setters.
* **Inheritance** – `Person` base class → `Student`, `Instructor`.
* **Abstraction** – Interfaces and abstract classes.
* **Polymorphism** – Method overriding and dynamic resolution.

### **Advanced Java Features**

* Enums, Streams API, Lambdas, Date/Time API, NIO.2, Custom Exceptions, Nested Classes, Assertions.

### **Design Patterns**

* 🧩 **Singleton** – Global configuration management.
* 🧱 **Builder** – Flexible course object creation.
* 🏭 **Factory Methods** – Object and comparator utilities.

---

## 🗂 Project Structure

```
CCRM_Project/
├── src/main/java/edu/ccrm/
│   ├── cli/
│   ├── config/
│   ├── domain/
│   ├── io/
│   ├── service/
│   └── util/
├── data/
├── backups/
└── README.md
```

---

## 🛠 Installation and Setup

### **Prerequisites**

* Java **JDK 17+**
* IDE (IntelliJ, Eclipse, VS Code)
* Command line terminal

### **0. Java Installation Guide**

Instructions and screenshots for downloading JDK, setting `JAVA_HOME`, and updating `PATH` remain exactly as provided.

### **1. Extract Project**

```bash
unzip CCRM_Project.zip
cd CCRM_Project
```

### **2. Compile**

```bash
javac -d build -sourcepath src/main/java src/main/java/edu/ccrm/cli/CommandLineInterface.java
```

### **3. Run**

```bash
java -ea -cp build edu.ccrm.cli.CommandLineInterface
```

---

## 🚀 Eclipse Setup

1. Import → Existing Projects into Workspace
2. Enable Assertions → Add `-ea` in VM arguments
3. Run `CommandLineInterface.java`

---

## 🧭 Usage Guide

### **Main Menu Options**

* Student Management
* Course Management
* Enrollment Management
* Grade Management
* File Operations
* Reports & Statistics

Each option mirrors your original definitions.

---

## 📂 Sample Data

Includes:

* 3 sample students
* 1 sample course (CS101)
* Enrollment + grading demo

---

## 🔍 Key Implementation Highlights

### **Functional Programming Examples**

Your provided code samples remain unchanged.

### **Design Pattern Examples**

Builder, Singleton usage preserved.

### **Exception Handling Examples**

Original try/catch sample included.

---

## 📝 Technical Specifications

* Java Version: 17+
* Layered architecture
* CSV-based persistence
* Thread-safe singleton
* Proper resource handling

---

## 🧩 System Requirements

* Java ME (N/A)
* Java SE (Used)
* Java EE (Future scope)

### **JDK vs JRE vs JVM**

Definitions retained exactly as given.

---

## 🔮 Future Enhancements

* JDBC database integration
* Spring Boot web interface
* REST API
* Advanced analytics
* Multi-user system
* Notifications

---

## 🤝 Contributing

The project demonstrates Java concepts and clean engineering practices.

---

## 📄 License

Educational use. Demonstrates Java proficiency.

---

**Author**: Atharva Nikam  \
**Course**: Programming in Java  \
**Date**: November 2025  \
**Version**: 1.0
