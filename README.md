<h1 align="center">Cub3d</h1>

<p align="center">
	<b>🎮 <i>A Wolfenstein-inspired 3D game built with raycasting.</i></b><br>
</p>

<p align="center">
  <img alt="Language" src="https://img.shields.io/badge/Language-C-blue"/>
  <img alt="Status" src="https://img.shields.io/badge/Status-Completed-success"/>
  <img src="https://img.shields.io/badge/Grade-100%2F100-success"/>
  <img alt="42" src="https://img.shields.io/badge/School-42-black"/>
</p>

---

## 📑 Table of Contents

* [📖 Description](#-description)
* [🚀 Features](#-features)
* [🎮 Controls](#-controls)
* [▶️ Installation & Usage](#-installation--usage)
* [🧠 How It Works](#-how-it-works)
* [📂 Project Structure](#-project-structure)
* [🎯 Learning Objectives](#-learning-objectives)
* [🏆 Conclusion](#-conclusion)
* [👤 Authors](#-authors)

---

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

## ▶️ Installation & Usage

### Requirements:
* GCC / Clang
* Make
* MiniLibX
* Unix-based system (Linux / macOS)

### How to run the program:
1. Build:
	```bash
	make
	```

2. Execute:
	```bash
	./cub3D tests/file.cub
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
├── minilibx		# Small C library used for rendering graphics
├── src/            # Source files
├── includes/       # Header files
├── textures/       # Wall textures
├── tests/          # Map configuration files
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

## 👤 Authors

chuchard and nileempo – 42 Students
