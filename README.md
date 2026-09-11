<img width="1280" height="640" alt="git (1)" src="https://github.com/user-attachments/assets/8920b256-2ba8-4988-b824-5351134eb4bd" />



# 🩸 Curse of the Crimson Crypt

## 🎯 Basic Details

### Team Name

**HOST**

### Team Members

* **Team Lead:** T S SEETHALAKSHMI
* **Member 2:** NIRANJANA V R

---

# Project Description

**Curse of the Crimson Crypt** is a single-file desktop horror game that combines spooky exploration, a monster chase, jumpscares, and unexpected comedy.

The player explores a dark crypt using a mouse-controlled flashlight, escapes a horned beast by repeatedly pressing the **SPACEBAR**, and finally discovers that the terrifying demon only wants compensation for a dropped wallet.

---

# The Problem (that doesn't exist)

Exploring a completely dark crypt while being chased by a terrifying supernatural creature is already stressful.

But there is one serious problem nobody has solved:

**What happens when a terrifying demon becomes more concerned about your wallet than your life?**

Our project addresses this extremely important and completely imaginary problem.

---

# The Solution (that nobody asked for)

We created a horror game that starts like a serious supernatural survival experience and ends like a visit to a government office.

The player:

1. Enters a pitch-black crypt.
2. Uses a flashlight controlled by the mouse.
3. Searches the room for a hidden golden chalice.
4. Accidentally triggers a monster chase.
5. Mashes **SPACEBAR** to escape.
6. Gets hit with a terrifying jumpscare.
7. Suddenly finds themselves in bright daylight.
8. Discovers that the terrifying demon is wearing **reading glasses**.
9. Gets scolded for running away.
10. Receives an itemized **damage invoice** because they dropped their wallet.
11. Must sign the invoice to finally escape.

**The real final boss was paperwork.**

---

# 🛠️ Technical Details

## Technologies / Components Used

### For Software

**Languages Used**

* HTML5
* CSS3
* JavaScript

**Frameworks**

* None

**Libraries**

* None

**APIs / Web Technologies**

* HTML5 Canvas API
* Web Audio API
* SVG
* Mouse Events
* Keyboard Events

**Tools Used**

* Visual Studio Code
* Web Browser
* GitHub
* GitHub Pages

---

### For Hardware

No special hardware components are required.

**Required Hardware:**

* Desktop/Laptop
* Keyboard
* Mouse
* Speakers/Headphones

---

# 🎮 Implementation

## For Software

### Installation

The project is designed as a **single HTML file**, so no complicated installation is required.

Download or clone the project repository and open:

```text
index.html
```

in a modern web browser.

No external assets or libraries need to be installed.

---

## Run

Simply double-click:

```text
index.html
```

or open it using a modern browser such as:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox

For the best experience, use a desktop/laptop with **keyboard, mouse and audio enabled**.

---

# 🎮 Gameplay Flow

```text
              START
                ↓
       DARK CRYPT / INTRO
                ↓
      MOUSE-CONTROLLED
         FLASHLIGHT
                ↓
       EXPLORE THE ROOM
                ↓
      FIND GOLDEN CHALICE
                ↓
         CLICK CHALICE
                ↓
        MONSTER AWAKENS
                ↓
        CORRIDOR CHASE
                ↓
      MASH SPACEBAR
                ↓
     ┌──────────┴──────────┐
     ↓                     ↓
 REACH THE END          GET CAUGHT
     ↓                     ↓
     └──────────┬──────────┘
                ↓
            JUMPSCARE
                ↓
        1-SECOND HORROR
                ↓
          HARD CUT
                ↓
       BRIGHT DAYLIGHT
                ↓
       DEMON + GLASSES
                ↓
       "WHERE'S MY WALLET?"
                ↓
        DAMAGE INVOICE
                ↓
        SIGN THE INVOICE
                ↓
              EXIT
                ↓
              END
```

---

# 🕯️ Gameplay Features

## 1. Flashlight Exploration

The game begins in a completely dark room.

The player controls a flashlight beam using the mouse.

The flashlight reveals only a small area around the cursor while the rest of the crypt remains hidden in darkness.

The player must explore the room and locate a **hidden golden chalice**.

---

## 2. Golden Chalice Trigger

The golden chalice is hidden somewhere inside the crypt.

When the player discovers and clicks the chalice:

```text
CHALICE FOUND
      ↓
CURSE ACTIVATED
      ↓
MONSTER AWAKENS
      ↓
CHASE BEGINS
```

This transitions the game into the corridor chase.

---

## 3. Corridor Chase

The player is chased by a terrifying **horned beast**.

The chase uses custom SVG silhouettes rather than external images or emojis.

The player must repeatedly press:

```text
SPACEBAR
```

to make the character run faster.

A distance meter continuously decreases as the monster approaches.

### Objective

**Reach the end of the corridor before the monster catches you.**

---

## 4. Screen Shake

During the chase, the screen shakes dynamically to create a feeling of danger.

The effect becomes more intense as the monster gets closer.

This creates a sense of:

> **"RUN. RUN. RUN."**

---

# 😱 5. Jumpscare

When the player reaches the end of the corridor — or gets caught — the game triggers a short jumpscare.

The jumpscare includes:

* Screen strobing
* Rapid visual transition
* Zooming demon mouth
* Screen shake
* Synthesized horror screech
* Approximately one second of intense horror

All sound effects are generated directly using the **Web Audio API**.

No external audio files are used.

---

# 😂 6. The Bureaucracy Twist

Immediately after the jumpscare:

**HARD CUT.**

The terrifying atmosphere disappears.

The screen becomes bright and cheerful.

Cheery elevator-style music begins playing.

The demon appears again — but this time:

**wearing reading glasses.**

Instead of attacking the player, the demon starts scolding them.

The player discovers that the demon wasn't chasing them to kill them.

The player had simply:

> **DROPPED THEIR WALLET.**

The demon is angry because the player caused damage while running away.

---

# 🧾 7. Damage Invoice

The demon presents the player with an itemized invoice.

Example:

| Item                            |     Damage |
| ------------------------------- | ---------: |
| Ancient Crypt Floor             |       ₹450 |
| Broken Coffin                   |       ₹800 |
| Monster's Emotional Trauma      |     ₹1,200 |
| Emergency Demon Consultation    |       ₹750 |
| Wallet Retrieval Fee            |       ₹500 |
| Running Away Without Permission |       ₹999 |
| **TOTAL**                       | **₹4,699** |

The invoice is completely ridiculous and forms the main comedic ending of the game.

---

# ✍️ 8. Interactive Signature Pad

The player cannot exit immediately.

They must sign the invoice using an HTML5 canvas-based signature pad.

The player uses the mouse to scribble their signature.

Once a valid signature is detected:

```text
SIGNATURE ACCEPTED
        ↓
INVOICE APPROVED
        ↓
DEMON SATISFIED
        ↓
EXIT GRANTED
```

The game then displays the final ending.

---

# 🔊 Audio System

The game does not use external sound files.

All sounds are synthesized using the **Web Audio API**.

### Generated Sounds Include:

* Ambient crypt sounds
* Horror drones
* Monster chase sounds
* Warning tones
* Jumpscare screech
* Impact sounds
* Button/interface sounds
* Cheerful elevator music

This keeps the project completely self-contained in a single HTML file.

---

# 📚 Project Documentation

## Screenshots

### Screenshot 1 — Crypt Exploration

**Caption:**
The player explores the pitch-black crypt using a mouse-controlled flashlight beam to search for the hidden golden chalice.

---

### Screenshot 2 — Monster Chase

**Caption:**
The player is chased through the corridor by the horned beast while repeatedly pressing SPACEBAR to increase their escape speed.

---

### Screenshot 3 — Bureaucracy Ending

**Caption:**
The horror suddenly transforms into a comedic bureaucracy scene where the demon, wearing reading glasses, presents the player with a damage invoice.

---

# 📊 Diagrams

## Game Architecture / Workflow

**Caption:**
The game progresses through multiple stages: exploration, chalice interaction, monster chase, jumpscare, comedic transition, invoice interaction and signature-based exit.

---

# 🖥️ Game State Structure

```text
INTRO
  │
  ↓
EXPLORATION
  │
  │ Click Chalice
  ↓
CHASE
  │
  ├── Monster catches player
  │
  └── Player reaches destination
              │
              ↓
          JUMPSCARE
              │
              ↓
        COMEDIC TWIST
              │
              ↓
       DAMAGE INVOICE
              │
              ↓
       SIGNATURE PAD
              │
              ↓
             END
```

---

# 🔧 Hardware

## Schematic & Circuit

**Not Applicable**

This project is entirely software-based and does not require electronic circuits or physical components.

---

# 📸 Build Photos

## Components

**Not Applicable**

No physical components are used.

---

## Build Process

The project was developed as a single HTML file containing:

```text
HTML
 ↓
Game Interface

CSS
 ↓
Visual Effects & Animations

JavaScript
 ↓
Game Logic & Interaction

Canvas API
 ↓
Flashlight + Signature Pad

SVG
 ↓
Monster & Player Silhouettes

Web Audio API
 ↓
All Game Sounds
```

---

# 🏆 Final Product

**Caption:**
The completed playable horror-comedy game featuring the crypt exploration, monster chase, jumpscare and unexpected bureaucratic ending.

---

# 🎥 Project Demo Video

**[Add your demo video link here]**

### What the video demonstrates

The demo demonstrates the complete gameplay experience:

* Entering the dark crypt
* Controlling the flashlight with the mouse
* Finding the golden chalice
* Triggering the monster
* Escaping through the corridor
* Mashing SPACEBAR
* Experiencing the jumpscare
* Seeing the unexpected comedy transition
* Meeting the glasses-wearing demon
* Receiving the damage invoice
* Signing the invoice
* Completing the game

---

# 🔗 Additional Demos

**Live Demo:** [Add GitHub Pages link]

**GitHub Repository:** [Add repository link]

**Demo Video:** [Add video link]

---

# 👥 Team Contributions

### T S SEETHALAKSHMI

* Developed the overall game concept
* Implemented the game logic
* Created the crypt exploration system
* Implemented the mouse-controlled flashlight
* Developed the monster chase
* Implemented keyboard-based running mechanics
* Created the jumpscare sequence
* Implemented the interactive invoice and signature pad

### NIRANJANA V E

* Designed the game's visual interface
* Worked on CSS animations and horror effects
* Created/customized SVG character silhouettes
* Assisted with the comedic ending design
* Tested the gameplay

### [Member 3]

* Implemented and tested Web Audio API sound effects
* Created synthesized horror and elevator sounds
* Assisted with game balancing and debugging
* Worked on documentation and deployment

---

# 💡 What Makes the Project Useless?

The player spends several minutes:

**exploring a haunted crypt → running from a demon → surviving a jumpscare...**

only to discover that the entire supernatural crisis was actually about:

## 🧾 A LOST WALLET.

And after surviving the apocalypse, the player still has to:

### **SIGN THE INVOICE.**

---

# ❤️ Conclusion

**Curse of the Crimson Crypt** combines horror, interaction and comedy into one intentionally ridiculous experience.

The project begins as a traditional horror game but deliberately breaks the player's expectations with an absurd bureaucratic ending.

The result is a game that asks one very important question:

> **Why fight a demon when you can just sign the paperwork?**

---

**Made with ❤️ at TinkerHub Useless Projects**
