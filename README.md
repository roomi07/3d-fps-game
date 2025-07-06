# 🔫 Doom-Inspired 3D FPS Game in Python

This is a retro-style **first-person shooter (FPS)** game inspired by the legendary **Doom**, built entirely using **Python** and **Pygame**. It features raycasting-based 3D rendering, custom weapon animations, enemy AI, pathfinding, a fully designed level, and dynamic victory/game over screens.

## 🎮 Game Features

- ✅ **Real-Time Raycasting Engine** for a pseudo-3D environment
- 🔫 **Weapon System** with smooth sprite-based animation
- 🧟‍♂️ **Enemy AI** including Soldiers, CacoDemons, and CyberDemon (Boss)
- 🧠 **Pathfinding Logic** for enemies to chase and attack the player
- 💥 **Collision Detection** and damage system
- 🗺️ **Hand-Designed Level** with different wall textures and enemy placements
- 🩸 **Blood screen feedback** on player damage
- 🏆 **Victory Screen** when all enemies are defeated
- 💀 **Game Over Screen** when player health drops to 0
- 🌄 **Dynamic Sky Movement** based on player rotation
- 🖼️ **Translucent Victory Overlay** for a cinematic ending

## 🧱 Built With

- Python 3.x
- Pygame
- Object-Oriented Programming
- Raycasting technique for 3D rendering

## 📁 Project Structure

```bash
doom-fps/
│
├── main.py                  # Game loop and setup
├── settings.py              # Game constants and configuration
├── player.py                # Player control, movement, and aiming
├── map.py                   # Level map layout and wall definitions
├── raycasting.py            # Raycasting engine for 3D rendering
├── sprite_object.py         # Static and animated sprite handling
├── object_renderer.py       # Wall, sky, HUD, and screen drawing
├── object_handler.py        # Manages all NPCs and animated/static sprites
├── npc.py                   # Enemy behavior, animations, pathfinding
├── pathfinding.py           # BFS-based pathfinding logic
├── weapon.py                # Weapon drawing and animation
└── resources/               # All assets (textures, sprites, sounds)
