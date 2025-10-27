
# 🏓 Ping Pong — The Desktop Chaos Edition

A fast, minimal, and slightly chaotic **Electron-based Ping Pong game** built with  
**HTML, CSS, JavaScript, and Node.js**.

This isn’t your average Pong clone — it’s a clean-coded experiment designed to teach, test, and entertain.  
Run it locally, package it as a desktop app, or just open it in your browser. Either way, prepare to lose to your own reflexes.

---

## ⚡ Features
- 🧱 Classic two-player gameplay
- 🖥️ Works as a **desktop app (Electron)** or in-browser
- ⚙️ Simple physics engine with smooth paddle collisions
- 🎨 Clean and minimal UI, optimized for all resolutions
- 💾 No dependencies other than Electron and Node.js
- 🧩 Customizable speed, paddle size, and score limits
- 💥 Cross-platform (Windows, macOS, Linux)

---

## 🧠 Controls

| Player | Move Up | Move Down |
|:-------|:--------|:----------|
| 🟦 Left Paddle | `W` | `S` |
| 🟥 Right Paddle | `↑` | `↓` |

**Reset the game:** `R`  
**Quit (Electron app):** `Esc`

---

## 🚀 Installation & Setup

### 🔧 Prerequisites
- [Node.js](https://nodejs.org/) (v18+ recommended)
- [npm](https://www.npmjs.com/)
- [Git](https://git-scm.com/)

### 💻 Clone the Repository
```bash
git clone https://github.com/itsnony/ping-pong.git
cd ping-pong
````

### 📦 Install Dependencies

```bash
npm install
```

### ▶️ Run the Game (Development Mode)

```bash
npm start
```

This will launch the game in an Electron window.

### 🏗️ Build for Production

```bash
npm run build
```

The packaged app will be generated inside the `dist/` folder for your OS.

---

## 🧩 Project Structure

```
ping-pong/
├── src/
│   ├── index.html        # Main UI
│   ├── style.css         # Game styling
│   ├── script.js         # Game logic and physics
│   ├── preload.js        # Electron preload script
│   └── main.js           # Electron main process
├── package.json          # Project config
├── README.md             # You’re reading it
└── assets/               # Icons, sounds, etc.
```

---

## ⚙️ Configuration

You can tweak gameplay variables directly in `script.js`:

```js
const ballSpeed = 6;      // Default 6
const paddleSpeed = 5;    // Default 5
const maxScore = 10;      // Default 10
```

Save and restart the app to apply changes.

---

## 🧪 Developer Notes

* Built on **Electron 31+**
* Tested on macOS, Windows 11, and Ubuntu 24.04
* Ideal for learning how to connect browser games with Node.js runtime
* Lightweight — only a few MB once built

---

## 🧠 Why Electron?

Because why not.
It lets you run a browser game as a native desktop app with no extra setup —
and if you want to add menus, save data, or online play later, you already have Node.js at your disposal.

---

## 🪄 Future Plans

* Add sound effects & music toggle
* Add AI mode (single-player vs bot)
* Replays / score history
* Mobile controls (touch paddles)
--

