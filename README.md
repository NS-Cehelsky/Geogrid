# 🌍 GeoGrid — Geography Puzzle Game

A daily-style geography puzzle game inspired by grid-based trivia games. Fill a 3×3 grid with countries that satisfy both the row and column category for each cell — and score points based on how obscure your picks are.

**[▶ Play it live](https://ns-cehelsky.github.io/Geogrid/)**

---

## 🎮 How It Works

The board is a 3×3 grid. Each row and column has a geographic category (e.g. *"In Scandinavia"*, *"Island nation"*, *"Flag has blue"*). Your job is to find a country that satisfies **both** the row and column category for each cell.

- You get **12 guesses** total — wrong answers count too
- Each country can only be used **once** per board
- **Scoring:** each correct answer earns 5–100 points based on rarity — smaller, less obvious countries score more than large, well-known ones
- The board is randomly generated every game

---

## ✨ Features

- **140+ countries** spanning every continent and region
- **Region-based categories** — Scandinavia, Southeast Asia, the Caribbean, West Africa, the Middle East, and more
- **Flag color categories** — flag has red, blue, green, black, no white, etc.
- **Geography categories** — island nation, landlocked, has a coastline
- **Population categories** — 100M+, 10–50M, under 10M, under 1M
- **Rarity scoring** — rewards deep geographic knowledge over guessing the obvious
- **Pop & shake animations** — satisfying feedback on correct and wrong answers
- **Dark mode support** — automatically adapts to system preference
- **Fully responsive** — works on mobile and desktop
- **Zero dependencies** — pure HTML, CSS, and vanilla JavaScript

---

## 🛠️ Built With

| Technology | Usage |
|---|---|
| HTML5 | Structure and game layout |
| CSS3 | Styling, gradients, animations, dark mode |
| Vanilla JavaScript | Game logic, scoring, board generation |

No frameworks. No libraries. No build tools. Just a single `index.html` file.

---

## 🚀 Getting Started

### Play locally
Just download `index.html` and open it in any browser — no server needed.

### Deploy to GitHub Pages
1. Create a new **public** repository on GitHub
2. Upload `index.html` to the root of the repo
3. Go to **Settings → Pages**, set source to `main` branch, root folder
4. Your game will be live at `https://YOUR-USERNAME.github.io/REPO-NAME/`

---

## 📁 Project Structure

```
geogrid/
└── index.html      # Entire game — HTML, CSS, and JS in one file
└── README.md       # This file
```

---

## 🧠 How Scoring Works

When you pick a correct country for a cell, it's ranked by **population** among all valid answers for that cell. The rarest pick (smallest population) scores close to **100 pts**, while the most obvious one scores as low as **5 pts**.

For example, for *"In Scandinavia" + "Island nation"*:
- Picking **Iceland** (very obvious) → ~10 pts
- Picking **Faroe Islands** → ~90 pts

This rewards players who think beyond the first country that comes to mind.

---

## 🙏 Inspiration

Inspired by [GeoRiddle](https://georiddle.org/) and the broader genre of grid-based trivia games.  
