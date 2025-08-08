# DolphinTracking

An **open-source ultrasonic tracking system** for Virtual Reality (VR) that is low-cost, low-latency, and resistant to reflections.  
The goal is to make VR more **accessible and affordable** for everyone — without relying on expensive proprietary hardware.

---

## 🔍 Overview

This project proposes a novel tracking system for VR that uses **continuously modulated ultrasonic signals** instead of traditional pulse-based tracking.  
Multiple base stations emit **frequency sweeps** constantly. The tracker listens with a microphone and calculates its **position in space** — without cameras or optics.

---

## 💡 Key Features

- 📡 **Continuous ultrasonic emission** – no Time-of-Flight needed  
- 🎚️ **Per-station frequency modulation** – for unique signal identification  
- 🚫 **Reflection filtering** – via frequency-time consistency checks  
- 🌡️ **Environmental compensation** – accounts for temperature/humidity using a reference mic  
- ⚡ **Ultra-low latency** – limited only by microphone processing speed  
- 💸 **Extremely low cost** – target price: under €10 per tracker/base station

---

## 📐 How It Works

1. **Base stations** emit modulated ultrasonic signals (e.g., 20–40 kHz) in continuous frequency sweeps.
2. Each station uses a **unique sweep pattern** to be individually identifiable.
3. The **tracker** (e.g., on a headset) receives these signals through a microphone.
4. By matching received frequencies with known sweep timings, the **distance to each station** can be calculated.
5. With distances to four or more stations, the tracker computes its **3D position via triangulation**.
6. **Reflections are ignored** by checking for mismatches in expected signal behavior.

---

## 🧪 Project Status

This project is currently in the **concept phase**.

✅ Prior art published (to block patents)  
🚧 Prototyping in progress  
🔜 Hardware suggestions coming soon  
📂 Code for signal processing and positioning planned

---

## 🎯 Goal

This project aims to be an **open tracking solution** for:
- Hobby developers & makers
- Low-cost VR/AR setups
- Education & research
- Humanitarian tech (affordable accessibility to immersive tools)

---

## 📜 License

MIT License — free for private, academic, or commercial use.  
(We may later switch to CERN-OHL for hardware-specific open source compliance.)

---

## 🤝 Contribute

Contributions are welcome! You can help with:
- DSP code (FFT, Goertzel)
- Microcontroller firmware (STM32, RP2040, ESP32, etc.)
- 3D case design
- Testing & prototyping
- Documentation & examples
Or any other stuff you like. Please throw a dm on discord. Username mh48
---


## ✍️ Author

Idea & concept: MokkaHornisse48 (Nikolas Nowak)
