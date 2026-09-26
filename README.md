# 3D C++ Physics Playground

A low-level 3D physics sandbox built in C++ using [Raylib](https://www.raylib.com/). This project serves as a lightweight framework for testing custom character movement, vector math, and frame-rate independent engine mechanics.

## Features

- **Vector-Based Acceleration**: Multi-directional movement with normalized diagonal input vectors.
- **Momentum & Friction**: Custom drag calculation for smooth horizontal deceleration.
- **Vertical Physics**: Jump dynamics, gravity acceleration, and floor collision detection.
- **3D Camera Tracking**: Smooth perspective camera tracking synchronized with player movement.

## Controls

- **W / A / S / D**: Move (Accelerate)
- **SPACE**: Jump

## Tech Stack & Requirements

- **Language**: C++17
- **Framework**: Raylib
- **Platform**: macOS (Apple Silicon / Intel)
- **Compiler**: `clang++`

## Build & Run

Ensure Raylib is installed via Homebrew (`brew install raylib`).

```bash
clang++ main.cpp -std=c++17 -lraylib -L/opt/homebrew/lib -I/opt/homebrew/include -o app && ./app

