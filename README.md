# Tic-Tac-Toe in C

A simple command-line Tic-Tac-Toe game written in C with two difficulty levels: **Human (Standard)** and **God Mode (Impossible to Win)**.

## Features
- Play against the computer with two difficulty levels.
- Randomized first turn.
- Smart AI that blocks winning moves and plays strategically.
- Score tracking for Player, Computer, and Draws.
- Simple and clean command-line interface.

## How to Compile and Run

### Requirements
- GCC Compiler
- Dev-C++ (optional)

### Compilation with GCC
```sh
gcc tic_tac_toe.c -o tic_tac_toe
```

### Running the Game
```sh
./tic_tac_toe
```

### Compilation and Execution in Dev-C++
1. Open Dev-C++.
2. Create a new project and select **C Project**.
3. Copy and paste the code into `main.c`.
4. Click **Compile & Run (F9)**.

## Game Instructions
1. Select difficulty level (1 for Standard, 2 for God Mode).
2. The game randomly decides who plays first.
3. Enter row and column (1-3) to place your move.
4. The game ends when a player wins or there's a draw.
5. Option to restart the game after each round.

## Controls
- Enter **1-3** for row and column positions.
- Press **1** to play again or **0** to exit after a match.

## Example Gameplay
```
Select difficulty level:
1. Human (Standard)
2. God (Impossible to win)
Enter your choice: 1

Tic-Tac-Toe
  X | O | X
 ---+---+---
  O | O | X
 ---+---+---
  X |   |  

Enter row and column (1-3) for X: 3 3

Congratulation You have won.!!!
```

## License
This project is open-source and free to use.

## Contributions
Feel free to contribute by submitting a pull request or reporting issues.

Happy Coding! 🎮

