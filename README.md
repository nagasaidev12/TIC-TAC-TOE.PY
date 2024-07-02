#TictacToe-AI

This code implements the TicTacToe game logic and AI players using Alpha-Beta Pruning.

The main key functions used in code are:

gameBoard() - Prints the current state of the board

boardFull() - Checks if the board is full (no more empty spaces)

winningPlayer() - Checks if a player has won by checking all possible winning combinations

getScore() - Returns a score of 1 if X wins, -1 if O wins, 0 for tie

alphaBeta() - Implements minimax with alpha-beta pruning to determine best move

computerMove() - Uses alphaBeta to determine the best move for the AI player and make the move

playerMove() - Gets input from the human player and makes their move

play() - Main game loop, calls the other functions to alternate moves between AI and human players until game over

To play the game firstly, we should call play() function. This game requires 2 players. By default player1 will be our AI agent i.e , x_player and player2 will be user i.e, o_player can be random.

Alpha-Beta pruning improves efficiency greatly by pruning branches that doesn't need to be searched.

This allows our AI agent to play perfectly and never lose a game.

