# Task 7: Priority Scheduling (Preemptive)

## Processes
| Process | Arrival Time | Burst Time | Priority |
|---------|--------------|------------|----------|
| P1      | 0            | 8          | 2        |
| P2      | 1            | 3          | 1        |
| P3      | 2            | 5          | 3        |

## Gantt Chart
| P1 (0-1) | P2 (1-4) | P1 (4-11) | P3 (11-16) | P1 (16-19) |

## Results
| Process | Completion Time | Turnaround Time | Waiting Time |
|---------|----------------|----------------|--------------|
| P1      | 19             | 19             | 11           |
| P2      | 4              | 3              | 0            |
| P3      | 16             | 14             | 9            |

## Averages
- **Average Waiting Time (AWT)**: 6.67 ms
- **Average Turnaround Time (ATAT)**: 12.0 ms
