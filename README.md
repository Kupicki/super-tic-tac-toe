# ⚡ Super Tic-Tac-Toe (Ultimate Strategy Grid)

> A lightweight, client-side, mobile-first casual strategy game designed for instant play and web platforms (YouTube Playables, PWA, GitHub Pages).

🎮 **[Play Live Demo](https://seu-usuario.github.io/nome-do-repo/)** *(lembre-se de trocar com seu link)*

---

## 🌟 Highlights & Key Features

- **Zero Latency / 100% Client-Side:** No external backend dependencies, zero database calls, instant loading.
- **Game Modes:**
  - **Solo vs Smart AI:** Heuristic-based strategic engine (Casual & Master levels) with humanized move delay.
  - **2-Player Local:** Pass-and-play couch multiplayer on the same screen.
- **Multilingual Support (i18n):** Instant in-game localization switcher:
  - English (Default)
  - Português
  - Español
  - हिन्दी (Hindi)
  - 简体中文 (Simplified Chinese)
- **Built-in Web Audio API:** Procedural, dynamic retro sound synthesis without any heavy `.mp3` or `.wav` assets.
- **Mobile-First & Touch Optimized:** Responsive Tailwind layout, neon visual feedback, and `touch-action: manipulation` for zero touch delay.

---

## 🕹️ Game Rules & Mechanics

Ultimate Tic-Tac-Toe takes the classic 3x3 game and scales it into a 9x9 tactical battlefield:
1. **The Grid:** The board consists of 9 mini-boards arranged in a 3x3 macro grid.
2. **The Directive:** The cell position you play in a mini-board dictates which mini-board your opponent is forced to play in next.
3. **Macro Win:** Win 3 mini-boards in a row (horizontally, vertically, or diagonally) to conquer the Super Board.
4. **Free Move:** If you are sent to a mini-board that is already completed or tied, you gain a Free Move to play anywhere!

---

## 🛠️ Tech Stack

- **Markup & Layout:** HTML5, Tailwind CSS
- **Game Engine & Logic:** Vanilla JavaScript (ES6+)
- **Audio:** Native Browser Web Audio API
- **Deployment:** GitHub Pages / Static Web Hosting

---

## 📄 License
MIT License. Developed by Gabriel (Gabe).
