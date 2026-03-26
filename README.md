# 🎮 Game Boy Color Tetris (JS Edition)

A faithful and nostalgic implementation of the classic **Tetris**, inspired by the original Game Boy Color's vibrant palette and enhanced hardware vibe. This project uses pure web technologies to deliver a fluid gameplay experience, focusing on performance and collision precision while celebrating the Color era.

## 🚀 Features

* **Classic Physics Engine:** Precise collision detection and piece rotation logic.
* **Ghost Piece:** A translucent projection of the piece at the bottom of the board to improve player accuracy.
* **Difficulty Progression:** Gradual drop speed increases based on the player's level (calculated by lines cleared).
* **Scoring System:** Points calculated proportionally to the current level and the number of lines cleared simultaneously (Single, Double, Triple, and Tetris).
* **Retro Audio:** Sound effects generated via `Web Audio API` (square wave synthesis), eliminating the need for external assets.
* **UI State Management:** Integrated Start, Pause, and Game Over screens with state resets for seamless new matches.
* **Responsive Design:** An adaptive interface that maintains the original console's aspect ratio across various resolutions.

## 🕹️ Controls

| Key | Action |
| :--- | :--- |
| **Enter** | Start / Restart Game |
| **Backspace** | Pause / Resume Match |
| **Arrows ← / →** | Move piece laterally |
| **Arrow ↑** | Rotate piece |
| **Arrow ↓** | Soft Drop (Controlled descent) |
| **Space** | Hard Drop (Instant descent) |
| **C** | For Credits |
| **L** | For Language Change |

### 🕹️ Touch screen

| Key | Action |
| :--- | :--- |
| **Start** | Start / Restart Game |
| **Back** | Pause / Resume Match |
| **Arrows ← / →** | Move piece laterally |
| **Arrow ↑** | Rotate piece |
| **Arrow ↓** | Soft Drop (Controlled descent) |
| **Hard** | Hard Drop (Instant descent) |
| **Credits** | For Credits |
| **Language** | For Language Change |

## 🛠️ Technologies Used

* **HTML5 Canvas:** Low-latency graphical rendering for the grid and preview.
* **Vanilla JavaScript (ES6+):** Core game logic, state management (`gameState`), and audio synthesis.
* **CSS3:** Styling based on custom variables (`:root`) and depth effects to emulate classic hardware.
* **Web Audio API:** Oscillator manipulation for 8-bit sound effects.

## 📦 How to Run

The project is entirely client-side and requires no servers or compilation:

1.  Clone the repository.
2.  Open the `index.html` file in any modern browser.

---
Developed with a focus on clean code and a retro user experience.
