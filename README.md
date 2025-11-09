# 🐍 Ultra-Modern Snake Game (HTML, CSS, JS)

## [Game Preview]

<img width="1893" height="962" alt="Screenshot 2025-11-10 042739" src="https://github.com/user-attachments/assets/b84a2fe0-e840-400b-8661-10f128bfaf18" />


> A fully interactive, ultra-modern Snake Game built with pure **HTML, CSS, and JavaScript** — no external frameworks.  
> Sleek, dark, and futuristic with glowing effects and smooth transitions.

🎮 **Play Online:** [🔗 www.github.snake.com](https://www.github.snake.com)  
💻 **Note:** This game is **available only for PC** (desktop/laptop browsers).

---

## 🔮 Overall Theme

- **Ultra-Dark Mode** background (`#0a0a0a`) with a subtle visible grid.
- **Full-screen gameplay area** that fills the window.
- UI elements appear as **minimal glowing overlays or pop-ups** — immersive and distraction-free.

---

## 👤 Startup Flow

1. On load, a **popup** asks for **Name** and **Age**.  
2. A **Settings Popup** lets players customize:
   - **Snake Color** (neon green `#39FF14`, cyan `#00FFFF`, orange `#FFA500`, magenta `#FF00FF`, yellow `#F5FF00`)
   - **Snake Speed** (slider 1–10)
   - **Game Variant**
     - **Box Mode** → snake dies on wall
     - **Loop Mode** → snake wraps around edges
3. Click **Start Game** to begin.

---

## 🕹️ Gameplay

- Runs in a **fullscreen canvas view**.
- **Grid** remains faintly visible.
- **Snake** and **Apple** use crisp glowing blocks.
- Eating an apple triggers a glowing **digestion animation**.
- Apples spawn randomly (never on the snake).

---

## ⚡ Controls

| Key | Action |
| --- | --- |
| ↑ / W | Move Up |
| ↓ / S | Move Down |
| ← / A | Move Left |
| → / D | Move Right |
| P | Pause Menu |
| ESC | Back / Exit |

---

## 💀 Game Over Screen

- Big, glowing **red "GAME OVER"** with pulse/flicker animation.  
- Background darkens slightly.  
- Displays **Score**, **High Score**, and buttons:
  - 🔁 Restart  
  - 🏠 Return to Menu  

---

## 📊 Player History

- Stores **Name**, **Age**, and **Scores** in `localStorage`.  
- View history by player from the **History Menu**.

---

## 🧩 Menus

- **Main Menu**
  - New Game
  - History
  - Settings
  - Exit
- Smooth **fade/slide animations** and glowing text.

---

## 🧠 Design Style

- Fonts: *Poppins*, *Orbitron*, *Consolas*
- **Neon glows**, **soft shadows**, **blurred overlays**
- Buttons glow on hover
- Minimal text on screen edges:
  > “Use W/A/S/D to move – P to pause – Esc to exit”

---

## 🎮 Technical Details

- Built using `<canvas>` for rendering.  
- Fully **responsive** on PC screens (desktop/laptop).  
- Stores all data in **localStorage**.  
- Pure **HTML/CSS/JS** — no frameworks.  
- Sound support: place `eat.wav` and `game_over.wav` in the same folder as `index.html`.

---

## 🧱 Folder Structure

```

📁 ultra-modern-snake/
├── index.html
├── asset/
│   ├── favicon.png
│   ├── eat.wav
│   └── game_over.wav
└── README.md

```

---

## 🚀 How to Play

1. Open `index.html` in your browser.  
2. Enter your name and age.  
3. Adjust settings and hit **Start Game**.  
4. Use **W/A/S/D** or **Arrow Keys** to control the snake.  
5. Eat apples, grow longer, and chase your high score!

---

### 🧩 Credits

**Developer:** [@mohitscodiclab](https://github.com/mohitscodiclab)  
**Engine:** HTML5 Canvas  
**Theme:** Neon-Dark / Futuristic  
**Availability:** 🖥️ **PC Only**

---

### 🧠 Prompt Inspiration

This game was designed from the concept prompt:

> “Create a fully interactive, ultra-modern snake game using HTML, CSS, and JavaScript — sleek, dark, and immersive with a futuristic feel.”


