
# Graph Search Visualizer

This program allows you to visualize various graph search algorithms by interactively creating and manipulating a graph. You can add and remove nodes, add weighted edges, and run different algorithms on the graph.

## Search Algorithms

**Uninformed search algorithms**
- [x] BFS - Breadth-first search
- [x] DFS - Depth-first search
- [x] UCS - form Cost Search  - 
- [x] ITS - Iterative-deepening Search 
- [x] DLS - Depth-Limited Search 

**Informed search algorithms**
- [x] Greedy
- [x] A*

## Installation

1. Clone the repository to your local machine.
2. Make sure you have Python and Pygame installed.
3. Run the code using a Python IDE or from the command line.

## Usage

1. Upon launching the program, a window will appear where you can draw your graph.
2. To add a node, left-click anywhere on the canvas. To remove a node, right-click on an existing node.
3. You can add weighted edges by left-clicking on one node and dragging the mouse to another node. Release the mouse button to create the edge.
4. The panel on the right side of the window provides various buttons and options:
   - **Directed**: Toggle the directed/undirected property of the graph.
   - **Clear**: Clear the entire graph.
   - **BFS**: Run the Breadth-First Search algorithm on the graph.
   - **UCS**: Run the Uniform Cost Search algorithm on the graph.
   - **DFS**: Run the Depth-First Search algorithm on the graph.
   - **ITD**: Run the Iterative Deepening algorithm on the graph. You can input the maximum depth in the console.
   - **DLS**: Run the Depth-Limited Search algorithm on the graph. You can input the maximum depth in the console.
   - **GRY**: Run the Greedy Best-First Search algorithm on the graph.
   - **AST**: Run the A* Search algorithm on the graph.
   - **Speed**: Adjust the speed of the algorithm visualization.
   - **Show H**: Toggle the display of node heuristics.
   - **Show C**: Toggle the display of edge costs.
5. Follow the on-screen instructions and interact with the buttons and graph to visualize the selected algorithms.

## Example

1. Left-click to add nodes, right-click to remove nodes.
2. Left-click and drag to add weighted edges.
3. Use the buttons on the panel to select and run different algorithms.
4. Adjust the speed and toggle the display options as needed.

![alt text](https://github.com/KAYounes/AIProject/blob/master/Example_Image.png?raw=true)

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvement, please feel free to submit a pull request.
<!-- 
## License

This project is licensed under the MIT License. -->
<!-- # How to run?

You have to use python environment, which support pygame. If not found, simply use the following command in your terminal. 
```
pip install pygame
``` -->
<!-- 
# Demo 
STEPS:
1. Build a graph
2. Select the start state and final state(s)
3. Select the search algorithm (Uninfored and Informed)
4. Press start
5. Repeat -->


Under supervision of **Dr. Ammar Mohammed**, *Professor of Artificial Intelligence, FGSSR, Cairo University*
