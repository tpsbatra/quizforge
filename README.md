# 🎯 QuizForge

> Build it. Play it. Any topic.

A real-time multiplayer quiz platform that runs as a single HTML file — powered by Firebase and playable on any device.

![Players](https://img.shields.io/badge/Players-100%2B-8b5cf6?style=flat-square)
![Firebase](https://img.shields.io/badge/Backend-Firebase-orange?style=flat-square)
![License](https://img.shields.io/badge/License-Free-10b981?style=flat-square)
![Hosting](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-181717?style=flat-square&logo=github)

---

## 🚀 Play Now

👉 **[https://tpsbatra.github.io/quizforge](https://tpsbatra.github.io/quizforge)**

- **Host a game** — open the link on your laptop, enter the host PIN, create a room
- **Join a game** — open the link on any phone or device, enter the 4-digit code or scan the QR

---

## ✨ Features

- 🎮 **Any topic** — use built-in Prompt Engineering questions or upload your own Excel/CSV file
- 📱 **Any device** — players join from phones, tablets, or laptops — no app install needed
- 👥 **100+ players** — Firebase Realtime Database handles concurrent connections
- ⚡ **Speed scoring** — 200 base points + up to 800 speed bonus per question
- 🔥 **Streak tracking** — consecutive correct answers build a streak multiplier
- 📊 **Live leaderboard** — animated rank movements after every question
- 👑 **New leader splash** — crown animation when leadership changes
- 🎲 **Random names** — assign fun AI-themed nicknames for anonymity
- 🎵 **Background music** — lobby music + correct/wrong sound effects
- 📁 **Excel upload** — bring your own questions in a simple template format
- 📱 **QR code** — auto-generated for players to scan and join instantly
- ⬇️ **CSV export** — download full results after every game
- 🔐 **Host PIN** — only authorised hosts can create rooms

---

## 🏗️ How It Works
```
Players scan QR / visit URL
         ↓
   GitHub Pages
   (serves HTML)
         ↓
   Firebase Realtime DB
   (syncs all game state)
         ↓
   Host laptop scores everyone
   Players see results in real-time
```

---

## 📁 Question File Format

Upload your own questions as `.xlsx` or `.csv`:

| question | option_a | option_b | option_c | option_d | correct_answer | explanation |
|----------|----------|----------|----------|----------|----------------|-------------|
| What is Python? | A snake | A language | A drink | A planet | B | Python is a programming language |

Download the template from within the app when creating a game room.

---

## ⚙️ Setup

Full setup instructions are in the **[Setup Guide](QuizForge_Setup_Guide.docx)** included in this repo.

**Quick version:**
1. Create a free Firebase project at [console.firebase.google.com](https://console.firebase.google.com)
2. Create a Realtime Database in test mode
3. Copy your 4 Firebase config values
4. Open the app → paste config values → done

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Vanilla HTML / CSS / JS — single file |
| Realtime sync | Firebase Realtime Database |
| Hosting | GitHub Pages |
| Excel parsing | SheetJS |
| QR generation | qrcodejs |
| Audio | Web Audio API |

---

## 📄 License

Free to use, modify, and share.

---

*Built with ❤️ using Claude*
