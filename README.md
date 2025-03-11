# Tic-Tac-Toe AI with Minimax Algorithm

## Overview
This project implements a Tic-Tac-Toe AI using the **Minimax Algorithm**. The AI plays optimally, ensuring that 'X' (AI) always makes the best possible move.

## Features
- **Winner Detection**: Checks for a winner in rows, columns, and diagonals.
- **Board Full Check**: Determines if the board is full, resulting in a tie.
- **Minimax Algorithm**: Implements the minimax algorithm to evaluate the best possible move for 'X'.
- **Optimal Move Selection**: AI chooses the best move based on minimax evaluation.

## How It Works
1. **`check_winner(board)`**: Determines if there is a winner.
2. **`is_full(board)`**: Checks if the board is full.
3. **`minimax(board, depth, is_maximizing)`**: Recursively evaluates the board to find the optimal move.
4. **`best_move(board)`**: Uses minimax to determine the best move for 'X'.

## Example Usage
```python
board = [
    ['X', 'O', 'X'],  # Example Tic-Tac-Toe board configuration
    ['O', 'X', ' '],
    [' ', ' ', 'O']
]

print("Best move for 'X':", best_move(board))
```

## Running the Program
1. Save the script as `tic_tac_toe.py`.
2. Run the script using Python:
   ```bash
   python tic_tac_toe.py
   ```
3. The output will display the best move for 'X'.

## Future Enhancements
- Implementing a GUI for better user interaction.
- Adding an interactive mode for human vs AI gameplay.

