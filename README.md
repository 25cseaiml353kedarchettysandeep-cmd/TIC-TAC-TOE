# Tic-Tac-Toe

## Aim
To implement a two-player Tic-Tac-Toe game and detect wins or a draw.

## Algorithm
1. Create an empty 3×3 board and set player X to start.
2. Ask the current player for a row and column.
3. Reject out-of-range or occupied positions without consuming a turn.
4. Place the mark and check rows, columns, and diagonals for a win.
5. Switch players; if all cells are used without a winner, report a draw.

## How to run
Requires Python 3.10 or newer. No third-party packages are required.

```bash
python tic_tac_toe.py
```

## Sample output
```text
Interactive game: players enter row and column numbers from 0 to 2; the program announces a winner or a draw.
```

## Notes
This is a two-player console game; it does not use an AI opponent.

## Repository structure
- `tic_tac_toe.py` — program source code
- `README.md` — aim, algorithm, run instructions, and sample output

> Before submission, run the program on your own computer and capture the actual output. Sample output may vary with user input.


## Sample output
See [`output.txt`](output.txt) for a sample console run. Re-run the program locally to confirm output for your chosen input.


## Output file
See [`OUTPUT.txt`](OUTPUT.txt) for an example console run. Interactive output depends on the input entered.
