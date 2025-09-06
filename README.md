# 🖥️ Non-Preemptive SJF Scheduler

This project simulates **Non-Preemptive Shortest Job First (SJF) CPU scheduling**, a fundamental concept in operating systems.  

It calculates **waiting time** and **turnaround time** for each process based on arrival and burst times, displaying the process execution order and average times.

--------------------------------------------------------------------------------------------------

## ⚙️ How It Works

1. Define a list of processes with:
   - **Process ID**  
   - **Arrival Time**  
   - **Burst Time**  

2. The program schedules processes using the **Shortest Job First** principle:
   - Selects the process with the shortest burst time from those that have already arrived  
   - Non-preemptive: once a process starts, it runs to completion  

3. Calculates:
   - **Waiting Time (WT)** for each process  
   - **Turnaround Time (TAT)** for each process  

4. Displays the process table and **average waiting and turnaround times**.

--------------------------------------------------------------------------------------------------

## 🚀 Usage

1. Run the Python script:
```bash
python sjf_non_preemptive.py
Example Input (in script):

processes = [0, 1, 2, 3]
arrival_time = [0, 2, 4, 5]
burst_time = [7, 4, 1, 4]
Sample Output:


Process  Arrival Time  Burst Time  Waiting Time  Turnaround Time
0        0            7           0             7
1        2            4           5             9
2        4            1           3             4
3        5            4           4             8

```
Average Waiting Time: 3.00
Average Turnaround Time: 7.00

--------------------------------------------------------------------------------------------------

✨ Features

✅ Calculates waiting time and turnaround time for each process

✅ Implements non-preemptive SJF CPU scheduling

✅ Computes average waiting and turnaround times

✅ Demonstrates scheduling efficiency based on shortest job selection
