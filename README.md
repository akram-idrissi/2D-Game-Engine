# 2D Game Engine
This game engine provides beginner developers who are not familiar with pygame a structure and set of classes to start building games using python.

The game object model used in this book is a hybrid of the monolithic hierarchy and the component object models. This is, in part, inspired by the game object model used in [Unreal Engine 4](https://docs.unrealengine.com/4.26/en-US/ProgrammingAndScripting/ProgrammingWithCPP/UnrealArchitecture/Actors/). There is a base Actor class with a handful of overridable methods, and a list of components.

# Set up
* Open the terminal and clone this repository using: `git clone https://github.com/akram-idrissi/2D-Game-Engine.git`
* Install the required modules using: `pip install -r requirements.txt`

# Demo
* Open your editor of choice
* Be sure to be in the same folder where the repo is located, open terminal and run `python main.py`
* A game will run that showcases all features of the engine.

# Structure
```
.
├── actors          # Has the actor base and its subclasses.                 
├── components      # Has the component base class all the utility classes used by the actors.
├── audio           # Has classes to handle sounds and music.
├── core            # Has classes that are the backbone of the engine.
└── demo            # Has a game that showcases all the features of the engine.
```

# Usage
* `core/game.py` is where you'll create all instances of your game.
* `main.py` is where the main loop is defined. It come with pre-defined code,
    make sure to keep it and build on top of it as needed.
* This is optional, but you can create a folder called `game` where you put all your defined classes
    and keep it separated from the engine code. 

# Features
This engine supports:  
* Sprites rendering
* Animated sprites rendering
* Single animated sprite rendering (one image that has multiple frames)
* Input handling (mouse and keyboard)
* Sounds and music
* Tilemap rendering
* Animated tilemap rendering
* Collision detection
* Tiles collision detection
* Camera

# Upcoming features
* Fonts rendering
* HUD screens
* Perfect pixel collision
* Particles 
* Levels
* and many more