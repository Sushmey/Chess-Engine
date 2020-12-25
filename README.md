# Chess-Engine
A basic chess engine website.
I wrote this engine using two Javascript libraries.
[chessboard.js](https://chessboardjs.com) to display the board, make it interactive and the drag the pieces to move them.
[chess.js](http://www.lib4dev.in/info/jhlywa/chess.js/98154), a Javascript chess library that is used for chess move generation/validation, piece placement/movement, and check/checkmate/stalemate detection - basically everything but the AI.

# How it works
This program uses a minimax function with alpha-beta pruning with a user input depth. The more the depth, the better is the engine. The alpha-beta pruning optimises the code to make it faster and use less resources by not checking "bad" moves (moves with really bad evaluation).
This code can be made better with a better evaluation and maybe referring a table of opening moves so that it doesn't have to calculate openings and just focus on middle and endgame.

# Try it out !
[Click here to try out the engine!](https://greatestchessengine.netlify.app/)
