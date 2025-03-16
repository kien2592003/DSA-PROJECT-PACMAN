Pac-Man AI Game (DSA Project)

Overview

This project is a Pac-Man-inspired game implemented in Java. It features AI-driven ghosts (Ghouls) that use different pathfinding algorithms like Breadth-First Search (BFS) and Dijkstra's Algorithm to chase the player. This project was developed as part of a Data Structures and Algorithms (DSA) course.

Features

Classic Pac-Man gameplay mechanics

Intelligent ghost behavior using BFS and Dijkstra's Algorithm

Object-oriented design with clear separation of game logic and AI behaviors

Implemented in Java with an Eclipse project structure

Project Structure

dsa_project/
├── src/
│   ├── game/                 # Core game logic
│   │   ├── GameLogic.java
│   │   ├── MazeLoader.java
│   │   ├── PacManGame.java
│   │   ├── PacManKeyListener.java
│   ├── GhoulBehaviours/      # AI behaviors for ghosts
│   │   ├── BFSGhoulBehavior.java
│   │   ├── DijkstraGhoulBehavior.java
│   ├── Model/               # Game entity models
│       ├── PacMan.java
│       ├── Ghoul.java
├── bin/                     # Compiled Java class files
├── .classpath               # Eclipse project configuration
├── .project                 # Eclipse project metadata

Setup and Installation

Prerequisites

Java Development Kit (JDK) 8 or higher

Eclipse IDE (recommended) or any Java IDE

Steps to Run the Game

Clone this repository:

[git clone https://github.com/yourusername/dsa-pacman-game.git
cd dsa-pacman-game
](https://github.com/kien2592003/DSA-PROJECT-PACMAN.git)

Open the project in Eclipse:

Select File > Open Projects from File System

Choose the extracted project folder

Click Finish

Run PacManGame.java as a Java Application.

Contributors

Le Trung Kien – Developer

License

This project is licensed under the MIT License - see the LICENSE file for details.

Future Improvements

Implement A* pathfinding for smarter ghost movement

Add power-ups and special abilities for Pac-Man

Improve game UI and animations

