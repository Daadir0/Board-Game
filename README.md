# 3D Board Game (Unity Project) 🎲🛠️

This is a simple 3D board game developed in Unity as a practice project to learn game development fundamentals.  
Custom meshes for the board and pieces were modeled in Blender, and the gameplay is built entirely in C# and Unity.

## How to Play
- **Move Pieces**: Double **left-click** on your movable pieces.
- **Red Pieces**: Only red pieces can be moved during your turn.
- **Gold Pieces**: When a piece turns gold, you can claim points by double **right-clicking** — but only after the round ends.
- **Ending a Round**: The round ends when a player lands in an empty hole.

## Game Rules
- The board contains **12 holes** in total — **6 holes per player**.
- Each hole starts with **4 balls**.
- On your turn, select any hole on your side and collect all the balls.
- Distribute the balls **one by one** into the following holes in an **anticlockwise** direction, starting from the hole after the one you picked.
- If you end your move in a non-empty hole, collect all the balls there and continue spreading.
- If you end in an **empty hole**, your turn ends.
- **Empty Holes**: Once a hole is emptied, it becomes a *point hole*.  
  If the hole gathers **4 balls again** later, you can claim it as a point for your side.

## Features
- Custom 3D assets modeled in Blender.
- Interactive gameplay using Unity’s Event System.
- Turn-based game logic fully handled in C#.
- Basic 3D UI for piece interactions and points.

## Technologies Used
- Unity
- Blender (for 3D models)
- C#

## License
This project is open-source and free to explore or modify.
