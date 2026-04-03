<h1 align="center">🛡️ PCare - AI Parental Care Assistant</h1>

<h4 align="center">
  🏆 1st Place Winner - METU CENG Senior Design Project Competition (Out of 28 Projects)
</h4>

<p align="center">
  <i>An innovative, AI-assisted Android ecosystem designed to monitor and protect children's online journeys in absolute stealth mode.</i>
</p>

---

## 🔗 Official Links & Demo
* ⚡ **Watch the Demo Video:** [YouTube Demo (Full System Walkthrough)](https://www.youtube.com/watch?v=NQUwLg6v2xk)
* ⚡ **Official Product Site:** [METU PCare Website](https://senior.ceng.metu.edu.tr/2024/PCare/)
* ⚡ **High-Resolution Poster:** [Download PDF Poster](https://senior.ceng.metu.edu.tr/2024/mainpage/logos/PCare-poster.pdf)

---

## 📸 System Overview (Demoday Poster)
![PCare Poster](./poster.png)

---

## 📌 Project Overview
**PCare** is a dual-application ecosystem consisting of a **Parent Dashboard** and a **Child Service App**. It leverages sophisticated technologies like real-time Machine Learning (YOLO) and NLP sentiment analysis to provide parents with comprehensive insights into their child's digital footprint—without ever compromising the child's device performance or revealing its presence.

⚠️ **Note on Source Code:** *The source code for PCARE is closed-source due to its proprietary nature, security architecture, and its status as an award-winning project. This repository serves as a technical showcase of the system's architecture and capabilities.*

---

## 🚀 Core Features & Technical Engineering

### 🕵️‍♂️ 1. Absolute Stealth Mode (Child Application)
*   **Invisible Operation:** The child application runs purely as a background service without an app icon or user interface.
*   **Auto-Boot Resilience:** Engineered to automatically reboot its tracking services immediately upon device startup or restart.
*   **Zero-Latency Performance:** Deeply performance-tested to ensure background operations run without creating CPU spikes, crashes, or noticeable battery drain.

### 🧠 2. AI-Powered Vision & YOLO Integration
*   **Continuous Screen Capturing:** Seamlessly takes background screenshots at intervals.
*   **Threat Detection:** Utilizes a highly trained **YOLO (You Only Look Once)** computer vision model to instantly recognize dangerous or inappropriate objects (e.g., firearms, cigarettes) on the screen.

### ⌨️ 3. Keyboard Tracking & Sentiment Analysis
*   **Real-time Keylogging:** Discreetly tracks keystrokes and search queries.
*   **Sentiment Analysis:** Evaluates the emotional tone of the child's typing (positive, neutral, negative) to flag potential cyberbullying, depression, or distress in real-time.

### 🌐 4. Digital Footprint Monitoring
*   **Web History:** Logs all visited URLs and flags potentially harmful domains.
*   **Usage Time Tracker:** Accurately calculates screen time to promote balanced digital diets.

### 📱 5. Parent Dashboard (Control Center)
*   **Real-time Analytics:** Parents receive categorized notifications based on the severity of the flagged content.
*   **Remote Configuration:** Parents can remotely toggle tracking layers (Screen, Web, Keyboard, Time) on or off depending on the child's needs.

---

## 🛠️ System Architecture & Tech Stack

This project was built with a decoupled architecture structure to ensure real-time data synchronization between the child and parent nodes.

*   **Mobile Engineering:** `Kotlin`, `Android SDK`, `Clean Architecture`, `MVVM`
*   **Machine Learning (AI):** `YOLO Object Detection`, `Python`
*   **Backend & Sync:** `Firebase Realtime Database`, `Firebase Authentication`

---

## 🎓 Academic Recognition & Rigorous Testing
This product was built not just as a concept, but as a fully tested system encompassing:
*   **Unit & Integration Tests:** Ensuring seamless data flows between the keyboard tracker and Sentiment Analysis module.
*   **System Testing (Incognito validation):** Validating absolute invisibility across various Android OS versions.

