# Asteroids Game

**Asteroids** is a classic 1979 arcade game recreated using Python and Pygame. Pilot your spaceship through a hazardous asteroid field and blast them into smaller pieces — but beware! The more you shoot, the faster they get!

---

## 🎮 Features

- 🛸 **Classic Gameplay**: Navigate and destroy asteroids like the original arcade game
- 💥 **Asteroid Splitting**: Large → medium → small
- 🎯 **Smooth Controls**: Responsive ship movement and rotation
- 🔄 **Realistic Collisions**: Custom circular collision detection
- ⏫ **Progressive Difficulty**: Each split increases asteroid speed

---

## 🕹️ How to Play

Control your spaceship using the following keys:

- ⬆️ **Up Arrow**: Accelerate (thrust)
- ⬅️➡️ **Left/Right Arrows**: Rotate the ship
- 🔫 **Spacebar**: Fire projectiles

---

## 🎯 Game Objective

Destroy all asteroids without getting hit. When you shoot an asteroid:

- 🪨 **Large asteroid** → splits into **2 medium ones**
- 🪨 **Medium asteroid** → splits into **2 small ones**
- 🪨 **Small asteroid** → is completely destroyed
- 🔺 **Split asteroids** move **1.2× faster** than the original

The more you shoot, the harder it gets! ☄️

---

## 📦 Requirements

- Python 3.7 or higher
- pip (Python package installer)
- Pygame (automatically installed with the steps below)

---

## 🚀 Installation

```bash
git clone https://github.com/your_username/asteroids-game.git
cd asteroids-game
pip install -r requirements.txt
python main.py
