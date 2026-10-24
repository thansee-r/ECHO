<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:000000,40:1a0033,100:003b4d&height=260&section=header&text=ECHO&fontSize=90&fontColor=00F0FF&animation=twinkling&fontAlignY=40&stroke=FF00E5&strokeWidth=2&desc=Your%20hand%20is%20the%20controller&descAlignY=65&descSize=22&descColor=ffffff" width="100%" alt="ECHO"/>

<a href="https://github.com/thansee-r/ECHO">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&pause=1000&color=FF00E5&center=true&vCenter=true&width=650&height=40&lines=%F0%9F%96%90%EF%B8%8F+Wave+hello+to+touch-free+computing;%E2%98%9D%EF%B8%8F+%E2%9C%8C%EF%B8%8F+%F0%9F%A4%9F+%F0%9F%96%96+Pick+a+mode+with+your+fingers;No+mouse.+No+keyboard.+Just+a+webcam." alt="typing"/>
</a>

<br/><br/>

![Python](https://img.shields.io/badge/PYTHON-3.10.11-00F0FF?style=for-the-badge&logo=python&logoColor=black&labelColor=0d1117)
![Platform](https://img.shields.io/badge/PLATFORM-WINDOWS-FF00E5?style=for-the-badge&logo=windows&logoColor=white&labelColor=0d1117)
![Input](https://img.shields.io/badge/INPUT-WEBCAM-00F0FF?style=for-the-badge&logo=opencv&logoColor=black&labelColor=0d1117)
![Modes](https://img.shields.io/badge/MODES-4-FF00E5?style=for-the-badge&labelColor=0d1117)

![Stars](https://img.shields.io/github/stars/thansee-r/ECHO?style=social)
![Forks](https://img.shields.io/github/forks/thansee-r/ECHO?style=social)
![Last Commit](https://img.shields.io/github/last-commit/thansee-r/ECHO?style=flat-square&color=00F0FF&labelColor=0d1117)
![Repo Size](https://img.shields.io/github/repo-size/thansee-r/ECHO?style=flat-square&color=FF00E5&labelColor=0d1117)

<br/>

### ⚡ [Quick Start](#-quick-start) &nbsp;•&nbsp; 🎯 [Modes](#-the-4-modes) &nbsp;•&nbsp; 🧠 [How It Works](#-how-it-works) &nbsp;•&nbsp; 🗺️ [Roadmap](#️-roadmap) &nbsp;•&nbsp; 👥 [Team](#-the-team)

</div>

<br/>

---

## 🎬 Demo

<div align="center">

<!-- 👉 Replace with your main demo GIF (recommended width: 800px) -->
<!-- <img src="assets/demo.gif" width="85%" alt="ECHO demo"/> -->

<sub>📹 Add a demo GIF here: it is the first thing visitors look at.</sub>

</div>

---

## 💡 Why ECHO?

<table>
<tr>
<td align="center" width="25%">
<h3>🖐️</h3>
<b>Touch-Free</b><br/>
<sub>Control everything with your hand</sub>
</td>
<td align="center" width="25%">
<h3>📷</h3>
<b>Just a Webcam</b><br/>
<sub>No gloves, sensors or extra gear</sub>
</td>
<td align="center" width="25%">
<h3>⚡</h3>
<b>Real-Time</b><br/>
<sub>Instant recognition, live feedback</sub>
</td>
<td align="center" width="25%">
<h3>🎛️</h3>
<b>4 Modes</b><br/>
<sub>One app, many use cases</sub>
</td>
</tr>
</table>

---

## 🎯 The 4 Modes

> Hold up fingers in front of the webcam after launch. ECHO switches modes instantly.

<div align="center">

| ☝️ **1 Finger** | ✌️ **2 Fingers** | 🤟 **3 Fingers** | 🖖 **4 Fingers** |
|:---:|:---:|:---:|:---:|
| 🦾 **Assistive** | 📊 **Presentation** | 💬 **Communication** | 🎮 **Entertainment** |
| <sub>description</sub> | <sub>description</sub> | <sub>description</sub> | <sub>description</sub> |
| <!-- <img src="assets/assistive.gif" width="170"/> --> | <!-- <img src="assets/presentation.gif" width="170"/> --> | <!-- <img src="assets/communication.gif" width="170"/> --> | <!-- <img src="assets/entertainment.gif" width="170"/> --> |

</div>

<details>
<summary><b>🦾 Assistive Mode: gestures</b></summary>
<br/>

| Gesture | Action |
|---|---|
| <!-- gesture --> | <!-- action --> |

</details>

<details>
<summary><b>📊 Presentation Mode: gestures</b></summary>
<br/>

| Gesture | Action |
|---|---|
| <!-- gesture --> | <!-- action --> |

</details>

<details>
<summary><b>💬 Communication Mode: gestures</b></summary>
<br/>

| Gesture | Action |
|---|---|
| <!-- gesture --> | <!-- action --> |

</details>

<details>
<summary><b>🎮 Entertainment Mode: gestures</b></summary>
<br/>

| Gesture | Action |
|---|---|
| <!-- gesture --> | <!-- action --> |

</details>

---

## 🧠 How It Works

```mermaid
%%{init: {'theme':'dark','themeVariables':{'primaryColor':'#1a0033','primaryBorderColor':'#00F0FF','lineColor':'#FF00E5','primaryTextColor':'#ffffff'}}}%%
flowchart LR
    A[📷 Webcam Feed] --> B[🖐️ Hand Detection]
    B --> C[🔢 Finger / Gesture Recognition]
    C --> D{🎛️ Mode Selector}
    D -->|1| E[🦾 Assistive]
    D -->|2| F[📊 Presentation]
    D -->|3| G[💬 Communication]
    D -->|4| H[🎮 Entertainment]
```

---

## 🚀 Quick Start

> [!IMPORTANT]
> ECHO was built and tested on **Python 3.10.x**. Use this version to avoid dependency issues.
> 📥 Recommended: [**Python 3.10.11** (Windows installer, 64-bit)](https://www.python.org/downloads/release/python-31011/)

```bash
# 1️⃣  Clone the repo
git clone https://github.com/thansee-r/ECHO.git
cd ECHO

# 2️⃣  Create a virtual environment
python -m venv .venv

# 3️⃣  Activate it
.venv\Scripts\activate            # Windows
# source .venv/bin/activate       # macOS / Linux

# 4️⃣  Install dependencies
pip install -r requirements.txt

# 5️⃣  Launch ECHO 🚀
python main.py
```

<details>
<summary><b>💻 Using VS Code?</b></summary>
<br/>

```bash
cd ECHO
code .
```

Open the integrated terminal with `` Ctrl + ` `` and continue from step 2.

</details>

<details>
<summary><b>🛠️ Troubleshooting</b></summary>
<br/>

| Problem | Fix |
|---|---|
| Dependency errors on install | Confirm `python --version` shows **3.10.x** |
| `activate` is blocked in PowerShell | Run `Set-ExecutionPolicy -Scope Process RemoteSigned`, then activate again |
| Camera does not open | Close other apps using the webcam and check camera permissions |
| Gestures are not detected | Improve lighting and keep one hand fully in frame |

</details>

---

## ⚠️ Limitations

> [!WARNING]
> - ✋ **Single-hand** gesture recognition only
> - 💡 Performance may vary in **poor or uneven lighting**

---

## 🗺️ Roadmap

- [x] Real-time hand tracking via webcam
- [x] Four interaction modes
- [ ] Multi-hand gesture support
- [ ] Better low-light performance
- [ ] More gestures per mode

<sub>Edit this list to match your real plans.</sub>

---

## 🛠️ Built With

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
<!-- ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white) -->
<!-- ![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge&logo=google&logoColor=white) -->

---

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

1. 🍴 Fork the repo
2. 🌿 Create a branch: `git checkout -b feature/amazing-gesture`
3. 💾 Commit: `git commit -m "Add amazing gesture"`
4. 📤 Push: `git push origin feature/amazing-gesture`
5. 🔀 Open a Pull Request

---

## 👥 The Team

<div align="center">

<table>
  <tr>
    <td align="center" width="200">
      <a href="https://github.com/Rishi18360">
        <img src="https://github.com/Rishi18360.png?size=140" width="120" alt="Rishi Raj A"/><br/><br/>
        <b>Rishi Raj A</b><br/>
        <sub>@Rishi18360</sub>
      </a>
    </td>
    <td align="center" width="200">
      <a href="https://github.com/ihsansak">
        <img src="https://github.com/ihsansak.png?size=140" width="120" alt="Ihsan Sakeer"/><br/><br/>
        <b>Ihsan Sakeer</b><br/>
        <sub>@ihsansak</sub>
      </a>
    </td>
    <td align="center" width="200">
      <a href="https://github.com/thansee-r">
        <img src="https://github.com/thansee-r.png?size=140" width="120" alt="Thanseer Ahmed M S"/><br/><br/>
        <b>Thanseer Ahmed M S</b><br/>
        <sub>@thansee-r</sub>
      </a>
    </td>
    <td align="center" width="200">
      <a href="https://github.com/AshwinSabu05">
        <img src="https://github.com/AshwinSabu05.png?size=140" width="120" alt="Ashwin Sabu"/><br/><br/>
        <b>Ashwin Sabu</b><br/>
        <sub>@AshwinSabu05</sub>
      </a>
    </td>
  </tr>
</table>

</div>

---

<div align="center">

### ⭐ If ECHO impressed you, drop a star!

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:003b4d,50:1a0033,100:000000&height=140&section=footer" width="100%" alt="footer"/>

</div>
