# 🎮 WackyFlip-Minis

A curated collection of mini games and spin-offs from the [Wacky Flip](https://wackyflip.com) universe
Quick to play, hard to quit — bite-sized chaos, fun, and flips for everyone!

---

## 🎯 Overview

`WackyFlip-Minis` is a dedicated repository for short-form, standalone mini-games built within the Wacky Flip platform. These games are designed to be quick, quirky, and endlessly replayable — perfect for coffee breaks, mobile bursts, or warm-ups before full game sessions.

Each mini game is powered by the Wacky Flip engine and shares the same offbeat humor, physics-driven mechanics, and signature visual style.

---

## 🕹️ What’s Inside

This repo includes fully playable versions of mini games such as:

### ✅ Featured Mini Games

* **Noob Flip:**
  A ragdoll flipping challenge. Time your jump, flip through the air, and land in style!

* **Bottle Launch:**
  Launch a spinning bottle through obstacles and land it upright to win.

* **Flip Shot:**
  A precision-based physics shooter where you flip with every shot you take.

* **Obstacle Hop:**
  Tap to hop across a rainbow-colored platform gauntlet. Miss once and it's game over!

* **Crazy Spinner:**
  Spin, bounce, and deflect as long as you can without falling off the edge.

Each mini game is designed to run independently or be embedded within the main WackyFlip.com platform.

---

## ⚙️ Tech Stack

* **HTML5 + JavaScript (Vanilla & Phaser.js)** – Lightweight performance for browser delivery
* **WackyFlip-Core (Lite)** – Shared logic and physics modules
* **Modular Architecture** – Easy to add or remove games individually
* **Mobile-Friendly Design** – All mini games are optimized for tap & swipe controls

---

## 📁 Repository Structure

```
WackyFlip-Minis/
├── /games/
│   ├── noob-flip/
│   ├── bottle-launch/
│   ├── flip-shot/
│   └── obstacle-hop/
├── /shared/
│   └── core-lite/       # Reusable game logic, physics, input utils
├── index.html           # Demo launcher or game selector
├── launcher.js          # Game selection + loading logic
└── styles.css           # UI and visual themes
```

---

## 🚀 Getting Started

### 1. Clone the repository:

```bash
git clone https://github.com/wackyflipgame/WackyFlip-Minis.git
cd WackyFlip-Minis
```

### 2. Open the launcher:

Just open `index.html` in any modern web browser — no build process required!

---

## 🎨 Adding a New Mini Game

1. Create a new folder inside `/games/your-game-name`
2. Follow the structure of an existing mini game
3. Import shared physics or input modules from `/shared/` as needed
4. Register the game in `launcher.js` for inclusion in the selector menu

---

## 🧑‍💻 Contributing

We welcome quirky, fun, and weird ideas that fit the [Wacky Flip](https://wackyflip.com) vibe!
Submit your mini game via a pull request with:

* A short game description
* Game preview or screenshot
* Control instructions and play goal

---

## 📜 License

Codebase is available under the **MIT License**.
All game assets, music, and art are © Wacky Flip Studios unless otherwise stated.

---

## 🔗 Related Repositories

* [`WackyFlip-Web`](https://github.com/wackyflipgame/WackyFlip-Web) – Frontend integration
* [`WackyFlip-Core`](https://github.com/wackyflipgame/WackyFlip-Core) – Main engine
* [`WackyFlip-Assets`](https://github.com/wackyflipgame/WackyFlip-Assets) – Shared visual elements

---

## 📬 Support & Feedback

Found a bug in a mini game? Want to suggest a fun spin-off?
Open an [issue](https://github.com/wackyflipgame/WackyFlip-Minis/issues) or contact us at [minis@wackyflip.com](mailto:minis@wackyflip.com).
