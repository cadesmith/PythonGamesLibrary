# PythonGamesLibrary
*Capstone project created for Networks course at Colgate University*

## Project Description
A library of four online games that can be played in a terminal. The games are designed for two players and include Battleship, Connect Four, Tic Tac Toe, and Hangman.

## Server and Client Setup
Server Address: Hosted on the IPv4 address "149.43.0.29" and on port 5000.
Client and Server Code: Each game has its client Python file and server Python file. For example, BattleshipClient.py handles the player's connection, and BattleshipServer.py sets up the server for each player to connect.

## Running a Game
Server Terminal: Open a terminal in the code editor, navigate to the Library folder, and run python3 server.py. This terminal will act as the server. The server can be started remotely on any device, and the players will be able to connect via an alternate device.
Player Terminals: Open two other terminals, navigate to the same folder, and enter python3 client.py in each. These will be the player terminals.
Gameplay: Follow the on-screen instructions in the client terminals to play the games. Each terminal represents one player.
