#Tic-Tac-Toe

-Utilized JavaScript, CSS, HTML to create an interactive Tic Tac Toe game
-playable with 2 players, no ai available

*Installation Instructions*
None, just go to the url and enjoy

*Steps to play*

1. Decide amognst yourselves who will go first (note, O will always start first and X will go second)
2. select your place on the board and click the space you'd like to enter your value
3. Allow the next player to make their move
4. Winner is determined by aligning 3 of your symbol horizontally, vertically, or diagonally.
5. Click the Reset button to clear the board and play again.
-if a tie results, a prompt will appear and the board will reset itself-

*Approach Taken*
I utilized my dynamic understanding of the complex and intelectually intensive game of tic tac toe to determine how I would go about designing the game. I struggled (and still do) to use javascript and the concept of arrays to manipulate data effectively and efficiently. Instead of opting to utilize arrays, I looked to using if/else statements for my game logic, utilizing hasClass() and removeClass() to manipulate the board.

*Unsolved Issues*
Fortunately, there's only one current issue. If you attempt to reset the board by clicking on a tile to yield the prompt that a player has won and a game will be reset, the board will display with colored tiles of where the O's were placed over the course of the game, regardless if X or O won. Clicking outside of the tiles will remove the highlighting.