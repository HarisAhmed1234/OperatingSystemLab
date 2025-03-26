# Task 6: Priority Scheduling (Non-Preemptive)

## Processes
| Process | Arrival Time | Burst Time | Priority |
|---------|--------------|------------|----------|
| P1      | 0            | 7          | 3        |
| P2      | 1            | 4          | 1        |
| P3      | 2            | 6          | 2        |
| P4      | 3            | 5          | 4        |

## Gantt Chart
| P2 (1-5) | P3 (5-11) | P1 (11-18) | P4 (18-23) |

## Results
| Process | Completion Time | Turnaround Time | Waiting Time |
|---------|----------------|----------------|--------------|
| P1      | 18             | 18             | 11           |
| P2      | 5              | 4              | 0            |
| P3      | 11             | 9              | 3            |
| P4      | 23             | 20             | 15           |

## Averages
- **Average Waiting Time (AWT)**: 7.25 ms
- **Average Turnaround Time (ATAT)**: 12.75 ms
