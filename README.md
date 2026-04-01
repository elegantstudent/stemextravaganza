# 🌐 AI Club Hub | STEM Extravaganza

[![Live Demo](https://img.shields.io/badge/Demo-Live_Site-00ffcc?style=for-the-badge&logo=github)](https://elegantstudent.github.io/stemextravaganza/)
[![Tech Stack](https://img.shields.io/badge/Tech-Vanilla_JS%20%7C%20HTML5%20%7C%20CSS3-ff0055?style=for-the-badge)](#)

> **An interactive, web-based hub engineered for the 2024 STEM Extravaganza to showcase our AI Club's logic matrices, algorithms, and projects.**

## 💻 Project Overview
This repository contains the source code for a single-page web application (SPA) built to engage students at our STEM Extravaganza booth. Instead of a standard presentation, we engineered an interactive terminal that uses a diagnostic quiz algorithm to match users with one of our custom-built games. 

The application features a custom UI, dynamic state-based routing, and three fully playable minigames built entirely from scratch using the **HTML5 Canvas API** and **Vanilla JavaScript**.

Note: This codebase was generated utilizing AI assistance. My role focused on prompt engineering, architectural design, debugging, and deployment.

## ✨ Core Features
* **Algorithmic Matchmaking:** A dynamic quiz that routes users to specific games based on their input parameters (APM/Reflex vs. Logic/Strategy).
* **Zero Dependencies:** Built entirely without external frameworks or libraries to demonstrate strong fundamental knowledge of DOM manipulation, the Canvas API, and JavaScript game loops.
* **Custom AI Logic:** Features a custom-built Tic-Tac-Toe algorithm and a functional Pong opponent that tracks Y-axis ball coordinates.
* **Dynamic Routing:** Single-file SPA architecture utilizing JavaScript to manage active view states seamlessly.

## 🎮 The Games Directory
1. **Neon Pong:** A physics-based paddle game featuring a functional CPU opponent. Demonstrates collision detection and trajectory calculation.
2. **AI Tic-Tac-Toe:** A logic puzzle featuring a "smart-ish" algorithm that actively blocks player wins while looking for its own victory conditions.
3. **Neon Snake:** A grid-based survival game featuring array-based body tracking, boundary collision, and a custom hacker-themed canvas boot sequence.
4. **0x32 Wordle:** An external integration routing to our custom cryptographic word deduction game.

## 🛠️ Technical Implementation
* **Frontend:** `HTML5`, `CSS3` (CSS Variables, Flexbox/Grid, Keyframe Animations)
* **Logic & Engine:** `Vanilla ES6 JavaScript`
* **Rendering:** `HTML5 Canvas API` (`requestAnimationFrame` & `setInterval` game loops)

## 🚀 How to Run Locally
Because this project uses vanilla web technologies without a build step, running it is incredibly simple:
1. Clone this repository: `git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git`
2. Navigate to the directory and open `index.html` in any modern web browser.
3. Alternatively, view the live production build via GitHub Pages [here](https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPO-NAME/).

---
*Developed by the BASIS San Antonio Shavano AI Club.*
