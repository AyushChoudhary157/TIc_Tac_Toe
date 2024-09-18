# TIc_Tac_Toe

This code is for a **Tic-Tac-Toe** game using JavaScript, where players X and O take turns marking boxes in a 3x3 grid. It features a simple interface with buttons to reset the game or start a new game, along with functionality to check for a winner after each move.

### Key Components:
- **HTML Elements:**
  - `boxes`: Represents the 9 cells in the Tic-Tac-Toe grid.
  - `resetBtn` & `newGameBtn`: Buttons to reset the game.
  - `msgContainer` & `msg`: A container and message box to display the winner.

### Game Logic:
1. **Turn Tracking:** A boolean `turnO` is used to toggle turns between player O and player X.
2. **Winning Patterns:** The `winPatterns` array contains all the possible winning combinations (rows, columns, diagonals).
3. **Reset and Enable/Disable Boxes:** 
   - `resetGame`: Resets the game state.
   - `enableBoxes` and `disableBoxes`: Enables or disables the boxes based on the game state.
4. **Click Event Handling:** 
   - When a box is clicked, it is marked with "O" or "X" based on the current player's turn.
   - After each click, the `checkWinner` function is called to see if any player has won by matching one of the winning patterns.
5. **Displaying the Winner:** 
   - If a winning pattern is found, the winner is displayed using `showWinner`, and the boxes are disabled to prevent further moves.

Players can reset or start a new game using the provided buttons, which clears the board and restarts the turn sequence.

![image](https://github.com/user-attachments/assets/e64a656b-c87c-4dc8-bd4c-2f7b5893b58d)
![image](https://github.com/user-attachments/assets/9e05a70c-62bc-4f8e-bcd3-5ae6b94040cb)
![image](https://github.com/user-attachments/assets/7d2fe877-ec59-411a-acc2-0af6cf86eb61)


