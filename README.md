# Simulating-Conway-s-Game-of-Life

Mathematician John Conway devised the “Game of Life”, in which simple rules lead to surprisingly complex behaviour.
The Game of Life is “played” on a two-dimensional orthogonal grid of square cells (imagine a piece of
graph paper), each of which is in one of two possible states, live or dead. Every cell interacts with its eight neighbours,
which are the cells that are horizontally, vertically, or diagonally adjacent. All cells beyond the grid may be
assumed dead.

At discrete points in time, called “generations”, births and deaths occur simultaneously, according to the following
rules:
1. Any live cell with two or three live neighbours stays live.
2. Any dead cell with three live neighbours becomes a live cell.
3. All other live cells become dead in the next generation. Similarly, all other dead cells stay dead.


These rules continue to be applied repeatedly to create further generations. The initial pattern of live and dead
cells entirely determines the future evolution of the system, as the configuration of live and dead cells in each
generation is totally determined by the configuration in the preceding one.
Using Numpy and Matplotlib, simulate Conway’s game on a 500 by 500 grid. Represent the grid with a Numpy
array in which 1 represents a live cell and 0 represents a dead cell. Initialize the grid with an initially random
assortment of ones and zeros, and then evolve the grid for 100 generations, using Conway’s three rules. Use
Matplotlib to create a 100-step movie showing the evolution of the grid as it goes through each generation. 

# Expected Output
![game_of_life](https://github.com/user-attachments/assets/c50ff6ab-c08b-46a2-a6ce-d5e81ab9b966)
