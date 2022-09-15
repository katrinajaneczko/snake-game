# snake-game
This repository is to be shown as a proof of concept for a project pitch for my Software Design class. The project is entitled Snake Hunt: A Competitive Multiplayer Game in Python.

### Requirements
To run the relevant files, you will need will need to download Python (https://www.python.org/downloads/) (preferably version 3.7 or newer) and install Pygame(https://www.pygame.org/wiki/GettingStarted). Python and the required libraries are compatible with Windows XP or newer, Linux/UNIX, and macOS.

## Client_Server Folder
This folder contains 3 files: client.py, server.py, and network.py. First, replace the IP address string in both network.py and server.py to be your computer's, or simply write "localhost". Then open a terminal and run server.py in it. Open a new terminal and run client.py, and you will see it connect. To connect a second client, open a new terminal and run client.py. Now there will be 2 windows showing a red square and a green square. The player's square is green and the other player is red. If 2 clients are connected, they each see thier own square as green and the other's as red. Movements of a player in one window are displayed in both windows, and the server will read and print positions of the 2 players to keep track of their movements and send them to the other player. To create the code for these files, I referenced Python’s socket module documentation and a YouTube tutorial by the channel Tech With Tim (https://www.youtube.com/watch?v=F257x_E6H4k). 

<img width="1004" alt="Screen Shot 2022-09-15 at 3 18 24 PM" src="https://user-images.githubusercontent.com/73796086/190490676-e71103c6-6b69-47d9-b793-576de6f83c4c.png">

## Game Folder
This folder contains 1 file: snake_oop.py. To run this file, open a terminal and run the file. This file just demonstrates how a rudimentary version of a snake game will work. 
