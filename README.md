# Tic-Tac-Toe in C

This is a simple **Tic-Tac-Toe (X-O)** game implemented in C.  
You play as **X**, while the computer plays as **O**.  
The game runs in the console and ends when either side wins or the board fills up (draw).

---

## Features
- 3x3 game board
- Player vs Computer mode
- Computer makes **random moves**
- Detects **win, loss, or draw**
- Clear console-based interface

---

## How It Works
1. The game board is initialized with empty spaces (`' '`).
2. The player chooses a position by entering:
   - **Row number** (1–3)
   - **Column number** (1–3)
3. The program checks if the chosen spot is free:
   - If valid → your move is placed.
   - If not → you must try again.
4. The computer then selects a random empty spot.
5. After each turn:
   - The **board is displayed**.
   - The program checks for a **winner**.
6. The game ends when:
   - Either player wins (3 in a row, column, or diagonal).
   - The board is full → **draw**.

---
## Example Gameplay:

 GAME STARTS

```bash
|----|----|----|
|    |    |    |
|----|----|----|
|    |    |    |
|----|----|----|
|    |    |    |
|----|----|----|
```

Enter row #(1-3): 1
Enter column #(1-3): 1

```bash
|----|----|----|
| X  |    |    |
|----|----|----|
|    |    |    |
|----|----|----|
|    |    |    |
|----|----|----|
```

(Computer plays...)

```bash
|----|----|----|
| X  |    |    |
|----|----|----|
|    | O  |    |
|----|----|----|
|    |    |    |
|----|----|----|
```

## Compilation & Execution

### Compile:
```bash
gcc tic-tac-toe.c -o tic-tac-toe
```
### Run:

```bash
./tic-tac-toe
```
