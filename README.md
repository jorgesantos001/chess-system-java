# Chess Game - Jogo de Xadrez

This is a chess game implemented in Java. The project includes the standard chess pieces: Bishop, King, Knight, Pawn, Queen, and Rook.

## Project Structure

- **boardgame**

  - `Board.java`: Represents the chessboard.

  - `Position.java`: Represents a position on the board.
  
  - `Piece.java`: Abstract base class for pieces.

- **chess**

  - `ChessMatch.java`: Manages the state of the chess game, including movement and check verification.

  - `ChessPiece.java`: Base class for chess pieces.

  - `Color.java`: Enumeration for piece colors (white and black).

- **chess/pieces**

  - `Bishop.java`: Implementation of the Bishop piece.

  - `King.java`: Implementation of the King piece.

  - `Knight.java`: Implementation of the Knight piece.

  - `Pawn.java`: Implementation of the Pawn piece.

  - `Queen.java`: Implementation of the Queen piece.
  
  - `Rook.java`: Implementation of the Rook piece.

## Requirements

- Java 11 or higher

## Compilation and Execution

1. **Clone the repository:**
 
  git clone https://github.com/jorgesantos001/chess-system-java.git

2. **Navigate to the project directory:**

3. **Navigate to the 'bin' directory:**
   
4. **Run the application:**
   
   java application/Program

## Description of Pieces

Bishop: Moves diagonally. Can move any number of squares in any diagonal direction.

King: Moves one square in any direction. Allows the special castling move.

Knight: Moves in an "L" shape: two squares in one direction and one square perpendicular. Can jump over other pieces.

Pawn: Moves one square forward, with the option to move two squares on its first move. Captures diagonally. Allows promotion upon reaching the last rank and the "en passant" capture option.

Queen: Moves any number of squares in any direction: vertical, horizontal, or diagonal.

Rook: Moves any number of squares vertically or horizontally. Participates in castling with the king.

## Special Features

Castling: Special move of the king and rook. Allows the king to move two squares towards the rook, and the rook to move to the opposite side of the king.

Promotion: When a pawn reaches the last rank, it can be promoted to any piece (except king).

En Passant: Special pawn capture move.
