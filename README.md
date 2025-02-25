# Robot Vacuum Cleaners Finding Shortest Path using A-Star Algorithm
------------------------  

## What is this project?  

This project focuses on optimizing the pathfinding of robot vacuum cleaners using the A-Star algorithm. To efficiently navigate and clean dirty spots, the project combines A-Star with the DBSCAN clustering algorithm and Euclidean distance to determine the shortest path. Additionally, a GUI is implemented using Python’s Tkinter library, allowing users to interactively select dirty cells and visualize the robot’s path in real time.

------------------------  

## Files:  
   - `AStar_RobotVacuumCleaners.ipynb`: Source code.
  
---

## Dependencies

Ensure the following libraries are installed before running the program:

### Data Processing Libraries:
```bash
pip install pandas numpy
import random
import math
import heapq
import csv
import io
import numpy as np
```

### DBSCAN Algorithm Libraries:
```bash
pip install scikit-learn
```
- **Scikit-learn**: Make sure to download the required with the following:
  ```python
  import nltk
  from sklearn.cluster import DBSCAN
  from sklearn.metrics.pairwise import pairwise_distances
  ```
  
### Elbow Point Detection Libraries:
```bash
pip install kneed
from kneed import KneeLocator
```

### GUI Libraries - Tkinter:
```bash
import tkinter as tk
from tkinter import messagebox
```

------------------------  

### Our Contributors:    
- Nguyễn Vân Phi Yến
- Trần Vọng Triển
- Nguyễn Thành Vinh
- Trầm Thái Tú

### Course Information:
- Course: Data Analytics
- Professor: PhD. Nguyễn An Tế
