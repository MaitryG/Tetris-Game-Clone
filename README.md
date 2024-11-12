# Tetris-Game-Clone
This is a clone of the classic Tetris Game. It is developed using PyGame and can be played by following the below steps:
- Go to https://trinket.io/library/trinkets/create?lang=pygame
- Copy the code from main.py file and paste it in the textbox given on the link.
- Click on the Run button at the top.
- Enjoy playing!

This code is a Tetris game built using Python and the Pygame library. It initializes constants for the game settings, colors, window dimensions, and piece templates, defining classic Tetris shapes like S, Z, I, O, J, L, and T. 

The main game loop is handled in the runGame function, which initializes the board, manages the active piece, and tracks the player's score and level. The player can rotate and move pieces left, right, or down, and drop pieces instantly to the bottom. The game levels up based on the player's score, which increases as complete rows are cleared. Functions such as getNewPiece, isValidPosition, addToBoard, and drawPiece help manage game mechanics, ensuring pieces appear and behave correctly. A pause screen and game-over screen are also displayed when needed, and the game can be exited with the ESC key.
