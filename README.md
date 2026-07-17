# Assignment-4-Heap-Data-Structures-Implementation-Analysis-and-Applications
# Assignment 4: Heap Data Structures – Implementation, Analysis, and Applications

## Student Information

**Name:** Bilal Mohammed  
**Course:** Advanced Big Data and Data Mining

---

## Overview

This project demonstrates the implementation and analysis of heap-based data structures using Python. The assignment includes the implementation of the Heapsort algorithm, comparison with Merge Sort and Quick Sort, and the development of a Priority Queue using a binary heap. The project also analyzes the time complexity of heap operations and demonstrates their application in task scheduling.

---

## Features

- Heapsort implementation using a binary max-heap
- Merge Sort implementation
- Quick Sort implementation
- Performance comparison of sorting algorithms
- Execution time visualization using Matplotlib
- Priority Queue implementation using Python's heapq module
- Task scheduling simulation
- Time complexity analysis of all heap operations

---

## Project Structure

```
Assignment4.py
README.md
Report.pdf (or Report.docx)
```

---

## Requirements

Install the required Python library before running the program.

```bash
pip install matplotlib
```

Python Version:

- Python 3.8 or later

---

## How to Run

Run the program using:

```bash
python Assignment4.py
```

or in Google Colab/Jupyter Notebook, simply execute all cells.

---

## Program Output

The program performs the following tasks:

1. Implements Heapsort.
2. Compares Heapsort with Merge Sort and Quick Sort.
3. Displays execution time for different input sizes.
4. Generates a comparison graph.
5. Implements a Priority Queue.
6. Demonstrates task insertion, extraction, priority updates, and scheduling.
7. Prints the theoretical time complexity of all operations.

---

## Time Complexity

### Heapsort

| Case | Complexity |
|------|------------|
| Best | O(n log n) |
| Average | O(n log n) |
| Worst | O(n log n) |
| Space | O(1) Auxiliary |

### Priority Queue

| Operation | Complexity |
|-----------|------------|
| Insert | O(log n) |
| Extract Maximum | O(log n) |
| Increase Key | O(n) |
| Is Empty | O(1) |

---

## Key Insights

- Heapsort provides consistent O(n log n) performance for all input cases.
- Merge Sort and Quick Sort may execute faster on random datasets but have different space and worst-case characteristics.
- Binary heaps provide efficient priority queue operations.
- Priority queues are widely used in operating systems, scheduling algorithms, graph algorithms, and task management.

---

## Applications

- CPU Process Scheduling
- Task Scheduling Systems
- Operating Systems
- Event Simulation
- Network Packet Scheduling
- Dijkstra's Shortest Path Algorithm
- A* Search Algorithm
- Job Scheduling

---

## Conclusion

This project demonstrates the efficiency and practicality of heap data structures. The implementation confirms the theoretical performance of Heapsort and binary heap-based priority queues. Experimental results align with the expected time complexities, showing that heaps are highly effective for sorting and priority-based scheduling applications.

---

## Author

**Bilal Mohammed**

**Course:** Advanced Big Data and Data Mining
