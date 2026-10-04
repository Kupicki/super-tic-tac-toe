# ⚡ Super Tic-Tac-Toe (Ultimate Strategy Grid)

> A lightweight, client-side, mobile-first casual strategy game designed for instant play and web platforms (YouTube Playables, PWA, GitHub Pages).

🎮 **[Play Live Demo](https://kupicki.github.io/super-tic-tac-toe/)**

---

## 🌟 Highlights & Key Features

- **Zero Latency / 100% Client-Side:** No external backend dependencies, zero database calls, instant loading.
- **Game Modes:**
  - **Solo vs Smart AI:** Heuristic-based strategic engine (4 difficulty tiers: Easy, Medium, Hard, Extreme) with humanized move delay.
  - **2-Player Local:** Pass-and-play couch multiplayer on the same screen.
- **In-Game Economy & Rewarded Ads:**
  - **Cyber Coins (🪙):** Earn coins by winning Solo matches or watching simulated 5-second rewarded video ads.
  - **2x Win Doubler:** Option to double your match rewards upon victory.
  - **Mock Ad SDK:** Ready for YouTube Playables / web portal SDK integrations.
- **Tactical Power-Ups (Solo Mode):**
  - **Undo Move (30 🪙):** Rollback the AI's and player's last moves seamlessly.
  - **Tactical Hint (20 🪙):** Algorithmic highlight of the mathematically optimal move.
- **Cosmetics Shop (Home Screen Exclusive):**
  - **Tab 1: Marker Skins (X & O):** 10 unlockable styles + default (Neon Cyber, Toxic Biohazard, Stealth Titanium, Golden Prestige, Matrix Green, Electric Thunder, Fire & Ice, Vaporwave Sunset, Blood Moon, Cosmic Nebula, Supernova Radiance).
  - **Tab 2: Board / Grid Themes:** 10 unlockable arena skins + default (Midnight Obsidian, Toxic Bio-Lab, Minimalist Carbon, Cyberpunk Neon, Glacial Arctic Ice, Royal Emerald, Retro Synthwave 80s, Solar Magma, Deep Space Nebula, Crimson Sanctuary, Golden Hyperdrive).
  - Interactive live previews, dynamic CSS glows, and instant state persistence.
- **Multilingual Support (i18n):** Instant in-game localization switcher:
  - 🇺🇸 English (Default)
  - 🇧🇷 Português
  - 🇪🇸 Español
  - 🇮🇳 हिन्दी (Hindi)
  - 🇨🇳 简体中文 (Simplified Chinese)
- **Built-in Web Audio API:** Procedural, dynamic retro sound synthesis (clicks, victory fanfare, coin jingles, power-up chimes, rewind sfx).
- **Mobile-First & Touch Optimized:** Responsive Tailwind layout fitting any screen height without scrollbars, neon visual feedback, and `touch-action: manipulation` for zero touch delay.

---

## 🕹️ Game Rules & Mechanics

Ultimate Tic-Tac-Toe takes the classic 3x3 game and scales it into a 9x9 tactical battlefield:
1. **The Grid:** The board consists of 9 mini-boards arranged in a 3x3 macro grid.
2. **The Directive (The Golden Rule):** The cell position you play in a mini-board dictates which mini-board your opponent is forced to play in next.
3. **Macro Win:** Win 3 mini-boards in a row (horizontally, vertical, or diagonal) to conquer the Super Board.
4. **Free Move:** If you are sent to a mini-board that is already completed or tied, you gain a Free Move to play anywhere!

---

## 🛠️ Tech Stack

- **Markup & Layout:** HTML5, Tailwind CSS
- **Game Engine & Logic:** Vanilla JavaScript (ES6+)
- **Audio:** Native Browser Web Audio API (zero audio files needed)
- **Monetization & Retention:** LocalStorage Economy, Cosmetic Shop, Rewarded Video Mock SDK
- **Deployment:** GitHub Pages / Static Web Hosting

---

## 📄 License
MIT License. Developed by Gabriel (Gabe).
