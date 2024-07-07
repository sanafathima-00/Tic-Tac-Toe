# Tic Tac Toe Game

This is a classic Tic Tac Toe (also known as "X and O") game implemented in HTML, CSS, and JavaScript. The game allows two players to take turns marking the board with their respective symbols (X or O) and determines the winner or declares a draw based on the rules of the game.

## How to Play

1. Open `Tic.html` in your web browser.
2. The game board consists of a 3x3 grid.
3. Players take turns clicking on empty cells to place their symbol (X or O).
4. The first player to get three of their symbols in a row (horizontally, vertically, or diagonally) wins.
5. If all cells are filled and no player has won, the game is declared a draw.

## Files

- `Tic.html`: The main HTML file containing the game interface.
- `Tac.css`: CSS file for styling the game elements.
- `Toe.js`: JavaScript file with game logic.

## How It Works

- The game uses event listeners to capture user clicks on the grid cells.
- The current player's symbol (X or O) is alternated after each move.
- The game checks for winning conditions (three in a row) or a draw.
