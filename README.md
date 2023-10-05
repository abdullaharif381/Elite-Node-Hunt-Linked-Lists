# Maze Solver

This C++ program is a maze solver that reads maze data from a file and finds the "Elite Node" following a specific set of rules.

## Overview

The program consists of two main classes: `Node` and `Maze`. It also includes a `main` function to run the maze-solving process.

### Node Class

The `Node` class represents individual cells in the maze. Each node has a data value and pointers to neighboring nodes in four directions: up, down, left, and right.

### Maze Class

The `Maze` class handles the creation of the maze, reading data from a file, and solving the maze. Here are some key methods and functionalities of the `Maze` class:

- **Read**: Reads maze data from a specified file, creating the maze structure with linked nodes.

- **Print**: Displays the maze on the console with proper formatting.

- **visit**: Solves the maze by following clues based on the data in each cell.

- **EliteNode**: Identifies and displays the "Elite Node" based on specific criteria.

### Main Function

The `main` function initializes the maze-solving process, reads maze data from a file (maze_data.txt), and prints the maze. It then proceeds to solve the maze by following clues and identifies the "Elite Node."

## Usage

To run the program, execute the `run()` function in the `main` function. Make sure to provide maze data in a file named `maze_data.txt` in the same directory as the executable.

## Notes

- The program includes comments for clarity and readability.

- It uses the Windows API function `Sleep` for pausing at certain points during execution.

## Author

This maze-solving program was created by Abdullah Arif as an assignment for Data Structures course at FAST-NUCES, Lahore.

Feel free to reach out for any questions or suggestions!

---

Please let me know if you have any further modifications or if there's anything else you'd like to include, my master.
