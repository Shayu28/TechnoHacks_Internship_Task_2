# TechnoHacks_Internship_Task_2

ALGORITHM:

Initialize Pygame:
Set up the screen with a width of 700 pixels.
Set the title of the window to "TicTacToe".
Define colors, images for X and O, and a font for the end message.

Draw Grid:
Define a function to draw a grid with lines separating the cells.

Initialize Grid:
Create a 3x3 grid with center coordinates for each cell and an initial state.

Click Handling:
Detect mouse clicks and determine which cell was clicked.
If it's X's turn, place an X in the clicked cell; if it's O's turn, place an O.
Toggle between X and O turns.

Check Win Condition:
Check if any player has won by checking rows, columns, and diagonals.
Display a message and end the game if a player has won.

Check Draw Condition:
Check if the game has ended in a draw (all cells filled).
Display a message and end the game if it's a draw.

Display Message:
Display a message in the center of the screen for a specified duration.

Rendering:
Fill the screen with white color.
Draw the grid.
Draw X's and O's based on the current game state.
Update the display.

Main Loop:
Initialize game variables and the game grid.
Enter the main game loop.
Handle events (quit, mouse clicks).
Render the game.
Check for win or draw conditions and end the game if necessary.

Game Loop:
Continuously run the game loop until the program is terminated.
