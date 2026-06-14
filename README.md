# 🪟 Smart Curtain — Clap-Controlled Automatic Curtain System

A miniature smart bedroom with an automatic curtain system controlled by hand claps, built using Arduino and FC-04 sound sensor — awarded **Best FC-04 Project** at PROTEK Electrical Days 2023, Universitas Jenderal Soedirman.

---

## 🔍 Overview

This project implements a clap-controlled smart curtain system on a miniature bedroom model. Using an FC-04 sound sensor to detect clap patterns, the Arduino microcontroller processes the input and drives a motor to open or close the curtain automatically. The system also features an LCD display for status feedback and LED ambient lighting.

The project was presented at **PROTEK (Projek Keteknikan)** as part of the **Electrical Days 2023** event organized by HMTE (Himpunan Mahasiswa Teknik Elektro) Universitas Jenderal Soedirman, and received the award for **Best FC-04 Project**.

---

## 🏆 Achievement

> 🥇 **FC-04 Terbaik (Best FC-04 Project)**
> PROTEK — Projek Keteknikan, Electrical Days 2023
> Himpunan Mahasiswa Teknik Elektro (HMTE), Universitas Jenderal Soedirman

---

## ⚙️ System Architecture

```
[Hand Clap Sound]
       ↓
[FC-04 Sound Sensor — Clap Detection]
       ↓
[Arduino — Control Logic]
       ├── Motor Driver → DC Motor (Curtain Open/Close)
       ├── LCD Display  → Status Feedback
       └── LED Lighting → Ambient Room Light
```

---

## 🛠️ Hardware Components

| Component | Function |
|---|---|
| Arduino | Main microcontroller & logic processing |
| FC-04 Sound Sensor | Detects clap sound as trigger input |
| DC Motor | Drives curtain open/close mechanism |
| Motor Driver | Controls motor direction & speed |
| LCD Display | Shows curtain status (Open/Closed) |
| LED Strip | Ambient lighting inside miniature bedroom |
| Miniature Bedroom Model | Physical prototype housing the system |

---

## 💻 Software & Tools

| Tool | Usage |
|---|---|
| Arduino IDE | Firmware programming (C/C++) |

---

## 🔧 Features

- **Clap-controlled automation** — single or double clap pattern toggles curtain open/close
- **FC-04 sound sensor** — detects sound threshold for clap recognition
- **Motor-driven curtain** — smooth open and close actuation via DC motor
- **LCD status display** — real-time feedback showing curtain state
- **LED ambient lighting** — integrated room lighting for miniature display
- **Compact miniature model** — fully enclosed bedroom prototype for demonstration

---

## 🔄 Sequence of Operation

1. System initializes — curtain in closed position, LCD shows "CURTAIN: CLOSED"
2. User claps once → FC-04 sensor detects sound threshold
3. Arduino processes input → motor activates, curtain opens
4. LCD updates → "CURTAIN: OPEN"
5. User claps again → motor reverses, curtain closes
6. LCD updates → "CURTAIN: CLOSED"
7. Cycle repeats on each clap input

---

## 📁 Repository Structure

```
smart-curtain/
├── firmware/
│   └── smart_curtain.ino     # Arduino firmware (C/C++)
├── docs/
│   └── images/               # System photos & award certificate
└── README.md
```

---

## 📸 Documentation

| Miniature Model | Night Mode (LED) | Award Certificate |
|---|---|---|
| ![Model](docs/images/model.jpg) | ![Night](docs/images/night-mode.jpg) | ![Award](docs/images/certificate.jpg) |

---

## 👤 Author

**Farhan Ibnufajar**
Electrical Engineering — Universitas Jenderal Soedirman (Unsoed)

[![GitHub](https://img.shields.io/badge/GitHub-farhanibnufajar-181717?style=flat&logo=github)](https://github.com/farhanibnufajar)
[![Portfolio](https://img.shields.io/badge/Portfolio-farhanibnufajar.github.io-00C6FF?style=flat&logo=github-pages)](https://farhanibnufajar.github.io)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
