# TIc_Tac_Toe

Tic-Tac-Toe game using JavaScript, where players X and O take turns marking boxes in a 3x3 grid. It features a simple interface with buttons to reset the game or start a new game, along with functionality to check for a winner after each move.

Key Components:
HTML Elements:
boxes: Represents the 9 cells in the Tic-Tac-Toe grid.
resetBtn & newGameBtn: Buttons to reset the game.
msgContainer & msg: A container and message box to display the winner.
Game Logic:
Turn Tracking: A boolean turnO is used to toggle turns between player O and player X.
Winning Patterns: The winPatterns array contains all the possible winning combinations (rows, columns, diagonals).
Reset and Enable/Disable Boxes:
resetGame: Resets the game state.
enableBoxes and disableBoxes: Enables or disables the boxes based on the game state.
Click Event Handling:
When a box is clicked, it is marked with "O" or "X" based on the current player's turn.
After each click, the checkWinner function is called to see if any player has won by matching one of the winning patterns.
Displaying the Winner:
If a winning pattern is found, the winner is displayed using showWinner, and the boxes are disabled to prevent further moves.
Players can reset or start a new game using the provided buttons, which clears the board and restarts the turn sequence.
