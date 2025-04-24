# 🔍📊 Algorithm Visualizer – C++ with OpenGL

A powerful desktop-based **algorithm visualizer** built using **C++**, **OpenGL** and **GLUT** to help users understand and study fundamental algorithms like sorting and searching through **real-time graphical animation**.

---

## 🎯 Objective

To create a visual learning tool that simulates and demonstrates classic algorithmic concepts like searching and sorting to improve clarity, intuition and conceptual understanding.

---

## 💡 Features

- ✨ Real-time visualization of:
  - **Sorting algorithms** (Bubble Sort, Selection Sort, Insertion Sort, etc.)
  - **Searching algorithms** (Linear Search, Binary Searc)
  - Potential extension to **graph and pathfinding algorithms**
- 📉 Step-by-step animation to enhance learning
- 🎛️ User-friendly interaction via keyboard/mouse
- 🔄 Replay and control algorithm flow (pause, play, reset)

---

## 🧰 Technologies Used

- **C++**
- **OpenGL** – Open Graphics Library for rendering 2D/3D graphics
- **GLUT** – OpenGL Utility Toolkit for handling windows and input

---

## 🛠️ Installation & Setup

1. **Install OpenGL and GLUT**

   Make sure OpenGL and GLUT libraries are installed on your system.

   - On Linux:
     ```bash
     sudo apt-get install freeglut3-dev
     ```

   - On Windows:
     Download and configure GLUT with your C++ IDE (e.g., Visual Studio, Code::Blocks).

2. **Clone the repository**

   ```bash
   git clone https://github.com/jahnavinischal/algorithm-visualizer-cpp.git
   cd algorithm-visualizer-cpp

3. **Compile and run**
- On Linux:
  ```bash
  g++ main.cpp -lGL -lGLU -lglut -o visualizer
  ./visualizer
- On windows: Use your IDE to add GLUT libraries and build the project.
---
**Screenshots: buble sort in action**
![image](https://github.com/user-attachments/assets/a9693f7c-1aa7-4943-bcd6-d55c5cdb080c)
![image](https://github.com/user-attachments/assets/f43c6c40-7508-4273-9939-ee96d1d5dee7)
![image](https://github.com/user-attachments/assets/40f5d1c4-0929-422b-a4ee-4c0080becf81)
![image](https://github.com/user-attachments/assets/b798678b-215b-4b40-ae52-7949bc88d0a8)
---
## 📚 Future Enhancements
- Add other algorithms like pathfinding algorithms like Dijkstra’s and A*

- Include time/step counters for educational feedback
