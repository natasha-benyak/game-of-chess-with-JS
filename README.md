# CHESS GAME
#### Video Demo:  <https://youtu.be/gI9AwlcQLe0>
#### Description:

This is a simple chess game made using javascript.

The rules of the game are the same as in a traditional game of chess.
The chess pieces are then arranged the same way each time.
The second row (or rank) is filled with pawns. The rooks go in the corners, then the knights next to them,
followed by the bishops, and finally the queen, who always goes on her own matching color
(white queen on white, black queen on black), and the king on the remaining square.
The game is player by two payers. Controllers are with cursor of the mouse.

Each type of chess piece has its own method of movement. A piece moves to a vacant square except when capturing an opponent's piece.

Except for any move of the knight and castling, pieces cannot jump over other pieces. A piece is captured (or taken) when an attacking enemy piece replaces it on its square (en passant is the only exception). The captured piece is thereby permanently removed from the game.[1] The king can be put in check but cannot be captured (see below).

The king moves exactly one square horizontally, vertically, or diagonally. A special move with the king known as castling is allowed only once per player, per game (see below).
A rook moves any number of vacant squares horizontally or vertically. It also is moved when castling.
A bishop moves any number of vacant squares diagonally.
The queen moves any number of vacant squares horizontally, vertically, or diagonally.
A knight moves to the nearest square not on the same rank, file, or diagonal. (This can be thought of as moving two squares horizontally then one square vertically, or moving one square horizontally then two squares vertically—i.e. in an "L" pattern.) The knight is not blocked by other pieces: it jumps to the new location.
Pawns have the most complex rules of movement:
A pawn moves straight forward one square, if that square is vacant. If it has not yet moved, a pawn also has the option of moving two squares straight forward, provided both squares are vacant. Pawns cannot move backwards.
A pawn, unlike other pieces, captures differently from how it moves. A pawn can capture an enemy piece on either of the two squares diagonally in front of the pawn (but cannot move to those squares if they are vacant).

The player will need to click on the figure he is wishing to play with and options where the piece could move will be displayed in green.
He then must click on a chosen location where he wants the piece to go.

At the bottom of the board game the score will be displayed, counting life as figures of each opponent will be taken.

This game is made of 4 files.

index.html - contains the basic sceleton of the game and which elements
(e.g. texts, board,...) will be presented to the user.

package.json - it is JSON file and contains metadata about the project.

Javascript folder has two other files:

chess.js - this file is the heart of the project and makes the game run.
This is where all functions are kept that make the chess pieces move the way they are intended to move.

.eslintrc.js file- ESLint config file is defined as a JavaScript object that exports a file.
In that file "rules" are not defined.

Please note that CSS file is omitted - instead CSS is inputed in .html file under
style tags and in chess.js file.