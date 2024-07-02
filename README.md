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

#CHATBOT WITH RULE-BASED RESPONSES

This is a simple rule-based chatbot that allows defining responses using regular expressions. It checks the user statement against each rule sequentially and outputs the first match.

Firstly,the code imports the re module for regular expressions.

Creates a rules dictionary that maps patterns to responses

Defines a match_rule function that takes the rules and a statement

Loops through the rules and uses re.search to match the statement against each pattern Returns the response if a match is found

In Main loop: Gets user input statement Calls match_rule to find a matching rule If a match is found, prints the response Otherwise prints a default response

This allows us to easily define rules and responses without needing complex NLP.
