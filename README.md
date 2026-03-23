# 🦑 AI Red Light Green Light — Squid Game Edition

> A real-time AI-powered recreation of the iconic *Red Light, Green Light* game using computer vision and pose detection.

---

## 📌 Overview

This project is a fun and interactive AI experiment inspired by the *Squid Game* series. It uses live webcam input, MediaPipe pose detection, and frame-differencing to enforce game rules — if you move during **Red Light**, it's game over.

---

## ✨ Features

- 🎥 Real-time webcam-based motion tracking
- 🤖 AI-powered pose detection via MediaPipe
- 🔴🟢 Dynamic Red Light / Green Light game logic
- 🔊 Integrated sound effects for immersive gameplay
- ⏱️ Countdown timer with visual feedback
- 🏆 Win / Game Over detection with score display
- 🙋 Player name overlay using pose landmarks

---

## 🧠 Tech Stack

| Category | Technology |
|---|---|
| Language | Python |
| Computer Vision | OpenCV |
| Pose Detection | MediaPipe |
| Numerical Processing | NumPy |
| Audio | Pygame |

---

## ⚙️ How It Works

1. Capture live video stream via webcam
2. Detect human pose landmarks using MediaPipe
3. Alternate game phases:
   - 🟢 **Green Light** → Movement allowed
   - 🔴 **Red Light** → Movement restricted
4. Apply frame differencing to detect motion between frames
5. Trigger win/loss logic based on movement during Red Light
6. Display final outcome — **You Win** or **Game Over**

---

## 📁 Project Structure

```
RED LIGHT GREEN LIGHT/
├── frames/                  # Game visual assets
├── sounds/                  # Audio files
└── RedLightGreenLight.py    # Main game script
```

---

## 🚀 Installation & Setup

**1. Install dependencies:**

```bash
pip install opencv-python mediapipe numpy pygame
```

**2. Run the game:**

```bash
python RedLightGreenLight.py
```

---

## 🎮 Controls

| Key | Action |
|-----|--------|
| `Q` | Quit the game |
| `R` | Restart the game |

---

## 🎥 Demo

📺 [Watch on YouTube](https://your-youtube-link-here.com)

---

## 🔮 Future Enhancements

- [ ] Multi-player tracking support
- [ ] Difficulty level customization
- [ ] Leaderboard integration
- [ ] Web or mobile deployment

---

## 📬 Connect

- 🐙 GitHub: [github.com/Janviswa](https://github.com/Janviswa)
- 💼 LinkedIn: [linkedin.com/in/jananiv05](https://www.linkedin.com/in/jananiv05/)

---

⭐ *If you found this project interesting, consider giving it a star!*
