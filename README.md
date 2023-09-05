# Conway's Game of Life

This is an implementation of Conway's Game of Life in C. The game is a cellular automaton, which evolves over time according to a simple set of rules. The Game of Life is a zero-player game, meaning that its evolution is determined by its initial state, requiring no further input.

## Overview

The Game of Life is a zero-player game where cells on a grid evolve according to a set of rules. The implementation here allows configuring the grid size, seeding initial state, running simulations and displaying the results.

The key files are:

- main.c - Main program 
- conway.c - Implements Conway logic
- conway.h - Header file for Conway ADT
- run.bat - Compiles and runs the program

## Implementation

The `conway` ADT encapsulates the state and logic for the simulation. The key methods are:

- `conway_init` - Initialize grid 
- `conway_seed` - Set initial state  
- `conway_simulate` - Run one iteration of the simulation
- `conway_print` - Print current grid state

The main program initializes a Conway grid, seeds it, runs simulations and prints output.

## Running 

To compile and run:

```
run.bat
```

This will:

1. Compile main.c and conway.c into a.exe
2. Run the executable

The output will show the grid evolving over generations.
