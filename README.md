# Reversi Move Counter GUI

A small Tkinter GUI that lets you design an N×N Reversi (Othello) board and count how many positions black can legally play next.

## Features
- Supports board sizes from 4 to 30.
- Click cells to cycle between empty (`.`), black (`B`), and white (`W`).
- Press **Count moves** to compute how many valid black moves exist on the current board using the standard Reversi rules (orthogonal and diagonal flips).

## How to run
```bash
python main.py
```

Use the spinbox at the top to change the board size, click cells to set up the position, then click **Count moves** to see the total.
