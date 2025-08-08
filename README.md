September 2023

# TarZan - Free Roam RPG and Tower Defense Game

Test Progressive Assistant - Game Development using Unity (C#).

## Overview

**TarZan** is an engaging RPG and Tower Defense game developed using Unity and C#. The game allows players to explore a vast world filled with dynamic biomes, NPC interactions, wildlife, and challenging tower defense levels. The game world is procedurally generated using the **Wave Function Collapse** algorithm, providing a unique terrain for each playthrough. Enemies navigate the terrain using the **A\* Pathfinding** algorithm, ensuring they take the most efficient route to their target.

## Features

### General Features

- **Procedural Terrain Generation**: The world is procedurally generated using **Wave Function Collapse** to create diverse, explorable landscapes.
- **A\* Pathfinding**: Enemies follow the shortest path to their target, creating a more challenging and dynamic gameplay experience.
- **Free Roam & Tower Defense**: The game features a free roam mode where players explore biomes and tame animals, and a tower defense mode where players protect a tower from waves of enemies.
- **FPS Camera System**: The camera behaves as a first-person shooter (FPS), giving the player full control of movement and vision.

### Gameplay Features

- **Explorable Biomes**: The terrain includes multiple biomes with unique foliage, weather effects, and interactive elements.
- **NPC Interactions**: Players can speak with NPCs, including one located on top of a giant tree to start the tower defense game.
- **Animal Companions**: Tame animals to use as pets, which help during the tower defense and attack other wildlife.
- **Wave-based Tower Defense**: Each level increases enemy difficulty. The game uses A\* to generate a maze for the tower defense layout.
- **Boss Battles**: Battle with a dragon as the final boss. Defeating it leads to the victory page.

### Pathfinding & Maze Generation

- **A\* Pathfinding**: Enemies use A\* to navigate the generated terrain to reach their target. The maze used for tower defense also utilizes A\* to ensure the shortest path for enemy movement.

### Combat & Actions

- **Player Actions**: Players can move, sprint, jump, climb trees, punch, throw rocks, and grapple objects using a variety of controls (e.g., W, A, S, D for movement, Left Click for punch, etc.).
- **Combat System**: Players fight against enemies using their attack and defense attributes. Animals can also be tamed and used to fight enemies.

## Technologies Used

- **Unity**: Game development engine for building and rendering the game.
- **C#**: Programming language for scripting gameplay mechanics.
- **Wave Function Collapse**: Algorithm used for procedural map generation.
- **A\* Pathfinding**: Algorithm used for enemy pathfinding.
- **Post Processing Effects**: For enhanced visuals and aesthetics.

## Gameplay

### Main Menu

- Display the **TarZan logo** and a scenic view of a **forest/grassland**.
- Interactive **buttons** for starting the game, changing settings, or exiting.
- **Fade animations** for smooth transitions between scenes.

### Settings Page

- **Dropdown menus** for adjusting **antialiasing** and **quality settings**.
- **Slider** for adjusting **volume**.
- **Toggle** for switching between fullscreen and windowed modes.

### Loading Page

- Shows an animation to indicate that the game is loading, providing feedback to the player.

### Game Page

- The **terrain system** includes multiple biomes and decorative elements such as trees, grass, and rocks.
- The player can explore, fight enemies, and interact with NPCs.
- The **tower defense mode** is activated by speaking to an NPC. Each wave of enemies will increase in difficulty.
- The player can **tame animals** to help during tower defense.

### Tower Defense Mechanics

- Use **A\* Pathfinding** to create a maze for the tower defense layout.
- Enemies will spawn in waves, with each wave becoming more difficult than the last.
- The player needs to defend the tower, which has limited health points. If the tower's health reaches 0, the game ends.

## Controls

- **Movement**: W, A, S, D
- **Punch**: Left Click
- **Sprint**: Left Shift
- **Jump**: Space
- **Climb**: Space (while near a tree)
- **Strafe**: A, D
- **Throw Rock**: X
- **Pause Game**: P
- **Grapple**: Right Click

## Enemy Behavior

- **Wildlife Animals**: Animals will follow the player if close, and can be tamed once defeated.
- **Enemies in Tower Defense**: Enemies spawn with increasing speed and health. They follow the shortest path to the tower using **A\* Pathfinding**.

## Final Boss - The Dragon

- The **Dragon** is a powerful final boss that can move, attack, and chase the player. Once defeated, the player is shown the **Victory Page**.

## Contributing

We welcome contributions to improve **TarZan**!

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes and commit them (`git commit -am 'Add feature'`).
4. Push to your fork (`git push origin feature-name`).
5. Submit a pull request.

## Acknowledgements

- **Wave Function Collapse** for procedural world generation.
- **A\* Pathfinding** for intelligent enemy navigation.
- **Unity** for providing a powerful game engine to build this project.
- **Design Patterns** and **Object-Oriented Programming** principles for structuring the game.
