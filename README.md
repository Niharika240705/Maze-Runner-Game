**Maze Runner: AI-Powered Maze Game with Kruskal and Dijkstra Algorithms**

Maze Runner is a Python-based arcade game created with Pygame. The player navigates through an auto-generated maze using Kruskal’s algorithm for maze creation and Dijkstra’s algorithm for enemy pathfinding. Your goal: reach the exit and collect coins while avoiding a relentless AI enemy!

**Key Features:**
- **Maze Generation:** Utilizes Kruskal’s algorithm for creating unique, solvable mazes every run.
- **Pathfinding AI:** Enemy leverages Dijkstra’s algorithm to intelligently chase the player.
- **Gameplay Mechanics:**
  - Collect coins placed randomly in the maze.
  - Race against a timer and an enemy to reach the exit.
  - Dynamic difficulty and replayability with new mazes every game (seed-based).
- **Smooth Controls:** Arrow keys to move; escape/restart options in-game.
- **Visuals:** Clean grid-based design with distinct player, enemy, coin, and exit indicators.

**Tech Stack:** Python 3, Pygame

**How it works:**
- The maze is generated on startup using Kruskal’s algorithm.
- The player starts at one end, with coins and an enemy distributed at random.
- Every few frames, the enemy recalculates the shortest path to the player using Dijkstra’s algorithm, ensuring an engaging chase.
- Collect all coins and reach the exit before time runs out or before getting caught.

***


