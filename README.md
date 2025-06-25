Asteroids GameA classic arcade video game from 1979 where you control a spaceship in an asteroid field. The objective is to destroy all asteroids while avoiding being hit. When you shoot a large asteroid, it splits into smaller asteroids, creating more challenges.🚀 About the ProjectA classic Asteroids arcade game built with Python and Pygame. Pilot your spaceship through an asteroid field, shooting asteroids that split into smaller, faster pieces when hit.✨ FeaturesClassic Gameplay: Navigate your ship and destroy asteroidsAsteroid Splitting: Large asteroids break into medium ones, medium into small onesSmooth Controls: Responsive ship movement and rotationCollision Detection: Realistic physics-based collisionsProgressive Difficulty: Asteroids become faster and more numerous as they splitPrerequisitesPython 3.7 or higherpip (Python package installer)📦 Installation and ExecutionFollow these steps to get the game running on your local machine:Clone the repository:git clone https://github.com/your-username/asteroids-game.git
cd asteroids-game
Create and activate a virtual environment (recommended):python -m venv venv
# On Windows
.\venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
Install dependencies:pip install pygame
Run the game:python main.py
🎮 How to PlayArrow Keys: Move and rotate your ship↑ Up Arrow: Thrust forward← → Left/Right Arrows: Rotate shipSpacebar: Shoot bulletsObjective: Destroy all asteroids without getting hit🕹️ Game MechanicsLarge Asteroids: Split into 2 medium asteroids when shotMedium Asteroids: Split into 2 small asteroids when shotSmall Asteroids: Destroyed completely when shotSplit asteroids move 1.2x faster than their parent asteroid📂 Project Structureasteroids-game/
├── main.py             # Main game loop
├── asteroid.py         # Asteroid class
├── player.py           # Player ship class
├── shot.py             # Bullet/shot class
├── circleshape.py      # Base circle collision class
├── constants.py        # Game constants
└── README.md           # This file
⚙️ Technical DetailsEngine: PygameLanguage: Python 3Physics: Custom collision detection using circular boundariesGraphics: Vector-based rendering
