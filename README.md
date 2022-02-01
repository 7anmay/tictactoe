# Tic-Tac-Toe 
This is the captone project for the course Udacity C++ Nanodegree Program, option A.
The simple Tic-Tac-Toe game created in C++ with SDL2.

## Dependencies for Running Locally
SDL2 is required to compile the program. To install it, use the following commands:

**Debian**
```
$ sudo apt-get install libsdl2-dev

```

## Basic Build Instructions
```
    1. clone this repo
    2. cd `sourcefolder` 
    3. make
    4. ./tictactoe
```

## Project Structure
```
.
├── build
├── Makefile
├── README.md
├── src
│   ├── App.cpp
│   ├── App.h
│   ├── Board.cpp
│   ├── Board.h
│   ├── Bot.cpp
│   ├── Bot.h
│   ├── Game.cpp
│   ├── Game.h
│   ├── main.cpp
│   ├── Util.cpp
│   └── Util.h
└── tictactoe
```
## Implementation Details
```
This is a single player tictactoe game. The game has a 3 difficulty level bot which chooses the level o difficulty randomly. The feature to choose difficulty will be added in the future.
The App class acts as an entrypoint into the game. The Board class defines the playboard used to play the game  and itsel is acts as the playfield. The class Bot is the computer player that plays the game in 3 different difficulty levels which are choosen on by random. State of the game and turn taken by the players are managed by Game class, it updates the state of the game quickly by taking in input from the GUI, basically it acts as a interface between the game and the user.    

```

## Rubrik Criterias 
```
a. The project uses Object Oriented Programming techniques
b. Classes use appropriate access specifiers for class members. Classes encapsulate behavior. Classes abstract implementation details from their interfaces.
c. The project accepts user input and processes the input. using the sdl library

```
