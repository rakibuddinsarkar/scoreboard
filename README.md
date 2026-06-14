# 🧮 Digital Scoreboard App - UI Logic & QA Edge Case Playground

This repository contains a dynamic **Digital Scoreboard Application** built using front-end web technologies. It serves as a practical project for mastering state management, conditional DOM manipulation, and interactive user interfaces. 

From an SQA perspective, this app is an excellent asset for showcasing **Functional Testing, Boundary Value Analysis, and UI/UX state verification**.

---

### 🛠️ Core Technologies Used
* **Structure:** HTML5
* **Styling & Layout:** CSS3 (Flexbox/Grid for aligned scoreboard panels)
* **Interactivity & Logic:** JavaScript (ES6+ for score handling, event listeners, and data-reset workflows)

---

### 🎯 SQA Perspective: Critical Edge Cases & Logic Tested
Developing and verifying this micro-app provided solid practical experience in identifying software defects, focusing on scenarios such as:
1. **Boundary Value Testing (BVT):** Checking application behavior at critical thresholds (e.g., verifying score additions at $0$ and maximum allowed digits).
2. **Negative Flow/Input Validation:** Ensuring counters do not display negative values upon unexpected inputs or multiple reduction clicks (preventing negative scores).
3. **State Transition Verification:** Testing that the **Reset** button accurately clears all dynamic numbers and restores the UI to its absolute default state instantly.
4. **UI/UX Consistency:** Verifying layout responsiveness so the score counters remain centered and legible across mobile, tablet, and desktop viewports.

---

### 📂 Project Structure Overview
```text
├── src/ / assets/
│   ├── app.js             # Event handlers, arithmetic score calculations, and DOM modifiers
│   ├── style.css          # Responsive display grids and custom button aesthetics
│   └── index.html         # Scoreboards component structure and layout hooks
└── README.md              # Project documentation
