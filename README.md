#Infeasible puzzles
An infeasible puzzle deficiency is calculated by looking at the number of inversions in the start state as compared to the goal state. A given puzzle configuration is infeasible if the number of inversions are odd (http://www.geeksforgeeks.org/check-instance-8-puzzle-solvable/).

#Known deficiencies
The given heuristic of number of misplaced tiles works fine for easy board configurations. However, in case of complex configurations, where large number of moves are involved to reach the goal state from the initial state, the heuristic does not perform well and hence the search takes a long time to produce the output. This happens because the given heuristic is inefficient in capturing the progress of the search.

#How to run
Edit and save the file to enter start and goal states in the format mentioned later. Run the file using the command "clisp 8_puzzle.lisp" from the terminal.

#Output
The output shows the sequence of states expanded to reach the goal state from the initial state. Additionally, loop count and open list length are shown in every iteration for debugging purposes.
