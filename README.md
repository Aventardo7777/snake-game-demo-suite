# Dual-Version Snake Game Demo Suite
<div align="center">
<img src="https://img.shields.io/badge/Python-3.6+-blue" alt="Python Version">
<img src="https://img.shields.io/badge/Frontend-HTML5%20Canvas-orange" alt="HTML Canvas">
<img src="https://img.shields.io/badge/License-MIT-green" alt="MIT License">
<img src="https://img.shields.io/badge/Game-Type-Snake%20Game-purple" alt="Game Type">
</div>

## 📖 Project Introduction
This repository contains two complete independent versions of classic Snake game, covering desktop local game and web online playable version:
1. **Python Pygame Desktop Version**: Object-oriented architecture, exquisite rounded UI, dark high-end color matching, progressive difficulty, collision detection & game restart mechanism;
2. **HTML5 Canvas Web Version**: Zero dependency pure front-end single file, support one-click online access via GitHub Pages, playable on PC/mobile browsers.

## ✨ Core Functional Features
### 🖥️ Pygame Desktop Version
- Object-oriented modular programming, clear game logic separation
- Custom rounded rectangle rendering engine, eliminate rough square UI
- Dynamic difficulty acceleration: score increases → game speed rises automatically
- Dual collision detection: wall collision & self-body collision
- Game over overlay mask, support Enter key quick restart
- Dark high-tech color palette, built-in multi-size Chinese font rendering

### 🌐 HTML Canvas Web Version
- Native Canvas drawing without any third-party JS libraries
- Fully responsive, compatible with PC & mobile browsers
- One-click online access via GitHub Pages without local environment
- Lightweight single-file integration, all logic encapsulated in snake.html

## 🧰 Environment Installation Guide
### 1. Run Pygame Desktop Snake
#### Step 1 Install Dependency
pip install pygame
#### Step 2 Clone Repository & Execute
git clone https://github.com/Aventardo7777/snake-game-demo-suite.git
cd snake-game-demo-suite
python snake_game.py
### 2. Play HTML Web Snake Online
Online Access Linkhttps://Aventardo7777.github.io/snake-game-demo-suite/
Directly open the link to play the web version snake game, no installation required.
Local Offline PlayDouble click snake.html file, open with Chrome/Edge browser.

## 📁 Standard Project File Tree
<img width="1081" height="273" alt="image" src="https://github.com/user-attachments/assets/6780d84f-cc51-4192-a24c-077154cd19c8" />

## ⚙️ Custom Modification Guide
### Pygame Version Adjustable Parameters
#### 1 .Window size: Modify WIDTH, HEIGHT = 800, 600
#### 2 .Initial speed: Adjust SPEED = 8
#### 3 .Color theme: Rewrite BG_COLOR / SNAKE_COLOR / FOOD_COLOR RGB values
#### 4 .Game grid size: Change CELL_SIZE = 20
### HTML Web Version Adjustable Parameters
#### Open snake.html, modify JS constants at the top of file to adjust speed, grid size, background color.

## 📜 Open Source License
This project is open-sourced under the MIT License.
All source code allows personal learning, modification, secondary development, commercial use without extra authorization, only retain the original open source statement of this repository.
