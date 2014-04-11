8-puzzle-solver-cpp
===================

The solver for the famous 8-puzzle problem using A* Search and Manhattan distance heiristics. The solver takes in the
input puzzle and return a solved output.

Salient features of the code are :-

1. A* search with iterative deepening implemented using the Manhattan distance heuristics. 
2. Repeat of searched states were avoided by keeping track of the visited states using a boolean vector.
3. A state was represented using two parameters - The present state of the puzzle and number of moves needed to reach 
   that state.
4. A priority queue with priority based on Manhattan Distance heuristics was implemented using the STL containers.
5. The feasibility for the solution of the puzzle was checked using equivalence classes with respect to reachablity. This
   proves to be a critical optimization in the early stage of the code.


Repo contents :

1. A c++ code to solve an 8 puzzle
2. A sample input to check the code against testcases
3. The corresponding output for the given input.
