# X-O Game - Python Tkinter

A simple desktop Tic-Tac-Toe/X-O game built with Python and Tkinter. The game provides an interactive 3x3 board, two-player turn switching, score tracking for Player X and Player O, winner detection, and reset/new game controls.

![X-O Game Screenshot](img.png)

## Features

* Desktop GUI built with Tkinter
* 3x3 interactive Tic-Tac-Toe board
* Two-player local gameplay
* Automatic turn switching between X and O
* Winner detection for rows, columns, and diagonals
* Score tracking for Player X and Player O
* Winner popup messages
* Reset button to clear the board
* New Game button to reset both the board and scores

## Tech Stack

* Python
* Tkinter

## Project Structure

```text
X-O-Game-Python-Tkinter/
├── main.py      # Main Tkinter game application
├── img.png      # Game screenshot used in README
└── README.md
```

## Requirements

Python 3 is required.

Tkinter is included with most Python installations. On some Linux distributions, you may need to install it manually:

```bash
sudo apt install python3-tk
```

## How to Run

Clone the repository:

```bash
git clone https://github.com/joeljebitto-dev/X-O-Game-Python-Tkinter.git
cd X-O-Game-Python-Tkinter
```

Run the game:

```bash
python3 main.py
```

On Windows, you can also try:

```bash
python main.py
```

## How to Play

1. Launch the application.
2. Player X starts first.
3. Click an empty square to place the current player's mark.
4. The game automatically switches turns after each valid move.
5. When a player completes a row, column, or diagonal, the winning cells are highlighted and a popup announces the winner.
6. Use **Reset** to clear the current board.
7. Use **New Game** to reset both the board and player scores.

## Notes

* This is a beginner-friendly GUI project for learning Tkinter event handling, buttons, frames, labels, variables, and basic game logic.
* The O player is represented internally with `0` in the button text.
* The game is designed for local two-player play on the same computer.

## Future Improvements

* Add draw/tie detection
* Disable the board briefly after a win before resetting
* Improve responsive window sizing
* Refactor repeated win-checking logic into reusable functions
* Add single-player mode with a basic AI opponent
* Add sound effects or animations
* Package the app as an executable

## Author

Built by [Joel Jebitto](https://github.com/joeljebitto-dev).
