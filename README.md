# 1. Create the README.md file using a 'here document'
cat > README.md << EOF
# Hi 👋, I'm Devadharshan D
[cite_start]A passionate **Automation & Robotics Engineering** undergraduate [cite: 4] [cite_start]and an **AI/ML enthusiast** [cite: 4, 5] who builds real-time control systems and AI-driven decision pipelines.

## 🌟 About Me:
* [cite_start]🎓 I'm currently pursuing a B.Tech in Automation & Robotics Engineering at Amrita Vishwa Vidyapeetham[cite: 8].
* [cite_start]💻 I have hands-on expertise with **microcontrollers, PLCs, sensors, and simulation tools**[cite: 6].
* [cite_start]🤖 My primary interests are **robotics, AI, machine learning, and industrial automation**[cite: 4].
* [cite_start]🚀 I'm actively working on Edge AI Model Compression for **YOLOv8** [cite: 40] [cite_start]and publishing papers on **Adaptive PID Control** [cite: 43] [cite_start]and **Reinforcement Learning**[cite: 42].
* [cite_start]📧 How to reach me: devadharshan11@gmail.com [cite: 2]

---

## 🔗 Socials:
[cite_start][<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />](www.linkedin.com/in/devadharshan-d-717294238) [cite: 2]
[cite_start][<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />](https://github.com/devadharshan11-design) [cite: 2]

---

## 🛠️ Tech Stack:
[cite_start]*(Based on Skills and Projects from Resume [cite: 5, 47, 49])*

### Languages & Data
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
<img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white" />
<img src="https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=matlab&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />

### AI/ML & Computer Vision
<img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
<img src="https://img.shields.io/badge/YOLOv8-000000?style=for-the-badge&logo=yolo&logoColor=yellow" />

### Embedded & Control Systems
<img src="https://img.shields.io/badge/Embedded_C-000000?style=for-the-badge&logo=arduino&logoColor=white" />
<img src="https://img.shields.io/badge/PLC_Programming-000000?style=for-the-badge&logo=siemens&logoColor=white" />
<img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white" />
<img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white" />

---

## ⚙️ Key Projects & Research

### Real-Time Lane Assist with Adaptive PID (Computer Vision)
> [cite_start]Achieved **93% accuracy** and **0.99s correction delay** in CARLA simulator; paper accepted for presentation at an IEEE conference[cite: 43, 44].

### Edge AI Model Compression for YOLOv8
> [cite_start]Engineered compression for deploying **YOLOv8n on Raspberry Pi 5**, achieving a **34% inference speedup** (4.13 FPS) while maintaining 99.7% accuracy[cite: 40].

### PLC-Based Adaptive Smart Traffic Control
> [cite_start]Integrated **YOLOv8 with FESTO PLC** for real-time traffic management, achieving **<1s response time** and 90%+ accuracy[cite: 31, 32].

---

## 📈 GitHub Stats:
*(Replace `[YOUR-GITHUB-USERNAME]` with your actual username)*

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=[YOUR-GITHUB-USERNAME]&show_icons=true&theme=vue" alt="Devadharshan's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=[YOUR-GITHUB-USERNAME]&layout=compact&theme=vue" alt="Devadharshan's Top Languages" />
</p>

---

<div align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark" />
</div>

EOF

# 2. Add an optional command to verify the file content
# This shows the first 10 lines of the newly created README.md
head -n 10 README.md