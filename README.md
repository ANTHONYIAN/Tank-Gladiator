# 🚩 Tank Gladiators

> **The ultimate retro tank warfare experience.** > *Developed for the January 17th Game Showcase.*
<img width="1920" height="1080" alt="sample 1" src="https://github.com/user-attachments/assets/146aeb1b-aa23-437f-b4fa-ca669817257d" />

<img width="1920" height="1080" alt="sample 2" src="https://github.com/user-attachments/assets/e5222892-9884-48fc-a52f-47026de0bf66" />


<img width="1920" height="1080" alt="sample 3" src="https://github.com/user-attachments/assets/acb2baec-40d0-4a6c-80ac-ea3e775276e3" />

<img width="1920" height="1080" alt="sample 4" src="https://github.com/user-attachments/assets/f4587ca5-eb5e-489e-ab6a-7498b59980b6" />




## 🎮 About The Game

**Tank Gladiators** is a high-performance, 2D tactical shooter built entirely from scratch using **Vanilla JavaScript** and **HTML5 Canvas**. 

Inspired by 8-bit classics like *Battle City*, this project pushes the boundaries of modern web technologies without relying on game engines. It features a custom physics engine, smart enemy AI, and a fully synthesized **procedural audio system** that generates sound effects (explosions, lasers, power-ups) in real-time.

## ✨ Key Features

* **3 Distinct Game Modes:**
    * **🏰 Campaign:** Battle through **100 unique stages** of increasing difficulty.
    * **🤝 Co-op Mode:** Team up with a friend to defend the Eagle Flag.
    * **⚔️ PvP Warfare:** A competitive 1v1 deathmatch to destroy the enemy base.
* ** dynamic Audio System:** * Custom **Web Audio API** implementation.
    * No external MP3s! All sounds (Mario-style power-ups, heavy explosions, burning effects) are synthesized code.
* **Destructible Environments:**
    * Brick walls crumble with particle effects.
    * Steel blocks deflect standard bullets but melt under laser fire.
* **Smart AI:** Enemies hunt the player, strafe, and utilize different tactics based on their tank class.

## 🕹️ Controls

| Action | Player 1 (Green) | Player 2 (Blue) |
| :--- | :---: | :---: |
| **Move Up** | `W` | `↑` |
| **Move Left** | `A` | `←` |
| **Move Down** | `S` | `↓` |
| **Move Right** | `D` | `→` |
| **Fire** | `SPACE` | `ENTER` |

> **System Controls:**
> * `P` : Pause / Resume Game
> * `ESC` : Return to Main Menu

## ⚡ Power-Ups

Collect flashing tanks to gain tactical advantages:

* 💣 **Grenade:** Instantly destroys all visible enemies.
* ⏰ **Time Stop:** Freezes enemies in place for 10 seconds.
* 🛡️ **Shield:** Grants temporary invulnerability.
* 🧱 **Fortress:** Rebuilds concrete walls around your base.
* ❤️ **1-Up:** Grants an extra life.
* ⚡ **LASER BEAM (New!):** Fires a high-speed beam that melts steel and instakills enemies without breaking brick walls.

## 🛠️ Technical Stack

* **Language:** JavaScript (ES6+)
* **Rendering:** HTML5 Canvas API (2D Context)
* **Audio:** Web Audio API (Oscillators, Gain Nodes, Biquad Filters)
* **Physics:** Custom AABB Collision Detection
* **Build Tool:** Electron (for Desktop Executable)

## 🚀 How to Run

### Option 1: Play in Browser
Simply open `index.html` in any modern web browser (Chrome, Firefox, Edge).

### Option 2: Build Desktop App (Electron)
To run this as a standalone `.exe` application:

1.  Install Node.js.
2.  Run `npm init -y`
3.  Run `npm install electron --save-dev`
4.  Run `npm start`

--- *Built with code, fueled by nostalgia.*
