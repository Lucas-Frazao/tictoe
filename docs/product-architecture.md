main.py
   │
   ├── Creates the initial 2D board
   ├── Imports functions from board.py and logic.py
   ├── Runs the main game loop:
   │     ├── print_board(board)          ← from board.py
   │     ├── Get player move (row, col)
   │     ├── make_move(board, row, col, player) ← from board.py
   │     ├── check_win(board, player)    ← from logic.py
   │     ├── check_draw(board)           ← from logic.py
   │     └── Switch player
   │
board.py
   ├── create_board() → returns a fresh 2D board
   ├── print_board(board)
   └── make_move(board, row, col, player) → updates board or returns False if invalid
          (This function modifies the board in place for simplicity)

logic.py
   ├── check_win(board, player) → returns True/False
   └── check_draw(board) → returns True/False