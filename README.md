PathQuest | Dijkstra Pathfinding Visualizer

PathQuest is a web-based visualizer for Dijkstra’s Algorithm, one of the most famous algorithms in Graph Theory. This tool allows users to see how the algorithm "explores" a grid to find the shortest path between a start and end point while navigating around custom-built obstacles.

🚀 Features
Interactive Grid: Click and drag to draw walls/obstacles in real-time.

Algorithm Visualization: Watch the "wavefront" expansion as Dijkstra's explores unvisited nodes.

Shortest Path Highlight: Once the target is found, the optimal path is backtracked and displayed in yellow.

Responsive Control: Clear the grid or restart the visualization with a single click.

🛠️ Tech Stack
Language: JavaScript (ES6+)

Styling: CSS3 (Animations & Grid Layout)

Structure: HTML5

🧠 The DSA Behind the Project: Dijkstra's Algorithm
Dijkstra's algorithm is a Greedy Algorithm used to find the shortest path from a starting node to all other nodes in a weighted graph. In this project, each grid cell is treated as a node with a weight of 1.

How it works:

Initialization: All nodes are assigned a distance of infinity, except the Start node (distance = 0).

Selection: The algorithm picks the unvisited node with the smallest distance.

Relaxation: It updates the distance of all neighboring nodes. If a shorter path is found, the neighbor’s distance is updated and the current node is marked as its "parent."

Termination: The process repeats until the End node is reached or all reachable nodes are visited.

Complexity Analysis

Time Complexity: O(V 
2
 ) in this implementation (using an array-based search for the minimum distance node).

Space Complexity: O(V) to store the grid and distances, where V is the number of vertices (cells).

💻 How to Run Locally
I am currently a first-year Bachelor of Computer Applications (BCA) student at YCMOU, and I built this to run efficiently in any modern browser without heavy dependencies.

Clone the repository:

git clone https://github.com/neetamaan20-cloud/PathQuest-DSA.git

Navigate to the folder:

cd PathQuest-DSA

Start a local server (using Python 3 as I did during development):

python3 -m http.server 8000

📁 Project Structure
index.html: UI structure and controls.

style.css: Grid styling and pathfinding animations.

script.js: Implementation of Dijkstra's logic and DOM manipulation.
