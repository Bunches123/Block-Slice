# 🔪 Block Slicer

A fast-paced, browser-based arcade game inspired by classic slicing mechanics. Swipe your blade, slice incoming blocks into pieces, build up high-scoring combos, and dodge explosive bombs!

---

## ✨ Features

* **Physics-Based Slicing:** Smooth 60 FPS canvas animations featuring realistic gravity, block fragment splitting, and dynamic particle effects.
* **Combo & Scoring System:** Chain multiple block slices in a single swipe to build multiplier combos and maximize your score.
* **Hazard Mechanics:** Watch out for bombs! Slicing a bomb ends the run immediately.
* **In-Game Economy & Shop:** Earn coins during gameplay to unlock a variety of unique swords with distinct trail colors and visual particle effects.
* **Modern Glassmorphism UI:** Clean, translucent aesthetic with responsive menus, dynamic HUD overlay, and seamless transitions.
* **Zero Dependencies:** Fully self-contained in a single lightweight web application—no external installation or build tools required.

---

## 🎮 How to Play & Controls

1. **Launch the Game:** Open `index.html` in any modern web browser.
2. **Start a Run:** Click **Play** from the main menu.
3. **Controls:**
   * **Mouse / Touch:** Click/tap and drag across the screen to swipe your blade.
4. **Rules:**
   * 🟩 **Blocks:** Slice them before they fall off the screen to earn points and coins.
   * 💣 **Bombs:** Avoid slicing at all costs! Hitting a bomb triggers an instant **Game Over**.
   * ⚡ **Combos:** Slice 3 or more blocks in a single continuous stroke to trigger bonus points.

---

## 🛠️ Tech Stack & Architecture

* **Frontend:** HTML5 Canvas, Modern CSS3 (Glassmorphism styling, Flexbox/Grid)
* **Scripting:** Pure JavaScript (ES6+)
* **Animation & Physics:** Custom 2D particle & rigid body physics engine powered by `window.requestAnimationFrame()`
* **State & Data:** Browser `localStorage` for high scores, collected coins, and unlocked sword inventory.

---

## 🚀 Getting Started

Since the entire game is built as a self-contained application, setting it up takes seconds:

1. **Clone or Download:**
   ```bash
   git clone [https://github.com/your-username/block-slicer.git](https://github.com/your-username/block-slicer.git)
   cd block-slicer
