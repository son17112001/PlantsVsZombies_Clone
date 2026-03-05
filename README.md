# Plants vs Zombies Clone (Unity)

A 2D fan-made clone of the classic **Plants vs. Zombies** game, built using **Unity** and the **Universal Render Pipeline (URP)**. This project serves as an educational resource for learning game mechanics, state machines, and Unity animation systems.

## 🎮 Key Features

- **Classic Gameplay:** Protect your home from waves of zombies using various plants.
- **Plant Variety:** Includes Peashooter, Sunflower, Cherry Bomb, Wall-nut, and more.
- **Zombie Types:** Multiple zombie variants including Normal, Conehead, and Newspaper zombies.
- **Grid-Based Mechanics:** Custom grid management system for plant placement.
- **Animation System:** Comprehensive animations for both plants (idle, shooting, exploding) and zombies (walking, eating, dying).
- **Audio System:** Integrated sound effects for shooting, eating, and background music.
- **UI & HUD:** Functional game HUD, progress bars, and inventory system.

## 🛠 Tech Stack & Tools

- **Engine:** Unity 2022+ (recommended)
- **Render Pipeline:** Universal Render Pipeline (URP)
- **Text System:** TextMesh Pro
- **Version Control:** Git

## 📂 Project Structure

- `Assets/Scripts/Mechanic`: Core game logic including managers, factories, and pooling systems.
- `Assets/Scripts/Plant Type`: Individual behaviors for different plant species.
- `Assets/Scripts/ZombieType`: Behaviors and state machines for different zombie variants.
- `Assets/Prefab`: Pre-configured game objects for quick deployment.
- `Assets/Animation`: Animation controllers and clips.
- `Assets/Audio`: Sound assets and music.

## 🚀 Getting Started

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/tiin1705/PlantsVsZombies_Clone.git
    ```
2.  **Open with Unity Hub:** Add the cloned folder and open it with the appropriate Unity version.
3.  **Ensure URP Setup:** Check `Project Settings > Graphics` to ensure the URP asset is assigned.
4.  **Play:** Open `Assets/Scenes/SampleScene.unity` and hit the Play button!

## 📜 Credits
Developed for educational purposes. Original game concept by PopCap Games.
