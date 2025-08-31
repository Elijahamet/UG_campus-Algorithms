
# UG-Campus Algorithm Project – TechTutors  

This project is a collection of classical algorithms implemented in **Java** as part of the TechTutors' study of algorithm design and analysis. It demonstrates how fundamental algorithms can be applied to solve real-world problems such as route optimization, scheduling, sorting, and transportation logistics.  

## 📌 Features & Implemented Algorithms  

### 1. Graph Algorithms
- **Floyd–Warshall Algorithm (`FloydWarshall.java`)**  
  - All-pairs shortest path algorithm.  
  - Time Complexity: **O(V³)**  
  - Space Complexity: **O(V²)**  

- **A* Search (`AStarSearch.java`)**  
  - Pathfinding using heuristics (like in Google Maps).  
  - Time Complexity: **O(E log V)**  
  - Space Complexity: **O(V)**  

- **Critical Path Method (`CriticalPath.java`)**  
  - Scheduling and project management algorithm.  
  - Time Complexity: **O(V + E)**  

- **Graph Representation (`Graph.java`, `Nodes.java`, `Edge.java`)**  
  - Supports graph traversal and manipulation.  

---

### 2. Sorting Algorithms (`SortingAlgorithms.java`)
- Bubble Sort: `O(N²)`  
- Insertion Sort: `O(N²)`  
- Selection Sort: `O(N²)`  
- Merge Sort: `O(N log N)`  
- Quick Sort: Avg `O(N log N)`, Worst `O(N²)`  

---

### 3. Optimization & Operations Research
- **Northwest Corner Method (`NorthwestCorner.java`)**  
  - Initial feasible solution for transportation problems.  
  - Time Complexity: **O(m + n)**  

- **Vogel’s Approximation (`VogelAlgo.java`)**  
  - Improved initial feasible solution for transportation.  
  - Time Complexity: **O(m × n × min(m, n))**  

- **Route Optimizer (`RouteOptimizer.java`)**  
  - Applies shortest-path algorithms for navigation-like problems.  

---

### 4. Simulation
- **Traffic Simulator (`TrafficSimulator.java`)**  
  - Models traffic flow based on graph data.  
  - Time Complexity: `O(T × (V + E))`  

- **Weather Integration (`WeatherIntegration.java`)**  
  - Demonstrates how weather data can influence routing decisions.  

---

### 5. Other Utilities
- **Accessibility Features (`AccessibilityFeatures.java`)** – Custom utilities to handle user interactions.  
- **GUI Components (`App.java`, `AppFrame.java`)** – Basic interface for running and testing the algorithms.  

---

## ⚙️ How to Run  

1. Clone or download this repository.  
2. Open it in an IDE (e.g., **IntelliJ IDEA**, **Eclipse**, or **VS Code** with Java extension).  
3. Compile the project:  
   ```bash
   javac src/*.java
Run the main application:

bash
Copy
Edit
java src/App
📊 Complexity Summary
Algorithm	Time Complexity	Space Complexity
Floyd–Warshall	O(V³)	O(V²)
A* Search	O(E log V)	O(V)
Critical Path	O(V + E)	O(V + E)
Bubble Sort	O(N²)	O(1)
Merge Sort	O(N log N)	O(N)
Quick Sort (avg)	O(N log N)	O(log N)
Northwest Corner	O(m + n)	O(1)
Vogel’s Approximation	O(m × n × min(m, n))	O(m × n)

👥 Authors
This project was developed by TechTutors:

Opuni

Elijah

Kelvin

Nana Yaw

Tony

Justice

Frank

📖 License
This project is for educational purposes only. You may use and modify the code for learning and research.

yaml
Copy
Edit

---

Would you like me to also make a **shorter student-friendly README** (with less technical jargon) that you can hand in directly to your lecturer, or keep this **detailed professional version**?







Ask ChatGPT

