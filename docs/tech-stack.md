# Tech Stack: Simple Terminal Tic Tac Toe

## Overview
Pure Python implementation with zero external dependencies. Designed to be clean, readable, and slightly more organized than a single-file script.

## Core Decisions

| Component         | Choice                  | Reason |
|-------------------|-------------------------|--------|
| **Programming Language** | Python 3           | Simple, readable, great for terminal apps |
| **Dependencies**  | None                    | Zero external packages for maximum simplicity |
| **Display**       | Plain `print()`         | Built-in, no libraries needed |
| **User Input**    | `input()`               | Standard library only |
| **Code Organization** | Multiple files     | Better separation of concerns while staying simple |
| **Architecture**  | Functional + modular    | Easy to understand and maintain |

## File Structure

| File          | Purpose                              |
|---------------|--------------------------------------|
| `main.py`     | Entry point and main game loop       |
| `board.py`    | Board display and move handling      |
| `logic.py`    | Win detection, draw detection, rules |

## Constraints
- No external libraries (no `rich`, `colorama`, `pygame`, etc.)
- Keep code clean and readable
- Prioritize simplicity over advanced patterns

## Status
✅ Tech stack defined and agreed upon