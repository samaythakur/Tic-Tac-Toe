# Tic-Tac-Toe

# Project Overview 
Developed a GUI-based Tic-Tac-Toe game using the Python programming language and the Tkinter library. The project provides an interactive interface where two players can play alternately using symbols X and O. The game includes turn-based logic, automatic winner detection, draw condition checking, and game reset functionality. It demonstrates the practical implementation of event-driven programming, GUI development, conditional statements, and game state management concepts in Python.

# Project Flow
1.Start the application and initialize the game board.

2.Create a 3×3 grid using Tkinter buttons.

3.Assign Player X as the first player.

4.Detect button click events from the user.

5.Update the selected cell with the current player's symbol.

6.Switch turns dynamically between Player X and Player O.

7.Continuously check for:
  -Row-wise win
  -Column-wise win
  -Diagonal wise win
  
8.If a player wins:
  -Display winner message
  -Reset the game automatically
  
9.If all cells are filled without a winner:
  -Declare the match as a draw
  -Reset the game
  
10.Repeat gameplay for a new match.

# Result
The Tic-Tac-Toe game was successfully implemented with a user-friendly graphical interface. The application correctly handled player turns, validated moves, detected winning conditions, identified draw situations, and automatically reset the game after completion. The project effectively demonstrated GUI programming and logical decision-making in Python.

# Conclusion
This project helped in understanding the fundamentals of Python GUI development using Tkinter and strengthened knowledge of event-driven programming and game logic implementation. It also improved problem-solving skills through the use of conditional checking, state management, and interactive user interface design. The project can be further enhanced by adding features such as single-player AI mode, score tracking, sound effects, and improved graphical styling.
