

<div style="padding: 1rem 0;">
<style>
  .section { margin-bottom: 2rem; padding: 1rem; border: 1px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); background: var(--color-background-secondary); }
  .label { font-size: 12px; color: var(--color-text-secondary); margin-bottom: 0.75rem; font-family: var(--font-mono); }
  .preview { background: #0d1117; border-radius: 8px; padding: 1.25rem; }
  .ascii { font-family: var(--font-mono); font-size: 9px; line-height: 1.2; white-space: pre; color: #e6edf3; overflow-x: auto; }
  .gradient-text { font-family: var(--font-mono); font-size: 28px; font-weight: 700; background: linear-gradient(90deg, #ff6b9d, #c44dff, #4d9fff); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; letter-spacing: 2px; }
  .typing-text { font-family: var(--font-mono); font-size: 18px; color: #58a6ff; border-right: 2px solid #58a6ff; white-space: nowrap; overflow: hidden; width: fit-content; animation: typing 3s steps(20) infinite alternate, blink 0.7s step-end infinite; }
  @keyframes typing { from { width: 0 } to { width: 100% } }
  @keyframes blink { 50% { border-color: transparent } }
  .badges { display: flex; flex-wrap: wrap; gap: 6px; }
  .badge { padding: 4px 10px; border-radius: 4px; font-size: 11px; font-family: var(--font-mono); font-weight: 600; }
  .b-blue { background: #1f6feb; color: #cae8ff; }
  .b-green { background: #196c2e; color: #56d364; }
  .b-purple { background: #6e40c9; color: #d2a8ff; }
  .b-orange { background: #9e6a03; color: #f8e3a1; }
  .name-gradient { font-family: var(--font-mono); font-size: 22px; font-weight: 700; background: linear-gradient(135deg, #56d364, #58a6ff, #d2a8ff); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; margin-bottom: 6px; }
  .sub { color: #8b949e; font-family: var(--font-mono); font-size: 12px; }
  .choose-btn { margin-top: 10px; padding: 5px 14px; border-radius: 6px; border: 1px solid #30363d; background: #21262d; color: #58a6ff; font-size: 12px; cursor: pointer; font-family: var(--font-mono); }
  .choose-btn:hover { background: #30363d; }
</style>
  
  <div class="section">
    <div class="label">Style 1 — Gradient Name Banner</div>
    <div class="preview">
      <div class="gradient-text">THANAWAT SUKAMPORN</div>
      <div style="color:#8b949e; font-family:monospace; font-size:13px; margin-top:6px;">Computer Engineering · AI/ML Enthusiast · KU</div>
    </div>
  </div>
</div>

```python
#!/usr/bin/env python3
# -*- coding: utf-8 -*-

class Thanawat_Sukamporn:
    """
    ╔══════════════════════════════════════════════════════════╗
    ║         COMPUTER ENGINEERING STUDENT @ KU               ║
    ║              Kasetsart University, Bangkok               ║
    ╚══════════════════════════════════════════════════════════╝
    """

    def __init__(self):
        self.name        = "Thanawat Sukamporn (ธนวัฒน์ สุขอัมพร)"
        self.nickname    = "Fronk"
        self.university  = "Kasetsart University"
        self.faculty     = "Computer Engineering"

         # Important
        self.SuperAIEngineer_Status    = "Super Ai Engineer SS5 : Track Innovator @Kasetsart University"
        self.location    = "Pathum Thani, Thailand 🇹🇭"
        self.languages   = ["th_TH 🇹🇭", "en_US 🇬🇧"]

        self.focus_areas = [
            "🤖  AI / Machine Learning / Image Processing",
            "🦾  Robotics & IoT & Mechatronics Automation",
            "🔒  Cybersecurity & CTF",
        ]

        self.currently_building = "AI-powered apps & embedded systems"
        self.fun_fact = "Won gold at national level with an AI X-Ray lung cancer detector 🫁"

    def say_hi(self):
        print("Thanks for stopping by — hope something here inspires you! 🙌")


me = Thanawat_Sukamporn()
me.say_hi()
```

---

<div align="center">

## 🏆 Competition Highlights

| 🥇 Gold | 🥈 Silver | 🥉 Bronze |
|:---:|:---:|:---:|
| i-NEW GEN Award 2025 (National) | FABLAB Walking Robot Challenge | VoltX Challenge 2025 |
| Arduino IoT "Innovate for Water Security" | Arduino Explore IoT Hackathon 2024 | Innovedex Robotics Competition 2024 |
| | | |

</div>

---

## ⚙️ Tech Stack

```yaml
AI / ML:
  Libraries:   [Keras, PyTorch, NumPy, OpenCV, matplotlib, pandas]
  Tasks:       [Image Classification, Object Detection (YOLO), NLP, Fine-tuning]
  Platforms:   [AWS Bedrock, AWS SageMaker, Kaggle]

Robotics & IoT:
  Frameworks:  [ROS, ROS2, Gazebo, Node-RED]
  Hardware:    [Arduino, Raspberry Pi, NVIDIA Jetson, CIRA Robotics]
  Protocols:   [BLE, MQTT, IR Sensor, Ultrasonic Sensor, Servo Control]

Cloud (AWS):
  Compute:     [Lambda, ECS Fargate]
  Data:        [DynamoDB, S3, SQS, SNS]
  Security:    [IAM, VPC]
  DevOps:      [CloudWatch, X-Ray, API Gateway]

Programming:
  Languages:   [Python, C++, C#, Java, SQL, ASM, Go, Rust]
  Web / API:   [Django, .NET Framework, Flask]
  OS:          [Ubuntu, Windows Server]
```

---

## 🚀 Notable Projects

### 🔬 Dooduangsassss — Online Astrology Bot *(Super AI Engineer Season 5)*
> Image Classification service using MobileNetV3-Large + Flask API, deployed on LINE Messaging API Bot.

### 🫁 AI CT-Scan / X-Ray Analyzer *(i-NEW GEN Award 2025 — Gold)*
> AI program for lung cancer screening using publicly available datasets (IQ-OTH/NCCD). Submitted to NRCT — 1,549 competing teams.

### 💧 Arduino IoT Water Security Monitor *(Arduino Education Day Thailand 2024 — 1st Place)*
> Real-time water safety system using Arduino Uno R4 WiFi, IR sensors, Ultrasonic sensors, and BLE via Arduino Nano 33.

### 🦿 Hexapod Walking Robot *(FABLAB Challenge — 1st Runner-Up)*
> 18-DOF hexapod robot controlled by Raspberry Pi Pico W + PCA9685, driving 18 MG90S micro servos.

### 🗑️ Zero Waste BCG Smart Bin *(Arduino Explore IoT Hackathon 2024 — 1st Runner-Up)*
> Automated waste sorter using Linear Motor + Inductive Sensor + Arduino MKR WiFi 1010, with live Arduino Cloud dashboard.

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=combine1234&theme=dark&hide_border=true&background=0d1117&ring=f5a623&fire=f5a623&currStreakLabel=f5a623" />
</div>

---

## 📡 Connect with Me

<div align="center">

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-Visit-0d1117?style=for-the-badge)](https://combine1234.github.io/Thanawat_Port_Web/index.html)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Thanawat_Sukamporn-0077B5?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/thanawat-sukamporn)
[![Facebook](https://img.shields.io/badge/Facebook-Thanawat_Sukamporn-1877F2?style=for-the-badge&logo=facebook)](https://facebook.com)
[![GitHub](https://img.shields.io/badge/GitHub-COMBINE1234-181717?style=for-the-badge&logo=github)](https://github.com/combine1234)

📞 062-730-2299 &nbsp;|&nbsp; 📍 Pathum Thani, Thailand

</div>

---

<div align="center">
  <sub>⚡ Built with passion for AI, Robotics & Cloud • Kasetsart University 🌾</sub>
</div>
