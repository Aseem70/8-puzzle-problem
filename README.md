# 8-puzzle-problem
This project finds the cheapest solution for 8 puzzle using Dijkstra's Algorithm, DFS and BFS. Assuming the input is a 3 newRow 3 matrix as per the samples provided.

To compile (non M1 macbook):

g++ -std=c++17 -Wall 8Puzzle.cpp

To compile on a M1 macbook:

g++ -std=c++17 -Wall 8Puzzle.cpp -arch x86_64

Steps to run the program:

1. If not already initialized, initialize sample files for the input

2. In the code, make sure to mention the correct filename

3. Once that is ensured, you can use this command: ./a.out
to run the code and see the different cost results based on the different algorithms used.
