# Frogger Game

A classic arcade-style Frogger game implementation using C++ and OpenGL/GLUT.

## Description
This is a modern recreation of the classic Frogger arcade game where players guide a frog across busy roads and dangerous rivers. The game features multiple levels of increasing difficulty, high score tracking, and smooth OpenGL graphics.

## Features
- Multiple game levels with increasing difficulty
- High score system with persistent storage
- Smooth animations and graphics
- Menu system with multiple options
- Lives system and score tracking
- Obstacle and collision detection
- River crossing mechanics with moving logs

## Prerequisites
- C++ compiler with C++11 support
- OpenGL
- GLUT (or freeGLUT)
- Windows OS (current version)

## Building the Project
1. Ensure you have all prerequisites installed
2. Clone the repository
3. Compile using your preferred C++ compiler
4. Link against OpenGL and GLUT libraries

Example compilation with g++:
```bash
g++ -o Frogger.exe main.cpp Game.cpp Graphics.cpp Input.cpp -lopengl32 -lglu32 -lfreeglut
```

## Controls
- **Arrow Keys** or **WASD**: Move the frog
- **ESC**: Pause/Menu
- **Enter**: Select menu options
- **P**: Pause game
- **R**: Reset frog position

## Game Elements
- **Roads**: Avoid cars and other vehicles
- **River**: Use logs to cross safely
- **Safe Zones**: Rest areas between obstacles
- **Score Display**: Current score and high scores
- **Lives**: Represented by heart icons

## Game States
- Menu
- Playing
- High Scores
- Game Over

## Scoring System
- Points awarded for successful crossings
- Bonus points for completing levels
- High scores saved automatically


## License
This project is available for educational and personal use.

## Acknowledgments
- Original Frogger game concept
- OpenGL and GLUT communities
- Contributors and testers