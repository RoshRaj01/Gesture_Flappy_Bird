# 🐦 Gesture Controlled Flappy Bird

A modern twist on the classic **Flappy Bird**, controlled entirely using **hand gestures via your webcam**. Built using **HTML5 Canvas + MediaPipe Hands**, this project demonstrates real-time computer vision integrated with browser-based gameplay.

---

## 🚀 Features

* ✋ **Hand Tracking Control**

  * Move your hand up/down to control the bird
* 🤌 **Pinch Gesture Detection**

  * Pinch to flap, collect items, and restart after game over
* 🎮 **Classic Arcade Gameplay**

  * Pipes, enemies, and collectibles
* ⚡ **Smooth Physics Engine**

  * Fixed timestep game loop (60 FPS)
* 📷 **Live Camera Feed**

  * Real-time hand tracking overlay

---

## 🧠 Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Computer Vision:** MediaPipe Hands
* **Rendering:** HTML5 Canvas
* **Libraries:**

  * `@mediapipe/hands`
  * `@mediapipe/camera_utils`
  * `@mediapipe/drawing_utils`

---

## 🎮 How to Play

| Gesture          | Action                              |
| ---------------- | ----------------------------------- |
| ✋ Hand Up        | Bird goes up                        |
| ✋ Hand Down      | Bird goes down                      |
| 🤌 Pinch         | Flap / collect fruit / restart game |
| ❌ Hit pipe/enemy | Game over                           |

👉 If camera is not available:

* Click / tap screen to flap

---

## 📸 Screenshots

<img width="1919" height="903" alt="image" src="https://github.com/user-attachments/assets/156a1f0b-e55a-4a7f-a5e0-7e58824cccd8" />


<img width="1918" height="896" alt="image" src="https://github.com/user-attachments/assets/790bdee6-331a-4ade-943d-9b32fa217703" />

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/RoshRaj01/Gesture_Flappy_Bird.git
cd Gesture_Flappy_Bird
```

### 2. Run the project

Just open the HTML file in your browser:

```bash
open index.html
```

Or simply double-click the file.

---

## 🔐 Permissions

* The game requires **camera access** for gesture control.
* If denied:

  * You can still play using **mouse/touch input**.

---

## 🧩 Project Structure

```
Gesture_Flappy_Bird/
│
├── index.html        # Main game file
└── README.md
```

---

## ⚡ How It Works

* MediaPipe detects **21 hand landmarks**
* Average finger tip position → controls bird movement
* Distance between thumb & index → detects **pinch**
* Game loop runs at **fixed 60 FPS** for smooth physics

---

## 🎯 Future Improvements

* 🔊 Sound effects & background music
* 🏆 Leaderboard system
* 🎨 Custom themes / skins
* 🤖 AI difficulty scaling
* 🕶️ AR mode

---

## 🙌 Credits

* Inspired by the original **Flappy Bird**
* Powered by **Google MediaPipe**
