Asteroids Game
A classic arcade video game from 1979 where you control a spaceship in an asteroid field. The objective is to destroy all asteroids while avoiding being hit. When you shoot a large asteroid, it splits into smaller asteroids, creating more challenges.
🚀 About the Project
A classic Asteroids arcade game built with Python and Pygame. Pilot your spaceship through an asteroid field, shooting asteroids that split into smaller, faster pieces when hit.
✨ Features
Classic Gameplay: Navigate your ship and destroy asteroids
Asteroid Splitting: Large asteroids break into medium ones, medium into small ones
Smooth Controls: Responsive ship movement and rotation
Collision Detection: Realistic physics-based collisions
Progressive Difficulty: Asteroids become faster and more numerous as they split
Prerequisites
Python 3.7 or higher
pip (Python package installer)
📦 Installation and Execution
Follow these steps to get the game running on your local machine:
Clone the repository:
git clone https://github.com/your-username/asteroids-game.git
cd asteroids-game


Create and activate a virtual environment (recommended):
python -m venv venv
# On Windows
.\venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate


Install dependencies:
pip install pygame


Run the game:
python main.py


🎮 How to Play
Arrow Keys: Move and rotate your ship
↑ Up Arrow: Thrust forward
← → Left/Right Arrows: Rotate ship
Spacebar: Shoot bullets
Objective: Destroy all asteroids without getting hit
🕹️ Game Mechanics
Large Asteroids: Split into 2 medium asteroids when shot
Medium Asteroids: Split into 2 small asteroids when shot
Small Asteroids: Destroyed completely when shot
Split asteroids move 1.2x faster than their parent asteroid
📂 Project Structure

asteroids-game/
├── main.py             # Main game loop
├── asteroid.py         # Asteroid class
├── player.py           # Player ship class
├── shot.py             # Bullet/shot class
├── circleshape.py      # Base circle collision class
├── constants.py        # Game constants
└── README.md           # This file


⚙️ Technical Details
Engine: Pygame
Language: Python 3
Physics: Custom collision detection using circular boundaries
Graphics: Vector-based rendering

