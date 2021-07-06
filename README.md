# N_Queens_Genetic
This repo contains the implementation of the classic N-Queens problem using the Genetic Algorithm with Python.

## 8- Queen

1. 8 X 8 2d board.
2. Queens can be allocated that no queen can be attacked by another queen horizontally, vertically or diagonally

## Task

1. Write a fitness function which checks the fitness of a board by checking the number of non-attacking pair of queens.   Hint: Maximum number of non-attacking pairs of queens can be (8*7)/2. Input: board, Output: a number telling the fitness of the board
2. Write a Crossover function. A crossover function will take two boards, an index number as input and return two new boards.
3. Write a Mutation function.
4. Create a population of randomly generated boards.
5. Randomly select two members of the population.
6. Randomly generate an index number.  
7. Call crossover function using the above two as input.  
8. Call fitness function for the new boards from the output.
9. Call mutation function if necessary.
10. Add new members to a new population set if appropriate.
11. Run 5 to 10 until the new population set is large enough.
12. Select a few members from the old population to add to the new population set.
13. Run 1- 12 until a board with highest fitness value is created.
