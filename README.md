﻿# Sudoku_Game
# 🧩 Sudoku Solver in C++

A simple yet powerful **Sudoku Puzzle Solver** built using **C++ and backtracking algorithm**. The program solves a predefined 9x9 Sudoku grid using recursion and prints the solved puzzle in a readable format.

## 🔍 How It Works

This solver follows the **backtracking algorithm** approach. It recursively tries to place numbers from 1 to 9 in empty cells while checking row, column, and 3×3 sub-grid constraints.

## 💡 Features

- Solves any valid 9x9 Sudoku puzzle
- Uses standard **backtracking technique**
- Clean console output with grid formatting
- C++ implementation using basic arrays and functions
- Beginner-friendly and well-structured code

## 📌 Technologies Used

- C++
- Backtracking Algorithm
- 2D Arrays
- Functions and Recursion

## 📥 Sample Input Grid (inside code)

```cpp
int grid[9][9] = {
  {3, 0, 6, 5, 0, 8, 4, 0, 0},
  {5, 2, 0, 0, 0, 0, 0, 0, 0},
  {0, 8, 7, 0, 0, 0, 0, 3, 1},
  {0, 0, 3, 0, 1, 0, 0, 8, 0},
  {9, 0, 0, 8, 6, 3, 0, 0, 5},
  {0, 5, 0, 0, 9, 0, 6, 0, 0},
  {1, 3, 0, 0, 0, 0, 2, 5, 0},
  {0, 0, 0, 0, 0, 0, 0, 7, 4},
  {0, 0, 5, 2, 0, 6, 3, 0, 0}
};

Compile:
g++ Sudoku_Game.cpp -o Sudoku_Game

Run:
./Sudoku_Game       // Linux/Mac
Sudoku_Game.exe     // Windows

Sample Output

3 1 6  | 5 7 8  | 4 9 2 
5 2 9  | 1 3 4  | 7 6 8 
4 8 7  | 6 2 9  | 5 3 1 
-------------------------
2 6 3  | 4 1 5  | 9 8 7 
9 7 4  | 8 6 3  | 1 2 5 
8 5 1  | 7 9 2  | 6 4 3 
-------------------------
1 3 8  | 9 4 7  | 2 5 6 
6 9 2  | 3 5 1  | 8 7 4 
7 4 5  | 2 8 6  | 3 1 9 
