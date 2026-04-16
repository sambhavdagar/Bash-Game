# Bash-Game
A fully interactive, terminal-based platformer game developed entirely using Bash scripting. This project pushes the boundaries of standard shell scripting by utilizing escape sequences, array-based screen buffering, and real-time keyboard input detection to create a playable game with physics and procedural generation.
+1

🚀 Features
Real-Time Physics & Movement: Fluid player mechanics including left/right movement, jumping, and falling under gravity.

Procedural Level Generation: Dynamic 2D map generation utilizing characters to build the environment.

Collision Detection: Solid walls that block movement and deadly spikes that cause instant game over upon contact.


Item Collection & Combat: Collect coins to increase your score and gather ammo to shoot in four directions (W, A, S, D) or break blocks.

Multi-State UI: Features distinct screens including a Welcome Screen (with ASCII art), Running Game UI, Game Over Screen, and a Win Screen.


🗺️ Game Legend
The procedurally generated environment uses the following characters:

@ : Player 

# : Walls / Blocks 


$ : Coins (Score) 


* : Ammo 


^ : Spikes (Instant Death) 


% : Win Tile (Level Complete) 


🛠️ Technical Stack
Language: Bash Scripting 

Rendering: ANSI Escape Codes and Array-Based Screen Buffering for smooth, flicker-free terminal rendering.


Input Handling: Unix Terminal Input/Output configuration for non-blocking, real-time keystroke detection.


Algorithms: Random Number Generation for dynamic environments.

💻 How to Run
Open your Unix/Linux/macOS terminal.

Navigate to the project directory.

Make the script executable by running: chmod +x game.sh (Replace game.sh with your actual filename)

Run the game: ./game.sh
