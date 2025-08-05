# Disk Scheduling Algorithm Simulator

A GUI-based Python application to visualize and compare the performance of various disk scheduling algorithms using total head movement and animation. This tool is useful for understanding how each algorithm works and analyzing their efficiency in different scenarios.

---

## Features

- Visual simulation of 6 Disk Scheduling Algorithms:
  - FCFS (First-Come, First-Served)
  - SSTF (Shortest Seek Time First)
  - SCAN
  - LOOK
  - C-SCAN (Circular SCAN)
  - C-LOOK (Circular LOOK)
- Input custom request sequences and initial head positions
- Interactive GUI to:
  - Visualize disk head movement
  - View total head movement and time
  - Plot graph comparing algorithms
  - Save graph image

---

## Tech Stack

- **Platform:** PyCharm
- **Language:** Python 3+
- **Libraries Used:**
  - `Tkinter` – GUI
  - `Pandas` – Data handling
  - `Matplotlib` – Graph plotting
  - `copy` – Deep copy operations

---

## Installation

### 1. Clone this repository

```bash
git clone https://github.com/Darshil0209/Disk-Scheduling-Algorithm-Simulator.git
cd Disk-Scheduling-Algorithm-Simulator
```

### 2. Install Dependencies
```bash
pip install pandas matplotlib
```

### 3. How to Run
Open the project folder in PyCharm.
Locate and open the main.py file.
Run the file using Ctrl + Shift + F10 or the green play button.

### 4. Usage Instructions
On running the app, you'll be prompted to choose a disk scheduling algorithm.
Enter:
    The request sequence (track numbers)
    The initial head position

Click VISUALISE to see an animated simulation.
Click GRAPH to:
    Compare total head movements of all algorithms
    Save the graph as an image
