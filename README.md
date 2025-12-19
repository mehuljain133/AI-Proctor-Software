<h1 align="center">🎓 Proctoring-AI 🔥</h1>
<p align="center">
  <strong>The Ultimate AI-Powered Online Exam Proctoring System</strong><br>
  Monitor candidates automatically via webcam & microphone using advanced AI 🚀
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/TensorFlow-2+-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-lightgrey?style=for-the-badge" />
  <img src="https://img.shields.io/badge/FPS-Maxed-up-red?style=for-the-badge" />
</p>

---

## 🚀 About Proctoring-AI

**Proctoring-AI** is an **all-in-one automated exam monitoring system** designed to detect suspicious behaviors in real-time using **AI-powered vision and audio analysis**.  
Whether it’s **eye tracking**, **mouth detection**, **phone detection**, or **speech monitoring**, this system is **optimized for maximum performance** on CPUs and GPUs alike.  

---

## 🛠 Features

### Vision-Based Monitoring
| Feature | Description | FPS on Intel i5 |
|---------|-------------|----------------|
| 👀 **Eye Tracking** | Detect where candidate is looking | 7.1 |
| 😮 **Mouth Detection** | Detect if candidate opens mouth | 7.2 |
| 🧍‍♂️ **Person Counting** | Detect # of people in frame | 1.3 |
| 📱 **Phone Detection** | Detect mobile phones instantly | 1.3 |
| 🤯 **Head Pose Estimation** | Track head movement & direction | 8.5 |
| 🪞 **Face Spoofing** | Detect fake faces/images | 6.9 |

### Audio-Based Monitoring
- 🎙 **Live Speech-to-Text** using Google API
- 📄 **Exam Content Matching** using NLTK
- 🕵️‍♂️ **Suspicious Word Detection** in real-time
- 🔄 Multi-threaded for **smooth recording & processing**

---

## ⚡ Installation (Super Easy)

```bash
# 1️⃣ Create virtual environment
python -m venv venv

# 2️⃣ Activate it
# Windows
./venv/Scripts/activate
# Mac/Linux
source ./venv/bin/activate

# 3️⃣ Install dependencies
pip install --upgrade pip
pip install -r requirements.txt
````

> 💡 **Note:** `person_and_phone.py` requires a YOLO model download.

**Vision Requirements:**

* TensorFlow >2
* OpenCV
* sklearn==0.19.1 (for face spoofing)

**Audio Requirements:**

* pyaudio
* speech_recognition
* nltk

---

## 🔧 How It Works (Next-Level AI)

### Face Detection & Landmarks

* Dlib replaced with **TensorFlow CNN models**
* Robust for **angled and occluded faces**
* Quantized model available for **edge devices** (⚡ faster FPS)

### Eye & Mouth Tracking

* Real-time **gaze tracking** and **mouth opening detection**
* Fully customizable thresholds for alerting

### Person & Phone Detection

* **YOLOv3 TensorFlow 2** implementation
* Detects **intruders or unauthorized phones**

### Head Pose Estimation

* Track head direction with **real-time 3D angles**

### Face Spoofing Detection

* Detect **images/videos trying to impersonate the candidate**
* Uses **state-of-the-art anti-spoofing model**

### Audio Analysis

* Converts live speech to text
* Matches with **exam content**
* Highlights suspicious answers

---

## 📈 To-Do (Next-Level Upgrades)

* [x] Replace HOG & Dlib with CNN-based models
* [ ] Replace YOLOv3 with faster lightweight models (like YOLOv8 Tiny)
* [ ] Face recognition for candidate verification
* [ ] ID-card verification using AI
* [ ] Improve face spoofing detection accuracy

---

## ⚡ Contributing

* 🌟 Want to make this better? Submit **pull requests**
* 📝 Update README and document new features
* 🚀 Let’s make Proctoring-AI **viral trending #1 on GitHub**

---

## 📜 License

MIT License.
⚠️ Facial landmark model is trained on **non-commercial datasets**—check licensing before commercial use.

---
<p align="center">
  Made with ❤️ by <strong>Mehul Jain</strong>
</p>
