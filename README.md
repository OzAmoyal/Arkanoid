# Arkanoid Game
An implementation of the nostalgic Arkanoid brick breaker game using Java.
Arkanoid is a classic brick-breaking game where the player controls a paddle to deflect a ball against a wall of bricks. The goal of the game is to clear all of the bricks by breaking them. The player can lose the game by letting the ball fall below the bottom of the screen.
## Project Structure
The project is structured using the Model-View-Controller (MVC) design pattern. The model represents the game state, such as the position of the paddle, the ball, and the bricks. The view is responsible for displaying the game state to the user. The controller is responsible for handling user input and updating the game state.

The listener design pattern is used in the project to decouple the classes that listen for events from the classes that generate events. For example, the BallRemover class listens for the BallRemove event, which is generated by the Ball class. This allows the BallRemover class to be independent of the Ball class, which makes the code more modular and easier to maintain.

The project is divided into folders to organize the code and make it easier to find. For example, the game folder contains the classes that represent the game state, such as the paddle, the ball, and the bricks. The animations folder contains the classes that represent animations in the game, such as the countdown animation and the win animation. This organization makes it easier to find the code that you are looking for and to understand how the code works.

## Features

- Supports multiple levels
- Interactive Gameplay
- Score Tracking
- Responsive Controls
- Pause and Resume
- Game Over and Victory Screens

## Technologies

* Java 8
* Biuoop-1.4 GUI Library (included)

## Usage

1. Download the project from GitHub.
    ``` git clone https://github.com/OzAmoyal/Arkanoid.git ```
2. Open a terminal window and navigate to the project directory.
3. Run the following command to compile and run:
```ant run``` to play a usual 4 levels implemented or
```ant -Dargs="1 2 3 4 ...."``` to run to select a specific level order.

## Controls

* Use the arrow keys to move the paddle.
* Press 'P' to pause the game and resume it.

## Screenshots:
<img src ="https://user-images.githubusercontent.com/93612510/171703696-a9af6ffd-b0c2-4afd-9605-49df49ec1192.png" width=400 height=300 />
