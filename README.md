<div align="center">

<img src="assets/banner.svg" alt="J.A.R.V.I.S - Voice assistant for Windows" width="100%"/>

<br/>

<a href="../../releases/latest">
  <img src="https://img.shields.io/badge/%E2%AC%87%EF%B8%8F%20%20DOWNLOAD%20NOW-00e5ff?style=for-the-badge&labelColor=02080d" alt="Download" height="52"/>
</a>

<sub><b>Windows • Free • No Python needed</b></sub>

<br/><br/>

[✨ Features](#-features) &nbsp;•&nbsp; [⬇️ Install](#%EF%B8%8F-download--install) &nbsp;•&nbsp; [🗣️ Commands](#%EF%B8%8F-try-saying) &nbsp;•&nbsp; [⚙️ AI Setup](#%EF%B8%8F-optional-enable-ai-answers) &nbsp;•&nbsp; [❓ FAQ](#-faq)

</div>

<!-- 📸 ADD YOUR REAL HUD SCREENSHOT / GIF HERE (most important part!)
<div align="center"><img src="assets/screenshot.png" width="85%" alt="JARVIS HUD"/></div>
-->

<img src="assets/divider.svg" width="100%" alt=""/>

## 👋 What is JARVIS?

**JARVIS** is a voice-controlled desktop assistant with a glowing sci-fi **arc-reactor HUD**.

Just talk to it like a friend. It opens your apps, checks your PC, tests your internet, sets timers, takes notes, answers questions, and even cheers you up. It talks back in a natural voice, and the text on screen stays in sync with the speech.

> **Download → Extract → Double-click → Talk.** &nbsp; That's the whole setup.

<div align="center">

| 🎙️ **Hands-free** | ⚡ **Instant** | 🧠 **Friendly** | 🔒 **Private** |
|:---:|:---:|:---:|:---:|
| Just say "Jarvis" | Runs right on your PC | Talks like a human, not a robot | Your notes stay on your computer |

</div>

### 🔄 How it works

<div align="center">

| **1️⃣ &nbsp;SAY** | ➜ | **2️⃣ &nbsp;THINK** | ➜ | **3️⃣ &nbsp;ACT & REPLY** |
|:---:|:---:|:---:|:---:|:---:|
| *"Jarvis, open YouTube"* | | JARVIS understands you | | Does it, and answers in voice + on screen |

</div>

<img src="assets/divider.svg" width="100%" alt=""/>

## ⬇️ Download & Install

> ### ⚠️ IMPORTANT: download BOTH
> JARVIS will **not** work with the `.exe` alone. You need these two together:
>
> | # | Download | What it is |
> |:-:|---|---|
> | **1** | 📄 **`Jarvis.exe`** | The app |
> | **2** | 📁 **`_internal`** folder | Files the app needs to run |
>
> **Keep them side by side in the same folder.**

### 🚀 Quick Start

| Step | What to do |
|:---:|---|
| **1** | 📥 Download **`Jarvis.exe`** **and** the **`_internal`** folder (or grab the ZIP from [Releases](../../releases/latest) if available) |
| **2** | 📁 Put both in **one folder**, for example `C:\Jarvis\` |
| **3** | 🖱️ Double-click **`Jarvis.exe`** |
| **4** | 🎤 Allow microphone access when Windows asks |
| **5** | 🗣️ Say **"Jarvis, hello"** and enjoy! |

Your folder should look like this:

```
📁 Jarvis
 ├── 📄 Jarvis.exe
 └── 📁 _internal
```

> 💡 **Windows SmartScreen warning?** Click **More info → Run anyway**. This appears for any new app that is not digitally signed.

<img src="assets/divider.svg" width="100%" alt=""/>

## ✨ Features

<table>
<tr>
<td width="50%" valign="top">

### 🎙️ Natural Voice Control
- Wake word: **"Jarvis"** (even catches mis-hearings)
- Adjustable mic sensitivity + **far-field mode**
- Switchable recognition accent
- Understands **Bangla / Banglish** small talk

### 💻 Control Your PC
- Open apps, websites & settings pages
- Volume and brightness control
- Minimize all / switch windows
- Screenshots, empty recycle bin
- Shutdown / restart with **voice confirmation**

### 🧠 Smart Conversation
- Warm, human-like replies
- Reacts to your mood and good news
- Ask anything with an AI model *(optional)*
- Remembers things you tell it

</td>
<td width="50%" valign="top">

### 📊 System Monitor
- CPU, RAM, GPU, storage, battery, uptime
- See which apps are eating resources
- Full PC specs on request

### 🌐 Network Toolkit
- Internet **speed test**
- Local & public IP, Wi-Fi info
- **"Who's on my Wi-Fi?"** LAN scan
- Ping any host, open ports, data usage
- Live network alerts

### 🛠️ Handy Extras
- ⏱️ Timers
- 🌦️ Weather
- 📝 Voice notes
- 📞 Phone calls via ADB *(optional)*
- 🔧 Your own shortcuts & custom replies

</td>
</tr>
</table>

### 🎨 Sci-Fi HUD

A glowing cyan **arc-reactor interface** that comes alive while JARVIS listens, thinks and speaks.

<img src="assets/divider.svg" width="100%" alt=""/>

## 🗣️ Try Saying

<table>
<tr>
<td width="50%" valign="top">

**💻 Your PC**
```text
"Jarvis, open YouTube"
"Jarvis, open Chrome in incognito"
"Jarvis, set volume to 40"
"Jarvis, take a screenshot"
"Jarvis, how much RAM do I have?"
"Jarvis, which apps are using my CPU?"
```

</td>
<td width="50%" valign="top">

**🌐 Network & Extras**
```text
"Jarvis, run a speed test"
"Jarvis, who is on my Wi-Fi?"
"Jarvis, what's my IP address?"
"Jarvis, set a timer for 10 minutes"
"Jarvis, what's the weather?"
"Jarvis, tell me a fun fact"
```

</td>
</tr>
</table>

> 💬 You can also just chat: *"I'm bored"*, *"How are you?"*, *"I passed my exam!"*

<img src="assets/divider.svg" width="100%" alt=""/>

## ⚙️ Optional: Enable AI Answers

For general-knowledge questions, JARVIS can use an AI model through any OpenAI-compatible API (Groq by default).

Create a file named **`jarvis_config.json`** next to `Jarvis.exe`:

```json
{
  "llm": {
    "api_key": "YOUR_API_KEY_HERE",
    "base_url": "https://api.groq.com/openai/v1",
    "model": "llama-3.3-70b-versatile"
  }
}
```

> 🔒 **Never share your API key** or upload this file to GitHub.

<details>
<summary><b>🔧 Add your own websites & apps (click to expand)</b></summary>

<br/>

```json
{
  "sites": { "my blog": "https://example.com" },
  "apps":  { "my editor": "C:\\Path\\To\\App.exe" }
}
```

Then just say *"Jarvis, open my blog"*.

</details>

<img src="assets/divider.svg" width="100%" alt=""/>

## 💻 System Requirements

| | |
|---|---|
| 🪟 **OS** | Windows 10 / 11 (64-bit) |
| 🎤 **Microphone** | Any working mic |
| 🌐 **Internet** | Needed for speech recognition, weather and AI answers |
| 🐍 **Python** | ❌ Not needed |

<img src="assets/divider.svg" width="100%" alt=""/>

## ❓ FAQ

<details>
<summary><b>The app won't open / shows a missing file error</b></summary>

<br/>

Make sure `Jarvis.exe` and the `_internal` folder are in the **same folder**. Never move the exe out on its own.

</details>

<details>
<summary><b>JARVIS can't hear me</b></summary>

<br/>

Check your Windows microphone permissions and default input device. Then try saying *"increase sensitivity"* or *"I am far from the mic"*.

</details>

<details>
<summary><b>Windows Defender / SmartScreen blocks it</b></summary>

<br/>

Click **More info → Run anyway**. The app is not code-signed yet, so Windows is cautious with new programs.

</details>

<details>
<summary><b>Does it work on Mac or Linux?</b></summary>

<br/>

Not yet. JARVIS is Windows only for now.

</details>

<img src="assets/divider.svg" width="100%" alt=""/>

## 💬 Feedback & Support

Found a bug or have a feature idea? Open an [Issue](../../issues) and tell me. I read every one!

If you enjoy JARVIS, please **⭐ star this repo**. It really helps!

## 📜 License

JARVIS is **free to use** for personal use. The source code is **not public**, and redistribution, modification or reselling of the app is not allowed without permission.

© 2026 Abu Tanim. All rights reserved.

<div align="center">

<br/>

**Made with ❤️ by [Mr. Tan](https://github.com/Mr74nX)**

*"Sometimes you gotta run before you can walk."*

<img src="assets/divider.svg" width="100%" alt=""/>

</div>
