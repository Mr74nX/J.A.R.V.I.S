<div align="center">

# 📖 J.A.R.V.I.S. — Full Manual

<sub>Version 3.3.3 &nbsp;•&nbsp; Windows 10/11 &nbsp;•&nbsp; [← Back to README](README.md)</sub>

</div>

<img src="assets/divider.svg" width="100%" alt=""/>

## Contents

1. [Install & first minute](#install--first-minute)
2. [How JARVIS listens](#how-jarvis-listens)
3. [Every command](#every-command)
4. [The HUD tabs](#the-hud-tabs)
5. [AI features (optional)](#ai-features-optional)
6. [Security toolkit](#security-toolkit)
7. [WhatsApp & phone calls](#whatsapp--phone-calls)
8. [Reminders](#reminders)
9. [Reading your screen](#reading-your-screen)
10. [Building code & websites](#building-code--websites)
11. [Updates](#updates)
12. [Settings reference](#settings-reference)
13. [Privacy](#privacy)
14. [Troubleshooting](#troubleshooting)
15. [Limitations](#limitations)
16. [Responsible use](#responsible-use)

<img src="assets/divider.svg" width="100%" alt=""/>

## Install & first minute

1. Download the ZIP from [Releases](../../releases/latest), extract it anywhere, and run `Jarvis.exe`.
2. Allow microphone access when Windows asks.
3. JARVIS greets you. Say **"what time is it"** to check it's listening.
4. Say **"help"**, or press the **HELP** button, for a clickable list of everything JARVIS can do.
5. Open **Settings → Microphone** and talk — the live level bar should jump past the white line. If it barely moves, raise the sensitivity or say **"I am far away"**.
6. Tell it your name: **"my name is …"**. It remembers and uses it from then on.
7. If anything seems broken at any point, say **"run a self test"** — it checks the microphone, internet, speech service, both voices and the command engine, and shows a ticked report.

<img src="assets/divider.svg" width="100%" alt=""/>

## How JARVIS listens

- **Always on by default** — just talk, no button needed. Turn on **Wake word** in Settings if you want JARVIS to only react when you start with "Jarvis" (useful in a noisy room or if others are talking nearby).
- JARVIS continuously measures the room's background noise and keeps its detection level just above it, so quiet and distant speech is still caught and your sentence isn't cut at the start.
- **Settings → Microphone** has: input device (if you have more than one mic), sensitivity (*Normal / High / Far-field*), recognition accent (try *English (India)* for a South Asian accent), and a live level meter.
- Also raise the microphone volume in **Windows Settings → System → Sound → Input** — it helps more than anything else.
- If the mic ever stops responding, say **"restart the microphone"**, or it will restart itself automatically within a few seconds.

<img src="assets/divider.svg" width="100%" alt=""/>

## Every command

JARVIS understands natural **English** sentences — these are just reliable examples, not the only way to say things.

### System & PC
| Say | Result |
|---|---|
| "tell me about my PC" / "what are my specs" | Model, CPU, RAM, GPU, storage, uptime |
| "what is using my CPU" / "why is my PC slow" | Busiest apps + a health verdict |
| "how much RAM/storage do I have" | Specific figures |
| "set volume to 40" / "brightness 60" | Direct control |
| "pause" / "next song" / "previous track" | Media keys |
| "lock the PC" / "sleep" / "hibernate" | Power (instant) |
| "shut down" / "restart" / "shut down in 10 minutes" / "cancel shutdown" | Power (**always confirms first**) |
| "take a screenshot" / "show desktop" / "close Chrome" | Everyday helpers |
| "run a security check" | Full PC security audit — see [Security toolkit](#security-toolkit) |

### Apps, web & search
| Say | Result |
|---|---|
| "open Chrome" / "open Notepad" / "open WhatsApp" | Any installed app, even Microsoft Store apps |
| "open ChatGPT" / "open Gemini" / "open an AI site" | 38 AI websites built in, flexible pronunciation |
| "open YouTube in Firefox" / "open incognito YouTube" | Choice of browser or private mode |
| "go to example dot com" / "open Downloads" | Websites & folders |
| "search python on YouTube" | Site-specific search (Amazon, Maps, Wikipedia, GitHub…) |
| "new tab" / "close tab" / "refresh" / "scroll down" | Browser keys (JARVIS briefly hides itself so the keys reach your browser) |

### Network
| Say | Result |
|---|---|
| "network status" | Online? latency, Wi-Fi, speed |
| "speed test" | Download + upload |
| "ping google" | Latency to any host |
| "who is connected to my Wi-Fi" | Scans **your own** network for devices |
| "what apps are using the internet" / "open ports" / "data usage" | Details |
| "turn on/off network alerts" | Spoken warnings when the internet drops or recovers |

### Facts & research
| Say | Result |
|---|---|
| "what is the capital of Bangladesh" / "who founded Microsoft" / "when was Einstein born" | Exact answer from Wikidata — **no API key needed** |
| "what does ubiquitous mean" | Dictionary definition — no key needed |
| "convert 100 dollars to taka" / "convert 5 km to miles" | Live conversion — no key needed |
| "translate thank you into Bangla" / "how do you say good morning in Hindi" | Quick translation |
| "what is Bangladesh" / "research electric cars" | Multi-source web research (better with a free AI key, works without one) |
| "tell me more" | Continues the last answer |
| "tell me the news" / "technology news" / "news in Japan" | Live headlines — see [the HUD tabs](#the-hud-tabs) |

### Memory & personality
| Say | Result |
|---|---|
| "my name is …" / "call me boss" | Remembered and used from then on |
| "remember that my birthday is 5 May" → later "when is my birthday" | Facts you teach it |
| "if someone asks who made you, say …" | Custom taught answers |
| "what do you remember" / "forget …" / "forget everything" | Manage memory |
| "welcome me" / "welcome Rahim" | Greetings — "welcome **to** me" greets *you* |
| "wish Nila happy birthday" / "tell Rahim that dinner is ready" | Speaks your messages and wishes |
| "I won!" / "I am sad" / "my exam is tomorrow" | Notices your mood and replies kindly |

### Reminders — see [full section](#reminders)
### Deadlines & countdowns — see [full section](#reminders)
### WhatsApp & calls — see [full section](#whatsapp--phone-calls)
### Reading your screen — see [full section](#reading-your-screen)
### Security — see [full section](#security-toolkit)

### Copy & paste
| Say | Result |
|---|---|
| "copy that" / "copy the answer" | Copies JARVIS's last spoken reply to the clipboard |
| "copy the project folder" | Copies the path of the last thing JARVIS built |
| "paste that" | Pastes your clipboard into whatever window is behind JARVIS |

### Fun
"hack the Rahim" (a harmless fake-hacking screen for friends — press **Esc** to stop, nothing real is touched) · "suit up" (gold theme) · "tell me a joke" · "I am bored"

<img src="assets/divider.svg" width="100%" alt=""/>

## The HUD tabs

Use the tabs at the top, say *"show network monitor"*, or press **Alt+1 … Alt+9** (Alt+0 for Settings).

| Tab | What's there |
|---|---|
| **Home** | Arc reactor, live gauges, globe, clock, conversation log |
| **System** | Specs, live load per core, drives, top processes with an **END** button |
| **Network** | Live traffic & latency graphs, Wi-Fi, apps using the internet, open ports, Scan/Speed test/Ping |
| **Apps** | Search and launch every installed app, website, or folder |
| **Control** | Volume/brightness sliders, media buttons, power buttons (each asks first) |
| **Memory** | What JARVIS remembers, taught answers, saved contacts |
| **Reminders** | Everything you've asked to be reminded about |
| **News** | Pick a category or country, click a headline for options |
| **Security** | Security check, CVE lookup, link checker, scam-message checker, password tools, hash/encode tools |
| **Settings** | Voice, microphone (with live meter), theme, updates, self-test |

**Keyboard:** `Ctrl+K` or `/` to type · `?` or `F1` for help · `Esc` closes pop-ups or stops the prank.

<img src="assets/divider.svg" width="100%" alt=""/>

## AI features (optional)

JARVIS is fully useful with **no key at all**. A free key (from [Groq](https://console.groq.com), no card needed) adds:

- **Research in its own words** — instead of a compressed summary of sources, the AI rewrites the answer entirely, names its sources, and says if they disagree.
- **"Explain this" for your screen** — a proper explanation of error messages, articles, or code, instead of a basic local summary.
- **Code & website building** — see [below](#building-code--websites).

Create `jarvis_config.json` next to `Jarvis.exe` (copy `jarvis_config.example.json`):

```json
{
  "pause": 0.65,
  "llm": { "base_url": "https://api.groq.com/openai/v1", "api_key": "YOUR_FREE_API_KEY_HERE", "model": "llama-3.3-70b-versatile" },
  "vision": { "model": "<a vision-capable model, for describing pictures on screen>" },
  "google": { "api_key": "YOUR_GOOGLE_API_KEY", "cx": "YOUR_SEARCH_ENGINE_ID" },
  "virustotal": { "api_key": "YOUR_FREE_VIRUSTOTAL_KEY" },
  "country_code": "880",
  "update": { "repo": "owner/repository" },
  "apps":  { "my editor": "C:\\Path\\To\\App.exe" },
  "sites": { "my blog": "https://example.com" }
}
```

| Key | What it unlocks |
|---|---|
| `llm` | AI-written answers and the code builder |
| `vision` | A proper picture description for "describe my screen" (asks permission every time before sending a screenshot) |
| `google` | 100 free official Google searches/day, more reliable than JARVIS reading Google's page itself |
| `virustotal` | An extra malware-scanner opinion in the Deep Scan link check |
| `country_code` | Default country for WhatsApp numbers saved without one |
| `apps` / `sites` | Your own shortcuts |

**Never share these keys, and never commit `jarvis_config.json` to GitHub** — the provided `.gitignore` already excludes it.

<img src="assets/divider.svg" width="100%" alt=""/>

## Security toolkit

All checks run **only on this PC and your own network**. JARVIS will not scan or attack anyone else's systems, and refuses to write exploits or malware.

**PC security check** — say *"run a security check"* or open the **Security** tab. Checks: antivirus & real-time protection, firewall, Remote Desktop, the old insecure SMBv1 protocol, User Account Control, the Guest account, automatic login, shared folders, how many admin accounts exist, Windows Update recency, BitLocker, startup programs, risky open network ports, and Wi-Fi encryption — with a 0–100 score and a fix for each issue. Some checks see more when JARVIS runs as administrator.

**Phishing & scam detection:**
- *Link check* (paste a link): flags non-HTTPS links, raw IP addresses, look-alike brand spellings (`paypa1.com`, `rnicrosoft.com`), brand names stuffed into an unrelated domain, link shorteners, risky domains, and more — scored 0–100.
- *Deep Scan*: additionally checks the link against public phishing/malware block-lists, how recently the domain was registered, and follows shortened links to their real destination. With a free VirusTotal key, it adds a malware-engine opinion too.
- *Suspicious message check* (paste an SMS/email/WhatsApp text): looks for urgency ("act now"), requests for your OTP/PIN/password, prize and lottery scams, requests to send money, and suspicious links — together, with a risk score.
- *By voice*: "is this link safe, <link>", "check this message for scams", "is the link in my clipboard safe".
- **This is pattern-matching, not a guarantee.** When in doubt, contact the company directly using a number or address you already know — never one from the message itself.

**Other tools:** "tell me about CVE-2021-44228", "latest critical vulnerabilities" (NIST database) · "generate a strong password" (copied to your clipboard, never spoken aloud) · "check my password" (tests strength and checks Have I Been Pwned — only 5 characters of the password's hash ever leave your PC) · hash/Base64/URL/JWT tools, all local.

<img src="assets/divider.svg" width="100%" alt=""/>

## WhatsApp & phone calls

1. **Save a contact first:** "save Rahim's number as 01712345678" (digits can be spoken: "zero one seven…"), or add one on the **Memory** tab.
2. **Messages:** "send Rahim a WhatsApp saying are we still meeting today" — JARVIS repeats the message back and waits for **"yes"** before sending.
3. **Calls:** "call Rahim on WhatsApp" / "video call Rahim on WhatsApp", or "call Rahim" (a regular phone call).

**Two ways to actually place the call** (JARVIS cannot use Bluetooth calling directly — Windows doesn't allow apps to do that):

| Method | Setup | What you get |
|---|---|---|
| **Phone Link** (Bluetooth) | Install Phone Link, pair your phone with Calls enabled | JARVIS opens WhatsApp Desktop/Web or a `tel:` link; it tries to press the call button for you, but depending on your WhatsApp/Phone Link version you may need to press it yourself |
| **ADB** (phone dials itself) | Install Android *platform-tools*, put the folder next to JARVIS, enable USB debugging, connect and authorise | Fully automatic — "call", "hang up" and "answer" all work by voice, and WhatsApp calls are placed directly from your phone |

Choose the method in **Settings → Calling method** (Auto picks whichever is ready), and check what's set up with **Settings → Check calling setup**.

During a call, JARVIS only reacts when you start with "Jarvis", so it doesn't interrupt your conversation.

<img src="assets/divider.svg" width="100%" alt=""/>

## Reminders

- **Set one:** "remind me to call Rahim at 5pm", "remind me in 20 minutes to drink water", "remind me every day at 8pm to take medicine", "remind me every Monday at 7am to go to the gym", "remind me tomorrow at 9am to submit the form".
- **Check them:** "what are my reminders", or the **Reminders** tab.
- **Cancel:** "cancel the reminder to call Rahim".
- JARVIS understands spoken times: "at five thirty", "half past six", "quarter to eight", "next Friday", "on 15 October".
- When one is due, JARVIS speaks it out loud and shows an on-screen popup — even if you're doing something else.

### Deadlines & countdowns

A different thing from a reminder: a **deadline doesn't ring an alarm**, it just counts the days down — for exams, trips, due dates, anything with a date rather than a specific moment.

- **Set one:** "my exam is on 15 November", "the project deadline is on 20 October", "I have a wedding on 1 December".
- **Check it:** "how many days until my exam", "when is my exam" → *"Exam is 13 days away, Sir, on 15 November."*
- **List them all:** "what are my deadlines" — or the **Reminders** tab, which has a separate Deadlines & Countdowns panel.
- **Cancel:** "cancel the deadline for exam".

<img src="assets/divider.svg" width="100%" alt=""/>

## Reading your screen

JARVIS only looks at your screen **when you explicitly ask** — never on its own.

- "what is on my screen" / "describe my screen" / "what window is this"
- "read this" / "read the error" / "explain this error"
- "read what I copied" / "explain what I copied" / "read what I selected"

JARVIS briefly hides its own window, takes a screenshot, and reads it with the OCR built into Windows — this works **offline**, nothing leaves your PC. Without an AI key you get a short local summary with error lines picked out. With an AI key, it gives a proper explanation, but **always asks permission first** ("Is that okay? Say yes") before sending any screen text to your AI provider. If you add a `vision`-capable model, it can describe pictures too — again, asking before every screenshot it sends.

⚠️ Don't use the AI-powered screen reading on screens showing passwords or private conversations.

<img src="assets/divider.svg" width="100%" alt=""/>

## Building code & websites

*Needs a free AI key — see [AI features](#ai-features-optional).*

Say "build me a to-do list website", "create a Python script that renames files", "make a landing page for a coffee shop". JARVIS asks "shall I start?", writes the files, and saves them in `Documents\JARVIS Projects\<name>\`, then offers to open the folder.

It will **not** build anything meant to attack or deceive people — phishing pages, malware, or exploit code.

<img src="assets/divider.svg" width="100%" alt=""/>

## Updates

JARVIS checks for a newer version 25 seconds after starting, then every 6 hours. When one's available:

- A glowing **⬆ UPDATE x.y** button appears next to the tabs
- An orange dot appears on **Settings**
- JARVIS tells you out loud

Click the button (or say "update now", then "yes"). The new version downloads, is checked against its SHA-256 checksum, installs, and JARVIS restarts itself — your config and memory are kept. Turn automatic checks off in Settings if you prefer to update manually.

<img src="assets/divider.svg" width="100%" alt=""/>

## Settings reference

Most things live in the **Settings** tab (voice, microphone, theme, updates). Advanced options go in `jarvis_config.json` — see [AI features](#ai-features-optional) for the full list of keys.

**Files JARVIS creates on your PC:**

| File | Purpose |
|---|---|
| `%USERPROFILE%\.jarvis_memory.json` | Your name, facts, taught answers, contacts, reminders, settings |
| `%USERPROFILE%\.jarvis_notes.json` | Voice notes |
| `%USERPROFILE%\jarvis_errors.log` | Error details, for troubleshooting |
| `%USERPROFILE%\Pictures\jarvis_*.png` | Screenshots you ask for |
| `Documents\JARVIS Projects\` | Code/websites JARVIS builds for you |

<img src="assets/divider.svg" width="100%" alt=""/>

## Privacy

JARVIS has **no accounts, analytics, or tracking of its own**. Your memory, notes, reminders and contacts stay on your PC. Here's everything that talks to the outside world:

| Service | When | What's sent |
|---|---|---|
| Google speech recognition | Every time you speak | The audio of your sentence |
| Microsoft voice service | Every spoken reply | The text of the reply |
| Google / DuckDuckGo / Bing / Wikipedia / Wikidata | When you ask a question | Your question |
| wttr.in | "weather …" | The city name |
| Have I Been Pwned | "check my password" | Only the first 5 characters of the password's hash |
| OpenPhish / URLhaus / NIST NVD | Link & CVE checks | The link or CVE ID |
| GitHub | Update check | Nothing identifying |
| Your AI provider *(only with a key)* | Questions, screen text, code requests | The content involved, plus your name and remembered facts for personalisation |

Offline, PC control, system info, memory, reminders, typed commands and the offline voice all still work.

<img src="assets/divider.svg" width="100%" alt=""/>

## Troubleshooting

| Problem | Try this |
|---|---|
| Heard you but didn't answer | Say "run a self test". Check **Wake word** is off in Settings (if on, start with "Jarvis"). Details are in `jarvis_errors.log`. |
| Can't hear you / only up close | Settings → Microphone: watch the level bar, raise sensitivity, say "I am far away", raise mic volume in Windows, try a different accent. |
| Slow to respond | Settings → Response speed slider; turn on "Show timing details" to see which step is slow. |
| No voice, text only | Check Settings → Voice replies is on; check the self-test voice rows. |
| Blank window | Install the Microsoft Edge WebView2 Runtime. |
| Security check looks incomplete | Run JARVIS as administrator for the fullest audit. |
| WhatsApp call doesn't start automatically | Press the call button yourself, or set up ADB for full automation. |
| "I could not reach any speed test server" | Your network may be blocking them; the message explains why. |
| Network scan misses a device | Phones asleep don't answer — wake it and scan again. |

<img src="assets/divider.svg" width="100%" alt=""/>

## Limitations

- Voice commands are **English only**.
- Speech recognition and the natural voice need the internet.
- Several features rely on Windows-specific behaviour (Wi-Fi names, brightness on laptop screens, WhatsApp UI automation that may break if WhatsApp changes its layout).
- Link/scam checks are heuristics, not a guarantee — always stay cautious with unexpected messages.
- Without an AI key, open-ended answers are a merged summary of sources, not a full rewrite.
- JARVIS cannot place Bluetooth calls directly; see [WhatsApp & phone calls](#whatsapp--phone-calls).

<img src="assets/divider.svg" width="100%" alt=""/>

## Responsible use

- **Network scan:** only scan networks you own or have permission to scan.
- **Prank mode** is a harmless animation — nothing is hacked, copied, or deleted. Stop it (Esc) immediately if anyone is upset.
- **Power actions and calls always ask for confirmation.** Speech recognition can mishear — listen to what JARVIS repeats before saying "yes".
- JARVIS is not a medical, legal, or emergency service. In an emergency, call your local emergency number.

<div align="center">

<br/>

[← Back to README](README.md)

<img src="assets/divider.svg" width="100%" alt=""/>

</div>
