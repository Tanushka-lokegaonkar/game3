# ✈️ Fighter Plane Game

A 2D horizontal-scrolling arcade shooter game developed in Python using the **Pygame** library. Take control of your fighter plane, dodge incoming enemy planes by soaring or diving, and blast them out of the sky!

---

## 🎮 How to Play & Controls

Launch your fighter jet and survive the endless waves of enemies. The game features dynamically increasing speed to challenge your reflexes!

### Keyboard Controls

| Key | Action | Description |
| :--- | :--- | :--- |
| **`▲ Up Arrow`** | **Jump / Fly Upwards** | Performs a parabolic loop upwards to dodge low-flying enemy planes. |
| **`▼ Down Arrow`** | **Duck / Dive Downwards** | Performs a dipping maneuver downwards to avoid high-flying enemy hazards. |
| **`▶ Right Arrow`** | **Shoot / Fire Laser** | Fires a projectile forward to destroy incoming enemy aircraft and score bonus points. |

### Mouse Controls
* **`Left Click` (Anywhere on the screen):** Used in the **Welcome Menu** to start the game loop.

---

## 🚀 Game Rules & Mechanics

1. **Survival:** You start the game with **3 Lives**. 
2. **Scoring:** - Your score increases automatically by **+1 point** per game tick just for staying alive.
   - Destroying an enemy plane with your bullets awards a massive **+10 points** bonus.
3. **Collisions:**
   - Hitting an enemy plane directly causes structural damage, costing you **1 Life**.
   - Colliding with enemies clears that specific enemy but resets the progressive speed modifier temporarily.
4. **Dynamic Difficulty:** The background scrolling and enemy movement speed progressively accelerate over time (`speed_increase_rate`), pushing your reaction speeds to their limits.
5. **Game Over:** Once your lives reach `0`, the game displays a "Game Over" screen for 2 seconds and safely exits.

---

## 🛠️ Installation & Setup Guide

Follow these simple steps to download, install, and run the game locally on your machine.

### Prerequisites
Make sure you have **Python 3.x** installed. You can download it from [python.org](https://www.python.org/).

### 1. Clone the Repository
Open your terminal or command prompt and clone this repository using Git:
```bash
git clone [https://github.com/Tanushka-lokegaonkar/game3.git](https://github.com/Tanushka-lokegaonkar/game3.git)
cd game3
```

### 2. Install Dependencies
This project relies on the pygame library. Install it using pip:

```Bash
pip install pygame
```

3. Verify Directory Structure

Ensure your local project directory structure matches the required game assets paths:

```text
game3/
├── assets/
│   └── player1.png
├── plane/
│   ├── BG1.png
│   ├── BG2.png
│   ├── Bullet (1).png
│   ├── enemy1.png
│   ├── enemy2.png
│   ├── enemy3.png
│   ├── Fly (1).png
│   ├── Fly (2).png
│   └── hit.wav
└── main.py (or your game script name)
```

4. Run the Game
   
Execute the game script using Python:
```bash
python main.py
```

## 🔗 Project Links

* **Live Deployment:** [![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)](https://game3-coral.vercel.app/) — [Play the game directly in your browser!](https://game3-coral.vercel.app/)

* **GitHub Repository:** [![GitHub repo](https://img.shields.io/badge/GitHub-Repository-blue?style=flat-square&logo=github)](https://github.com/Tanushka-lokegaonkar/game3) — View source code and project updates.


* **Original Source Code:** [![GitHub source](https://img.shields.io/badge/GitHub-Source%20Code-darkgreen?style=flat-square&logo=github)](https://github.com/Tanushka-lokegaonkar/1ts-game) — Explore the initial development files and template branches.
