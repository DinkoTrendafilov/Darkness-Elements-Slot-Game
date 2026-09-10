# 🧛 Darkness Elements — Slot Game

[![Play Now](https://img.shields.io/badge/▶️_PLAY_NOW-Live_Demo-gold?style=for-the-badge)](https://dinkotrendafilov.github.io/Darkness-Elements-Slot-Game/)

A fully-featured **8-symbol, 40-line** horror-themed slot machine built with pure HTML, CSS, and JavaScript — plus a **Python Monte Carlo simulator** for RTP verification.

---

## 🎮 Play the Game

👉 **[Click here to play Darkness Elements](https://dinkotrendafilov.github.io/Darkness-Elements-Slot-Game/)**

No installation needed — runs directly in your browser.

---

## ✨ Features

- 🎰 **40 Paylines** across 5 reels × 4 rows
- 🧛 **8 Horror Symbols** with weighted distribution
- 🌟 **Full Screen Bonus** — 1,000,000× per line
- 💰 **Progressive Jackpot** — 1 in 10,000 chance
- 🩸 **Rare Collection** — collect all 4 rare 5-of-5 symbols for 500× multiplier
- ✨ **Multiplier System** — ×2 to ×64 with weighted distribution
- 🎲 **Gamble Feature** — double or nothing with dice
- 🎵 **Full Sound Engine** — Web Audio API generated music & SFX
- 🔐 **Cryptographically Secure RNG** — uses `crypto.getRandomValues()`
- 💾 **Save / Load** — progress saved to `localStorage`
- 📱 **Responsive Design** — works on desktop and mobile

---

## 📊 Verified RTP

**95.99%** — verified via 100,000,000 spin Monte Carlo simulation

| Metric | Value |
|--------|-------|
| **RTP** | 95.99% |
| **Volatility Index** | 5.86× (very high) |
| **Rare Collection** | 1 in 5,988 spins |
| **Jackpot** | 1 in 9,853 spins |
| **Winning Spins** | 92.93% |
| **Average Multiplier (wins)** | ~4.00× |

---

## 🗂️ Project Structure

| File | Description |
|------|-------------|
| `index.html` | Playable slot game (open in browser) |
| `SDD.ipynb` | Vectorized Python Monte Carlo simulator |
| `README.md` | This file |
| `LICENSE` | MIT License |

---

## 🚀 Quick Start

### Play the Game

Just open **[the live demo](https://dinkotrendafilov.github.io/Darkness-Elements-Slot-Game/)** or download `index.html` and open it in any modern browser.

### Run the Simulation

```bash
pip install numpy
jupyter notebook SDD.ipynb


🎯 Game Mechanics
Symbols & Weights
Symbol	Weight	Probability
🧛 Vampire	3	10.00%
⚰️ Coffin	3	10.00%
🐦‍⬛ Raven	3	10.00%
🦇 Bat	3	10.00%
🧙‍♀️ Witch	4	13.33%
🌙 Moon	4	13.33%
🕯️ Candle	5	16.67%
🔮 Crystal Ball	5	16.67%
Multiplier Pool
Multiplier	Frequency
×64	1
×32	2
×16	4
×8	20
×4	75
×2	122

Average multiplier: ×4.00


⚠️ Disclaimer

This is a demo / educational project for learning about:

    Slot game mechanics

    RTP calculation

    Monte Carlo simulation

    Cryptographically secure RNG

    Web Audio API

No real money is involved.


🙏 Credits

Created by Dinko Trendafilov

⭐ If you like this project, give it a star!
