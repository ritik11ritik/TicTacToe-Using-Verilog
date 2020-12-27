# TicTacToe-Using-Verilog

Tic Tac Toe is a very popular paper-and-pencil game in a 3x3 grid for two players. The player who makes the first three of their marks in a diagonal, vertical, or horizontal row wins the game.

Let's define the rules for the game at first. In this game, a player plays the Tic Tac Toe game with a computer. When the player/ computer plays the game, a 2-bit value is stored into one of the nine positions in the 3x3 grid like Xs/ Os in the real paper-and-pencil version. 2'b00 is stored into a position when neither the player or computer played in that position. Similarly, 2'b01 (X) is the value to be stored when the player played in the position and 2'b10 (O) is the value to be saved when the computer played in the position. The player/ computer plays the game by pressing their corresponding button.

Consider the 3x3 grid table as the order of positions being played:
