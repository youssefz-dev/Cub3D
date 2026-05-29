# Cub3D

A lightweight 3D raycasting engine written in C, inspired by early first-person games such as Wolfenstein 3D.

This project explores real-time rendering techniques, computer graphics fundamentals, mathematical calculations, and game engine architecture using a custom raycasting implementation.

## Overview

Cub3D transforms a 2D map into a navigable 3D environment using raycasting techniques.

The project simulates a first-person perspective by projecting walls, applying textures, handling player movement, and rendering scenes in real time.

## Features

* Real-time 3D rendering
* Raycasting-based engine
* First-person camera
* Texture mapping
* Collision detection
* Player movement and rotation
* Custom map parsing
* Interactive environment rendering

## Technical Concepts

### Raycasting

* Ray generation
* Wall intersection detection
* Distance calculations
* Perspective projection

### Rendering Pipeline

* Wall rendering
* Texture mapping
* Frame generation
* Screen projection

### Mathematics

* Trigonometry
* Vector calculations
* Distance computation
* Angle normalization

### Engine Systems

* Game loop
* Event handling
* Input processing
* Rendering updates

## Controls

```text id="gk8tzm"
W     Move Forward
S     Move Backward
A     Move Left
D     Move Right
← →   Rotate Camera
ESC   Exit
```

## Architecture

The project is organized into several core systems:

* Map parser
* Rendering engine
* Raycasting module
* Texture manager
* Player controller
* Event handling system

## Technologies

* C
* MiniLibX
* Raycasting
* Computer Graphics
* Linux
* Real-Time Rendering

## Learning Outcomes

Through this project, I gained practical experience with:

* Computer graphics fundamentals
* Raycasting algorithms
* Real-time rendering
* Performance optimization
* Mathematical modeling
* Event-driven programming
* Graphics engine architecture

## Getting Started

```bash id="3k8h6y"
git clone <repository-url>
cd cub3d
make
./cub3D maps/map.cub
```

## Example Map

```text id="x7z31r"
111111111111
100000000001
100N00000001
100000000001
111111111111
```

## Project Context

This project was developed as part of the 42 curriculum and is designed to provide a practical understanding of computer graphics, rendering techniques, and real-time engine development.
