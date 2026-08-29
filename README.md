# 🚆 Train Consist Management App

A **Java Console-Based Application** that simulates a **Train Consist Management System**. This project is designed as a learning application to understand **Core Java**, **Collections Framework**, **Java Streams**, **Algorithms**, **Exception Handling**, **Regular Expressions**, and **Data Structures** through 20 incremental real-world use cases.

The application demonstrates how railway operators manage train formations, passenger bogies, cargo bogies, capacities, searching, sorting, validation, and safety rules.

---











## 📌 Project Objectives

The Train Consist Management App helps learners understand:

- Core Java Fundamentals
- Java Collections Framework
- Java Stream API
- Object-Oriented Programming (OOP)
- Searching & Sorting Algorithms
- Exception Handling
- Regular Expressions
- Performance Benchmarking
- Defensive Programming
- Clean Code Practices

---

# ✨ Features

- Initialize Train Consist
- Add & Remove Passenger Bogies
- Maintain Unique Bogie IDs
- Ordered Train Formation
- Preserve Insertion Order
- Map Bogie Capacity
- Sort Bogies using Comparator
- Stream API Filtering
- Grouping using Collectors
- Capacity Aggregation
- Regex Validation
- Goods Safety Compliance
- Performance Benchmarking
- Custom Exceptions
- Runtime Exception Handling
- Bubble Sort
- Arrays.sort()
- Linear Search
- Binary Search
- Defensive Programming

---

# 🛠 Technologies Used

- Java 17+
- Java Collections Framework
- Java Stream API
- Regular Expressions
- OOP Principles
- IntelliJ IDEA
- Git
- GitHub

---

# 📂 Project Structure

```
TrainConsistManagementApp
│
├── src
│   ├── model
│   │      Bogie.java
│   │      GoodsBogie.java
│   │
│   ├── exception
│   │      InvalidCapacityException.java
│   │      CargoSafetyException.java
│   │
│   ├── service
│   │      TrainService.java
│   │
│   ├── util
│   │      ValidationUtil.java
│   │
│   └── TrainConsistManagementApp.java
│
├── README.md
└── .gitignore
```

---

# 📚 Use Cases

## ✅ UC1 – Initialize Train and Display Consist Summary

- Initialize Train Consist
- Display Welcome Message
- Create Empty ArrayList
- Display Initial Bogie Count

### Concepts

- Class
- Main Method
- ArrayList
- List Interface

---

## ✅ UC2 – Add Passenger Bogies

- Add Bogies
- Remove Bogies
- Search Bogies

### Concepts

- ArrayList
- add()
- remove()
- contains()

---

## ✅ UC3 – Track Unique Bogie IDs

- Store Bogie IDs
- Prevent Duplicates

### Concepts

- Set
- HashSet

---

## ✅ UC4 – Maintain Ordered Train Formation

- Attach Engine
- Pantry
- Cargo
- Guard Coach

### Concepts

- LinkedList
- addFirst()
- addLast()
- removeFirst()
- removeLast()

---

## ✅ UC5 – Preserve Insertion Order

- Ordered Unique Bogies

### Concepts

- LinkedHashSet

---

## ✅ UC6 – Map Bogie Capacity

- Store Capacity
- Display Capacity

### Concepts

- HashMap
- Map Interface
- entrySet()

---

## ✅ UC7 – Sort Bogies by Capacity

- Comparator Sorting

### Concepts

- Comparator
- Lambda Expression
- Collections.sort()

---

## ✅ UC8 – Filter Passenger Bogies

- Filter Capacity > 60

### Concepts

- Stream API
- filter()
- collect()

---

## ✅ UC9 – Group Bogies

- Group by Type

### Concepts

- Collectors.groupingBy()

---

## ✅ UC10 – Count Total Seats

- Aggregate Capacity

### Concepts

- map()
- reduce()

---

## ✅ UC11 – Validate Train ID

- Regex Validation
- Train ID
- Cargo Code

### Concepts

- Pattern
- Matcher
- Regex

---

## ✅ UC12 – Goods Safety Compliance

- Validate Goods Bogies
- Petroleum Safety Rules

### Concepts

- allMatch()
- Streams
- Lambda

---

## ✅ UC13 – Performance Comparison

- Loop vs Streams

### Concepts

- System.nanoTime()

---

## ✅ UC14 – Custom Exception

- Validate Capacity

### Concepts

- Checked Exception
- Custom Exception

---

## ✅ UC15 – Runtime Exception Handling

- Cargo Assignment
- try-catch-finally

### Concepts

- Runtime Exception
- finally

---

## ✅ UC16 – Bubble Sort

- Manual Sorting

### Concepts

- Bubble Sort
- Nested Loops

---

## ✅ UC17 – Arrays.sort()

- Production Sorting

### Concepts

- Arrays.sort()

---

## ✅ UC18 – Linear Search

- Sequential Search

### Concepts

- O(n)

---

## ✅ UC19 – Binary Search

- Optimized Search

### Concepts

- Divide & Conquer
- O(log n)

---

## ✅ UC20 – Defensive Programming

- Prevent Search on Empty Train

### Concepts

- IllegalStateException
- Fail Fast Principle

---

# 📖 Concepts Covered

## Core Java

- Classes
- Objects
- Constructors
- Encapsulation
- Collections
- Exception Handling
- Regex

---

## Java Collections

- ArrayList
- LinkedList
- HashSet
- LinkedHashSet
- TreeSet
- HashMap

---

## Java Stream API

- stream()
- filter()
- map()
- reduce()
- collect()
- groupingBy()
- allMatch()
- forEach()

---

## Algorithms

### Sorting

- Bubble Sort
- Arrays.sort()
- Comparator

### Searching

- Linear Search
- Binary Search

---

## Exception Handling

- try
- catch
- finally
- throw
- throws
- Checked Exception
- Runtime Exception
- Custom Exception

---

## Regular Expressions

- Pattern
- Matcher
- Character Classes
- Quantifiers

---

## Performance

- Time Complexity
- Space Complexity
- System.nanoTime()

---

# ▶️ How to Run

### Clone Repository

```bash
git clone https://github.com/BL-Anbu/TrainConsistManagementApp.git
```

### Open Project

Open the project using **IntelliJ IDEA** or **Eclipse**.

### Compile

```bash
javac TrainConsistManagementApp.java
```

### Run

```bash
java TrainConsistManagementApp
```

---

# 🎯 Learning Outcomes

After completing this project, you will understand:

- Core Java
- Java Collections
- Stream API
- OOP Concepts
- Sorting Algorithms
- Searching Algorithms
- Exception Handling
- Defensive Programming
- Clean Code Practices
- Real-world Data Structure Usage

---

# 🚀 Future Enhancements

- Database Integration
- Spring Boot REST API
- JWT Authentication
- Kafka Event Processing
- Docker Support
- Microservices Architecture
- Railway Reservation Module
- Admin Dashboard
- Passenger Management
- Ticket Booking System

---

# 👨‍💻 Author

**Anbarasu A**

- Java Full Stack Developer
- Spring Boot Developer
- GitHub: https://github.com/BL-Anbu

---

# ⭐ Support

If you found this project helpful, please consider giving it a **⭐ Star** on GitHub.

---

# 📄 License

This project is developed for **learning and educational purposes**.
