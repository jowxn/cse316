CPU Scheduling Algorithms Comparison

Introduction

This project implements and compares various CPU scheduling algorithms, including:

First-Come-First-Serve (FCFS)

Shortest Job Next (SJN)

Round Robin (RR)

Priority Scheduling

Multilevel Queue Scheduling

The goal is to evaluate their efficiency based on waiting time, turnaround time, response time, and CPU utilization. The project also provides data visualization through Gantt charts and statistical graphs, with an optional GUI for user interaction.

Features

Algorithm Implementation:

Simulates process execution using multiple scheduling techniques.

Defines process attributes like arrival time, burst time, priority, and quantum (for RR).

Supports both predefined and user-input process data.

Performance Analysis & Visualization:

Computes key performance metrics.

Generates Gantt charts for process execution order.

Provides comparative bar charts, line graphs, and tables for analysis.

GUI (Optional):

Allows users to input process details and select scheduling algorithms.

Displays real-time Gantt charts and performance metrics.

Enhances user interaction and visualization.

Technologies Used

Programming Language: Python

Libraries:

NumPy & Pandas (Data handling & computation)

Matplotlib & Seaborn (Visualization)

Tkinter / PyQt / Streamlit (For GUI, if implemented)

Installation & Setup

Clone the repository:

git clone https://github.com/jowxn/cse316.git
cd cpu-scheduling-comparison

Install dependencies:

pip install numpy pandas matplotlib seaborn

Run the program:

python main.py

(Optional) Run the GUI version:

python gui.py

Usage

Select a scheduling algorithm.

Enter process details manually or use predefined test cases.

View Gantt charts and performance metrics.

Compare algorithm efficiency using graphical analysis.

Future Enhancements

Machine Learning-based scheduler prediction.

Real-time OS-based simulation.

Multi-core scheduling support.

Contributors

Jowan Jow Mathew
Thomas Prinil
Mazin Hami C M

License

This project is licensed under the MIT License.
