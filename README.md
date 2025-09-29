# cub3d

A **42 School** project to create a 3D game engine inspired by **Wolfenstein 3D** using **raycasting**.  
The goal is to learn about graphics programming, mathematics (vectors, rays), and efficient rendering.

---

## Project Overview
- Render a 3D world from a 2D map using **raycasting**.
- Implement basic movement and camera rotation.
- Use the **MiniLibX** library for graphics.
- Parse `.cub` map files with textures and configuration.

---

## Features
- 3D projection using raycasting.
- Movement:
  - Forward / Backward
  - Strafe left / right
  - Rotate camera left / right
- Map parsing with:
  - Walls and empty spaces
  - Player spawn point
  - Textures for walls (N, S, E, W)
  - Floor and ceiling colors
- Collision detection.
- Smooth gameplay at real-time speed.

---

## Usage
### 1. Clone the repository
```bash
git clone https://github.com/your-username/cub3d.git
cd cub3d
```
### 2. Build
```bash
make
```
### 3. Run
```bash
./cub3d maps/example.cub
```
### 4. Controls

W / A / S / D → Move player

← / → → Rotate camera

ESC → Exit game

