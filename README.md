# ConwaysGameOfLife-Python
Conways’s Game Of Life is a Cellular Automation Method created by John Conway. 
This game was created with Biology in mind but has been applied in various fields such as Graphics, terrain generation,etc..

The “game” is a zero-player game, meaning that its evolution is determined by its initial state, requiring no further input. 
One interacts with the Game of Life by creating an initial configuration and observing how it evolves, or, for advanced “players”, by creating patterns with particular properties.

#How the game works 

Because the Game of Life is built on a grid of nine squares, every cell has eight neighboring cells,as shown in the given figure. A given cell (i, j) in the simulation is accessed on a grid [i][j], where i and j are the row and column indices, respectively. The value of a given cell at a given instant of time depends on the state of its neighbors at the previous time step. Conway’s Game of Life has four rules. 

#RULES 
1. If a cell is ON and has fewer than two neighbors that are ON, it turns OFF
2. If a cell is ON and has either two or three neighbors that are ON, it remains ON.
3. If a cell is ON and has more than three neighbors that are ON, it turns OFF.
4. If a cell is OFF and has exactly three neighbors that are ON, it turns ON.

#Layout
[(i-1, j-1)]  [(i-1, j)]  [(i-1, j+1)]
 [(i, j-1)]    [(i, j)]    [(i, j+1)]
[(i+1, j-1)]  [(i+1, j)]  [(i+1, j+1)] 

#Approach
1. Initialize the cells in the grid.
2. At each time step in the simulation, for each 
   cell (i, j) in the grid, do the following:
   a. Update the value of cell (i, j) based on 
      its neighbors, taking into account the 
      boundary conditions.
   b. Update the display of grid values.
   
#Libraries Needed
1. numpy (Linear Algebra)
2. matplot
3. argparse
4. pygame

