# Rock Dodge Game

A 2D arcade-style survival game developed in C++ using OpenGL and GLUT.

## Overview

Rock Dodge Game is a simple yet engaging game where the player controls a character and must avoid falling rocks for as long as possible. The score increases every time a rock successfully passes the player without collision.

The project demonstrates fundamental game development concepts including real-time rendering, collision detection, user input handling, animation, and game state management.

## Features

- Character movement using keyboard arrow keys
- Randomly generated falling rocks
- Multiple obstacle designs
- Collision detection system
- Real-time score tracking
- Game Over screen
- Restart functionality
- 60 FPS game loop

## Technologies Used

- C++
- OpenGL
- GLUT (OpenGL Utility Toolkit)

## Controls

| Key | Action |
|------|---------|
| ← | Move Left |
| → | Move Right |
| R | Restart Game |
| ESC | Exit Game |

## Game Mechanics

- Rocks spawn randomly at the top of the screen.
- The player must dodge incoming obstacles.
- The score increases whenever a rock leaves the screen without hitting the player.
- The game ends immediately when a collision occurs.

## Project Concepts

This project demonstrates:

- Computer Graphics Fundamentals
- OpenGL Rendering
- Event-Driven Programming
- Collision Detection
- Animation and Game Loops
- Random Object Generation
- Real-Time User Interaction

## How to Build and Run

### Requirements

- C++ Compiler
- OpenGL
- GLUT / FreeGLUT

### Compile Example (g++)

```bash
g++ main.cpp -o RockDodgeGame -lglut -lGL -lGLU
```

### Run

```bash
./RockDodgeGame
```
