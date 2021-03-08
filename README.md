# ICS4U Tic Tac Toe

Your goal will be to create the a two player Tic Tac Toe game on the command line.
You will need to use 2D lists in order to do so.

Your game must include:
* The ability for players to pick positions on the board to go (you don't have to worry about the user inputing invalid cordinates or cordinates that have already been taken, but you can if you want... I'm fine to assume both parties play fairly and correctly)
* The ability to determine if X or O won and print that out on the screen
* Comments!
* Docstrings (for any functions you write) [Example, check_win(board) should probably be a function, where board is the 2d list that represents the board]
* Good variable names in snake_case


This seems like a lot, but we will use the idea of 'modular design' (no, we have not talked about that yet, but consider this your introduction my diving feet first) to help us.

Let's consider some things our game will need to do

1. Print the board to the screen
2. Check if the board is full (if it is, it's a tie)
3. Check if there are three letters in a row, column, or diagonal on the board
4. Update the bord with a letter at a given position

4. Continue Looping while we are playing
5. Get input from the playeys

The first four things can be tackled one at a time, individually in functions.
```
def print_board(board):
  """Prints the board to the screen"""
```

```
def is_board_full(board):
  """ Returns True if the board is full, False otherwise"""
  # How would I implement something like this (loop through the 2d list and check all the elements perhaps?
```

```
def is_board_won(board):
  """ Returns True if one letter has three positions in any row, column, or diagonal"""
  # How would I check this? I'm not opposed to seeing if statements here!
```

```
def update_board(board, letter, pos1, pos2):
  """ Updates the board given the current letter at the given position"""
  # Something like board[pos1][pos2] = letter, but you'll need to be more careful than that.
  # Assume pos1 and pos2 represent a valid position on the board
```

* You know how to keep looping while checking some user input.
* You know how to get user input.


As I stated in the video, you will not be recieving any more videos for a little while, so you can focus on this assignment

If you have any questions, please let me know

