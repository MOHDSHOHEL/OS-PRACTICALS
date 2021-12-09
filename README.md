# OS-PRACTICALS
There are some practical example regarding cpu scheduling and process.
# Q1 RR(Round Robin Scheduling algorithm with fixed quanta value)
Round Robin(RR) scheduling algorithm is mainly designed for time-sharing systems. This algorithm is similar to FCFS scheduling, but in Round Robin(RR) scheduling, preemption is added which enables the system to switch between processes.
A fixed time is allotted to each process, called a quantum, for execution.Once a process is executed for the given time period that process is preempted and another process executes for the given time period.Context switching is used to save states of preempted processes.This algorithm is simple and easy to implement and the most important is thing is this algorithm is starvation-free as all processes get a fair share of CPU.


![Q1](https://user-images.githubusercontent.com/77627369/145346062-2b35c973-7aad-4709-8ecc-da98e29f1268.png)


# Demonstration of fork()
In this program parent and child run same codes and parent process is executed first![Q2](https://user-images.githubusercontent.com/77627369/145346200-3d66fde6-2afc-4cb2-800a-8785fb08c79c.png)
