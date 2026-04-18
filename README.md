# 🎲 Risk or Reward Clicker

> Click. Multiply. Cash out. Or lose it all.

A gambling-psychology browser mini-game built with zero dependencies — pure HTML, CSS, and JavaScript in a single file.

## 🎮 Live Demo

Deploy to Vercel in one click → [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)

## 🕹️ How to Play

- Click boxes on the 5×5 grid to earn points
- Each safe click grows your **multiplier** by ×0.1 (compounding!)
- Hit a 💥 bomb → round score resets to zero
- **CASH OUT** to permanently save your score to the bank
- 3 safe clicks in a row → +50 bonus points
- 5 safe clicks in a row → +0.3 multiplier boost
- Every 3rd round is **CURSED** — ☠️ super bombs can halve your bank
- Every 5th round is **GOLDEN** — ⭐ jackpot gives 3× points + mult boost

## ✨ Features

- 4 difficulty modes (Easy 20% → Insane 60% bomb rate)
- Multiplier bar (green → gold → red as risk grows)
- Greed meter tracking clicks since last cash-out
- Streak system with visual dot indicators
- Cursed & Golden special rounds
- Persistent bank and best score per session
- Particle burst on cash-out
- Screen flash on bomb/jackpot
- Fully responsive — works on mobile

## 🚀 Deploy to Vercel

1. Fork or clone this repo
2. Go to [vercel.com](https://vercel.com) → New Project
3. Import your GitHub repo
4. Settings: Framework = **Other**, Build Command = *(empty)*, Output Directory = `.`
5. Deploy — done!

## 💻 Local Development

No build step needed. Just open `index.html` in any browser:

```bash
git clone https://github.com/YOUR_USERNAME/risk-or-reward-clicker
cd risk-or-reward-clicker
open index.html   # macOS
# or just drag the file into your browser
```

## 📁 File Structure

```
risk-or-reward-clicker/
├── index.html    # entire game — HTML + CSS + JS inlined
└── README.md
```

## 🛠️ Built With

- Vanilla HTML5 / CSS3 / JavaScript (ES6+)
- [Orbitron](https://fonts.google.com/specimen/Orbitron) + [Space Mono](https://fonts.google.com/specimen/Space+Mono) via Google Fonts
- Zero npm packages, zero build tools

## 📄 License

MIT — free to use, modify, and share.
