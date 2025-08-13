# 🎶 Neurogroove

**Autonomous AI Agent for Live Coding**
*An intelligent collaborator for real-time musical creativity in environments like TidalCycles.*

---

## 🌟 Overview

**Neurogroove** is an autonomous AI agent that lives inside your live coding environment, acting as a creative partner rather than just a tool.
It listens to your patterns, adapts to your style, and generates new rhythmic and melodic ideas on the fly — perfect for **algoraves**, **generative music**, and **experimental performances**.

Inspired by cutting-edge research in AI-human collaboration, Neurogroove aims to blur the line between performer and machine, creating an ever-evolving musical dialogue.

---

## ✨ Features

* **🎨 Real-Time Pattern Suggestion** – Dynamic rhythm, melody, and texture proposals while you code.
* **⚡ Instant Code Generation** – Generates snippets for rapid iteration without breaking the flow.
* **🧠 Style Adaptation** – Learns from your patterns over time to match and extend your creative voice.
* **🎚️ Live Collaboration** – Seamlessly integrates into live performance environments like **TidalCycles** and custom trackers.
* **🔄 Evolving Interaction** – Patterns shift and grow with every performance, never repeating the same way twice.

---

## 🚀 Installation

**Requirements:**

* [Haskell](https://www.haskell.org/) (for TidalCycles) or your custom tracker environment
* Python 3.9+
* An active OSC or WebSocket connection to your coding environment

```bash
# Clone this repository
git clone https://github.com/frangedev/neurogroove.git
cd neurogroove

# Install dependencies
pip install -r requirements.txt
```

---

## 🎛️ Usage

**1. Start your live coding environment** (e.g., TidalCycles in SuperCollider).
**2. Launch Neurogroove** in a separate terminal:

```bash
python neurogroove.py
```

**3. Play and let the AI join the jam.**
Neurogroove will listen, adapt, and inject new ideas via OSC messages.

Example TidalCycles binding:

```haskell
d1 $ s "bd sn" # gain 0.8
-- Neurogroove may suggest:
-- d1 $ s "bd sn cp" # speed "1 0.5 1.5"
```

---

## 🧪 Roadmap

* [ ] Support for multiple live coding languages (FoxDot, Sonic Pi)
* [ ] Interactive chat interface for AI-musician dialogue
* [ ] Pattern visualisation in real-time
* [ ] Style transfer between artists

---

## 📜 License

MIT License – free to use, modify, and remix.

---

## 🎧 Credits

Developed with love for the **algorave community**.
Inspired by the intersection of **neural networks, generative art, and live performance**.
