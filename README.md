This is a Java Swing application for CPU Scheduling. The program provides a graphical user interface (GUI) to manage a list of processes and calculate the average time taken and waiting time using different algorithms.

## Features:

Process Management: The application allows users to add, delete, and clear processes from the table.
Algorithm Selection: Users can choose from six different algorithms: First-Come-First-Served (FCFS), Shortest Job First (SJF), Shortest Remaining Time First (SRTF), Priority Non-Preemptive (PNP), Priority Preemptive (PP), and Round Robin (RR).
Gantt Chart Generation: The program generates a Gantt chart for each algorithm, showing the execution time of each process.
Statistics: The application calculates and displays the average time taken (TAT) and average waiting time (WAT) for each algorithm.
Classes:

CPUScheduling: The main class that creates the GUI and handles user input.
Process: A class representing a process, with attributes such as process ID, arrival time, burst time, and priority.
CPUAlgos: An abstract class that defines the algorithms for CPU scheduling.
Notes:

The application uses Java Swing for the GUI and Java AWT for graphics.
The program uses a defaultTableModel to manage the data in the table.
The checkVaidate() method validates the user input and checks for errors.
Future Development Ideas:

Add more algorithms for CPU scheduling.
Implement a more advanced Gantt chart generation algorithm.
Allow users to save and load process lists.
Add more statistics, such as average response time and turnaround time.
You can write a description for your GitHub repository by following this format:

## CPU Scheduling Simulator

A Java Swing application for CPU scheduling that allows users to manage a list of processes and calculate the average time taken and waiting time using different algorithms.

## Features
Process management: add, delete, and clear processes from the table
Algorithm selection: choose from six different algorithms
Gantt chart generation: generate a Gantt chart for each algorithm
Statistics: calculate and display average time taken (TAT) and average waiting time (WAT)
Classes
CPUScheduling: main class for GUI and user input handling
Process: class representing a process with attributes such as ID, arrival time, burst time, and priority
CPUAlgos: abstract class defining algorithms for CPU scheduling
Future Development Ideas
Add more algorithms for CPU scheduling
Implement advanced Gantt chart generation
Allow users to save and load process lists
Add more statistics, such as average response time and turnaround time
