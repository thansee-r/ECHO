<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0B0F19,100:151B2E&height=200&section=header&text=ECHO&fontSize=72&fontColor=FFFFFF&fontAlign=50&fontAlignY=45&desc=GESTURE%20INTERFACE%20FOR%20THE%20TOUCHLESS%20ERA&descAlign=50&descAlignY=68&descSize=14&descColor=8B93A7" width="100%" alt="ECHO"/>

<br/>

**Control your computer with a single hand.**<br/>
Real-time gesture recognition through any webcam. No hardware. No contact.

<br/>

<img src="https://img.shields.io/badge/PYTHON-3.10.11-0B0F19?style=flat-square&logo=python&logoColor=5B8CFF&labelColor=0B0F19&color=1E2540" alt="Python"/>
<img src="https://img.shields.io/badge/PLATFORM-WINDOWS-0B0F19?style=flat-square&logo=windows&logoColor=5B8CFF&labelColor=0B0F19&color=1E2540" alt="Platform"/>
<img src="https://img.shields.io/badge/INPUT-WEBCAM-0B0F19?style=flat-square&logo=opencv&logoColor=5B8CFF&labelColor=0B0F19&color=1E2540" alt="Input"/>
<img src="https://img.shields.io/github/last-commit/thansee-r/ECHO?style=flat-square&labelColor=0B0F19&color=1E2540" alt="Last commit"/>
<img src="https://img.shields.io/github/stars/thansee-r/ECHO?style=flat-square&labelColor=0B0F19&color=1E2540" alt="Stars"/>

<br/><br/>

[**Overview**](#overview) &nbsp;·&nbsp; [**Modes**](#modes) &nbsp;·&nbsp; [**Installation**](#installation) &nbsp;·&nbsp; [**Architecture**](#architecture) &nbsp;·&nbsp; [**Team**](#team)

</div>

<br/>

<div align="center">

<!-- Replace with your hero demo GIF or video thumbnail (recommended: 1200 x 675) -->
<!-- <img src="assets/demo.gif" width="88%" alt="ECHO in action"/> -->

</div>

<br/>

## Overview

ECHO turns your webcam into an input device. Show your hand, pick a mode with your fingers, and control the experience with gestures. There is no extra hardware to buy and nothing to wear.

<br/>

<table>
  <tr>
    <td width="33%" valign="top">
      <h4>Touchless</h4>
      <sub>Operate everything with hand gestures alone. No mouse, no keyboard.</sub>
    </td>
    <td width="33%" valign="top">
      <h4>Instant</h4>
      <sub>Real-time recognition with live on-screen guidance for every gesture.</sub>
    </td>
    <td width="33%" valign="top">
      <h4>Hardware-free</h4>
      <sub>Works with the webcam you already have. Nothing to install but Python.</sub>
    </td>
  </tr>
</table>

<br/>

## Modes

Hold up fingers in front of the camera at launch to choose a mode.

<br/>

<table>
  <tr>
    <th align="center" width="25%">01</th>
    <th align="center" width="25%">02</th>
    <th align="center" width="25%">03</th>
    <th align="center" width="25%">04</th>
  </tr>
  <tr>
    <td align="center"><b>Assistive</b><br/><sub>1 finger</sub></td>
    <td align="center"><b>Presentation</b><br/><sub>2 fingers</sub></td>
    <td align="center"><b>Communication</b><br/><sub>3 fingers</sub></td>
    <td align="center"><b>Entertainment</b><br/><sub>4 fingers</sub></td>
  </tr>
  <tr>
    <td align="center" valign="top"><sub><!-- one-line description --></sub></td>
    <td align="center" valign="top"><sub><!-- one-line description --></sub></td>
    <td align="center" valign="top"><sub><!-- one-line description --></sub></td>
    <td align="center" valign="top"><sub><!-- one-line description --></sub></td>
  </tr>
</table>

<br/>

Once a mode is active, follow the on-screen instructions to perform its gestures.

<details>
<summary><b>Gesture reference</b></summary>
<br/>

| Mode | Gesture | Action |
|---|---|---|
| Assistive | <!-- gesture --> | <!-- action --> |
| Presentation | <!-- gesture --> | <!-- action --> |
| Communication | <!-- gesture --> | <!-- action --> |
| Entertainment | <!-- gesture --> | <!-- action --> |

</details>

<br/>

## Installation

> [!IMPORTANT]
> ECHO was developed and tested on **Python 3.10.x**. Use this version to avoid dependency conflicts.
> Recommended: [Python 3.10.11, Windows installer (64-bit)](https://www.python.org/downloads/release/python-31011/)

<br/>

**1. Clone the repository**

```bash
git clone https://github.com/thansee-r/ECHO.git
cd ECHO
```

**2. Create and activate a virtual environment**

```bash
python -m venv .venv
.venv\Scripts\activate          # Windows
# source .venv/bin/activate     # macOS / Linux
```

**3. Install dependencies**

```bash
pip install -r requirements.txt
```

**4. Run**

```bash
python main.py
```

<details>
<summary><b>Troubleshooting</b></summary>
<br/>

| Issue | Resolution |
|---|---|
| Dependency errors | Confirm `python --version` reports 3.10.x |
| Activation blocked in PowerShell | Run `Set-ExecutionPolicy -Scope Process RemoteSigned`, then retry |
| Camera fails to open | Close other apps using the webcam and check camera permissions |
| Gestures not detected | Improve lighting and keep one hand fully in frame |

</details>

<br/>

## Architecture

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#0B0F19','primaryBorderColor':'#5B8CFF','primaryTextColor':'#E6E9F2','lineColor':'#5B8CFF','secondaryColor':'#151B2E','tertiaryColor':'#0B0F19','fontFamily':'Inter, sans-serif'}}}%%
flowchart LR
    A[Webcam] --> B[Hand Detection]
    B --> C[Gesture Recognition]
    C --> D{Mode Selector}
    D --> E[Assistive]
    D --> F[Presentation]
    D --> G[Communication]
    D --> H[Entertainment]
```

<br/>

## Limitations

- Single-hand gesture recognition only
- Performance may vary under poor or uneven lighting

<br/>

## Roadmap

- [x] Real-time hand tracking
- [x] Four interaction modes
- [ ] Multi-hand support
- [ ] Improved low-light performance
- [ ] Expanded gesture library

<br/>

## Contributing

Pull requests are welcome. For major changes, open an issue first to discuss what you would like to change.

```bash
git checkout -b feature/your-feature
git commit -m "Add your feature"
git push origin feature/your-feature
```

<br/>

## Team

<div align="center">

<table>
  <tr>
    <td align="center" width="200">
      <a href="https://github.com/Rishi18360">
        <img src="https://github.com/Rishi18360.png?size=140" width="96" alt="Rishi Raj A"/><br/><br/>
        <b>Rishi Raj A</b><br/>
        <sub>@Rishi18360</sub>
      </a>
    </td>
    <td align="center" width="200">
      <a href="https://github.com/ihsansak">
        <img src="https://github.com/ihsansak.png?size=140" width="96" alt="Ihsan Sakeer"/><br/><br/>
        <b>Ihsan Sakeer</b><br/>
        <sub>@ihsansak</sub>
      </a>
    </td>
    <td align="center" width="200">
      <a href="https://github.com/thansee-r">
        <img src="https://github.com/thansee-r.png?size=140" width="96" alt="Thanseer Ahmed M S"/><br/><br/>
        <b>Thanseer Ahmed M S</b><br/>
        <sub>@thansee-r</sub>
      </a>
    </td>
    <td align="center" width="200">
      <a href="https://github.com/AshwinSabu05">
        <img src="https://github.com/AshwinSabu05.png?size=140" width="96" alt="Ashwin Sabu"/><br/><br/>
        <b>Ashwin Sabu</b><br/>
        <sub>@AshwinSabu05</sub>
      </a>
    </td>
  </tr>
</table>

</div>

<br/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:151B2E,100:0B0F19&height=80&section=footer" width="100%" alt=""/>

<sub>If ECHO is useful to you, consider starring the repository.</sub>

</div>
