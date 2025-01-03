# sanke-game-with-Ai
Snake Game with AI using A* Pathfinding
This project is an implementation of the classic Snake game enhanced with an AI component. The AI uses the A* pathfinding algorithm to guide the snake towards the food while avoiding obstacles (its own body). The game is built using Pygame.

Features
Classic Snake Gameplay: A nostalgic rendition of the classic snake game.
AI-Powered Snake: The AI uses the A* algorithm for real-time pathfinding to navigate the grid and reach the food.
Dynamic Food Placement: Food spawns at random locations, avoiding the snake's current position.
Obstacle Avoidance: The snake avoids colliding with walls and its own body.


Requirements
Python 3.7+
Pygame
Installation


Clone the repository:
bash
Copy code
git clone https://github.com/coolkarni987/snake-game-ai.git
cd snake-game-ai


Install dependencies:
bash
Copy code
pip install pygame


Run the game:
bash
Copy code
python snake_game_ai.py

Controls
AI Mode: The game automatically moves the snake using the A* algorithm.
File Structure
snake_game_ai.py: Main game logic and AI implementation.
How the AI Works
The AI uses the A* algorithm to calculate the shortest path from the snake's head to the food. Key components:

Heuristic: Manhattan distance for path scoring.
Grid Navigation: Avoids walls and the snake's body by treating them as obstacles.
Dynamic Updates: Continuously recalculates the path as the game state changes.
Gameplay Screenshot
Add a screenshot or GIF of the game here.


Future Enhancements
Add difficulty levels.
Improve AI for handling situations with no possible path to the food.
Include manual controls for player mode.
Contributions
Contributions are welcome! Feel free to fork this repository and submit pull requests.

