**Path Finder
**


**Overview**

This is a Python-based terminal application that visualizes a pathfinding algorithm on a maze. The maze is represented as a grid, where the goal is to navigate from the start point (O) to the end point (X) while avoiding obstacles (#).



**Features**

Visual representation of the maze and the pathfinding process.

Utilizes Breadth-First Search (BFS) algorithm to find the shortest path.

Dynamic updates of the pathfinding process within the terminal.



**Requirements**

Python 3.x

curses module (pre-installed with Python on Unix-based systems)



**How to Run**

1. Clone the repository to your local machine: git clone https://github.com/your-username/path-finder.git

2. Navigate to the project directory:Run the Python script:

3. Run the Python script:python path_finder.py



**Controls**

The program runs automatically and visualizes the pathfinding process. No user input is required during execution.



**Maze Representation**

#: Wall/obstacle

 : Open path

O: Start point

X: End point

Red X: Path from start to end (highlighted during the visualization)



**How It Works**

The find_path function uses BFS to explore the maze starting from O.

Neighbors are checked in four directions (up, down, left, right), avoiding walls (#) and already visited nodes.

The path is visualized dynamically on the terminal using the curses library.



**Example Maze**


![image](https://github.com/user-attachments/assets/e49f830d-1668-452f-a6c8-5eb6a1485f42)



**Contributions**

Feel free to contribute by submitting issues or pull requests to improve the project.

License

This project is licensed under the MIT License. See the LICENSE file for details.
