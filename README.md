# TicTacToePython

This python project basically, tic tac toe is 2 player game that is played in a 3x3 matrix/board. The player 1 chooses a marker X or O and other player chooses the remaining one. So now the game play, player 1 then followed by player 2 will play in the order, each player will place their respective markers on the board, in the sequence. 

the game ends by either one player wins or match ties. The winning position will be 3 marker of a player in horizontal, vertical or diagonal way.it will be like 3+3+2 possibilities, else the match is consider to be tie.

So in normal game play, the game is played between 2 player but in my project 1 player can play against the computer based on a simple algorithm, and it’s the simple program so no big presenting tools were used.

Refer this link for better understanding of the project theme https://medium.com/byte-tales/the-classic-tic-tac-toe-game-in-python-3-1427c68b8874

(but this is not the entire project, make use of the concept and basic understanding of the gameplay)

Algorithms, 
1.I’ll have a list of possible moves with its index.
2.for markers in X and O
	2.1.for position in possible moves
		2.1.1. Copy the board and check by placing the marker in all position of possible list, if the is a winning position then I’ll place the computer’s marker onto the position and return.
		2.1.2. Or I’ll check all the corners if position is free then I’ll place the computer’s marker if not.
		2.1.3. I’ll check the free edges and move in there, by a random function.

Functions needed in this project,
1.	board
2.	insertion
3.	space Free
4.	print Board
5.	is Winner
6.	player Move
7.	Computer Move – Algorithm
8.	Random function
9.	Board is full
10.	Main driven function
