<div align="center">

# 💿 Disk Scheduling Algorithms

<p>
  A web-based simulator implementing six classic disk scheduling algorithms, built as a practice project for Operating Systems at <strong>Polytechnic University of the Philippines – San Juan (PUP-SJ)</strong>.
</p>

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/Status-Archived-lightgrey?style=for-the-badge)

</div>

---

## 📋 Overview

An interactive browser-based simulator that visualizes how different disk scheduling algorithms handle I/O requests. Users can input a request queue and initial head position, and the simulator computes the seek sequence, total head movement, and renders the results visually.

> Built as a practice project for Operating Systems — not intended for production use.

---

## ⚙️ Implemented Algorithms

| Algorithm | Description |
|-----------|-------------|
| **FCFS** | First-Come-First-Serve — services requests in arrival order |
| **SSTF** | Shortest Seek Time First — always picks the closest request to minimize head movement |
| **SCAN** | Elevator algorithm — arm sweeps in one direction, then reverses |
| **C-SCAN** | Circular SCAN — sweeps in one direction only, then jumps back to the start |
| **LOOK** | Like SCAN but reverses when no more requests exist in the current direction |
| **C-LOOK** | Like C-SCAN but jumps back only to the lowest pending request |

---

## 🛠️ Tech Stack

| Layer    | Technology    |
|----------|---------------|
| Language | JavaScript    |
| Markup   | HTML5         |
| Styling  | CSS3          |
| IDE      | VS Code       |

---

## 🖼️ Screenshots

> 📸 _UI screenshots coming soon._

<!-- Uncomment and replace with actual screenshots once available:
<div align="center">
  <img src="Practice JS/Assets/screenshot-main.png" width="700" alt="Main Interface" />
  <br/><br/>
  <img src="Practice JS/Assets/screenshot-results.png" width="700" alt="Algorithm Results" />
</div>
-->

---

## 🚀 Getting Started

No installation needed — just open it in your browser.

**1. Clone the repository**
```bash
git clone https://github.com/AgustinUno/DISK-ALGORITHMS.git
cd DISK-ALGORITHMS
```

**2. Open in browser**
```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows — just double-click index.html
```

**3. Input your request queue and head position**, select an algorithm, and run the simulation.

---

## 📁 Project Structure

```
DISK-ALGORITHMS/
├── index.html          # Landing / algorithm selection page
├── scripts.js          # Main logic
├── styles.css          # Main styles
├── page_1.html         # Simulation results page
├── page_1.js           # Results page logic
├── page_1.css          # Results page styles
├── Practice JS/Assets/ # Visual assets
└── README.md
```

---

## 🎓 Academic Context

> **Institution:** Polytechnic University of the Philippines – San Juan (PUP-SJ)
> **Subject:** Operating Systems
> **Type:** Practice Project
> **Languages:** JavaScript, HTML, CSS

---

<div align="center">
  <sub>Made with 💿 and a deep respect for disk I/O efficiency</sub>
</div>
