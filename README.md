# FutureSpark 🚀

FutureSpark is a premium, interactive, single-page career discovery game designed for students aged 11–14. It maps 5 custom questions (with 4 choices each) to 10 distinct career paths using a weighted matrix scoring model, rendering results in a sleek, scrollbar-free dark-mode SaaS dashboard inspired by modern products like Vercel, Linear, and Notion.

---

## ✨ Key Features

### 🎮 Gamified Assessment
- **5 Custom Questions:** Carefully weighted questions that capture interests, hobbies, strengths, and preferences.
- **Keyboard Navigation:** Quick response selection using hotkeys `1`, `2`, `3`, and `4` for a high-efficiency assessment experience.

### 📊 Premium SaaS Results Dashboard
- **100% Scrollbar-Free Viewport:** Fits perfectly inside `100vh` on desktop with fluid responsive scaling for tablet and mobile views.
- **Interactive Navigation Bar:** Top glassmorphic header dynamically synchronized with quiz states (Discover, Assessment, Results tabs).
- **Glowing Gradient Borders & Micro-Interactions:** Modern styling overlays that blend card borders into career-specific neon themes on hover.
- **Career Compatibility Chart:** Visualized scoring weights showing the top 3 matching careers.
- **Action Path Map:** Interactive milestone checklist for the matching career, persistently saved to `localStorage`.
- **Strengths & Talents:** Clean display grid highlighting structural traits (Problem Solver, Creative Thinker, Innovation Builder, Team Player).
- **Autosaved Reflections Notepad:** High-tech notepad journal enabling students to write down their reflections, automatically saved on input.
- **Responses Report Modal:** Detailed glassmorphism popup modal listing the full report of selected answers.

### 🔊 Audio & Speech Integration
- **Web Audio Synth Effects:** Dynamic retro hover chimes, click pops, and custom victory fanfare generated programmatically via Web Audio API.
- **Text-to-Speech Narration:** Real-time speech narration on results generation using the browser's Web SpeechSynthesis API.

---

## 🛠️ Technology Stack
- **Structure:** Semantic HTML5
- **Style:** Vanilla CSS3 (Custom properties, grid systems, clamp-scaling, glassmorphic backdrop-filters)
- **Logic:** Pure Vanilla ES6+ JavaScript (no external framework overhead or dependencies)
- **Audio:** Web Audio API (Oscillators, Gain nodes)
- **Speech:** Web SpeechSynthesis API

---

## 🚀 Getting Started

### Prerequisites
You only need a modern web browser to run the game!

### How to Run Locally
1. Clone the repository:
   ```bash
   git clone git@github.com:harihara8262-cell/FutureSpark.git
   ```
2. Navigate to the project folder:
   ```bash
   cd FutureSpark
   ```
3. Open `index.html` directly in your browser, or run a local HTTP server:
   ```bash
   # Using npx http-server
   npx http-server -p 8080
   ```
4. Access the game at `http://localhost:8080`!

---

## 📝 License
This project is open-source and free to customize.
