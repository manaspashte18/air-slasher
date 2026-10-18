# 🍉 Air Slasher — Webcam Fruit Ninja

An interactive browser-based Fruit Ninja game powered by your webcam and on-device machine learning hand tracking. Slice flying fruits with your bare hands, dodge bombs, and rack up combo multipliers!

## 🚀 Features

- **No controllers or special hardware needed**: Uses your standard webcam.
- **Privacy-first & Local**: Real-time hand landmark tracking runs 100% in your browser using **MediaPipe Hands** (no video is uploaded anywhere).
- **Fast & Responsive**: 60 FPS HTML5 Canvas rendering with slash trails, juice splatters, and floating score animations.
- **Game Mechanics**:
  - 8 distinct fruit types with custom juice colors.
  - 💣 Bombs to avoid.
  - Combo system for quick consecutive slashes (3x, 4x, etc.).
  - 3 lives system with screen flash effects on damage.
  - Dynamic difficulty scaling over time.
  - Persistent High Score saved in `localStorage`.

## 🎮 How to Play

1. Open `index.html` in any modern web browser (Chrome, Edge, Brave, etc.).
2. Click **START GAME** and allow webcam access when prompted.
3. Stand/sit about 1–2 feet away from the camera in good lighting.
4. Point your **index finger** and swipe through the fruits to slice them!
5. **Avoid the bombs** 💣 or you'll lose a life!

## 🛠️ Tech Stack

- **MediaPipe Hands** (Google) for 21-point 3D hand tracking
- **HTML5 Canvas & Vanilla JavaScript** (Zero external build dependencies)
- **CSS3** modern glassmorphism UI

## 🌐 Deploy to GitHub Pages

To make it playable online for anyone:
1. Go to your repository on GitHub.
2. Click **Settings** → **Pages** (under Code and automation).
3. Under **Branch**, select `main` and `/ (root)`.
4. Click **Save**. In a minute, your game will be live at `https://manaspashte18.github.io/air-slasher/`!
