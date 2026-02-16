# Cub3d

🧭 A Wolfenstein-inspired 3D game built with raycasting.

## 📖 Description

Cub3d is a simple 3D graphics group project developed as part of the 42 curriculum. The goal of this project is to explore the fundamentals of computer graphics by implementing a raycasting engine from scratch in C, inspired by early 3D games such as *Wolfenstein 3D*.

The program renders a pseudo-3D environment using a 2D map, simulating depth and perspective without relying on modern 3D libraries.

---

## 🚀 Features

* Real-time 3D rendering using raycasting
* Textured walls
* Smooth player movement
* Collision detection
* Keyboard controls
* Configurable maps

---

## 🎮 Controls

| Key       | Action                  |
| --------- | ----------------------- |
| `W` / `S` | Move forward / backward |
| `A` / `D` | Strafe left / right     |
| `←` / `→` | Rotate camera           |
| `ESC`     | Exit game               |

---

## 🛠 Installation

### Requirements

* GCC / Clang
* Make
* MiniLibX
* Unix-based system (Linux / macOS)

### Build

```bash
make
```

---

## ▶️ Usage

```bash
./cub3D maps/map.cub
```

---

## 🧠 How It Works

Cub3d uses a **raycasting algorithm** to simulate a 3D environment:

* The world is represented as a 2D grid map
* Rays are cast from the player's position
* Each ray detects wall intersections
* Distance calculations determine wall height
* Textures are applied based on hit position

This technique creates the illusion of depth and perspective, similar to early FPS engines.

---

## 📂 Project Structure

```
Cub3d/
├── src/            # Source files
├── includes/       # Header files
├── textures/       # Wall textures
├── maps/           # Map configuration files
├── Makefile
└── README.md
```

---

## 🎯 Learning Objectives

This project focuses on:

* Graphics programming fundamentals
* Raycasting mathematics
* Event handling
* Memory management
* Low-level rendering techniques
* Algorithm optimization

---

## 🏆 Conclusion

Cub3d is an introduction to graphics programming and real-time rendering. It demonstrates how mathematical concepts can be used to build immersive visual experiences from scratch.

---

## 👤 Author

chuchard and nileempo – 42 Students
