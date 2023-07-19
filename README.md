# Tic--Tac-Toe
This is a two player game wherein the players will have to choose either X or O in a 3x3 grid.

The First player can choose any position in the grid and both will get one move at a time, one after the other. The player who succeeds in
placing three of their marks in a horizontal, vertical, or diagonal row wins the game.

In the bakcend, the game maintains a 2-D array to save the current state of the 3x3 grid. A function is made to check if the box that's clicked by the player in the displaying grid is empty or noit and decides to put up an image of Oif the previous one was X and vice versa. Now, when the consecutive images match, the game ends.
