# CPU-Scheduling-Process-Management-Simulator
Developed a C++17-based CPU Scheduling Simulator implementing FCFS, SJF, Priority Scheduling, and Round Robin algorithms. Applied OOP and STL to manage processes, calculate waiting and turnaround times, generate Gantt charts, and compare scheduling performance through efficient algorithmic logic.
# CPU Scheduling and Process Management Simulator

A C++17-based simulation tool that demonstrates CPU scheduling algorithms used in operating systems. The project helps analyze process execution, calculate scheduling metrics, and compare algorithm performance.

## Overview

CPU scheduling is an essential operating system function that determines the order in which processes receive CPU time. This project simulates different scheduling algorithms and evaluates their performance using process scheduling metrics.

The simulator is designed to demonstrate C++ programming, object-oriented design, data structures, algorithms, and operating system concepts.

## Features

- **FCFS (First Come, First Served):** Executes processes in arrival order.
- **SJF (Shortest Job First):** Prioritizes processes with shorter burst times.
- **Priority Scheduling:** Selects processes according to priority.
- **Round Robin:** Allocates CPU time using a configurable time quantum.
- **Scheduling Metrics:** Calculates completion time, turnaround time, waiting time, and response time.
- **Gantt Chart:** Displays the execution sequence of processes.
- **Performance Comparison:** Compares scheduling algorithms using average waiting and turnaround times.

*Note: Include only features that have been implemented and tested.*

## Technologies Used

- **Language:** C++17
- **Concepts:** Object-Oriented Programming, Data Structures and Algorithms
- **Libraries:** C++ Standard Template Library (STL)
- **Tools:** GCC/G++, Git, GitHub

## Scheduling Metrics

The simulator uses the following formulas:

- **Turnaround Time (TAT)** = Completion Time − Arrival Time
- **Waiting Time (WT)** = Turnaround Time − Burst Time
- **Response Time (RT)** = First CPU Start Time − Arrival Time

Average waiting time and average turnaround time are calculated across all processes.

## Getting Started

### Prerequisites

Install a C++ compiler that supports C++17, such as GCC/G++.

Verify the installation:

```bash
g++ --version
```

### Installation

Clone the repository:

```bash
```

Navigate to the project directory:

```bash
cd CPU-Scheduling-Simulator
```

### Compilation

If your project uses a single source file named `main.cpp`:

```bash
g++ -std=c++17 -Wall -Wextra -o scheduler main.cpp
```

### Execution

On Windows:

```bash
scheduler.exe
```

On Linux or macOS:

```bash
./scheduler
```

If your project contains multiple source files, include them in the compilation command or use a build system such as CMake.

## Example Input

```text
Number of processes: 3

Process ID   Arrival Time   Burst Time   Priority
P1           0              5            2
P2           1              3            1
P3           2              1            3
```

## Example Output

The simulator can display a process scheduling table similar to:

```text
Process   Completion   Turnaround   Waiting
P1        5            5            0
P2        9            8            5
P3        6            4            3
```

The example above illustrates FCFS scheduling for the sample input. Your program's actual output may differ depending on the selected algorithm and implementation.

## Learning Outcomes

- Understanding CPU scheduling and process execution.
- Applying OOP principles to organize C++ code.
- Using STL containers and algorithms.
- Analyzing time complexity and algorithm trade-offs.
- Implementing scheduling calculations and validating results.
- Improving debugging and problem-solving skills.

## Future Enhancements

- Add a graphical visualization of the Gantt chart.
- Support importing process data from CSV files.
- Add automated unit tests for scheduling algorithms.
- Generate reports comparing algorithm performance.

## Author

**Sarvesh Chandurkar**

GitHub: https://github.com/SARVESH-C

