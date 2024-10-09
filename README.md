# Snake Game in Python

This project is a recreation of the classic Snake game using Python's turtle graphics library. The game includes functionalities for controlling the snake, growing it upon food consumption, and tracking the player's score. It's an excellent project for beginners looking to learn about object-oriented programming and game development in Python.

## Files

1. <b>main.py</b>: The main script to run the game. It initializes the game screen, listens for keyboard inputs, and controls the game loop.
2. <b>snake.py</b>: Contains the Snake class, which handles the snake's movement, growth, and direction control.
3. <b>food.py</b>: Manages the food object, which randomly appears on the screen and is consumed by the snake.
4. <b>scoreboard.py</b>: Tracks the player's score and displays it on the screen. It also handles the "Game Over" message.

## How to Play

1. Run main.py to start the game.
   
2. Use the arrow keys to control the snake's movement:<br>
     a. Up: Move the snake up.<br>
     b. Down: Move the snake down.<br>
     c. Left: Move the snake left.<br>
     d. Right: Move the snake right.
   
3. Eat the food that randomly appears on the screen to grow the snake and increase your score.
4. Avoid colliding with the walls or the snake's own body, or the game will end.
   
## Dependencies

1. Python 3.x
2. turtle module (part of the Python standard library)
   
## How to Run

Simply run the main.py script:

```
python main.py
```

## Future Improvements

1. Adding levels or increasing difficulty as the snake grows.
2. Implementing high score tracking.
3. Adding sound effects for a more engaging experience.
