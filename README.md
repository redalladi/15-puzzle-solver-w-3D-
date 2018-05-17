# Rubik-s-15-puzzle
Solver for: 15-puzzle, 3D 8-puzzle and 3D 15-Puzzle 
using noninformed and informed (heuristic) search algorithms: BFS, DFS, A*, Hill-climbing

User Manual

The program takes the initial node and the goal nodes as input from one of three files. The files should be named “15.txt” for the 15-puzzle, “26.txt” for the 26-puzzle and “63.txt” for the 63-puzzle. 

Each file contains the characters in the squares (or cubies) organized in squares (see input files). The characters are numbers and upper-case letters for the two first, to which we add lower case letters for the third. 

For the 15-puzzle, the 1st square contains the initial node and the next two squares the 1st and the second goal nodes. For 3D puzzles, each node is printed in three squares printed one after the other vertically, skipping a line between each. The nodes are printed one after the other vertically but skipping two lines between each node.  

As you open the program, you are asked to choose which n-Puzzle you want. Then, you choose between the goal node 1 and the goal node 2 that are in the file input. Finally, you choose between DFS, BFS, A* and GBFS. Then, the program starts the search. 
As it goes through it, it punctually asks you if you want to continue the search. If you choose to stop, you can choose to print the tree.
If the goal is reached, you can print the path (from goal state to initial state vertically), and then you can print the tree if you choose to.

How to read the tree? 
The tree is printed horizontally. The first node is on the left and the children on the right. The first child node is above its root and the next nodes are below it. If a state has no children, it is followed by a point. This is important to be able to read the tree. This is how you recognize which node is from which parent.

