# Tic-Tac-Toe Web Application

## Overview

This project is a web-based Tic-Tac-Toe game built using HTML, CSS, and JavaScript. The game allows two players to play against each other or a single player to play against a simple AI. The objective is to get three markers in a row (horizontally, vertically, or diagonally) to win the game.

## Features

- Two-player mode
- Single-player mode with AI opponent
- Interactive and responsive game board
- Visual feedback for winning combinations
- Reset button to start a new game

## Technologies Used

- HTML for structuring the web page
- CSS for styling the game interface
- JavaScript for game logic and interactivity

## Getting Started

### Prerequisites

To run this project, you only need a web browser. No additional software or dependencies are required.

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/BeastEren/PRODIGY_WD_03.git
   ```
2. **Navigate to the project directory:**
   ```sh
   cd PRODIGY_WD_03\tic-tac-toe
   ```

### Running the Game

1. Open the `index.html` file in your preferred web browser.
2. The game board will be displayed, and you can start playing immediately.

## Project Structure

```plaintext
tic-tac-toe/
├── index.html
├── css/
│   └── style.css
└── js/
    └── script.js
```

- `index.html`: The main HTML file that sets up the structure of the web page.
- `css/style.css`: The CSS file that contains styles for the game board and interface.
- `js/script.js`: The JavaScript file that contains the game logic and functionality.

## Game Logic

### User Clicks

- Each cell on the game board is clickable.
- When a cell is clicked, the `handleClick` function is triggered, placing the player's marker (X or O) in the cell.

### Tracking Game State

- The game state is tracked using a JavaScript array.
- The array stores the current state of each cell on the board (empty, X, or O).

### Checking for Winning Conditions

- After each move, the game checks for a win or a draw.
- The winning conditions are checked by evaluating all possible combinations of three markers in a row.

### AI Opponent

- The AI opponent uses a basic strategy to select its moves.
- The AI tries to block the player's winning moves and aims to win if possible.

## How to Play

1. Select the game mode (Two-player or Single-player).
2. The first player (X) starts by clicking on an empty cell.
3. Players take turns to place their markers (X or O) on the board.
4. The game checks for a win or draw after each move.
5. The game announces the result and highlights the winning combination, if any.
6. Click the "Reset" button to start a new game.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## Contact

For any questions or feedback, please contact [SOURAV SINGH](mailto: souravsinghami1@gmail.com).

---

Enjoy playing Tic-Tac-Toe!

---