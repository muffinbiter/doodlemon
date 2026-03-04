# 🎨 DOODLEMON

> **Your drawings become monsters!**  
> An AI-powered drawing & monster battle game

![HTML5](https://img.shields.io/badge/HTML5-Canvas-E34F26?style=flat-square&logo=html5)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=flat-square&logo=javascript)
![Mobile](https://img.shields.io/badge/Mobile-Friendly-4CAF50?style=flat-square)

---

## 🕹️ About

**DOODLEMON** is a 2D pixel art exploration + turn-based battle game where the monsters you fight are born from your own drawings.

Forget random loot drops — here, **your drawing IS the monster**.  
The AI analyzes your sketch's colors, shape, and detail to generate a completely unique Doodlemon every time. Even the same drawing can produce different results depending on how you color it.

---

## ✨ Features

### 🎨 Doodling System
- Draw freely on the canvas
- AI analyzes color, shape, and density to determine type, stats, and name
- Red → 🔥 Fire / Blue → 💧 Water / Green → 🌿 Grass / Yellow → ⚡ Electric

### 📖 Doodle Book Tier System
| Tier | Cost | Analysis |
|------|------|----------|
| Old Doodle Book | 5 coins | Shape only → Basic stats |
| Magic Doodle Book | 15 coins | Shape + Color → Elemental damage added |
| Legendary Doodle Book | 30 coins | Full analysis → Special ability granted |

### 🗺️ Stage Exploration
- **3 stages**: 🌿 Green Forest → 🌋 Volcanic Zone → ❄️ Frozen Tundra
- Mario-style side-scrolling pixel art backgrounds
- Hit the 🟡 Question Block to pop out coins!
- Defeat 2 regular mobs per stage → Boss appears

### ⚔️ Battle System
- Pokémon-style 1v1 turn-based battles
- Type effectiveness applies (Fire→Grass / Water→Fire / Grass→Water / Electric→Water)
- Choose between your freshly drawn Doodlemon or a previously captured one

---

## 🎮 Controls

### ⌨️ Keyboard
| Key | Action |
|-----|--------|
| `←` `→` | Move |
| `↑` / `Space` | Jump |
| `Z` | Battle Skill 1 |
| `X` | Battle Skill 2 |

### 📱 Mobile
On-screen D-pad buttons (multi-touch supported)

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/muffinbiter/doodlemon.git

# Navigate to the folder
cd doodlemon

# Open in your browser
open doodlemon.html
```

> No installation required — runs as a **single HTML file**.  
> The NeoDGM font is embedded directly in the file, so it works completely offline.

---

## 📁 File Structure

```
doodlemon/
├── doodlemon.html   # Entire game (font embedded, single file)
└── README.md
```

---

## 🗺️ Game Flow

```
Title Screen
  ↓
Explore (side-scroll, collect coins)
  ↓
Wild Doodlemon appears!
  ↓
Choose: [Draw a new Doodlemon] or [Battle with existing one]
  ↓
Select Doodle Book → Draw → AI Analysis → Doodlemon born!
  ↓
1v1 Turn-Based Battle
  ↓
Defeat 2 mobs → Boss Battle → Next Stage
  ↓
Stage 3 Boss (God of Ice) → GAME OVER 💀
```

---

## 🛠️ Tech Stack

- **HTML5 Canvas** — Game rendering (pixel art)
- **Vanilla JavaScript** — All game logic
- **AI Color Analysis** — Canvas ImageData API for pixel-level analysis
- **NeoDGM Font** — Pixel font (OFL 1.1 License)

---

## 📌 Background

Built as a PoC (Proof of Concept) demo for the Smilegate AI Center Task Force.  
The core concept — **drawing → AI interpretation → instant feedback loop** — was designed to demonstrate how AI can transform user-generated content into meaningful game elements in real time.

---

## 📄 License

- Game code: MIT License  
- NeoDGM Font: [OFL 1.1](https://github.com/neodgm/neodgm) © Eunbin Jeong
```
