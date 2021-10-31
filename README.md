# Numpy Arrays

PR: https://github.com/moayadalhaj/chess-board/pull/1

## Chess Board

create a ChessBoard class:

- contain an 8x8 grid

- Each cell in grid should have a color represented in RGB format.
  - black = (0,0,0)
  - white = (1,1,1)
  - blue = (0,1,1)
  - red = (1,.2,0)

That contains four methods:

- `add_red` method that accepts a row and column as input which colors corresponding cell.
- `add_blue` method that accepts a row and column as input which colors corresponding cell.
- `render` method that displays the chess board on screen with red and blue shown in correct - locations
- `is_under_attack` method that return boolean if red is under attack by a blue piece horizontally, vertically or diagonally

### Tests

- if queens on same row should be “under attack”, output willbe True
- if queens on same column should be “under attack”, output willbe True
- if queens on same diagonal should be “under attack”, output willbe True
- if queens with any other coordinates should NOT be “under attack”, output willbe False
