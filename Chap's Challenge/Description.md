You are to design and implement a program for a single-player graphical adventure game using only the tools available in the Java standard library. The objective of the game is to explore an imaginary world, collecting objects, solving puzzles, and performing actions to complete the game.

You should undertake this project in teams of 4-6 people. We want you to work in teams for two different reasons: firstly, to experience what it is like to work as part of a team on a software development project; secondly, to be involved in a larger project without you having to do all the work yourself.

### Chip and Chap

Chap's challenge is a creative clone of the (first level of the) 1989 Atari game Chips Challenge. In Chips Challenge, an actor moves through a maze directed by the keystrokes of the user, collects treasures and searches for the exit that leads to the next level.

### Architecture

The game should adopt high-level architecture consisting of four core components:
- The **Maze** package. This is responsible for maintaining the current state of the game, such as where the objects in the game currently are, and also for determining what actions are allowed within the game. 
- The **Application** package. This is responsible for managing the functionality of the game (e.g. starting new games, loading/saving games, moving the player, managing the application window(s), etc).
- The **Renderer** package. This is responsible for drawing the maze onto a canvas and mapping key strokes on the canvas back to objects in the game world, etc.
- The **Persistence** package. This is responsible for reading map files and reading/writing files representing the current game state. 
