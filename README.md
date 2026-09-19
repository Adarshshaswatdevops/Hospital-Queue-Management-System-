# Hospital Queue Management System

A C++ based Hospital Queue Management System developed using Data Structures.

## 📌 Project Description

This project manages patients in a hospital using different types of queues.

Normal patients are managed using a standard Queue, while emergency patients are managed using a Priority Queue according to their priority level.

## 🚀 Features

- Add Normal Patient
- Add Emergency Patient
- Assign Automatic Patient ID
- Set Emergency Priority
- Serve Next Patient
- View Normal Patient Queue
- View Emergency Patient Queue
- Search Patient by ID
- Search Patient by Name
- Display Patient Details

## 🧠 Data Structures Used

- Queue
- Priority Queue
- Vector
- Structure
- Searching
- FIFO (First In, First Out)

## ⚙️ Emergency Priority

Emergency patients are assigned three priority levels:

1. High
2. Medium
3. Low

Patients with higher priority are served before patients with lower priority.

## 💻 Technologies Used

- C++
- C++ STL
- Data Structures

## ▶️ How to Run

Compile the program using a C++ compiler:

```bash
g++ src/hospital_queue.cpp -o hospital_queue
