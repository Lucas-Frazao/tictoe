PRODUCT FEATURE ROADMAP: Simple Terminal Tic Tac Toe
=====================================================
 
GOAL
----
Build the simplest possible working Tic Tac Toe game in the terminal.
 
PRIORITY LEVELS
---------------
P0 (MVP)      : Core features required for a playable game
P1 (Polish)   : Small improvements that make the game nicer
P2 (Future)   : Nice-to-haves (currently out of scope)
 
P0 - MINIMUM VIABLE PRODUCT (Must Have)
---------------------------------------
1.  Create empty board          - Initialize a 3x3 board using 2D list
2.  Display the board           - Print the current board state in a clean grid format
3.  Player move input           - Accept player move (row and column) via terminal input
4.  Validate moves              - Check if move is within bounds and spot is empty
5.  Update board with move      - Place X or O on the board after valid move
6.  Switch players              - Alternate between Player X and Player O
7.  Win detection               - Check all rows, columns, and diagonals for a win
8.  Draw detection              - Detect when board is full with no winner
9.  Game loop                   - Main loop that continues until win or draw
10. Announce result             - Print winner or "It's a draw" message at the end
 
P1 - POLISH (Nice to Have)
--------------------------
11. Input validation messages   - Clear error messages for invalid moves
12. Show whose turn it is       - Display current player before each move
13. Play again option           - Ask user if they want to restart after game ends
 
P2 - FUTURE / OUT OF SCOPE
--------------------------
- AI opponent
- Color output in terminal
- Score tracking
- Graphical interface
- Move history / undo
 
IMPLEMENTATION ORDER
--------------------
1. Start with board.py   (features 1, 2, 5)
2. Then logic.py         (features 7, 8)
3. Finally main.py       (features 3, 4, 6, 9, 10)
 
STATUS
------
Roadmap defined. Ready to begin implementation.
 