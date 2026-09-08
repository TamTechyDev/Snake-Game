# 🐍 Retro Snake

[![Stars](https://img.shields.io/badge/stars-?style=social)](https://github.com/TamTechyDev/Snake-Game/stargazers)
[![Forks](https://img.shields.io/github/forks/TamTechyDev/Snake-Game?label=Forks&style=social)](https://github.com/TamTechyDev/Snake-Game/forks)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)
[![HTML](https://img.shields.io/badge/HTML-5-E34F26?logo=html5&logoColor=white)]()
[![CSS](https://img.shields.io/badge/CSS-3-1572B6?logo=css3&logoColor=white)]()
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)]()
[![No dependencies](https://img.shields.io/badge/Dependencies-none-green.svg)]()

> A colorful, cute retro snake game in a single HTML file. No build step, no dependencies — just open and play!

<div align="center">

| Control | Action |
|:--:|:--:|
| `↑ ↓ ← →` or `W A S D` | Move the snake |
| `SPACE` | Pause / Resume |
| `M` | Mute / Unmute sound |

</div>

On touch devices, an on-screen **D-pad** appears automatically.

## ✨ Features

- 🌈 **Rainbow-gradient snake** — kawaii eyes, rosy cheeks, and a little smile that follow the direction you move
- 🍎 **Glossy apple food** with a leaf and a soft pulse animation
- 💥 **Walls kill!** Hitting the boundary or your own body ends the game
- ⚡ **Progressive difficulty** — speed levels up every 5 apples
- 🔊 **Retro sound effects** generated with the Web Audio API (no audio files needed)
- 🏆 **Persistent high score** saved in `localStorage`
- ✨ **Smooth movement** via per-frame interpolation between ticks

## ▶️ Play It

**Option A — Local:**
Open `index.html` in any modern browser.

**Option B — Online (GitHub Pages):**
1. In this repo, go to **Settings → Pages**
2. Under *Build and deployment*, set **Source = "Deploy from a branch"**
3. Branch = `main`, Folder = `/ (root)`, then click **Save**
4. Wait a minute and play at:
   `https://TamTechyDev.github.io/Snake-Game/`

## 🛠️ Tech

Pure **HTML + CSS + JavaScript** using Canvas 2D. Everything lives in a single `index.html` file.

- Canvas 2D rendering with per-frame interpolation for smooth motion
- `requestAnimationFrame` game loop
- Web Audio API for retro-style SFX
- `localStorage` for the high score

## 📄 License

This project is licensed under the [MIT License](./LICENSE).

---

<div align="center"><sub>Built with 💖 — enjoy the game!</sub></div>
