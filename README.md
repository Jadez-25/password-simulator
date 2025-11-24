# 🔐 Password Strength Training Simulator

An interactive web-based cybersecurity simulation that demonstrates how attackers attempt to crack weak passwords. The project is designed to help users understand password strength, entropy, and how brute-force techniques operate — all through a cinematic, engaging experience.

---

## 🎯 Overview

This simulation lets users:

- Enter a sample password
- Watch a “dark-web attacker” attempt to brute-force it
- View real-time cracking output, attack speed, and ETA
- Receive feedback on password strength and security risks

The interface combines visual effects, sound design, and animated terminal output to create a realistic cybersecurity training experience.

---

## 🖼️ Features

### 🔥 Realistic Attack Simulation

- Simulates brute-force guessing character-by-character
- Displays GPU speed, guesses per second, and estimated time remaining
- Stronger passwords dynamically slow the simulated attack

### 🎬 Cinematic Hacker Interface

- Dark-mode aesthetic
- Neon accents, atmospheric shadows, and glitch effects
- Left panel hacker image + right panel attack console

### 🔊 Dynamic Audio System

- Glitch ambience
- Typing loop synced with cracking
- Heartbeat that speeds up as the attack progresses
- Flatline effect on password breach
- Full mute/unmute toggle

### ⚠️ Custom Alert Modals

- Win modal (green)
- Lose modal (orange)
- Warning modal (yellow)
- Restart Training built into modal

### 🧠 Password Strength Analysis

- Entropy calculation
- Detects lowercase, uppercase, numbers, symbols
- Flags common words and predictable patterns
- Provides actionable recommendations

---

## 🛠️ Tech Stack

- **HTML5** – single-page interface
- **CSS3** – grid layout, neon/glitch effects, animations
- **JavaScript (Vanilla)** – attack logic, sound control, UI state machine
- **No backend required** – runs entirely in-browser

---

## 📦 Project Structure

```
password-simulation/
│
├── index.html
└── assets/
    ├── css/
    │   └── style.css
    ├── imgs/
    │   └── hacker.jpg
    └── media/
        ├── flatline.mp3
        ├── glitch_ambience.mp3
        ├── heartbeat.mp3
        └── typing.mp3
```

---

## 🚀 Running the project locally

This is a static front-end project; no backend or build step is required.

1. Clone or download the repository.
2. Ensure all assets (images and audio files) are in the same paths referenced in `index.html`.
3. Open `index.html` in a modern browser  
   **or** use a simple static server (for example, the “Live Server” extension in VS Code) for the best experience with file paths and audio.

---

## 🌐 Deployment

This project can be hosted on any static-site platform (Netlify, GitHub Pages, Vercel, etc.):

- Set the **publish directory** to the project root (the folder containing `index.html`).
- No special build command or environment configuration is required.
- Once deployed, you can share the public URL as an interactive demo of the simulator.

---

## 📄 License

This project is released for educational and demonstrative purposes.

---

## 🙌 Credits

Designed and developed by **Jada Cropper**. Created as a standalone cybersecurity demonstration project showcasing password-cracking simulations, UI animation, and frontend development skill.
