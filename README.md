# conway-gol

This is an implementation of Conway's Game of Life in C. The game is a cellular automaton, which evolves over time according to a simple set of rules. The Game of Life is a zero-player game, meaning that its evolution is determined by its initial state, requiring no further input.

## Files

conway.h: Header file containing function prototypes and the conway struct.
conway.c: Source file implementing the functions for the Game of Life.

## Usage


Include the conway.h header file in your project.
Compile the conway.c source file along with your project.
Create a conway struct and initialize it using conway_init.
Seed the initial state using conway_seed or conway_seedTable.
Simulate the Game of Life using conway_simulate or conway_simulateN.
Print the current state of the Game of Life using conway_print.
When you are done, clean up the resources using conway_destroy.