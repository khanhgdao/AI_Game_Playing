# AI Game Playing
Implemented AI Agent to play in a two-player knight isolation game.
Algorithms options: Minimax, Alphabet Pruning, Iterative Deepening (with moves ordering) (last 2 were chosen as the final model).

The rules of Knight Isolation are a variation of the original Isolation game. In the original form of the game there are two players, each with their own game piece, and a 9-by-9 grid of squares. At the beginning of the game, the first player places their piece on any square. The second player follows suit, and places their piece on any one of the available squares. From that point on, the players alternate turns moving their piece like a queen in chess (any number of open squares vertically, horizontally, or diagonally). When the piece is moved, the square that was previously occupied is blocked, and cannot be used for the remainder of the game. The first player who is unable to move their queen loses. In this variant called Knight Isolation, the queens are replaced by knights, and their moves behave like a knight in chess (any move going two spaces vertically or horizonally, and then one move perpendicular to the previous move).

The AI agent I implemented will try to beat a custom AI agent which used Iterative Deepening depth level 4

<img width="489" alt="Screenshot 2024-10-31 at 17 44 29" src="https://github.com/user-attachments/assets/d7d5086d-2484-48e7-9adc-d80b61f08660">


## How to use:
- Install the libraries: `pip install -r requirements.txt`
- Run the cells in the game_playing_agent.ipynb (there's also interactive cell to play the game as human)
