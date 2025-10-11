# 🖥️ OS Microproject: CPU Scheduling & OS Theory

## 🚀 Overview
This microproject simulates two key CPU scheduling algorithms—**Shortest Job First (SJF)** and **Shortest Remaining Time First (SRTF)**—and presents a concise theoretical overview of **process states** and **types of operating systems**. It is designed to be educational, visually intuitive, and evaluator-friendly.

## 👩‍💻 Contributors
- **Aanchal Jain(50)**
- **Shivam Sankpal(63)**
-  **Yash Shinde(67)**

## 🧠 Theory Modules

### 🔄 Process States
- **New** – Process is being created
- **Ready** – Waiting to be assigned to a processor
- **Running** – Instructions are being executed
- **Waiting** – Waiting for an event (e.g., I/O)
- **Terminated** – Process has finished execution

### 🖥️ Types of Operating Systems
- **Batch OS** – Executes batches of jobs without user interaction
- **Time-Sharing OS** – Allows multiple users to share system resources simultaneously
- **Distributed OS** – Manages a group of distinct computers and makes them appear as one
- **Real-Time OS** – Provides immediate response to input, used in embedded systems
- **Network OS** – Supports networking capabilities and resource sharing across systems

## ⚙️ Simulation Features

### ✅ SJF (Non-Preemptive)
- Selects the process with the shortest burst time
- Once a process starts, it runs to completion

### ⏱️ SRTF (Preemptive)
- Continuously selects the process with the shortest remaining time
- Can preempt the current process if a shorter one arrives

### 📊 Output
- Gantt chart visualization
- Average waiting time and turnaround time
- Step-by-step execution trace


