# 🦍 Tunczzzz Studios - Official Website

![Status](https://img.shields.io/badge/Status-Live-brightgreen)
![Style](https://img.shields.io/badge/Style-Cyber--Storm-blueviolet)
![Tech](https://img.shields.io/badge/Tech-HTML5_|_JS_|_CSS3-blue)

The official high-fidelity web presence for **Tunczzzz Studios**, creators of immersive VR experiences like *Lethal Ape* and *Dread Baboon*. 

This repository contains the source code for the "Cyber-Storm" aesthetic website. The site features a fluid, responsive design with dynamic content loading.

🔗 **Live Site:** [https://tunczzzzstudios.github.io/Main/](https://tunczzzzstudios.github.io/Main/)

---

## ✨ Features

### 🌐 Visuals & Aesthetics
* **"Cyber-Storm" Design:** Custom HTML5 Canvas rain engine overlaying a moving aurora borealis background.
* **Glassmorphism UI:** Floating navigation and content cards with real-time backdrop blurring and neon glow effects.
* **Immersive Entry:** A centralized "Start" screen that ensures audio auto-play compliance with cinematic fade-ins.
* **Responsive Layout:** Adapts seamlessly from 4K desktop monitors to mobile devices.

### ⚡ Dynamic Functionality
* **Real-Time Data:** The game library and privacy policy text are **not hardcoded**. 
* **Auto-Fetch:** The site automatically pulls the latest game list from a remote JSON database (GitHub Gist) every time it loads.
* **Smart Filtering:** The script automatically filters out system pages (e.g., "Action required", "Overview") to show only playable games.

---

## 📂 Project Structure

```text
/ (Root)
│
├── index.html                # Main Home Page (The Hub)
│
└── Privacy-Policy/
    └── index.html            # Dynamic Privacy Policy Page
