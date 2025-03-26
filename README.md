# EEX5563MP

## Multilevel Queue (MLQ) CPU Scheduling Simulator

This repository contains a Python-based simulation of Multilevel Queue (MLQ) CPU Scheduling, a process scheduling technique used in operating systems. The simulator implements MLQ scheduling with an aging mechanism to mitigate CPU starvation.

### Features

Multiple Queues: Divides processes into different priority levels.

Preemptive Scheduling: Higher priority processes preempt lower ones.

Aging Mechanism: Prevents CPU starvation by gradually increasing the priority of long-waiting processes.

User Interface (GUI): Built using Tkinter for easy interaction.

Customizable Parameters: Configure the number of queues, time quantum, and process priorities.

### How to Use
Enter process details: Provide Process ID, Priority, and Burst Time.

Set scheduler parameters: Choose the number of queues and time quantum.

Run the scheduler: Click "Run Scheduler" to execute the MLQ scheduling.

View results: Check the total execution time and process movements

