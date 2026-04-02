# 🏎️ JavaScript Racing DOM Game

![JavaScript Racing DOM Game](javascript-racing.gif)

## 📖 Overview

**JavaScript Racing DOM Game** is a fast-paced, browser-based racing game where players control a car and avoid incoming obstacles to achieve the highest possible score. Built using **HTML5, CSS3, and Vanilla JavaScript**, this game delivers smooth gameplay, responsive controls, and engaging visual effects without relying on any external game engine.

---

**Live Demo** : https://gauravaswal98.github.io/Java-script-Car-Racing-Game/

## 🚀 Features

- **Dynamic Gameplay** – Dodge enemy cars while navigating a continuously moving road.
- **Pause & Resume** – Pause the game anytime using the space bar and resume from the same point.
- **Live Score Tracking** – Score increases as long as the player survives.
- **Immersive Visuals** – Animated cars, moving road lines, and a focused game area.
- **Responsive Controls** – Smooth keyboard controls using arrow keys for movement.

---

## 🎮 Controls

| Key | Action |
|----|-------|
| ⬅️ Left Arrow | Move Left |
| ➡️ Right Arrow | Move Right |
| ⬆️ Up Arrow | Move Forward |
| ⬇️ Down Arrow | Move Backward |
| ␣ Space Bar | Pause / Resume Game |

---

## 🧠 JavaScript Concepts Used

- **DOM Manipulation** – Dynamically creating and updating game elements.
- **Event Handling** – Managing keyboard inputs for player controls.
- **Game Loop Logic** – Continuous frame updates using animation techniques.
- **Collision Detection** – Detecting player and enemy car collisions.
- **State Management** – Handling game states such as start, play, pause, and game over.

---

## ⚙️ Core JavaScript Functionality

### 1️⃣ DOM Elements
- References to essential elements like score display, start button, game area, pause screen, and pause score panel.

### 2️⃣ Player Object
- Maintains player-related data such as:
  - Speed
  - Score
  - Pause state

### 3️⃣ Keys Object
- Tracks pressed keys (arrow keys and space bar) to ensure smooth and responsive controls.

### 4️⃣ Game Elements Storage
- Arrays to manage dynamic game components:
  - `lines` – Road divider lines
  - `enemies` – Enemy cars
  - `car` – Player’s car element

### 5️⃣ Event Listeners
- Start button click listener
- `keydown` and `keyup` listeners for real-time input handling

### 6️⃣ Pause Mechanism
- Space bar toggles the pause state
- Displays a pause screen with the current score

---

## 🛠️ Technologies Used

- HTML5  
- CSS3  
- JavaScript (Vanilla JS)

---

## 🔮 Future Enhancements

- Multiple difficulty levels
- Sound effects and background music
- Mobile touch controls
- Different car skins and themes
- Leaderboard system

---

## 👩‍💻 Author

**Gaurav Singh Aswal**  
Frontend Developer  

---

## 📜 License

This project is open-source and intended for learning and personal use.
