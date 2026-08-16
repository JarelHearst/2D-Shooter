**2D Shooter
**
A 2D top-down shooter built in Unity using C#. Players move through multiple levels, defeat waves of enemies, earn points, and progress through increasingly challenging stages.

This project was created to practice and demonstrate gameplay programming concepts including player controls, projectile-based combat, enemy spawning, health and damage systems, UI management, scoring, and multi-scene level progression.

**🎮 Gameplay**

The player controls a ship/character while aiming and firing projectiles at incoming enemies. Enemies can spawn dynamically throughout the level, and defeating them increases the player's score.

Each level tracks the number of enemies defeated and can trigger a victory state once the required number of enemies has been eliminated.

The game contains:

• Main Menu
• Level 1
• Level 2
• Level 3
• Victory and Game Over states
• Persistent high-score tracking

**🕹️ Controls**
Action	Keyboard / Mouse
Move	WASD / Arrow Keys
Aim	    Mouse
Shoot	Left Mouse Button
Pause	Configured through Unity's Input System

The project also includes support for additional input devices through Unity's Input System, including gamepads.

**✨ Features**

• 2D player movement and aiming
• Projectile-based shooting system
• Enemy spawning system
• Enemy health and damage
• Player health and lives support
• Team-based damage detection
• Score tracking
• Persistent high-score system using PlayerPrefs
• Multiple playable levels
• Level victory conditions
• Game Over system
• Pause menu
• Main menu and UI navigation
• Custom cursor support
• Particle/effect spawning for hits, victory, and game-over events
• Unity Input System support
• Keyboard, mouse, and gamepad input support

**🧠 Systems**
Player Controller

The player controller handles movement and aiming through Unity's Input System.

The controller was designed to support several movement styles:

• Horizontal movement
• Vertical movement
• Free-roam movement
• Asteroids-style physics movement

It also supports aiming toward the mouse or firing in the direction the player is facing.

**Shooting System
**
The shooting system creates projectile prefabs from configured spawn locations.

Projectile behavior includes:

• Configurable projectile speed
• Projectile lifetime
• Fire-rate control
• Multiple projectile spawn points
• Projectile effects
• Team-based damage detection

**Health & Damage
**
Characters and enemies use reusable Health and Damage components.

The system supports:

• Configurable health
• Maximum health
• Damage values
• Temporary invincibility
• Multiple lives
• Team IDs to prevent friendly fire
• Trigger and collision-based damage
• Hit effects
• Death behavior

**Enemy System**

Enemies use reusable components for movement, health, scoring, and destruction.

The EnemySpawner system allows levels to dynamically generate enemies and configure spawning behavior.

The Game Manager tracks defeated enemies and determines when the player has completed a level.

**Score System
**
Defeating enemies awards points that are tracked by the GameManager.

The game also stores the player's highest score using Unity's PlayerPrefs, allowing the high score to persist between sessions.

**UI System
**
The project contains a reusable UI management system responsible for:

• Main menu navigation
• Pause menu
• Score display
• High-score display
• Victory screen
• Game Over screen
• Scene loading
• UI page switching

**🗺️ Levels
**
The project currently contains four scenes:

MainMenu
Level1
Level2
Level3

Each playable level can define its own enemies, enemy spawners, victory requirements, and gameplay configuration.

**🛠️ Built With**

• Unity 6
• Editor 6000.5.6f1
• C#
• Unity Input System
• Unity 2D Physics
• TextMesh Pro
• Unity UI

**📁 Project Structure**

Assets/
├── Art/
├── Audio/
├── Prefabs/
├── Resources/
├── Scenes/
│   ├── MainMenu
│   ├── Level1
│   ├── Level2
│   └── Level3
│
└── Scripts/
    ├── Camera/
    ├── Enemies/
    ├── Health&Damage/
    ├── Player/
    ├── ShootingProjectiles/
    ├── UI/
    └── Utility/
    
**💻 Getting Started**

**Prerequisites
**
Install Unity Hub and a compatible Unity 6 editor.

The project was developed using:

Unity 6000.5.6f1

**Installation**

1. Clone the repository:

git clone https://github.com/JarelHearst/2D-Shooter.git

2. Open Unity Hub.
3. Select Add → Add project from disk.
4. Select the cloned 2D-Shooter folder.
5. Open the project using Unity 6000.5.6f1 or a compatible Unity 6 version.
6.Open: Assets/Scenes/MainMenu.unity
7. Press Play.
📸 Screenshots
Gameplay










**🎯 What I Practiced**

This project helped me gain additional experience with:

• Object-oriented programming in C#
• Component-based game architecture
• Unity's Input System
• Player movement and aiming
• Projectile mechanics
• Enemy spawning
• Collision detection
• Health and damage systems
• Game-state management
• Scene management
• UI programming
• Persistent data using PlayerPrefs
• Designing reusable gameplay components

**🚀 Future Improvements**

Possible additions to the project include:

• Additional enemy types
• Boss encounters
• More weapon types
• Power-ups
• Improved enemy AI
• Additional levels
• Sound and music improvements
• Controller-specific UI prompts
• Additional visual effects
• Expanded difficulty progression

👨‍💻 Developer

Jarel Hearst

Computer Science graduate and gameplay programmer focused on developing games with Unity and C#.

📄 License

This project was created for educational and portfolio purposes.
