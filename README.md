# Tic Tac Toe (C++)

A simple terminal-based Tic Tac Toe game written in C++, focusing on clean control flow, explicit logic, and minimal abstractions.

This project was built to practice core C++ concepts such as arrays, functions, control flow, and deterministic game loops.

---

## Features

- Classic 3×3 Tic Tac Toe
- Player vs Computer
- Randomized computer moves
- Win detection using data-driven patterns
- Tie detection
- Clean, readable terminal UI

---

## How the Game Works

- The board is represented as a 1D array of 9 characters.
- Each turn:
  1. The player selects a position (1–9).
  2. The game checks for a win or a tie.
  3. The computer selects a random available position.
  4. The game checks again for a win or a tie.
- The game ends immediately when a win or tie condition is met.

---

## Board Layout

  1 | 2 | 3
-------------
  4 | 5 | 6
-------------
  7 | 8 | 9


Each number corresponds to an index where the player can place a marker.

---

## Compilation & Execution

### Compile
```bash
g++ main.cpp -o tic_tac_toe

./tic_tac_toe
