# ProSync - CPU Task Explorer

**ProSync** is a C++ application that visualizes CPU scheduling algorithms and process management. This application offers users an interactive way to explore scheduling techniques like **First-Come-First-Serve (FCFS)**, **Shortest Job First (SJF)** (both preemptive and non-preemptive), and **Round Robin** with an optional time quantum. The application uses graphics to display Gantt charts, making it easy to visualize CPU task scheduling.

## Features
- **Interactive Input**: Choose between manual input or random process generation.
- **Multiple Scheduling Algorithms**:
  - First-Come-First-Serve (FCFS)
  - Shortest Job First (SJF) with both preemptive and non-preemptive modes
  - Round Robin (with customizable time quantum)
- **Gantt Chart Visualization**: Displays Gantt charts for each scheduling method to illustrate process execution.
- **Performance Metrics**: Calculate and display average waiting and turnaround times for each scheduling method.

## Installation and Setup
### Prerequisites
1. **C++ compiler**: Ensure you have a C++ compiler installed (e.g., g++, clang++).
2. **Graphics Library**: For graphics support, this project requires the **BGI graphics library**. Make sure you have `graphics.h` and BGI files (e.g., for Turbo C++ or alternatives like WinBGIm for newer compilers).

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/ProSync-CPU-task-explorer.git
   cd ProSync-CPU-task-explorer
Compile the code:
bash
Copy code
g++ ProSync.cpp -o ProSync -lgraph

Run the executable:
bash
Copy code
./ProSync

Usage
Input Mode: Select manual or random input for processes.
Scheduling Selection: Choose from FCFS, SJF (preemptive/non-preemptive), or Round Robin.
Output: Displays Gantt chart and metrics (average waiting and turnaround times).

Sample Usage
plaintext
Copy code
Input Mode?
0. Random
1. Manually
Select scheduling options as prompted. If Round Robin is selected, specify a time quantum. The Gantt chart and process metrics will be displayed.

Contributing
Feel free to open issues or submit pull requests for new features, bug fixes, or enhancements!
