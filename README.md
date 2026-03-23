# 🎮 AI Red Light Green Light Game (Squid Game)

## 📌 Overview

💡 This project was developed as a fun and interactive AI experiment inspired by the Squid Game series. This project presents an AI-powered recreation of the popular "Red Light, Green Light" game inspired by Squid Game, built using Computer Vision and Pose Detection techniques.

The system leverages real-time webcam input to monitor player movement and enforces game rules by detecting motion during "Red Light" phases.

## 🚀 Key Features

* Real-time webcam-based motion tracking
* AI-powered pose detection using MediaPipe
* Dynamic Red Light / Green Light game logic
* Integrated sound effects for immersive experience
* Countdown timer with visual feedback
* Win/Loss detection with score display
* Player name overlay using pose landmarks


## 🧠 Technologies Used

* Python
* OpenCV
* MediaPipe (Pose Detection)
* NumPy
* Pygame (Audio Processing)


## ⚙️ System Workflow

1. Capture live video stream using webcam  
2. Detect human pose landmarks via MediaPipe  
3. Alternate between:  
   - 🟢 Green Light → Movement allowed  
   - 🔴 Red Light → Movement restricted  
4. Apply frame differencing to detect motion  
5. Trigger game logic based on movement detection  
6. Display final outcome (Win / Game Over)  


## 📁 Project Structure

```
RED LIGHT GREEN LIGHT/
│── frames/        # Game visual assets
│── sounds/        # Audio files
│── RedLightGreenLight.py
```


## ▶️ Installation & Execution

```bash
pip install opencv-python mediapipe numpy pygame
python RedLightGreenLight.py
```

## 🎮 Controls

* Press **Q** → Exit the game
* Press **R** → Restart the game


## 🎥 Demo

🎥 **YouTube Demo:** [https://your-youtube-link-here.com](https://your-youtube-link-here.com)


## 💡 Future Enhancements

* Multi-player tracking support
* Difficulty level customization
* Leaderboard integration
* Web or mobile deployment

## 📬 Contact

* GitHub: [github.com](https://github.com/Janviswa)
* LinkedIn: [linkedin.com](https://www.linkedin.com/in/jananiv05/)


⭐ If you found this project interesting, consider giving it a star!
