# DolphinTracking

An **open-source ultrasonic tracking system** for Virtual Reality (VR) that is low-cost, low-latency, and resistant to reflections.  
The goal is to make VR more **accessible and affordable** for everyone — without relying on expensive proprietary hardware.
Let the dolphins sing (:
---

## 🔍 Overview

This project proposes a novel tracking system for VR that uses **continuously modulated ultrasonic signals** instead of traditional pulse-based tracking.  
Multiple base stations emit **frequency sweeps** constantly. The tracker listens with a microphone and calculates its **position in space** — without cameras or optics.

---

## 💡 Key Goals
This project aims to be an **open tracking solution** for VR
- 📡 **Continuous ultrasonic emission** – no Time-of-Flight needed  
- 🎚️ **Per-station frequency modulation** – for unique signal identification  
- 🚫 **Reflection filtering** – via frequency-time consistency checks  
- 🌡️ **Environmental compensation** – accounts for temperature/humidity using a reference mic  
- ⚡ **Ultra-low latency** – limited only by microphone processing speed  
- 💸 **Extremely low cost** – target price: under €10 per tracker/base station

---

## 📐 The Plan

1. **Base stations** emit modulated ultrasonic signals (e.g., 20–40 kHz) in continuous frequency sweeps.
2. Each station uses a **unique sweep pattern** to be individually identifiable.
3. The **tracker** (e.g., on a headset) receives these signals through a microphone.
4. By matching received frequencies with known sweep timings, the **distance to each station** can be calculated.
5. With distances to four or more stations, the tracker computes its **3D position via triangulation**.
6. **Reflections are ignored** by checking for mismatches in expected signal behavior.

---

## 🧪 Project Status

This project is currently in the **concept phase**.

---


## 📜 License

MIT License — free for private, academic, or commercial use.

---

## 🤝 Contribute

Contributions are welcome! 
Please just throw a dm on discord. Planing to organize everything there. Username: mh48
---


## ✍️ Author

Idea & concept: MokkaHornisse48 (Nikolas Nowak)
