This project is a Java-based clone of the popular mobile game Flappy Bird, built using Swing for the graphical user interface and Java's built-in timer and event handling for game logic. The project replicates the core mechanics of the original game, where a player controls a bird and must navigate through an endless series of pipes without hitting them. The bird automatically descends due to gravity, and the player must tap the spacebar to make the bird "flap" and rise, timing the flaps to pass through gaps between the pipes.

Key Features:
Start Screen with Play Button: The game begins with a graphical start screen featuring a "Play" button. Clicking the button initiates the game, providing a smooth transition from menu to gameplay.

Core Gameplay Mechanics:

Bird Movement: The bird descends automatically due to gravity and can be made to "flap" upward by pressing the spacebar.
Pipes Generation: Pipes are dynamically generated at random heights, creating a unique challenge each time.
Score System: The player earns points by successfully passing through the pipes, and the current score is displayed on the screen.
Collision Detection: The game ends when the bird collides with a pipe or the ground, triggering a "Game Over" screen with the player's score.

Game Over & Restart: After the game ends, the player can restart the game by pressing the spacebar again.

Technologies Used:
Java Swing: For creating the game window, rendering the graphics, and handling the user interface.
Timers: Used for the main game loop and to control the generation of pipes at regular intervals.
Event Listeners: To capture key presses and handle interactions with the play button and gameplay.
