# Space Shooter Game

A classic 2D arcade space shooter game built with **Python** and **Pygame**, featuring object-oriented architecture, pixel-perfect collision detection, and progressive wave-based gameplay.

## Overview
Players pilot a yellow starfighter to defend against incoming waves of enemy ships (red, green, and blue). As each wave is cleared, the game advances to higher levels with larger enemy fleets. The game ends if the player's health bar depletes or if five enemy ships breach the bottom boundary.

## Key Features
* **Object-Oriented Design (OOP):** Built using clean class inheritance (`Ship` base class extended by `Player` and `Enemy` subclasses, alongside a dedicated `Laser` class).
* **Pixel-Perfect Collision:** Uses `pygame.mask` overlap detection for accurate hitboxes between ships and lasers.
* **Dynamic Wave & Level System:** Automatically scales wave sizes as the player progresses through levels at a smooth 60 FPS.
* **Real-Time HUD:** Displays remaining lives, current level, and a dynamic health bar beneath the player's ship.

## Controls
* **`W` / `A` / `S` / `D`:** Move ship (Up, Left, Down, Right)
* **`Spacebar`:** Fire laser
* **Mouse Click (Main Menu):** Start game

## Tech Stack
* **Language:** Python 3
* **Library:** Pygame

## How to Run

1. **Clone the repository:**
```bash
git clone [https://github.com/abdumalikm454-cpu/space-game-.git](https://github.com/abdumalikm454-cpu/space-game-.git)
cd space-game-
Organize Image Assets:
1.Create a folder named pic inside the project directory and move all .png image files into it so the game can load the sprites properly:
mkdir pic
mv *.png pic/

2.Install Pygame:pip install pygame

3.Run the game:python main.py
