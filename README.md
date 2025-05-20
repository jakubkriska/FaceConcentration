# FaceConcentration

# 🧠 FocusFlow — A Respectful Concentration Companion

> *Support, not control. Adapt, don’t dictate.*

**FocusFlow** is a privacy-first, locally-run attention support tool that helps individuals enhance their concentration through gentle, customizable guidance — all while respecting their individuality and autonomy.

---

## 🚀 Features

- 🧍 Local facial tracking via webcam (MediaPipe)
- 💻 Optional screen activity awareness (for contextual support)
- 📊 Real-time or post-session attention feedback
- 🎚️ Adjustable intervention level — from silent observer to focus coach
- 🔐 100% offline, privacy-respecting — no cloud, no tracking, no accounts

---

## 🧭 Manifesto

### 🎯 Our Purpose

We are building a tool to support and strengthen human focus — not to control, judge, or dictate it.  
This application is designed for people who want to improve their concentration, understand their patterns, and do so in a way that respects their autonomy and individuality.

### ✨ Core Principles

- **Respect the Individual** – You set the tone. The app adapts to your needs.
- **Support Without Surveillance** – All processing is local. Your data stays with you.
- **Customizable Involvement** – Choose how active the tool is in your focus sessions.
- **Empowerment Over Judgment** – No shaming, only encouragement and insight.
- **Built for Reflection and Growth** – Tools for understanding yourself, not optimizing you.

### 🛠️ Built-in Freedom

- Pause or disable any module  
- Choose your feedback style and tone  
- Export or erase your logs — or don’t log anything at all

---

## 🔧 Setup

### Requirements

- Python 3.8+
- macOS with webcam
- [Virtualenv](https://virtualenv.pypa.io/) or similar (recommended)

### Installation

```bash
git clone https://github.com/your-username/focusflow.git
cd focusflow
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python main.py

> **Note**  
> The prototype uses `MediaPipe`, `OpenCV`, and `numpy`.  
> Optional screen tracking modules may require elevated permissions on macOS.

---

## 📌 Roadmap

- [x] Local facial pose → attention score  
- [ ] Screen activity correlation module  
- [ ] User profile presets (Observer, Coach, Partner)  
- [ ] Session review dashboard  
- [ ] Full Swift GUI integration

---

## ❤️ Contributing

We welcome ideas, feedback, and collaborators who share the vision of humane tech.  
Feel free to open an Issue or submit a Pull Request.

---

## 📄 License

MIT License — Free to use, adapt, and build upon.

---

## 🙏 Acknowledgements

- [MediaPipe](https://github.com/google/mediapipe)  
- [OpenCV](https://opencv.org/)  
- Your attention. It matters.
