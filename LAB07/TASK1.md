# Task 1: FCFS Scheduling

## Processes
| Process | Arrival Time | Burst Time |
|---------|--------------|------------|
| P1      | 0            | 6          |
| P2      | 2            | 8          |
| P3      | 4            | 7          |
| P4      | 6            | 3          |

## Gantt Chart
| P1 (0-6) | P2 (6-14) | P3 (14-21) | P4 (21-24) |

## Results
| Process | Completion | Turnaround | Waiting |
|---------|------------|------------|---------|
| P1      | 6          | 6          | 0       |
| P2      | 14         | 12         | 4       |
| P3      | 21         | 17         | 10      |
| P4      | 24         | 18         | 15      |

**Averages**:
- **AWT**: 7.25 ms
- **ATAT**: 13.25 ms
