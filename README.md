<div align="center">

# 🤖 J.A.R.V.I.S

### Your own Iron-Man-style voice assistant for Windows

*Say **"Jarvis"** — and your PC listens.*

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011-00e5ff?style=for-the-badge&logo=windows&logoColor=white)
![Python](https://img.shields.io/badge/built%20with-Python-ffb300?style=for-the-badge&logo=python&logoColor=white)
![Price](https://img.shields.io/badge/price-FREE-2ea44f?style=for-the-badge)
![No Install](https://img.shields.io/badge/install-NOT%20REQUIRED-ff3b3b?style=for-the-badge)

<!-- 📸 Add a screenshot or GIF of your HUD here. This is the most important part! -->
<!-- <img src="assets/screenshot.png" width="800" alt="JARVIS HUD"> -->

[⬇️ **Download Now**](../../releases/latest) · [✨ Features](#-features) · [🗣️ Commands](#%EF%B8%8F-try-saying) · [❓ FAQ](#-faq)

</div>

---

## 👋 What is JARVIS?

JARVIS is a **voice-controlled desktop assistant** with a glowing sci-fi **arc-reactor HUD**.
Talk to it like a friend: open apps, check your PC, test your internet, set timers, take notes, ask questions, or just chat.
It talks back to you in a natural voice, and the text on screen stays in sync with the speech.

No complicated setup. **Download → Extract → Double-click → Talk.**

---

## ⬇️ Download & Install (2 minutes)

> ### ⚠️ IMPORTANT
> JARVIS needs **both** of these together. The app will **not** work with the `.exe` alone.
>
> | # | What to download | Why |
> |---|---|---|
> | 1 | **`Jarvis.exe`** | The app itself |
> | 2 | **`_internal`** folder | Required files the app runs on |
>
> **Keep them in the same folder, side by side!**

### Step by step

1. 📥 Download **`Jarvis.exe`** **and** the **`_internal`** folder from this repository (or grab the ZIP from [Releases](../../releases/latest) if available).
2. 📁 Put both in **one folder** (for example `C:\Jarvis\`). It should look like this:

   ```
   Jarvis/
   ├── Jarvis.exe
   └── _internal/
   ```
3. 🖱️ Double-click **`Jarvis.exe`**.
4. 🎤 Allow microphone access if Windows asks.
5. 🗣️ Say **"Jarvis, hello"**. That's it!

> 💡 **Tip:** If Windows SmartScreen shows a warning, click **More info → Run anyway**. This happens with any new app that isn't digitally signed.

---

## ✨ Features

<table>
<tr>
<td width="50%" valign="top">

### 🎙️ Natural Voice Control
- Wake word: **"Jarvis"** (also catches mis-hearings)
- Adjustable mic sensitivity, with a *far-field* mode
- Switch recognition accent
- Understands some **Bangla / Banglish** small talk too

### 💻 Control Your PC
- Open apps, websites and settings pages
- Volume & brightness control
- Minimize all / switch windows
- Screenshot, empty recycle bin
- Shutdown / restart with **voice confirmation**

### 🧠 Smart Conversation
- Friendly, human-like replies, not robotic
- Reacts to your mood and good news
- Ask anything, powered by an AI model *(optional, see setup)*
- Remembers things you tell it (notes & personal memory)

</td>
<td width="50%" valign="top">

### 📊 System Monitor
- CPU, RAM, GPU, storage, battery, uptime
- See which apps are eating your resources
- Full PC specs on request

### 🌐 Network Toolkit
- Internet **speed test**
- Local & public IP, Wi-Fi info
- **Who's on my Wi-Fi?** LAN scan
- Ping any host, open ports, data usage
- Live network alerts

### 🛠️ Handy Extras
- ⏱️ Timers
- 🌦️ Weather
- 📝 Voice notes
- 📞 Phone calls via ADB *(optional)*
- 🔧 Custom sites, apps & custom replies via config

</td>
</tr>
</table>

### 🎨 Sci-Fi HUD
A glowing cyan **arc-reactor interface** that animates while JARVIS listens, thinks and speaks.

---

## 🗣️ Try Saying

```text
"Jarvis, open YouTube"
"Jarvis, open Chrome in incognito"
"Jarvis, set volume to 40"
"Jarvis, how much RAM do I have?"
"Jarvis, which apps are using my CPU?"
"Jarvis, run a speed test"
"Jarvis, who is on my Wi-Fi?"
"Jarvis, set a timer for 10 minutes"
"Jarvis, what's the weather?"
"Jarvis, take a screenshot"
"Jarvis, tell me a fun fact"
"Jarvis, I'm bored"
```

---

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

> 🔒 Never share your API key or upload this file to GitHub.

You can also add your own shortcuts:

```json
{
  "sites": { "my blog": "https://example.com" },
  "apps":  { "my editor": "C:\\Path\\To\\App.exe" }
}
```

---

## 💻 System Requirements

| | |
|---|---|
| **OS** | Windows 10 / 11 (64-bit) |
| **Microphone** | Any working mic |
| **Internet** | Needed for speech recognition, weather and AI answers |
| **Python** | ❌ Not needed |

---

## ❓ FAQ

**The app won't open / shows a missing file error.**
Make sure `Jarvis.exe` and the `_internal` folder are in the **same folder**. Don't move the exe out alone.

**JARVIS can't hear me.**
Check Windows microphone permissions and your default input device. Try saying *"increase sensitivity"* or *"I am far from the mic"*.

**Windows Defender / SmartScreen blocks it.**
Click **More info → Run anyway**. The app is not code-signed, so Windows is cautious with new programs.

**Does it work on Mac or Linux?**
Currently Windows only.

---

## 💬 Feedback & Support

Found a bug or have a feature idea? Open an [Issue](../../issues) and tell me. I read every one!

If you like JARVIS, please **⭐ star this repo**. It really helps!

---

## 📜 License

JARVIS is **free to use** for personal use. The source code is **not public**, and redistribution, modification or reselling of the app is not allowed without permission.

© 2026 Abu Tanim. All rights reserved.

---

<div align="center">

**Made with ❤️ by [Mr. Tan](https://github.com/Mr74nX)**

*"Sometimes you gotta run before you can walk."*

</div>
