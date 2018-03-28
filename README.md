# XandO

Your job for this lab is to take the beginning of the main.cpp provided and adapt it to create a basic Tic-Tac-Toe game.

The game's board will be represented by a 2-dimensional array (2D array or "matrix") of characters. To specify locations, we will let the users input row and column coordinates that correspond to:

First, open main.cpp and read what code is provided already so you understand how it is working so far.

Next, replace the comments that begin with TODO: by implementing their algorithm descriptions. The parts of the algorithm are outlined in plain words and it is your job to translate those descriptions into C++ code.

A few clarifications:

1) The game will actually allow players to overwrite the other player's mark. For example, if X put their piece at (column 2, row 2) and then O puts their piece at that location as well, then the X will be replaced with an O

2) The game only ends when the users enter -1 for both the row and columns. Otherwise, it will continue playing forever, even if one player has "won"

3) Keep in mind that while the users enter the column first and then the row, C++ arrays are "row-major order" which means the notation specifies the row first and the column second when using bracket notation, such as:

board[1][2] = 'Z';

That line would put the letter Z in the cell at location row 1 and column 2 (the middle-right cell)

Submit to TurnIn and satisfy all the tests
