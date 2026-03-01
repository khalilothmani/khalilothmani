<div align="center">

<!-- Animated typing header -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Orbitron&weight=700&size=32&duration=3000&pause=800&color=00D4FF&center=true&vCenter=true&width=700&lines=Med+Khalil+Othmani;Robotics+%26+Embedded+Systems+Engineer;AI+%7C+Computer+Vision+%7C+IoT+Builder;Building+the+future%2C+one+bot+at+a+time+🤖)](https://git.io/typing-svg)

<br/>

<!-- Social badges -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/khalil-othmani-379155316)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-%23181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/khalilothmani)
[![Profile Views](https://komarev.com/ghpvc/?username=khalilothmani&style=for-the-badge&color=00d4ff&label=PROFILE+VIEWS)](https://github.com/khalilothmani)

</div>

---

## 🧠 About Me

```python
class KhalilOthmani:
    name        = "Med Khalil Othmani"
    role        = "Robotics & Embedded Systems Engineer"
    location    = "Tunisia 🇹🇳"
    focus       = ["Robotics", "Embedded Systems", "Computer Vision", "AI/ML", "IoT"]
    hardware    = ["ESP32", "Arduino", "STM32", "Raspberry Pi", "SIM800L", "NEO-6M GPS"]
    software    = ["Python", "C/C++", "JavaScript", "Node.js", "TensorFlow", "OpenCV", "ROS"]
    currently   = "Building intelligent systems that live in the physical world"
    philosophy  = "Hardware without software is dead. Software without hardware is blind."
```

> 🚀 I design and build complete systems — from bare-metal microcontrollers and custom PCBs, all the way up to backend APIs, AI models, and live web dashboards. Every project in this repo is something I built with my hands.

---

## ⚡ Tech Stack

<div align="center">

### 🔩 Hardware & Embedded
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-Espressif-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-C51A4A?style=for-the-badge&logo=Raspberry-Pi&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)

### 💻 Languages
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)

### 🤖 AI / Vision / Robotics
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![ROS](https://img.shields.io/badge/ROS-0A0FF9?style=for-the-badge&logo=ros&logoColor=white)
![Anaconda](https://img.shields.io/badge/Anaconda-44A833?style=for-the-badge&logo=anaconda&logoColor=white)

### 🌐 Web & Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Apache](https://img.shields.io/badge/Apache-D42029?style=for-the-badge&logo=apache&logoColor=white)

### 🛠️ Tools & Platforms
![Qt](https://img.shields.io/badge/Qt-217346?style=for-the-badge&logo=Qt&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 🚀 Project Showcase

> Every project listed here is a physical, working system — not simulations.

---

### 🤖 [Oliver — Robotic Hand Mimicry Arm](https://github.com/khalilothmani/Oliver-Robotic-Hand-Mimicry-Arm)
> *Real-time robotic hand that mirrors your exact finger movements.*

A physical robotic arm that uses **MediaPipe computer vision** to track your hand in real time via webcam, and instantly replicates every finger movement on a servo-driven robotic hand — like a digital mirror.

`Python` `MediaPipe` `OpenCV` `Arduino` `Servo Motors` `Serial Communication`

---

### 📡 [GPS WebService — Live Tracking System](https://github.com/khalilothmani/GPS_WebService)
> *Custom GPS tracker with cellular data streaming and a live web dashboard.*

Built end-to-end during an internship. An ESP32 reads GPS coordinates, transmits them over **SIM800L GSM/GPRS** via HTTP POST, and a **Node.js Express** backend stores them in **Aiven MySQL** on the cloud. A live map dashboard visualizes the data in real time. Includes **motion-based power management** (ADXL345 accelerometer + MOSFET switching) that extends battery life from 2.5h → **12–15 hours**.

`ESP32` `NEO-6M GPS` `SIM800L` `Node.js` `MySQL` `Aiven` `Render` `IoT`

---

### 🌌 [PROXIMA — Explorational Rover Robot](https://github.com/khalilothmani/PROXIMA-Explorational-Rover-Robot)
> *A compact wireless rover with live camera feed and dual-joystick control.*

PROXIMA streams live footage from an **ESP32-CAM** while being controlled via **NRF24L01** wireless. A custom-built remote with two analog joysticks controls both movement (left joystick) and a **pan-tilt camera head** (right joystick). An LCD screen on the remote shows real-time telemetry.

`Arduino` `ESP32-CAM` `NRF24L01` `L293D Motor Driver` `LCD 16x2` `C++`

---

### 🌠 [Nebula — The Cosmic Rover](https://github.com/khalilothmani/Nebula-the-Cosmic-Rover)
> *A Wall-E inspired robot with expressive OLED eyes, head movement, and a grasping arm.*

Nebula has a personality — it features **dual OLED displays** that show animated expressions, a servo-driven head that looks around, and a fully functional grasping arm. Controlled wirelessly via a custom NRF24L01 remote. The OLED animation system runs independently from locomotion.

`Arduino` `OLED Display` `Servo Motors` `NRF24L01` `I2C` `C++`

---

### 🕷️ [Sporky — Spider Robot v3](https://github.com/khalilothmani/Sporky-Spider-Robot-v3)
> *A 6-legged spider robot using inverse kinematics, controlled via Bluetooth.*

Sporky uses **inverse kinematics** math to compute precise servo angles for each of its 18 joints (3 per leg × 6 legs), producing smooth, natural walking gaits. Controlled in real time via Bluetooth with a PCA9685 PWM servo driver managing all servos over I2C.

`Arduino` `Inverse Kinematics` `PCA9685` `Bluetooth` `Servo Control` `C++`

---

### 👁️ [Third-Eye Project (TEP)](https://github.com/khalilothmani/Third-Eye-Project-TEP)
> *Your tiny guardian that sees what you can't.*

TEP is a compact wearable/mountable sensor device using a **9-DOF IMU (MPU-9265)** to detect orientation, motion, and spatial awareness. Designed as a guardian system that alerts when it detects anomalies in movement or positioning.

`STM32 / Arduino` `MPU-9265` `I2C` `IMU` `Sensor Fusion` `C++`

---

### 🤖 [Nova — The Explorer Robot](https://github.com/khalilothmani/Nova-The-Explorer-Robot)
> *A full explorer rover with live camera and wireless remote, designed for tight spaces.*

Nova is a rover bot with **ESP32-CAM live streaming**, wireless NRF24 control, and an ultrasonic obstacle detection system. Designed for exploration in confined environments with real-time video feed and responsive control.

`ESP32-CAM` `NRF24L01` `Arduino` `Ultrasonic Sensor` `C++`

---

### 🌊 [Watershed Algorithm — Python](https://github.com/khalilothmani/watershed-algorithm-python)
> *Image segmentation using the OpenCV watershed algorithm.*

An implementation of the classic **watershed segmentation algorithm** in Python using OpenCV — applied to real images to detect and separate overlapping objects. A core computer vision technique used in robotics and medical imaging.

`Python` `OpenCV` `Image Segmentation` `Computer Vision`

---

### 🌌 [Three-Body Problem — Python](https://github.com/khalilothmani/Three-body-problem-python)
> *Simulating the chaotic gravitational dance of three celestial bodies.*

A Python simulation of the famous **Three-Body Problem** — one of the most chaotically complex problems in classical physics. Visualizes gravitational interactions with matplotlib animation.

`Python` `NumPy` `Matplotlib` `Physics Simulation`

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=khalilothmani&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&show_icons=true&rank_icon=github" height="170"/>
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=khalilothmani&theme=tokyonight&hide_border=true&layout=compact&langs_count=8" height="170"/>

<br/><br/>

<img src="https://nirzak-streak-stats.vercel.app/?user=khalilothmani&theme=tokyonight&hide_border=true" height="150"/>

</div>

---

## 🏆 GitHub Trophies

<div align="center">

![Trophies](https://github-profile-trophy.vercel.app/?username=khalilothmani&theme=tokyonight&no-frame=true&no-bg=false&margin-w=6&column=7)

</div>

---

## 🛸 What I'm Working On

```
▸ Advanced robotic systems with embedded AI
▸ Real-time sensor fusion and navigation algorithms
▸ Cloud-connected IoT hardware platforms
▸ Computer vision pipelines for physical-world interaction
```

---

<div align="center">

*"The best way to predict the future is to build it."*

[![LinkedIn](https://img.shields.io/badge/Let's_Connect-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/khalil-othmani-379155316)

[![](https://visitcount.itsvg.in/api?id=khalilothmani&icon=6&color=6)](https://visitcount.itsvg.in)

</div>
