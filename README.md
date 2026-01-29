# GalaxyWars_SpaceShooterGame

# Intoduction 🗣:

Galaxy Wars is a 2D space shooter game built in C++ with SFML featuring multi level gameplay, varied enemy behaviors, power ups, resource upgrades, and a multi phase boss fight. The game uses structured OOP design with inheritance, polymorphism, and state driven mechanics to manage gameplay systems and interactions.

# Project Goal 🎯:

The main goal was to implement core OOP principles inside a complete, working game instead of small isolated examples. The design centers on class hierarchy, polymorphic behavior, modular logic, and state driven flow.
The game mechanics connect directly with OOP structure. Each gameplay feature maps to a specific class responsibility. Base classes define shared behavior, while derived classes extend and specialize it. This keeps the system organized and easy to expand.

# OOP Implementation Highlights 📢:

• Deep inheritance hierarchy for GameObject, Enemy, Boss, PowerUp, and Projectile
• Runtime polymorphism for enemy movement patterns and power up effects
• Encapsulation of player stats, game state, and entity data through controlled interfaces
• Composition through a central GameManager that controls all entities and systems
• Separate UI controller classes for menus, pause, victory, and high scores
• Operator overloading used in the resource and upgrade system
• Dynamic memory management with explicit allocation and cleanup
• Custom exception classes for file and asset loading errors
• File I/O for persistent high score storage
• State based architecture for menu, setup, gameplay, pause, and victory screens

# Game Mechanics Included 👀:

• Three difficulty levels with changing enemy distributions
• Multiple enemy types with different movement logic
• Aggressive and tracking enemies at higher levels
• Multi phase boss with timed attack pattern changes
• Player upgrades through collected resources
• Power ups for shield, health, and fire rate control
• Collision detection across enemies, projectiles, and power ups
• Score tracking and leaderboard persistence
• Sound effects and level based music control

👩‍💻🤝 This project was developed by Mesum Ali and Haider Rizwan with shared responsibility for design and logic. We reviewed each other’s
modules and aligned class structures to keep the architecture consistent. The result is a game that serves as a practical OOP
implementation case, backed by real gameplay systems and structured code.
