# Blazor WebAssembly Connect Four Game
This repository contains a Connect Four game built using Blazor WebAssembly. Connect Four is a popular two-player connection board game in which the players choose a color and then take turns dropping colored discs into a seven-column, six-row vertically suspended grid. The pieces fall straight down, occupying the lowest available space within the column. The objective of the game is to be the first to form a horizontal, vertical, or diagonal line of four of one’s own discs.

## Features
#### Two Player Mode: 
The game supports two players playing on the same device, taking turns to make their move.
![](https://github.com/jashnatfinthrive/Connect4/blob/master/Playersturns.gif)
#### Game State Management: 
The game state is managed effectively allowing for a smooth gameplay experience.
![](https://github.com/jashnatfinthrive/Connect4/blob/master/Tie.png)
#### Interactive UI: 
The game has a user-friendly and interactive UI, making the game fun and easy to play.
![](https://github.com/jashnatfinthrive/Connect4/blob/master/Wins.gif)

It also has error handling like column full where error handler indicator is simple, and uses the Bootstrap CSS framework to display an error in danger mode:
![](https://github.com/jashnatfinthrive/Connect4/blob/master/Columnfull.gif)
## Technologies Used
#### Blazor WebAssembly: 
This project is a demonstration of the capabilities of Blazor WebAssembly. Blazor WebAssembly is a single-page app framework for building interactive client-side web apps with .NET and C# instead of JavaScript. Blazor WebAssembly runs on the client in the web browser using WebAssembly.

# Summary
Learned a lot about Blazor and built a neat little game. Here are some of the skills learned:

* Created a component
* Added that component to the home page
* Used dependency injection to manage the state of a game
* Made the game interactive with event handlers to place pieces and reset the game
* Wrote an error handler to report the state of the game
* Added parameters to the component

This project serves as a practical example of Blazor WebAssembly in action and can be a valuable resource for those learning about the framework. Contributions to improve this project are welcome!
