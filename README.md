# 🥊 Pixel Fighters

**Arcade-style 2D fighting game** built with pure HTML5, CSS3 & Canvas API.  
No frameworks, no external assets — ready for **GitHub Pages**.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Canvas](https://img.shields.io/badge/Canvas%20API-000000?style=flat)

## ✨ Features

- **1 vs 1 local multiplayer** (same keyboard)
- 4 unique fighters with different stats & specials
- 4 arenas with distinct visual themes
- Punch, Kick, Special attacks + Combos
- Blocking system (reduces damage)
- Health bars + Special meter
- KO / Time-out victory conditions
- Particle effects & screen shake
- Animated main menu & character select
- Fully responsive pixel-art style

## 🎮 Controls

| Action        | Player 1 | Player 2      |
|---------------|----------|---------------|
| Move Left     | `Q`      | `←`           |
| Move Right    | `D`      | `→`           |
| Jump          | `Z`      | `↑`           |
| Block         | `S`      | `↓`           |
| Punch         | `F`      | `1`           |
| Kick          | `G`      | `2`           |
| Special       | `H`      | `3`           |

## 🚀 Play Online (GitHub Pages)

1. Fork / clone this repository
2. Go to **Settings → Pages**
3. Source: **Deploy from a branch** → `main` → `/ (root)`
4. Open `https://<your-username>.github.io/<repo-name>/`

## 📁 Project Structure

```
pixel-fighters/
├── index.html          # Entry point
├── css/
│   └── style.css       # UI & HUD styles
├── js/
│   ├── main.js         # Menu flow + game loop
│   ├── game.js         # Core game logic & rendering
│   ├── player.js       # Fighter class
│   ├── input.js        # Keyboard handling
│   ├── particles.js    # Particle system
│   ├── characters.js   # Fighter data
│   ├── arenas.js       # Arena data
│   └── constants.js    # Shared constants
├── assets/             # (empty – all art is procedural)
└── README.md
```

## 🛠️ Local Development

Just open `index.html` in a modern browser, or use any static server:

```bash
# Python
python -m http.server 8000

# Node
npx serve .
```

Then go to `http://localhost:8000`

## 🎨 Fighters

| Name   | Style            | Special      |
|--------|------------------|--------------|
| BLAZE  | Aggressive      | Fire Burst   |
| FROST  | Tanky            | Ice Spike    |
| SHADOW | Fast assassin    | Void Slash   |
| VOLT   | Electric         | Thunder      |

## 📜 License

MIT — free to use, modify and publish.

---

Made with ❤️ for the arcade spirit.
