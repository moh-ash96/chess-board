# chess-board

I was asked to make a chess game.

## Getting Started

To get started with the project:

* Clone the repository =>  `git clone https://github.com/moh-ash96/chess-board/`

* Cd into the folder =>  `cd chess-board`

* Run poetry init =>  `poetry init -n`

* Run poetry poetry add numpy matplotlib jupyterlab => `poetry add numpy matplotlib jupyterlab`

* Inter the shell =>  `poetry shell`

### Changelog

* First commit - basic project files

* Second commit has the file checks for the queen movements

### TODO Checklist

- [x] Define a ChessBoard class - should contain an 8x8 grid - Each cell in grid should have a color represented in RGB format. - black = (0,0,0) - white = (1,1,1) - blue = (0,1,1) - red = (1,.2,0).
- [x] Define add_red method that accepts a row and column as input which colors corresponding cell.
- [x] Define add_blue method that accepts a row and column as input which colors corresponding cell.
- [x] Define render method that displays the chess board on screen with red and blue shown in correct locations
- [x] Define is_under_attack method that return boolean if red is under attack by a blue piece horizontally, vertically or diagonally

[pull request](https://github.com/moh-ash96/chess-board/pull/1)
