# gameOfLife
Conway's game of life simulation

This project demonstrates Conway's game of life by simulating 15 generations of cells living and dying in a 20x20 grid.
Every cell interacts with each other through each generation which the program decides which cell lives and dies.

The rules are as follows:
1. Any live cell with fewer than two live neighbors dies, as if caused by under-population.
2. Any live cell with two or three live neighbors lives on to the next generation.
3. Any live cell with more than three live neighbors dies, as if by over-population.
4. Any dead cell with exactly three live neighbors becomes a live cell, as if by reproduction.

Each time the code is exectuted in java, a random collection of living cells is created and 15 generations transpire to show how the community changes over time.

To run this project:
1. Copy or clone the contents in main into a java IDE such as Eclipse
2. Run the code!

Code can be changed as the user wishes to have more or less generations or to change the rules on how each cell lives or dies.
