# 💻 CPU Scheduling Simulator

A Python-based Operating System project that simulates different CPU Scheduling Algorithms and compares their performance using Waiting Time and Turnaround Time.

Built using **Python and Google Colab**, this project helps understand how an Operating System manages CPU execution among multiple processes.

## 📌 Project Overview

CPU Scheduling is an important function of an Operating System. It determines which process gets the CPU for execution and in what order.

This project implements three CPU Scheduling Algorithms and visualizes their execution using Gantt Charts.

## 🚀 Features

- **FCFS (First Come First Serve):** Executes processes in their arrival order.
- **SJF (Shortest Job First):** Executes the available process with the shortest burst time first.
- **Round Robin:** Allocates CPU time to each process using a fixed Time Quantum.
- **Gantt Chart Visualization:** Displays the execution sequence of processes.
- **Performance Analysis:** Calculates Waiting Time and Turnaround Time.
- **Algorithm Comparison:** Compares the average performance of all three algorithms.

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- Matplotlib

## ⚙️ Algorithms Implemented

| Algorithm | Type | Working Principle |
|---|---|---|
| FCFS | Non-Preemptive | Arrival order |
| SJF | Non-Preemptive | Shortest burst time |
| Round Robin | Preemptive | Fixed time quantum |

## 📊 Performance Metrics

The simulator calculates:

- **Completion Time (CT):** Time at which a process finishes execution.
- **Turnaround Time (TAT):** Total time taken by a process from arrival to completion.
- **Waiting Time (WT):** Total time a process spends waiting in the ready queue.
- **Average Waiting Time:** Average waiting time of all processes.
- **Average Turnaround Time:** Average turnaround time of all processes.

### Formulas

- Turnaround Time = Completion Time − Arrival Time
- Waiting Time = Turnaround Time − Burst Time

## ▶️ How to Run the Project

1. Open Google Colab.
2. Upload the `CPU_Scheduling_Simulator.ipynb` notebook.
3. Run all code cells sequentially.
4. View the scheduling results and Gantt Charts.
5. Compare the average Waiting Time and Turnaround Time.

## 📁 Project Structure

```text
CPU-Scheduling-Simulator/
│
├── CPU_Scheduling_Simulator.ipynb
└── README.md
```

## 🎯 Learning Outcomes

- Understanding CPU Scheduling concepts.
- Implementing scheduling algorithms using Python.
- Learning how Gantt Charts represent process execution.
- Calculating CPU scheduling performance metrics.
- Comparing different scheduling algorithms.

## 🔮 Future Improvements

- Add more scheduling algorithms.
- Allow users to enter custom process details.
- Improve Gantt Chart visualization.
- Add preemptive scheduling techniques.

## 👩‍💻 Author

**Saijee Itokar**

B.Tech (Hons) – CSE (Data Analytics)

GitHub: [@saijeeitokar369](https://github.com/saijeeitokar369)

---

⭐ If you find this project useful, feel free to explore and learn from it!

**Developed as part of an Operating Systems academic project.**
