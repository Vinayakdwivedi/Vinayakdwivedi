<!--
████████████████████████████████████████████████████████████████
  GITHUB PROFILE README — @YourUsername
  Built with 💻 + ☕ + too many late nights
████████████████████████████████████████████████████████████████
-->

<div align="center">

<!-- DRONE ANIMATION -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg">
</picture>

<!-- ANIMATED DRONE SVG -->
<svg width="800" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <radialGradient id="glow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" style="stop-color:#00d4ff;stop-opacity:0.4"/>
      <stop offset="100%" style="stop-color:#00d4ff;stop-opacity:0"/>
    </radialGradient>
    <filter id="blur">
      <feGaussianBlur stdDeviation="2"/>
    </filter>

    <!-- Drone swirl path -->
    <animateMotion id="swirl"/>
  </defs>

  <!-- Glow under final drone position -->
  <ellipse cx="400" cy="160" rx="60" ry="10" fill="url(#glow)" opacity="0.6">
    <animate attributeName="opacity" values="0;0;0.6" dur="4s" fill="freeze"/>
    <animate attributeName="rx" values="60;80;60" dur="2s" begin="4s" repeatCount="indefinite"/>
  </ellipse>

  <!-- DRONE GROUP -->
  <g id="drone">
    <!-- Animate: swirl from top-left, spiral in, land center -->
    <animateMotion
      dur="3.5s"
      fill="freeze"
      calcMode="spline"
      keySplines="0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1; 0.2 0 0.4 1"
      keyTimes="0; 0.3; 0.6; 0.85; 1"
      path="M -100,20 C 50,-30 750,-20 650,80 C 550,160 200,40 300,100 C 380,145 390,148 400,150"
    />
    <!-- Hover bob after landing -->
    <animateTransform attributeName="transform" type="translate"
      values="0,0; 0,-4; 0,0" dur="1.8s" begin="3.5s" repeatCount="indefinite"
      additive="sum"/>

    <!-- Drone Body -->
    <rect x="-18" y="-6" width="36" height="12" rx="4" fill="#1a1a2e" stroke="#00d4ff" stroke-width="1.5"/>
    <rect x="-6" y="-10" width="12" height="20" rx="3" fill="#16213e" stroke="#00d4ff" stroke-width="1"/>
    <!-- Camera -->
    <circle cx="0" cy="8" r="3" fill="#00d4ff" opacity="0.9"/>
    <circle cx="0" cy="8" r="1.5" fill="#001f3f"/>

    <!-- Arms -->
    <line x1="-18" y1="-3" x2="-34" y2="-12" stroke="#00d4ff" stroke-width="1.5"/>
    <line x1="18" y1="-3" x2="34" y2="-12" stroke="#00d4ff" stroke-width="1.5"/>
    <line x1="-18" y1="3" x2="-34" y2="12" stroke="#00d4ff" stroke-width="1.5"/>
    <line x1="18" y1="3" x2="34" y2="12" stroke="#00d4ff" stroke-width="1.5"/>

    <!-- Propellers (spinning) -->
    <!-- TL -->
    <ellipse cx="-34" cy="-12" rx="10" ry="2" fill="#00d4ff" opacity="0.7">
      <animateTransform attributeName="transform" type="rotate" from="0 -34 -12" to="360 -34 -12" dur="0.15s" repeatCount="indefinite"/>
    </ellipse>
    <!-- TR -->
    <ellipse cx="34" cy="-12" rx="10" ry="2" fill="#00d4ff" opacity="0.7">
      <animateTransform attributeName="transform" type="rotate" from="0 34 -12" to="-360 34 -12" dur="0.15s" repeatCount="indefinite"/>
    </ellipse>
    <!-- BL -->
    <ellipse cx="-34" cy="12" rx="10" ry="2" fill="#00d4ff" opacity="0.7">
      <animateTransform attributeName="transform" type="rotate" from="0 -34 12" to="-360 -34 12" dur="0.15s" repeatCount="indefinite"/>
    </ellipse>
    <!-- BR -->
    <ellipse cx="34" cy="12" rx="10" ry="2" fill="#00d4ff" opacity="0.7">
      <animateTransform attributeName="transform" type="rotate" from="0 34 12" to="360 34 12" dur="0.15s" repeatCount="indefinite"/>
    </ellipse>

    <!-- LED lights -->
    <circle cx="-34" cy="-12" r="2" fill="#ff4444">
      <animate attributeName="opacity" values="1;0.3;1" dur="0.6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="34" cy="-12" r="2" fill="#44ff44">
      <animate attributeName="opacity" values="1;0.3;1" dur="0.6s" begin="0.3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="-34" cy="12" r="2" fill="#ff4444">
      <animate attributeName="opacity" values="1;0.3;1" dur="0.6s" begin="0.15s" repeatCount="indefinite"/>
    </circle>
    <circle cx="34" cy="12" r="2" fill="#44ff44">
      <animate attributeName="opacity" values="1;0.3;1" dur="0.6s" begin="0.45s" repeatCount="indefinite"/>
    </circle>
  </g>
</svg>

<br/>

<!-- TYPEWRITER HEADER -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&size=32&duration=3000&pause=800&color=00D4FF&center=true&vCenter=true&multiline=false&width=600&lines=Hey%2C+I'm+building+the+future+%F0%9F%9A%80;ML+%7C+IoT+%7C+Embedded+Systems;UAVs+%7C+Gesture+Tech+%7C+AI;From+Greater+Noida+%F0%9F%87%AE%F0%9F%87%B3" alt="Typing SVG" />
</a>

<br/><br/>

<!-- PROFILE VIEWS + GITHUB STATS BADGES -->
![Profile Views](https://komarev.com/ghpvc/?username=YourUsername&color=00d4ff&style=flat-square&label=VISITORS)
&nbsp;
[![GitHub followers](https://img.shields.io/github/followers/YourUsername?style=flat-square&color=00d4ff&labelColor=0d1117)](https://github.com/YourUsername)

</div>

---

<div align="center">

## `< about_me />`

</div>

```yaml
name        : "Your Name"
location    : "Greater Noida, Uttar Pradesh 🇮🇳"
focus       : ["Machine Learning", "IoT", "Embedded Systems", "UAV Engineering"]
currently   : ["Building autonomous drones", "Designing gesture-based wearables"]
learning    : ["Deep Learning", "ROS2", "FPGA", "Computer Vision"]
philosophy  : "Build things that move — physically and digitally."
```

---

<div align="center">

## `< tech_stack />`

### 🧠 AI / Machine Learning
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

### ⚡ IoT / Embedded Systems
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white)

### 🌐 Development
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

### 🛠️ Tools & Platforms
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

</div>

---

<div align="center">

## `< active_missions />`

</div>

<table align="center">
<tr>
<td width="50%" valign="top">

### 🚁 Autonomous UAV System
```
STATUS  ████████░░░░  [ IN PROGRESS ]
```
> Building a fully autonomous **UAV** with real-time obstacle avoidance, GPS waypoint navigation, and onboard computer vision for object detection. Powered by a custom flight controller and ML inference on edge hardware.

**Stack:** `C++` `Python` `ROS2` `OpenCV` `ArduPilot` `Raspberry Pi`

</td>
<td width="50%" valign="top">

### 🤌 Gesture Note Bracelet
```
STATUS  █████░░░░░░░  [ PROTOTYPING ]
```
> A **wearable bracelet** that interprets hand gestures using an IMU + flex sensors and converts them to text notes via a trained gesture-classification model. No screen, no typing — just motion.

**Stack:** `ESP32` `TensorFlow Lite` `MPU6050` `BLE` `Python`

</td>
</tr>
</table>

---

<div align="center">

## `< future_missions />`

</div>

```
┌─────────────────────────────────────────────────────────────────────┐
│  🛰️  SWARM DRONE COORDINATION  —  Multi-agent UAV mesh networking   │
│  🧠  EDGE AI MODULE            —  Inference unit for embedded MCUs   │
│  👁️  CV PIPELINE               —  Real-time aerial object tracking   │
│  🩺  IoT HEALTH MONITOR        —  Wearable vitals + anomaly alerts   │
│  🌾  AGRI-DRONE                —  Precision agriculture + NDVI maps  │
└─────────────────────────────────────────────────────────────────────┘
```

---

<div align="center">

## `< github_stats />`

<img height="165em" src="https://github-readme-stats.vercel.app/api?username=YourUsername&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=00d4ff&icon_color=00d4ff&text_color=c9d1d9"/>
&nbsp;
<img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YourUsername&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00d4ff&text_color=c9d1d9"/>

<br/>

[![GitHub Streak](https://streak-stats.demolab.com?user=YourUsername&theme=tokyonight&hide_border=true&background=0d1117&stroke=00d4ff&ring=00d4ff&fire=ff6b6b&currStreakLabel=00d4ff)](https://git.io/streak-stats)

</div>

---

<div align="center">

## `< find_me />`

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YourUsername)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/YourUsername)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your@email.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://yourportfolio.dev)

<br/>

```
  ╔══════════════════════════════════════════╗
  ║  "The best way to predict the future     ║
  ║   is to build it — with ML + hardware."  ║
  ╚══════════════════════════════════════════╝
```

<br/>

<!-- Activity Graph -->
[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=YourUsername&theme=react-dark&bg_color=0d1117&color=00d4ff&line=00d4ff&point=ffffff&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

<!-- Snake animation footer note:
     To enable the snake animation, add this GitHub Actions workflow:
     .github/workflows/snake.yml
     See: https://github.com/Platane/snk
-->
