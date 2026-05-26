# 🔪 KNIVES OUT — Player Dossier

A stylish browser-based social assassination game inspired by *Assassin / Killer* party games.

**KNIVES OUT** turns a group of players into hunters and targets in a closed elimination loop. Every player hunts one target while being hunted by someone else — until only one remains.

Built as a single-page HTML/CSS/JavaScript experience with a cinematic dossier-inspired UI.

---

## 🎮 Game Overview

In **KNIVES OUT**:

- Every player is assigned **one target**
- Every player is also being hunted
- Eliminate your target to **inherit their next target**
- Continue until only **one survivor** remains

**Core Loop:**  
`Eliminate → Inherit → Repeat`

---

## ✨ Features

### 🕵️ Immersive Player Dashboard
- Press-and-hold intel reveal system
- Hidden target information for privacy
- Live status display (`ALIVE`, `GHOST`, etc.)

---

### 🔗 Animated Kill Chain
Interactive SVG visualization showing:

- player elimination flow
- target inheritance
- loop progression
- replayable chain animation

---

### 🔐 Kill Confirmation System
Secure 6-character kill code flow:

1. Killer generates a temporary code
2. Victim enters the code
3. Kill is confirmed

Rules:
- expires after **10 minutes**
- uppercase alphanumeric only
- only valid for assigned target

---

### 🛡️ Immunity System
Timed limited-slot immunity rounds:

- first-come-first-serve claiming
- animated claim state
- live countdown timer
- resets every round

---

### 👻 Ghost Protocol
Dead players may get one final chance:

- alive players vote a ghost
- dead players assign a ghost target
- successful ghost kill = revive
- failure = permanent death

---

### 📜 Full Rulebook UI
Includes:
- valid vs invalid kill examples
- office floor exceptions
- witness rules
- meeting immunity
- physical-contact confirmation requirement

---

## 🛠 Tech Stack

- **HTML5**
- **CSS3**
- **Vanilla JavaScript**
- **SVG animations**
- Google Fonts:
  - Playfair Display
  - Courier Prime

No frameworks. No dependencies.

---

## 📂 Project Structure

```bash
knives-out/
│── index.html      # entire game (HTML + CSS + JS)
└── README.md
