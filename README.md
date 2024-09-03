This project is a Java-based clone of the popular mobile game Flappy Bird, built using Swing for the graphical user interface and Java's built-in timers and event handling for game logic. The game faithfully recreates the core mechanics of the original Flappy Bird, where the player controls a bird that must fly between gaps in pipes without crashing. The bird is controlled using the spacebar, which allows it to "flap" and rise while gravity constantly pulls it downward.

Key Features:
Simple and Addictive Gameplay:

Bird Movement: The bird is constantly falling due to gravity, and the player must press the spacebar to flap and keep the bird in the air.
Pipes Generation: Pipes are randomly generated at regular intervals, creating gaps that the player must navigate through.
Collision Detection: The game ends when the bird hits a pipe or falls to the ground. This triggers a "Game Over" screen where the final score is displayed.

Score System: The player scores points by successfully passing through the gaps in the pipes. The current score is displayed on the screen in real-time.

Game Over & Restart: When the game ends, the player can restart by pressing the spacebar, which resets the bird's position, clears the pipes, and resets the score.

Technologies Used:
Java Swing: For rendering the game window and handling the graphical user interface.
Timers: Manage the game loop and control the timing of the pipe generation and game updates.
Key Event Handling: Capture the player's input to control the bird's movement and manage the restart functionality.
