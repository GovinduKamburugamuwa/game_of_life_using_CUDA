
# Game of Life in CUDA

This project implements Conway's Game of Life using CUDA for parallel computation and SDL for graphical rendering. The Game of Life is a cellular automaton devised by mathematician John Conway, where cells on a grid evolve based on simple rules, creating complex patterns.

## Features

- **Parallel Processing**: Utilizes CUDA to leverage the power of the GPU, allowing for efficient calculations of cell states.
- **Real-Time Visualization**: Renders the game grid using SDL, providing an interactive view of the evolving patterns.
- **Wrap-Around Grid**: Implements a toroidal (wrap-around) grid, ensuring cells at the edges of the grid interact seamlessly.

## Requirements

- CUDA Toolkit
- SDL2
- A compatible NVIDIA GPU

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/GameOfLife.git
   cd GameOfLife
   ```

2. Compile the code using a CUDA-capable compiler.

3. Run the executable to start the game.

## How to Play

- The simulation automatically updates the grid based on the rules of the Game of Life.
- You can close the window to exit the game.

## Contributing

Feel free to submit issues or pull requests if you have suggestions for improvements or additional features!


