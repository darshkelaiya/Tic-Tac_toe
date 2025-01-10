
# Tic-Tac-Toe Game in Java

This is a simple console-based Tic-Tac-Toe game implemented in Java. The game allows two players to play the game on the same machine by taking turns to enter their moves for 'X' and 'O'. The game board is displayed after each move, and the game checks for win conditions or a draw after every turn.

## Features

- Two-player gameplay (Player 1 uses 'X' and Player 2 uses 'O').
- The game continues until there is a winner or a draw.
- The board is printed after every move.
- Players input the row and column numbers to place their marks on the board.
- Option to restart the game after finishing.

## How to Play

1. The game prompts Player 1 (X) to enter the row and column number for their move.
2. The game board is displayed after each move, showing the current state.
3. The game then prompts Player 2 (O) to enter their move.
4. The game checks after each move for a winner or a draw.
5. If a player wins, the game announces the winner and ends.
6. If the board is full without any player winning, the game declares a draw.
7. After each game, you can choose to play again by entering 'y' when prompted.

## How to Run

1. Clone or download this repository to your local machine.
2. Open the project folder in your Java IDE or text editor.
3. Compile the program using `javac tictactoe.java`.
4. Run the program using `java tictactoe`.
5. Follow the on-screen prompts to play the game.

## Example Gameplay

```
Enter row number for X: 0
Enter column number for X: 0
X|_|_
_|_|_
_|_|_

Enter row number for O: 1
Enter column number for O: 1
X|_|_
_|O|_
_|_|_

Enter row number for X: 0
Enter column number for X: 1
X|X|_
_|O|_
_|_|_

Enter row number for O: 1
Enter column number for O: 2
X|X|_
_|O|O
_|_|_

Enter row number for X: 2
Enter column number for X: 2
X|X|X
_|O|O
_|_|_

Player - 1 wins!
Want to play again? Enter y if yes : n
```

## Technologies Used

- Java 8 or later
- Basic console input/output



This README file provides all the necessary details to understand the game's functionality and how to set it up. You can modify it as per your project details.
