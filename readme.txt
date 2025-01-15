# Tic-Tac-Toe Game

A simple console-based implementation of the classic Tic-Tac-Toe game written in C++. This project allows a single player to compete against a computer opponent.

## Features
- **Player vs Computer Gameplay**: The player uses 'X', and the computer uses 'O'.
- **Dynamic Game Board**: The board updates in real-time with each move.
- **Winner Detection**: The game announces the winner or a tie at the end.
- **Randomized Computer Moves**: The computer makes random valid moves to keep the game engaging.

## How to Play
1. Clone the repository or copy the code.
2. Compile the code using a C++ compiler (e.g., `g++`).
3. Run the compiled program.
4. Enter a number (1-9) to place your marker on the board. Numbers correspond to positions as shown below:

```
 1 | 2 | 3
---|---|---
 4 | 5 | 6
---|---|---
 7 | 8 | 9
```

5. The computer will then make its move. The game alternates turns until there is a winner or a tie.

## Compilation and Execution

To compile and run the program, use the following commands:

```bash
# Compile the program
g++ -o tic_tac_toe tic_tac_toe.cpp

# Run the program
./tic_tac_toe
```

## Example Gameplay

```
     |     |     
     |     |     
_____|_____|_____
     |     |     
     |     |     
_____|_____|_____
     |     |     
     |     |     
     |     |     

Enter a spot to place a marker (1-9): 5

     |     |     
     |     |     
_____|_____|_____
     |  X  |     
_____|_____|_____
     |     |     
     |     |     

Computer placed 'O'.
```

## Code Breakdown

### Functions
- `drawBoard`: Displays the current state of the game board.
- `playerMove`: Handles the player's move by taking input and updating the board.
- `computerMove`: Generates a random valid move for the computer.
- `checkWinner`: Checks if there is a winner after each move.
- `checkTie`: Checks if the game ends in a tie.

## Requirements
- A C++ compiler (e.g., g++, clang++)

## Future Enhancements
- Add support for two-player mode.
- Improve the computer's AI for smarter moves.
- Create a graphical interface.

## Contributing
Feel free to fork this repository and make contributions. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License
This project is open-source and available under the MIT License. See the LICENSE file for details.

---

Enjoy playing Tic-Tac-Toe!

